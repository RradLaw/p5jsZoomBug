# p5jsZoomBug
Viewable at: http://rradlaw.github.io/p5jsZoomBug/

Problem exists with p5.js (v0.4.18) where if you zoom into a page which has a graphics, the graphics will be skewed. This is a major problem, as most mobile browsers zoom the page before loading, causing p5js canvases to not work as intended. The problem can be seen when you zoom the page, and then refresh.

100% zoom: https://www.dropbox.com/s/5yo1y9nyflugfpo/2015-11-11_16-11-13.png?dl=0

110% zoom: https://www.dropbox.com/s/tg3myx3dlghqf0l/2015-11-11_16-11-38.png?dl=0


Issue solved with adding pixelDensity(1) at the start of the code.

https://github.com/processing/p5.js/issues/1094#issuecomment-155751354
