# pjtried2018

Code
    # sumary
    import malib
    import numpy as np
    
    a=np.srand((10,10))

entre apostrophes inversés \`toto e=mc^2\` --> `toto e=mc^2`

entre tiréts bas \_toto e=mc^2\_ --> _toto e=mc^2_

entre deux tiréts bas \_\_toto e=mc^2\_\_ --> __toto e=mc^2__

entre asteriques \*toto e=mc^2\*  -->  *toto e=mc^2*

entre deux asteriques \*\*toto e=mc^2\*\* --> **toto e=mc^2**

Formules $a=4$

    Formules $a=4$



h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> x + &theta;<sub>1</sub>x

HTML ampersand entity codes for common math symbols can be found here. Codes for Greek letters here.

While this approach has limitations it works in practically all markdown and does not require any external libraries.

Complex Scalable Inline Rendering with LaTeX and Codecogs

If your needs are greater use an external LaTeX renderer like CodeCogs. Create an equation with CodeCogs editor. Choose svg for rendering and HTML for the embed code. Svg renders well on resize. HTML allows LaTeX to be easily read when you are looking at the source. Copy the embed code from the bottom of the page and paste it into your markdown.

<img src="https://latex.codecogs.com/svg.latex?\Large&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />

GitHub support only somtimes worked using the above raw html syntax for readable LaTeX for me. If the above does not work for you another option is to instead choose URL Encoded rendering and use that output to manually create a link like:

\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}

![\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}](https://latex.codecogs.com/svg.latex?x%3D%5Cfrac%7B-b%5Cpm%5Csqrt%7Bb%5E2-4ac%7D%7D%7B2a%7D)


