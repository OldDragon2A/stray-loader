# stray-loader
A loading bar for StrayMaverick.

Takes a list of actions with optional durations and displays the progress towards completion.  The actions can be changed using the textarea in the options section.  One action per line with and optional duration at the end of the line.


```
Never Ending Action
Action with Duration (PT5M)
Action with Duration (P1M)
```

An action without a duration will last until manually skipped.  Actions with a duration will automatically move to the next action in the list when the duration has elapsed. The duration can be specified in any format accepted by a [Moment.js](http://momentjs.com) [Duration](http://momentjs.com/docs/#/durations/creating/).

Should the list of actions run out or is empty, it will default to "Escaping the Moon Prison" with no duration.

## Keyboard Shortcuts

| Key | Description |
| :-- | :---------- |
| `O` | Open the options. |
| `S` | Start/Stop the current action. |
| `N` | Move to the next action. |
| `U` | Update the actions using the textarea in the options. |

## Screenshots

![Screenshot](/docs/screenshot.png "Screenshot")

With the options panel open.

![Screenshot](/docs/screenshot-with-options.png "Screenshot with options open")
