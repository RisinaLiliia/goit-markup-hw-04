# goit-markup-hw-04

Add markup and design of icons and decorative effects from the layout

https://www.figma.com/design/wuEpGhwCepGCOUw7mZFRac/Web-Studio-(Version-5.0)?node-id=297016-823&p=f&t=dQsJYG7LoXGYYrAP-0

To generate an SVG sprite, use the Icomoon service.
To optimize the created SVG sprite, use the svgomg service.

Criteria for accepting work by the mentor

Project
«A1» There is an images folder with images in the root of the project.
«A2» All vector images (icons) are collected in the SVG sprite icons.svg, which is located in the images folder.
«A3» All vector images are optimized.
«A4» There is a css folder with style files in the root of the project.
«A5» All styles are written in one styles.css file, which is located in the css folder.
«A6» There are no capital letters, spaces, or transliteration in the file names. The names contain only English letters and words.
«A7» The source code is formatted using Prettier.
«A8» All images and text content are taken from the layout.
«A9» The modern-normalize style normalizer is connected
«A10» All styles are written in one file styles.css, which is located in the css folder.
«A11» The code is written in compliance with the guidelines.

Markup

«B1» Vector graphics in svg format are used for all icons.
«B2» SVG icons are exported correctly. When exporting, the "group" is selected, not the vector itself.
«B3» All icons from the SVG sprite are added to HTML using the <svg> and <use> tags
«B4» Icons have been added to the benefits section (an untitled section with a list of benefits over Our Team).
«B5» Social network icons have been added to the Our Team section.
«B7» Social network icons have been added to the footer.
«B8» HTML markup of all layout elements has been performed.
«B9» Tags have been used according to their semantic content.

Design

«C1» A large image with a blackout effect (under the header) is made as a background. A multi-layered background with a gradient is used for blackout.
«C2» The background image in the block under the header does not stretch wider than its original size of 1440px.
«C3» The cards in the Our Team section have a permanent shadow effect.
«C4» The cards in the Our Portfolio section have a shadow effect when hovering anywhere on the card.
«C5» When hovering or focusing, the icons should go into the active state - change color, if specified in the layout.
«C6» Transitions are made for all hover and focus effects (color, background, shadow). Time - 250ms, time distribution function - cubic-bezier(0.4, 0, 0.2, 1).
«C7» Animated properties are clearly specified in the transitions. There is no value all anywhere.
«C8» In the main navigation, using the ::after pseudo-element, the link of the current page (where the user is currently located) is underlined.
«C9» The overlay with text on the cards of the Our Portfolio section appears when hovering anywhere on the card.
«C10» The blue overlay in the cards of the Our Portfolio section moves from the bottom.
«C11» The pseudo-elements do not have text content in the content property. They are used exclusively for decorative purposes.
