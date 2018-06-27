#gulp-include [![NPM version][npm-image]][npm-url] ![Travis build][travis-image]
>Makes inclusion of files a breeze.  
Enables functionality similar to that of snockets / sprockets or other file insertion compilation tools.

Fork of the [gulp-include](https://www.npmjs.com/package/gulp-include) with 'separateInputs' option:
  
- `separateInputs` (optional)
  * Boolean, `true` by default
  * Set this to `false` if you want to process each input file independent, when executing "require" logic. 
  So, if file required several times inside one file (or inside required by it files), then dublicates will be ignored. 
  But when another file will begin processing, all information about required files from previuos file will be discarded.