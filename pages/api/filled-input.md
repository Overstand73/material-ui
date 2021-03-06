---
filename: /packages/material-ui/src/FilledInput/FilledInput.js
title: FilledInput API
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# FilledInput

<p class="description">The API documentation of the FilledInput React component.</p>

```js
import FilledInput from '@material-ui/core/FilledInput';
```



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">autoComplete</span> | <span class="prop-type">string |   | This property helps users to fill forms faster, especially on mobile devices. The name can be confusing, as it's more like an autofill. You can learn more about it here: https://html.spec.whatwg.org/multipage/form-control-infrastructure.html#autofill |
| <span class="prop-name">autoFocus</span> | <span class="prop-type">bool |   | If `true`, the input will be focused during the first mount. |
| <span class="prop-name">classes</span> | <span class="prop-type">object |   | Override or extend the styles applied to the component. See [CSS API](#css-api) below for more details. |
| <span class="prop-name">className</span> | <span class="prop-type">string |   | The CSS class name of the wrapper element. |
| <span class="prop-name">defaultValue</span> | <span class="prop-type">union:&nbsp;string&nbsp;&#124;<br>&nbsp;number<br> |   | The default input value, useful when not controlling the component. |
| <span class="prop-name">disabled</span> | <span class="prop-type">bool |   | If `true`, the input will be disabled. |
| <span class="prop-name">endAdornment</span> | <span class="prop-type">node |   | End `InputAdornment` for this component. |
| <span class="prop-name">error</span> | <span class="prop-type">bool |   | If `true`, the input will indicate an error. This is normally obtained via context from FormControl. |
| <span class="prop-name">fullWidth</span> | <span class="prop-type">bool |   | If `true`, the input will take up the full width of its container. |
| <span class="prop-name">id</span> | <span class="prop-type">string |   | The id of the `input` element. |
| <span class="prop-name">inputComponent</span> | <span class="prop-type">union:&nbsp;string&nbsp;&#124;<br>&nbsp;func&nbsp;&#124;<br>&nbsp;object<br> |   | The component used for the native input. Either a string to use a DOM element or a component. |
| <span class="prop-name">inputProps</span> | <span class="prop-type">object |   | Attributes applied to the `input` element. |
| <span class="prop-name">inputRef</span> | <span class="prop-type">union:&nbsp;func&nbsp;&#124;<br>&nbsp;object<br> |   | Use that property to pass a ref callback to the native input component. |
| <span class="prop-name">margin</span> | <span class="prop-type">enum:&nbsp;'dense'&nbsp;&#124;<br>&nbsp;'none'<br> |   | If `dense`, will adjust vertical spacing. This is normally obtained via context from FormControl. |
| <span class="prop-name">multiline</span> | <span class="prop-type">bool |   | If `true`, a textarea element will be rendered. |
| <span class="prop-name">name</span> | <span class="prop-type">string |   | Name attribute of the `input` element. |
| <span class="prop-name">onChange</span> | <span class="prop-type">func |   | Callback fired when the value is changed.<br><br>**Signature:**<br>`function(event: object) => void`<br>*event:* The event source of the callback. You can pull out the new value by accessing `event.target.value`. |
| <span class="prop-name">placeholder</span> | <span class="prop-type">string |   | The short hint displayed in the input before the user enters a value. |
| <span class="prop-name">readOnly</span> | <span class="prop-type">bool |   | It prevents the user from changing the value of the field (not from interacting with the field). |
| <span class="prop-name">required</span> | <span class="prop-type">bool |   | If `true`, the input will be required. |
| <span class="prop-name">rows</span> | <span class="prop-type">union:&nbsp;string&nbsp;&#124;<br>&nbsp;number<br> |   | Number of rows to display when multiline option is set to true. |
| <span class="prop-name">rowsMax</span> | <span class="prop-type">union:&nbsp;string&nbsp;&#124;<br>&nbsp;number<br> |   | Maximum number of rows to display when multiline option is set to true. |
| <span class="prop-name">startAdornment</span> | <span class="prop-type">node |   | Start `InputAdornment` for this component. |
| <span class="prop-name">type</span> | <span class="prop-type">string |   | Type of the input element. It should be a valid HTML5 input type. |
| <span class="prop-name">value</span> | <span class="prop-type">union:&nbsp;string&nbsp;&#124;<br>&nbsp;number&nbsp;&#124;<br>&nbsp;bool&nbsp;&#124;<br>&nbsp;arrayOf<br> |   | The input value, required for a controlled component. |

Any other properties supplied will be spread to the root element ([ButtonBase](/api/button-base)).

## CSS API

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:


| Name | Description |
|:-----|:------------|
| <span class="prop-name">root</span> | Styles applied to the root element.
| <span class="prop-name">underline</span> | Styles applied to the root element.
| <span class="prop-name">focused</span> | Styles applied to the root element if the component is focused.
| <span class="prop-name">disabled</span> | Styles applied to the root element if `disabled={true}`.
| <span class="prop-name">adornedStart</span> | Styles applied to the root element if `startAdornment` is provided.
| <span class="prop-name">adornedEnd</span> | Styles applied to the root element if `endAdornment` is provided.
| <span class="prop-name">error</span> | Styles applied to the root element if `error={true}`.
| <span class="prop-name">multiline</span> | Styles applied to the root element if `multiline={true}`.
| <span class="prop-name">input</span> | Styles applied to the `input` element.
| <span class="prop-name">inputMarginDense</span> | Styles applied to the `input` element if `margin="dense"`.
| <span class="prop-name">inputMultiline</span> | Styles applied to the `input` element if `multiline={true}`.
| <span class="prop-name">inputAdornedStart</span> | Styles applied to the `input` element if `startAdornment` is provided.
| <span class="prop-name">inputAdornedEnd</span> | Styles applied to the `input` element if `endAdornment` is provided.

Have a look at [overriding with classes](/customization/overrides#overriding-with-classes) section
and the [implementation of the component](https://github.com/mui-org/material-ui/tree/master/packages/material-ui/src/FilledInput/FilledInput.js)
for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiFilledInput`.

## Inheritance

The properties of the [ButtonBase](/api/button-base) component are also available.
You can take advantage of this behavior to [target nested components](/guides/api#spread).

