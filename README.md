Installation
============

Installing SASS (If using Windows, should install Ruby first): **gem install sass**

Usage Examples
==============

Running SASS from command line: **sass input.scss filename.scss**

Watching the file (when input file changes, generating output file): **sass --watch input1.scss:input1.css input2.scss:input2.css**

Watching the directory: **sass --watch folder1:folder2**

Output styles
=============

Nested style: **sass --style nested styles.scss:nested.css**

Expanded style: **sass --style expanded styles.scss:expanded.css**

Compact style: **sass --style compact styles.scss:compact.css**

Compressed style: **sass --style compressed styles.scss:compressed.css**