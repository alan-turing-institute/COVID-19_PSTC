---
layout: page

jsarr:
- js/tileJS.js
---
<!-- Useful blog on how to include java script with jekyll -->
<!-- tileJS.js taken from https://github.com/tholman/tileJs -->

## Example Calendar JavaScript


<!-- Include the "metro-tile" class in your element -->
We could create calendar look from coloured, interactive tiles
<div id="metro-array" style="display: inline-block;">


            <!-- Simple grid for the demo! None of these styles are required, thats just how I've styled my tiles -->
            <!-- The only important thing is class="metro-tile" -->
            <div style="width: 230px; height: 230px; float: left; ">

              <a class="metro-tile" style="cursor: pointer; width: 230px; height: 110px; display: block; background-color: deepSkyBlue; color: #fff; margin-bottom: 10px;">
                You can
              </a>

              <a class="metro-tile" style="cursor: pointer; width: 230px; height: 110px; display: block; background-color: deepSkyBlue; color: #fff;">
                put
              </a>
            </div>

            <div style="width: 230px; height: 230px; float: left; margin-left: 10px">

              <a class="metro-tile" style="cursor: pointer; width: 230px; height: 230px; display: block; background-color: deepSkyBlue; color: #fff">
                anything you want
              </a>

            </div>

            <div style="width: 230px; height: 230px; float: left; margin-left: 10px">

              <a class="metro-tile" style="cursor: pointer; width: 230px; height: 110px; display: block; background-color: deepSkyBlue; color: #fff; margin-bottom: 10px;">
                in
              </a>

              <a class="metro-tile" style="cursor: pointer; width: 110px; height: 110px; margin-right: 10px; display: block; float: left; background-color: deepSkyBlue; color: #fff;">
                these
              </a>

              <a class="metro-tile" style="cursor: pointer; width: 110px; height: 110px; display: block; background-color: deepSkyBlue; float: right; color: #fff;">
                tiles
              </a>
            </div>

          </div>


Or could use open source calendar projects
