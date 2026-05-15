# ssp
Solar System Positions - what's observable

SSP is an interactive web page for planning astronomical observations, with a detailed description on the page. It has been validated by photographing asteroids and comets in the positions it predicts.

The file ssp.zip contains the complete runnable program (HTML, JS, etc). The Javascript embodies many of the Astronomical Algorithms from Jean Meeus' book of that name.

It is accompanied by a Java program called ElementUpdater which generates new Javascript files for SSP containing comet and asteroid orbital elements from the Minor Planet Centre. ElementUpdater generates several files for chart generation but the important ones for SSP are called _comets.js and _minors.js.

The file Holst_src.zip contains Java source files implementing the AA (Meeus) algorithms in a much stricter form. (Holst includes the major planets of course).
