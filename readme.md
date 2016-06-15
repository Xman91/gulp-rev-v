# gulp-rev-v
> `unicorn.css` → `unicorn.css?v=d41d8cd98f`


same with `gul-rev` but add md5 after filename, work with `gulp-rev-collector-v`


## Install

```
$ npm install --save-dev gulp-rev-v
```


## Usage

```js
var gulp = require('gulp');
var revV = require('gulp-rev-v');

gulp.task('default', function () {
	return gulp.src('src/*.css')
		.pipe(revV())
		.pipe(gulp.dest('dist'));
});
```


## API
see [gulp-rev](https://www.npmjs.com/package/gulp-rev)
