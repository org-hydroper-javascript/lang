# Output directory

## import.meta.outputDirectory

The `import.meta.outputDirectory` expression evaluates to the JetPM output directory path. For reliability, the bytecode compiler must emit a special instruction for this expression instead of a string constant.

## Meta data entries

[Plain meta data](metadata/plain-metadata.md) support file entries resolving files from the JetPM output directory path through the `File(outputDirectory, "path/to/file")` form.

```
package com.khronos.opengl {
    [[DLL(library = File(outputDirectory, "opengl.dll"))]]
    internal class DLL {
        [[DLL(name = "gl_createcontext")]]
        public native function createContext(): void;
    }
}
```