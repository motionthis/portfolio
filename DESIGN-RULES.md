# Portfolio Design Rules

Reference this file before writing any code for this project.
Source: Figma file `afI89efODS5hZ6rjPtKuol`

## Colors
- Background: `#EEECEC`
- Card fill: `#D5D4CF`
- Navy (text, strokes): `#000B28`
- Subtitle: `rgba(40, 0, 1, 0.70)`
- White (card outlines): `#FFFFFF` or `rgba(255, 255, 255, 0.90)` for soft variants

## Typography
- Font family: SF Pro
- Font weight: 860 (Heavy)
- Name: 48px in BOTH states, color #000B28
- Subtitle: 48px on home → 32px on Works state, color rgba(40, 0, 1, 0.70)
- Works label: 32px, color #000B28

## Profile Image (Avatar)
- Home state: 258×317px
- Works state: 173×207px
- Border: `1px #000B28 solid` (regular border, NOT outline)
- Border radius: `37px` in BOTH states
- Full color photo (NO grayscale filter)
- Background behind photo: `#B56035`

## Spacing
- Profile container gap: `18px`
- Icon gap: `22px`

## Image Cards (Gallery)
- Stroke: `outline: 2px white solid` (OUTSIDE stroke — use CSS `outline`, NOT `border`)
- Two cards use softer outline: `outline: 2px rgba(255, 255, 255, 0.90) solid`
- Border radius: `26px` (one small card uses `11px`)
- Background: `#D5D4CF`

## Videos
- All videos: `autoplay muted loop playsinline`
- Object-fit: `cover`

## Animations
- Easing: `cubic-bezier(0.22, 1, 0.36, 1)`
- Duration: `1s` for layout transitions
- Gallery enters from right to left
- Cards fade in with random order opacity animation
- Duration for card fade: `0.8s`

## Assets
- All media files in `Assets/` folder
- Profile photo: `Assets/portrait.jpeg`
- Videos: `Assets/{name}.mp4`

## Layout (Works state)
- Profile panel: left side, starts at x=149, y=320, width=419
- Image gallery: starts at x=663, y=105
- Gallery container: 855×2938px with absolute-positioned cards
- Works button: x=234, y=687, white background, padding 5px
