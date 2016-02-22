# Optimal Engine Charts v1.0.0

#### An interactive webapp for Kerbal Space Program v1.0.5

##### Live URL: [http://meithan.net/KSP/engines](http://meithan.net/KSP/engines/)
.

#### Description

This webapp will let you compute interactive optimal engine charts on demand. They are meant to answer this general question:

* What is the optimal engine for a given payload mass and desired Δv, subject to a minimum TWR (or acceleration) restriction, where by optimal we mean that the resulting ship should have the least possible mass?

#### How to use the app

Basic instructions:

1. Fill in the chart parameters, including payload and Δv ranges, minimum TWR, atmospheric pressure and maximum number of engines.
2. Select the engines that should be included in the analysis.
3. Click "Calculate!" and the chart will appear; details will be shown on the panel to the right.

You can get more help by opening the collapsible areas by clicking on the ? buttons. Some extra details are also given by mousing over the i tooltips.

The chart is interactive:

* Mouse over the chart to see details for the (payload, Δv) point under the mouse in the panel to the right.
* Click on the chart to lock the details panel to a specific point in the chart; click again to unlock.
* Click-and-drag to pan the currently displayed view; the chart will be recomputed with the new ranges.
* Hold the CTRL key and click-and-drag to zoom the chart to the selected area.
* Use the button controls under the chart to change the ranges, recall previous settings or save the chart.

Fore more info (like details on how the calculations are done) or to leave a message, visit the [development thread](http://forum.kerbalspaceprogram.com/index.php?/topic/114995-web-105-optimal-engine-charts-interactive-webapp/) at the KSP forums.

##### Version history

* 1.0.0 (June 30, 2015): Initial release.

##### License

Optimal Engine Charts is free software licensed under the GNU General Public License v3. Third-party additional software is used under the terms of the corresponding licenses. Built with Paper.js and jquery.js. Styles by Twitter Bootstrap. Icons by Glyphicons.

Copyleft ![](http://i.imgur.com/4R84dsR.png) Meithan West, 2015. Some rights reserved.