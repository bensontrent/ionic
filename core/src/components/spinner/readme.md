# ion-spinner

The Spinner component provides a variety of animated SVG spinners. Spinners are visual indicators that the app is loading content or performing another process that the user needs to wait on.

The default spinner to use is based on the platform. The default spinner for `ios` is `"lines"`, and the default for `android` is `"crescent"`. If the platform is not `ios` or `android`, the spinner will default to `crescent`. If the `name` property is set, then that spinner will be used instead of the platform specific spinner.



<!-- Auto Generated Below -->


## Properties

#### color

string

The color to use from your application's color palette.
Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`.
For more information on colors, see [theming](/docs/theming/basics).


#### duration

number

Duration of the spinner animation in milliseconds. The default varies based on the spinner.


#### mode

string

The mode determines which platform styles to use.
Possible values are: `"ios"` or `"md"`.


#### name

string

The name of the SVG spinner to use. If a name is not provided, the platform's default
spinner will be used. Possible values are: `"lines"`, `"lines-small"`, `"dots"`, `"bubbles"`,
`"circles"`, `"crescent"`.


#### paused

boolean

If true, the spinner's animation will be paused. Defaults to `false`.


## Attributes

#### color

string

The color to use from your application's color palette.
Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`.
For more information on colors, see [theming](/docs/theming/basics).


#### duration

number

Duration of the spinner animation in milliseconds. The default varies based on the spinner.


#### mode

string

The mode determines which platform styles to use.
Possible values are: `"ios"` or `"md"`.


#### name

string

The name of the SVG spinner to use. If a name is not provided, the platform's default
spinner will be used. Possible values are: `"lines"`, `"lines-small"`, `"dots"`, `"bubbles"`,
`"circles"`, `"crescent"`.


#### paused

boolean

If true, the spinner's animation will be paused. Defaults to `false`.


## CSS Custom Properties

| Name      | Description          |
| --------- | -------------------- |
| `--color` | Color of the spinner |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
