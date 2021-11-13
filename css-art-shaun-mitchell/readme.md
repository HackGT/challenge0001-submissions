# hexlabs css art

**live page**: [github.io/hex-art](https://shitchell.github.io/hex-art/)

--------------------------------------------------------------------------------

this is my entry into the 2021 hexlabs css art competition 😊

while fairly simple, my goal was to create a page that uses *no html*. it was
built using nothing but a text editor, includes no html other than the required
`<style>` tags, and was otherwise written with pure css.

## how it works

all modern browsers will create an `<html>`, `<head>`, and `<body>` tag when
those are missing from the page. this allows me, in spite of not explicitly
including any elements on the page, to make use of 4 css pseudo-elements:
`html::before`, `html::after`, `body::before`, and `body::after` (you can't
create pseudo-elements using the `<head>` or `<style>` tags). i use this to add
2 hexagons and 2 words to the page.

the final addition to the page for stylistic effect is the background. since
this is meant to be artful, a radial gradient with a slow 20s animation was used
to produce a subtle contrast with the hexlabs homages.

## credit where credit's due

this page uses the "roobert" font as found on [hexlabs.org](https://hexlabs.org/)
and the GT primary colors as described at
[brand.gatech.edu/our-look/colors](https://brand.gatech.edu/our-look/colors).

## whoami

**shaun mitchell** &lt;shaun@shitchell.com>

## scrot

![image](https://user-images.githubusercontent.com/621412/141294590-06d8942b-b0ae-4796-88ee-5de65f341c22.png)

![image](https://user-images.githubusercontent.com/621412/141294784-1317fd95-66e8-4cb4-a81a-9110188d5784.png)
