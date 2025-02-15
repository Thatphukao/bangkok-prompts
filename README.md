# Beyond the Chaos Interactive Screen

**Author:** That (Phukao) Prommolmard
**Date:** Feb 3 2025
**Contact:** [thatphukao@gmail.com](mailto:thatphukao@gmail.com)

## Overview

This project is an interactive HTML page that allows users to input text which is then animated as rising text. The animation appears over a white header with a gradient overlay, and each submitted text is displayed in two mirrored copies. The page is built using HTML, CSS, and JavaScript with modern coding practices such as CSS custom properties and ES6 syntax.

[You can preview the website here](http://htmlpreview.github.io/?https://github.com/Thatphukao/bangkok-prompts/blob/main/index.html)

### Installation

1. You can just download the whole thing. Make sure your files look like this:

   ```
   /project-folder
     ├── index.html
     └── libs/
           ├── Arlette THA.otf
           ├── GraphikThaiLoop-Regular.otf
           ├── Icon enter.svg
           └── LOGO.svg
   ```
2. Go to your web browser of choice and go to File, then open index.html file

## Usage

Type in the text box (below the prompt). It will be displayed at the top of the screen.

Click on the logo to download the prompt answers for a log of what people say (will refresh with browser refresh!)

## Customization

- Modify the HTML comment `<!-- CHANGE PROMPT HERE -->` at line 224 and the text below it to customize the prompt message displayed to users.
- CSS custom properties (found in the `:root` selector) allow you to easily change key aspects of the layout:

  - `--header-height`: Adjusts the height of the header and animation clipping area.
  - `--side-margin`: Controls the horizontal margins.
  - `--green-bg`: Changes the background color of the page.
  - You can change the interval of the texts over at line 257. This is in seconds, so if you want the interval to be exactly 2.3542 seconds you can put in that number.

## License

MIT License

Copyright (c) 2025 That (Phukao) Prommolmard

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Contact

For questions, suggestions, or further information, please reach out via email at [thatphukao@gmail.com](mailto:thatphukao@gmail.com).
