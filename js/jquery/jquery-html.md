## Reset Radio input

```html
<span onclick="resetExtraLuggage('field_name')">Reset</span>
```
```js
function resetExtraLuggage(field_name)
{
    $('input[type="radio"][name="' + field_name + '"]').prop('checked', false);
}
```