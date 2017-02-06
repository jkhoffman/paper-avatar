[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Abe90/paper-avatar)

# \<paper-avatar\>

User avatar in material style

## Example

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="paper-avatar.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<style is="custom-style">
	paper-avatar.red {
		--paper-avatar-color: red;
	}
	paper-avatar.large {
		--paper-avatar-width: 60px;
	}
</style>
<paper-avatar label="Abe90"></paper-avatar>
<paper-avatar label="Abe90" src="https://avatars.githubusercontent.com/u/4205629"></paper-avatar>
<paper-avatar label="Abe90" two-chars></paper-avatar>
<paper-avatar label="Abe90" class="red"></paper-avatar>
<paper-avatar label="Abe90" class="large"></paper-avatar>
<paper-avatar label="Abe90" jdenticon></paper-avatar>
```

## Two chars
The `two-chars` parameter is used to show two chars in the generated avatar.

If the `label` is composed of a single word, you'll see the first two letters of that word; the first letter will always appear capitalized.

If instead the `label` is composed of two words, will be displayed the first letter of every word.

### Example
- first: F
- First: F
- First Second: Fs
- First Second: FS



## Customization
There is the opportunity to change some parameters to customize the generated avatar.

The css parameters `--paper-avatar-color` and `--paper-avatar-width` correspond to the background color and the size (width and height) of the avatar.

The `colors` parameter is an array that contains the colors used for the background.


## Install

```
bower i Abe90/paper-avatar --save
```
