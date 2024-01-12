# Destructuring

**Syntax**

<table>
    <tr>
        <td colspan="2"><i>Destructuring</i></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>Identifier</i> [if keywords are enabled]</td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>IdentifierName</i> [if keywords are disabled]</td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><b>[</b> <i>Elision</i><sub>opt</sub> <b>]</b></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><b>[</b> <i>DestructuringElementList</i> <b>]</b></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><b>[</b> <i>DestructuringElementList</i> <b>,</b> <i>Elision</i><sub>opt</sub> <b>]</b></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><b>{</b> <i>DestructuringFields</i><sub>opt</sub> <b>}</b></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><b>{</b> <i>DestructuringFields</i> <b>, }</b></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>Destructuring</i> <i>NonNull</i> [lookahead ∉ <i>NonNull</i>]</td>
    </tr>
</table>

<table>
    <tr>
        <td colspan="2"><i>TypedDestructuring</i></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>Destructuring</i></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>Destructuring</i> <b>:</b> <i>TypeExpression</i></td>
    </tr>
</table>

<table>
    <tr>
        <td colspan="2"><i>DestructuringElementList</i></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>Elision</i><sub>opt</sub> <i>Destructuring</i><sup>allowIn</sup></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>Elision</i><sub>opt</sub> <i>DestructuringRest</i></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>DestructuringElementList</i> <b>,</b> <i>Elision</i><sub>opt</sub> <i>Destructuring</i><sup>allowIn</sup></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>DestructuringElementList</i> <b>,</b> <i>Elision</i><sub>opt</sub> <i>DestructuringRest</i></td>
    </tr>
</table>

<table>
    <tr>
        <td colspan="2"><i>DestructuringRest</i></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><b>...</b> <i>Destructuring</i></td>
    </tr>
</table>

<table>
    <tr>
        <td colspan="2"><i>DestructuringFields</i></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>DestructuringField</i></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>DestructuringFields</i> <b>,</b> <i>DestructuringField</i></td>
    </tr>
</table>

<table>
    <tr>
        <td colspan="2"><i>DestructuringField</i></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>FieldName</i> <b>:</b> <i>Destructuring</i><sup>allowIn</sup></td>
    </tr>
    <tr>
        <td>&nbsp;</td><td><i>IdentifierName</i></td>
    </tr>
</table>