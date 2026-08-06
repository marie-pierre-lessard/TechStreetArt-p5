# TechStreetArt-p5
A part of a class project at TechCollege, Aalborg, Denmark

The web app as a whole constitutes a styled art viewer with a responsive image carousel/selector that accommodates any picture (regardless of its orientation and dimensions), a reset button, a button to save and download the user's art, some text content, and an art game. Everything outside of the enhanced kaleidoscope function was meant to be reused as the setting and components of other games. The enhanced kaleidoscope function is a derivative work of the following P5 example, which I modified in order to create a kaleidoscope that was complete with a colour picker. 

[Kaleidoscope](https://p5js.org/examples/Repetition-Kaleidoscope): Revised by [Kasey Lichtlyter](https://www.klich.co). Edited and maintained by p5.js Contributors and Processing Foundation. Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en).

Applied mathematics being among the learning goals in this IT programme, it is worth emphasising that the method used to ensure the art viewer's responsiveness is my own original solution. I made ratio calculations based on what I learned in 9th grade in Quebec, Canada. (This is unfortunately missing from the middle-school curriculum elsewhere.) I also used the height and width of the browser's window object instead of the [Screen Orientation API](https://developer.mozilla.org/en-US/docs/Web/API/ScreenOrientation), the vulnerability-inducing [device-orientation events](https://developer.mozilla.org/en-US/docs/Web/API/Device_orientation_events) or the [orientation CSS media feature](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/At-rules/@media/orientation). 

## Sources/attributions

[Kaleidoscope](https://p5js.org/examples/Repetition-Kaleidoscope): Revised by [Kasey Lichtlyter](https://www.klich.co). Edited and maintained by p5.js Contributors and Processing Foundation. Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en).

This example and my web app both utilise the P5 JavaScript library, which has a [GNU Lesser General Public License (version 2.1)](https://p5js.org/copyright).

The sources cited in this school assignment in order to demonstrate my thought process and research abilities include: 
* excerpts from P5 reference pages, which are protected by the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en);
* a tip from the YouTube video [p5.js Tutorial | Getting Started with Creative Coding](https://www.youtube.com/watch?v=x1NxkEjfNtI&list=PL0beHPVMklwgMz4Z-mNp4_udo9mjBk7pn&index=1) by Patt Vira (facts/processes are not copyrightable according to EU and [YouTube](https://support.google.com/youtube/answer/2797466?hl=en) guides); 
* the mention of a [W3 Schools page](https://www.w3schools.com/js/js_random.asp), which explains the use of two built-in JavaScript methods (the code demonstrating the basic use of such functions is also not copyrightable);
* a [forum thread](https://forum.processing.org/two/discussion/13051/how-do-i-bind-p5-canvas-to-an-html-page.html) that illustrates the use of P5's `parent()` method better than the P5 reference pages. The link to the copyright notice of the Processing forum is [broken](https://processing.org/copyright.html), but this is a non-issue since I did not use any code snippet from that thread. The discussion just helped me understand how P5's `parent()` method works (facts/processes are not copyrightable).

The pictures are no longer the class project's pictures, which had different orientations, but the same number of pixels. The new pictures are picked randomly by [Unsplash](https://unsplash.com), which has a very permissive [open-source license](https://unsplash.com/license).

Several open-source [Google Fonts](https://fonts.google.com) were imported, and they are owned by their respective copyright holder. They are all licensed under the [SIL Open Font License, version 1.1](https://openfontlicense.org/open-font-license-official-text).

## License
Marie-Pierre Lessard hereby licenses this web app (an art viewer with a kaleidoscope game) under CC BY-NC-SA 4.0 (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International). You can read the terms and conditions [here](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en). Special attention should be given to the section [Disclaimer of Warranties and Limitation of Liability](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s5).
