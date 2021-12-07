---
title: "Functionality"
linkTitle: "Functionality"
weight: 1
description: >
  Functionality, settings and customization.
---

<p>
	A list with descriptions of the features and settings currently available in the mod is presented on this page. 
</p>

<div style="margin-right: 2em;">
	<p style="font-size:1.5em; font-weight:bolder;">Content:</p>
  
  <p style="font-size:1.2em;">Features:</p>
	<ol>
		<li style="font-size:1em;"><a href="#select-data">Selecting data</a></li>
		<li style="font-size:1em;"><a href="#drag-select">Click-hold-drag selection</a></li>
		<li style="font-size:1em;"><a href="#unselect">Unselect data</a></li>
    <li style="font-size:1em;"><a href="#mouseover-tooltip">MouseOver Tooltip</a></li>
    <li style="font-size:1em;"><a href="#center-text">Center text</a></li>
    <li style="font-size:1em;"><a href="#label-ratios">Label ratios</a></li>
    <li style="font-size:1em;"><a href="#negative-values">Negative values</a></li>
    <li style="font-size:1em;"><a href="#dynamic-visualization">Dynamic Visualization</a></li>
    <li style="font-size:1em;"><a href="#hover-effect">Outlined Hover on MouseOver</a></li>
    <li style="font-size:1em;"><a href="#settings-menu">Settings menu</a></li>
	</ol>

  <p style="font-size:1.2em;">Settings:</p>

  <ol>
		<li style="font-size:1em;"><a href="#show-labels">Show Labels For (...)</a></li>
		<li style="font-size:1em;"><a href="#show-in-labels">Show In Labels (...)</a></li>
    <li style="font-size:1em;"><a href="#labels-position">Labels Position (...)</a></li>
    <li style="font-size:1em;"><a href="#circle-type">Circle Type (...)</a></li>
	</ol>
  
  <br>
</div>

<p id="features">Features:</p>
<ul>
	<li id="select-data">Left Mouse and Ctrl-Clicking subsets of data.</li>
  <img src="left-click-ctrl-click.png" alt="Left Mouse and Ctrl-clicking subsets of data.">
  <p> Left Mouse clicking a subset of data will produce the highlighting of data seen in the chart on the left, whilst holding ctrl whilst clicking subsets of data will produce the highlighting on the right.</p>
  
  <li id="drag-select">Click-hold-drag selection for multiple subsets.</li>
  <img src="click-hold-drag.png" alt="Click-hold-drag selecting multiple subsets.">
  <p> Left Mouse holding and moving the mouse to cover the desired subsets, then releasing, will select all subsets that were present in the rectangular selection. </p>
  
  <li id="unselect">Unselect by clicking the mod background (canvas).</li>
  <img src="unselecting-canvas.png" alt="Unselect by clicking the mod background (canvas).">
  <p> By clicking anywhere on the canvas, in this example the white background around the Chart, the selection as seen on the left, will be unselected and the mod will go back to looking like it does when no subsets are selected, as seen on the right. </p>
  
  <li id="mouseover-tooltip">Tooltip with dynamic information on mouseOver.</li>
  <img src="mouseover-tooltip.png" alt="Tooltip and hovering outline example.">
  <p> Hovering over a sector will create an outline of the sector, as well as display a tooltip with information about the sector that is currently being hovered. </p>
  
  <li id="center-text">Dynamic sum of values as center text.</li>
  <img src="center-text.png" alt="Center text example.">
  <p> The center text available in the mod will give relevant information about the data that is currently selected on the chart. Either the whole set, as seen to the right, or one to several subsets, as seen in the two rightmost images. </p>
  
  <li id="label-ratios">Labels showing ratios on each sector.</li>
  <img src="sector-labels.png" alt="Labels inside sectors.">
  <p> The labels inside the sectors tell the users which percentage of the data set is present inside the subset. </p>
  
  <li id="negative-values">Red lines visualizing negative values.</li>
  <img src="negative-values.png" alt="Negative values outlined.">
  <p> On the outer part of a sector, the red line indicates that a value is negative rather than positive. This is to help the user navigate negative and positive values more easily. </p>
  
  <li id="dynamic-visualization">Dynamic visualization based on sector and donut size.</li>
  <img src="dynamic-visualization.png" alt="Different mod and sector resizings.">
  <p> Depending on the sizes of the sectors and the mod itself, different behaviours are expected within the Donut Chart. Some of these are the removal of labels when sectors are too small (middle) and the shortening of the center value name (right).</p>
	
  <li id="hover-effect">Outlined hover-effect when hovering a sector.</li>
  <img src="mouseover-tooltip.png" alt="MouseOver outline when hovering.">
  <p> When hovering a sector, as shown in the tooltip subsection, there is an outline present around the sector that you are currently hovering, which indicates the current sector.</p>
  
  <li id="settings-menu">Settings for adapting different visualization aspects of the mod.</li>
  <img src="settings-menu.png" alt="Settings menu in the mod.">
  <p> To change the way the mod is visualized, press the circled settings icon on the left, and a dropdown should appear of options that will change the look and placements of different aspects of your mod. Each of these settings are described underneath this section.</p>  
</ul>
<br>
<br>

<p>Settings:</p>
<p id="show-labels" style="font-size:1.2em; font-weight:bold;">Show labels for:</p>
<ul>
	<li>All</li>
  <img src="settings-all.png" alt="Show labels for: All">
  <p> Selecting "Show labels for: All" will show labels for all sectors.</p>  
  
  <li>Marked rows</li>
  <img src="settings-marked-rows.png" alt="Show labels for: Marked Rows">
  <p> Selecting "Show labels for: Marked Rows" will show labels for all sectors that are marked, and none when no specific sector(s) have been marked.</p>
	
  <li>None</li>
  <img src="settings-none.png" alt="Show labels for: None">
  <p> Selecting "Show labels for: None" will display no labels for any sectors, wether they have been selected or not.</p>
</ul>

<p id="show-in-labels" style="font-size:1.2em; font-weight:bold;">Show in labels:</p>
<ul>
	<li>Sector percentage</li>
  <img src="settings-all.png" alt="Show labels as a percentage.">
  <p> Selecting "Show in labels: Sector Percentage" will display the labels as a percentage.</p>
	
  <li>Sector value</li>
  <img src="settings-sector-value.png" alt="Show labels as a sector value.">
  <p> Selecting "Show in labels: Sector Value" will display the labels as the value of the corresponding sector.</p>
	
  <li>Sector category</li>
  <img src="settings-sector-category.png" alt="Show labels as the sector category.">
  <p> Selecting "Show in labels: Sector Category" will display the labels as the category of the current sector.</p>
  
  <li>Multiple values</li>
  <img src="settings-multiple-values.png" alt="Show multiple different sector options.">
  <p> You can also select multiple different values when choosing how to display the sector values, for instance Sector Category and Sector Values at the same time, or any (or all) combinations of the settings in the following subsection.</p>
</ul>

<p id="labels-position" style="font-size:1.2em; font-weight:bold;">Labels position:</p>
<ul>
	<li>Inside donut</li>
  <img src="settings-all.png" alt="Show labels inside the Donut.">
  <p> Selecting "Labels position: Inside donut" will display the labels inside the Donut Chart.</p>
  
  <li>Outside donut</li>
  <img src="settings-outside.png" alt="Show labels outside the Donut.">
  <p> Selecting "Labels position: Outside donut" will display the labels outside of the Donut Chart.</p>
</ul>

<p>Sorting:</p>
<ul>
	<li>Sort sectors by size</li>
  <img src="settings-unsorted.png" alt="Unsorted sectors.">
  <p> Unselecting "Sorting: Sort sectors by size" will remove the sorting done by size on the sectors. It is important to note that this disables the following two settings, as well.</p>
	
  <li>Sort sectors ascending</li>
  <img src="settings-ascending.png" alt="Sectors sorted in ascending order.">
  <p> Selecting "Sorting: Sort sectors ascending" will sort the sectors in ascending order.</p>
	
  <li>Sort sectors descending</li>
  <img src="settings-descending.png" alt="Sectors sorted in descending order.">
  <p> Selecting "Sorting: Sort sectors descending" will sort the sectors in descending order.</p>
</ul>

<p id="circle-type" style="font-size:1.2em; font-weight:bold;">Circle type:</p>
<ul>
	<li>Visualize whole circle</li>
  <img src="settings-all.png" alt="Donut Chart visualized as a whole circle.">
  <p> Selecting "Circle type: Visualize whole circle" will visualize the Donut Chart as a whole circle. </li>

  <li>Visualize semi-circle</li>
  <img src="settings-semi-circle.png" alt="Donut Chart visualized as a semi-circle.">
  <p> Selecting "Circle type: Visualize semi-circle" will visualize the Donut Chart as a semi-circle. </li>
</ul>
<br>
