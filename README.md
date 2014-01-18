potmaker
============
bash script to update .pot & .po files with any strings found in .php code

Description
--------------------------------------
* Find a .pot file
* Find all strings in .php files
* Merge new strings with existing .pot file
* Merge .pot file with any .po files in same directory

Notes
--------------------------------------
* This script works from the current directory
* Sorts strings by file
* Creates new .pot file if there isn't one already

Changelog
--------------------------------------

#### 0.2
* Tests for no strings found
* Generates first file (it previously did nothing if there was no file to be updated)

#### 0.1
* Initial commit.
