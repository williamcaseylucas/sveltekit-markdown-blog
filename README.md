# Markdown Blog

## Commands

- pnpm create svelte
- pnpm i
- pnpm i open-props lucide-svelte @fontsource/manrope @fontsource/jetbrains-mono
- pnpm run format
  - runs prettier on all your code (removed semicolons from prettier config)

## CSS

- padding-block -> left and right
- padding-inline -> top and bottom
- max-inline-size: 1440px; -> max-width: 1440px;
- height: 100% -> h-full
- height: 100vh -> min-h-screen
- margin: 0 auto -> margin-inline: auto (top/bottom 0, left/right auto)
  - apply this to parent container with child content you want centered inside

## open-props: Css Variables similar to tailwind

- open-props.style
- gives you awesome colors that work well together
- import in +layout.svelte root

## Lucide

- Good for icons

## Fontsource

- an easy way to install fonts

## fav.farm

- gives you favicon as emojis
- add to html header

## lib

- $app/environment has "dev" value that says whether it is in production or not
