# selectboxtohorizontalpicker
jquery plugin that converts selectbox into horizontal value bar picker

This plugin will convert normal html select box into a horizontal value picker bar. This is ideal when you have a html select box with around 3-10 values. The values will be shown in boxes next to each other like a horizontal bar with values that can be selected. The selected value is updated automatically to the select box binded.

```sh
<select id="selectid" name="selectname">
  <option value="4">1-4 members</option>
  <option value="5">1-5 members</option>
  <option value="6">1-6 members</option>
  <option value="7">1-7 members</option>
  <option value="8">1-8 members</option>
  <option value="9">1-9 members</option>
  <option value="10">1-10 members</option>
</select>
$(function() {
   $("#selectid").numberselector();
});
```

You can alter the styles using CSS.
