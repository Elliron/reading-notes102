# CSS
CSS creates rules that specify how content of an alement appears
 - imagine invisible box around html
 - CSS creates rules for each box
 - contains 2 parts
   - **selector** which element css applies to
   - **declaration** how to style
     - have property and value
     **property** apsect of element to change
     **value** chosen settings

## External CSS
  - **Link** location of CSS file
  - **href** file path
  - **type** doc type value=text/css
  - **rel** relationship with html page

May use more than one style sheet

## Internal CSS
  - **style** sits inside head/meta data

## Selectors
  - **universal** applies to all elements * {}
  - **type** matches element names h1 , h2
  - **class** elements with class attribute .p {}
  - **id** element with id attribute #introduction {}
  - **child** direct child element  li>a {}
  - **descendant** element inside another  p a {}
  - **adjacent sibling** matches direct sibling h1+p {}
  - **general sibling** not directly preceding h1~p{}

## How CSS Rules Cascade
  - **last rule** two identical selectors result in the second taking effecet
  - **specifity** more specific rule takes precedence
  - **important** adding *!important* will make it take precedence

## Inheritance
  - font-family and color properties on an element will effect child elements

## Why use external
  - allows you to style multiple pages with a single page
  - sites load faster
  - easier to read and edit

## Different versions of css
  - Browsers may use different versions

# Color

## Foreground Color
  - **RGB** how much red green blue
  - **HEX** 6 digit code representing rgb
  - **Names** color names

## Background Color
  - treats HTML element as if in box
  - changes box color
  - change colors with rgb, hex and names
  - defaults white(normaly)
  - may use padding to seperate for readability

## Understanding Color
  - **RGB** values between 0-244
  - **HEX** values in hexadecimal code
  - **Names** values by predefined names
  - **HUE** colloquial idea of color
  - **Saturation** amount of grey in color
  - **Brightness** how much black in color

## Contrast
Foreground and Background color may effect readability
  - low contrast is harder to read
    - harder for visual impairments and color blindness
    - harder with poor monitors or sunlight
  - high contrast
    - easier to read
    - difficult when you have to read alot
  - medium contrast
    - easy to read for long text

## Opacity
CSS3 introduced
  - value between 0.0 and 1.0
  - 0.0 to 1.0 = %0 to %100 
  - if two rules the last one takes effect

## HSL Colors
  - **Hue** colloquial idea
  - **Saturation** amount of grey
  - **Lightness** amount of white or black

## HSL and HSLA
  - **Hue** angle btween 0 and 360
  - **Saturation** percentage
  - **Lightness** %0 to %100
  - **Alpha** 0 to 1.0

  [<==Back](README.md)