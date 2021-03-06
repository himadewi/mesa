.. :changelog:

Release History
---------------

0.8.3 (2018-01-14) Hayden
+++++++++++++++++++++++++++++++++++++++++++

**Improvements**

* Datacollector fix #445
* A first network grid model with visualization, using NetworkX and sigma.js #388
* Cache pip packages for Travis setup #427
* Remove localhost hardcoding + allow secure sockets #421
* Update Chart.js to version 2.7.1 #401
* Bank reserves example #432
* Extended Grid to support hexagonal grids #409

**Fixes**

* Faster ContinuousSpace neighbor search #439
* Updating license year to 2018 #450
* Updating language on license in contributing file #446
* Updating license year to 2018 #450
* Removed mutable defaults from DataCollector constructor #434
* [BUGFIX] Torus adjustment in Grid class #429
* Batchrunfixedparameters #423
* [BUGFIX] Fix sidebar visibility in Edge #436
* Updating Travis svg to target #master, not branches. #343
* Email list language updates and link updates #399
* Fix math problems in flockers; use numpy in space #378
* Only start tornado ioloop if necessary #339
* ContinuousSpace: Fix get_distance calculation on toroidal boundary condition #430


0.8.2 (2017-11-01) Gila Bend
+++++++++++++++++++++++++++++++++++++++++++

**Improvements**

* Split parameter_values into fixed & variable parameters in batchrunner #393

**Fixes**

* Updating License year to 2017 -- very minor update #391
* Flockers: fix param naming #398
* Remove unused class parameters. #400
* [hotfix!] Disable e2e viz test for now. #414
* Fixing bug in release process. [6a8ecb6]
    * See https://github.com/pypa/pypi-legacy/issues/670.


0.8.1 (2017-07-03) Flagstaff (PyCon Sprints & then some)
++++++++++++++++++++++++++++++++++++++++++++++++++++++++

**Improvements**

* Bootstrap UI starter #383
* Add Sugarscape Constant Growback example #385
* Add best-practices document and describe models. #371
* Refactored & model standards related:
    * Prisoner's Dilemma refactor to meet new model standard format. #377
    * refactored boltzmann wealth model to new layout #376
    * Update tutorial to follow new model standards #370
    * Moving wolf sheep pngs to sub-folder for better organization #372
    * Add best-practices document and describe models. #371
* Modified loop over agents in schedule step method #356
* Added function to use local images as shapes in GridDraw #355

**Fixes**

* Fix math problems in flockers; use numpy in space #378
* Seed both global random number generators #373, #368
* Dictionary parameters fix #309
* Downgrade setuptools to fix #353
* Minor forest fire fix #338, #346
* Allow fixed seed for replication #107
* Fix tutorial and example readme for port change 8b57aa


0.8.0 (2017-01-29) - Edgar
+++++++++++++++++++++++++++

**Improvements**

* Updating contribution file to prevent future travis breaks #336
* Updating Travis svg to target #master, not branches. #343
* implement "end" message in visualization #346
* Move empty-cell functions to baseclass Grid #349

**Fixes**

* Only start tornado ioloop if necessary #339
* fix boundaries of ContinousSpace #345


0.7.8.1 (2016-11-02) Duncan
++++++++++++++++++++++++++++

**Improvements**

* Fixes #324 -- renames all examples to be the pythonic format of naming #328
* Changing to port 8521, fixes #320. #321
* Opens a browser window when launching the server #323
* Ticket #314 - added progress bar to BatchRunner #316
* Auto update year for copyright. #329

**Fixes**

* Minor bug fixes - Update ForestFire example notebook to new API, and rename Basic to Shape Example. #318
* On-demand model stepping rather than an endless buffer #310
* Updating contribution to prevent future travis breaks #330



0.7.7 (2016-08-18)
++++++++++++++++++

**Improvements**

* Fixes - variable name heading0/1 in ArrowHead shape is not intuitive. #295 #301
* Fixes - ArrowHead shape is not reflecting in the docs of api #300 #301
* Fixes - Documentation is not reflecting latest changes wrt width-height argument order in Grid() #296 #301


0.7.6 (2016-08-13)
++++++++++++++++++

Theme: Scipy Sprints 2016 ( ‘-’)人(ﾟ_ﾟ )
& Then some.

**Feature adds**

* Add new shapes & direction indication in CanvasGrid #285
* Provides support for text overlay on Circle and Rectangle shapes. #265

**Improvements**

* Fixes Parameters of CanvasGrid(): row, col, height, width inverted #285
* Fixes 'coordinates on grid are used inconsistently throughout the code' #285
* Moves Agent and Model class outside of  __init__.py #285
* Minor pep updates to boltzmann. #269
* Fix link to intro tutorial. #267
* Updating template text visualization/ModularVisualization.md #273
* Update intro_notebook and documents to include self.running = True in MoneyModel #275
* Update .rst file location to make sure ReadTheDocs works correctly #276
* Remove Mock code causing recursion and preventing build of docs. #281
* MultiGrid docstring missing methods #282
* No Docstring for model.grid.get_cell_list_contents #282
* Refactor forest fire example #223 #288
* Updating kernel version on forest fire model. #290
* Making examples pep complaint. fixes #270 #291
* Fixed pep8 examples and #292 #294
* Fixes #283 - Fixes formatting on viz readme #299
* Have Agent use self.model instead of passing it around #297


0.7.5 (2016-06-20)
++++++++++++++++++

**Pre-sprints**

* Update of tutorial files and docs #176, #172
* Adds np.int64() functions around some variables to get rid error caused by numpy update #188
* Made examples Readme.md more readable #189

**From PyCon Sprints**

* Updating model example readmes #207
* Added nose to requirements #208
* Updated link on style google style guide #209
* Reset visualization when websocket connection is opened #210
* Remove unused scipy dependency #211
* Introduce a requirements.txt for the tutorial. #212
* Remove references to running in tutorial #213
* Simplify travis.yml; add python versions #215
* Update Flocker Readme.md #216
* Syntax error in .rst was swallowing a code block #217
* Fixup HistogramModule in the tutorial. #218
* add more test coverage to time #221
* add a requirements.txt for WolfSheep. #222
* add a requirements.txt for Schelling. #224
* Refactor color patches example #227
* Ignored _build sphinx docs still in repo #228
* Intro Tut completely in ipynb #230
* pass optional port parameter to ModularServer.launch #231
* open vis immediately when running color patches #232
* Adds .DS_store to .gitignore #237
* Documentation Update #240
* Small fix for reading links #241
* Test batchrunner #243
* clean up TextVisualization #245
* Documentation Update #250
* Update Game of Life example to new format #253
* Update Flockers example to new format #254
* Update Epstein model to new layout #255
* Subclassing object is unnecessary in Python 3 #258

**Post PyCon Sprints**

* Adds a copy of jquery directly into the code. #261


0.7.0 (2016-03-06)
++++++++++++++++++
* #184 Adding terminal echo for server launch to signal person running the model
* #183 Adding Conway's Game of Life simulation to the examples.

0.6.9 (2016-02-16)
++++++++++++++++++

* #170 Adding multi-stage activation
* #169 Wolf-Sheep Cleanup
* Updates requirements to latest libraries


0.6.7 (2015-07-11)
++++++++++++++++++

**Improvements**

* Allow cell_list_content methods in Grids to accept single tuples in addition to lists


0.6.6 (2015-07-11)
++++++++++++++++++

Theme: Scipy Sprints ( ‘-’)人(ﾟ_ﾟ )

**Improvements**

* Standardizes the arguments passed to spatial functions to only tuples, not separate x and y coordinates. (Breaks backwards compatibility)


0.6.5.1 (2015-07-11)
++++++++++++++++++

Theme: Scipy Sprints ( ‘-’)人(ﾟ_ﾟ )

**Improvements**

* Adding version, license, copyright, title to __init__.py
* Auto updating version in setup.py

**Fixes**

* Updating MANIFEST.in to include visualization templates that were missing.


0.6.5 (2015-07-11)
++++++++++++++++++

Theme: Scipy Sprints ( ‘-’)人(ﾟ_ﾟ )

**Edits**

* Additions to tutorial doc
* Minor edits to README & Intro
* Minor edits / clean up to setup.py
* Removing .ipynb_checkpoints
* Removing out-of-date planning documentation.

**Fixes**

* Use setuptools' find_packages function to get the list of packages to install, fixes #141

**Improvements**

* Use package_data for include the web files
* Use a MANIFEST.in file to include the LICENSE file in source distributions
* Using conda on Travis allows much faster builds and test runs


0.6.2 (2015-07-09)
++++++++++++++++++

* Improvement: Adding continuous space.
* Improvement: Adding a simultaneous activation scheduler.
* New models:
	- Flockers
	- Spatial Demographic Prisoner's Dilemma (PD_Grid)

0.6.1 (2015-06-27)
++++++++++++++++++

* Fixes: Order of operations reversed: agent is removed first and then it is placed.
* Improvement: `LICENSE`_ was updates from MIT to Apache 2.0.

.. _`LICENSE` : https://github.com/projectmesa/mesa/blob/master/LICENSE


0.6.0 (2015-06-21)
++++++++++++++++++

* Improvment: Add modular server feature, which breaks up a model into a .py file and a .js file. This breaks backwards compatibility.

Pre 0.6.0
++++++++++++++++++

Code that is pre-0.6.0 is very unstable.

Our inital release was 0.5.0 (2014-11).

It included code for placing agents on a grid; a data collector and batch runner; and a front-end visualization using HTML 5 and JavaScript.

**General**

* Objects create -- Agent, Time, Space
* Project moved to Python 3
* Tornado server setup

**Front-end**

* Front-end grid implemented
* ASCII visualization implemented

**Examples models**

* Forest Fire
* Schelling
* Wolf-Sheep Predation

**0.1.0 (2014-09-19)**

* A conversation
* Birth
