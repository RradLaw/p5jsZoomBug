# p5jsZoomBug
Viewable at: http://law0102.github.io/p5jsZoomBug/

Problem exists with p5.js (v0.4.18) where if you zoom into a page which has a graphics, the graphics will be skewed. This is a major problem, as most mobile browsers zoom the page before loading, causing p5js canvases to not work as intended. The problem can be seen when you zoom the page, and then refresh.

100% zoom: https://dl.dropboxusercontent.com/u/32400917/ShareX/2015-11-11_16-11-13.png

110% zoom: https://dl.dropboxusercontent.com/u/32400917/ShareX/2015-11-11_16-11-38.png
