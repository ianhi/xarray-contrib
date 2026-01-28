# Editing this Site

## Building this Site

This site is built with [`mystmd`](https://mystmd.org/). To build the site run `myst start` from the top level of the repo. You can manage this from any virtual environment or via a tool such as `uvx` of `npx`

::::{tab-set}
:::{tab-item} uvx
:sync: uvx
`uvx --from mystmd myst start`
:::
:::{tab-item} npx
:sync: npx
`npx mystmd start`
:::
::::

This will start a server that will automatically update as you change the markdown files.
