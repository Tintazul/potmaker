potmaker
========

bash script to update .pot files with any strings found in .php code, and either push the .pot to Transifex or update any .po files locally

Description
-----------

* Find a .pot file
* Find all strings in .php files
* Merge new strings with existing .pot file
* If Transifex is enabled, push the .pot
* If not, merge .pot file with any .po files in same directory

Notes
-----

* This script works from the current directory
* Sorts strings by file
* Creates new .pot file if there isn't one already
* Transifex support is detected by the presence of `.tx/config`

Changelog
---------

#### 0.4

* Added: Transifex support (if Transifex is set up, it pushes the .pot; if not, it updates the .po files from the .pot)

#### 0.3

* It now handles plurals correctly

#### 0.2

* Tests for no strings found
* Generates first file (it previously did nothing if there was no file to be updated)

#### 0.1

* Initial commit.
