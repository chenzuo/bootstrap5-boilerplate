
# Bootstrap 5 Boilerplate - Basic

This is a Bootstrap 5 Boilerplate with Gulp 4+, cross-env, Sass, sourcemaps, concat, CSS & HTML minification, uglify, image optimization, template partials, BrowserSync.

[More in documentation](https://bootstrapstarter.com/template-basic5-bootstrap5-html/)

![bootstrapstarter](src/img/screenshot.png)




PS C:\Users\Jed\Documents\code\github\bootstrap5-boilerplate> npm run prod

> bootstrap5-boilerplate@1.0.1 prod
> cross-env NODE_ENV=prod gulp

[18:49:41] Using gulpfile ~\Documents\code\github\bootstrap5-boilerplate\gulpfile.js
[18:49:41] Starting 'default'...
[18:49:41] Starting 'del'...
[18:49:41] Finished 'del' after 69 ms
[18:49:41] Starting 'html'...
[18:49:41] Finished 'html' after 63 ms
[18:49:41] Starting 'css'...
[18:49:41] Finished 'css' after 708 ms
[18:49:41] Starting 'js'...
[18:49:44] Finished 'js' after 2.41 s
[18:49:44] Starting 'img'...
[18:49:44] gulp-imagemin: Minified 0 images
[18:49:44] 'img' errored after 287 ms
[18:49:44] Error in plugin "gulp-imagemin"
Message:
    ϵͳ�Ҳ���ָ����·����

    errno: ENOENT
    syscall: spawn C:\Users\Jed\Documents\code\github\bootstrap5-boilerplate\node_modules\optipng-bin\vendor\optipng.exe
    killed: false
    stdout:
    stderr: ϵͳ�Ҳ���ָ����·����

    failed: true
    signal: null
    cmd: C:\Users\Jed\Documents\code\github\bootstrap5-boilerplate\node_modules\optipng-bin\vendor\optipng.exe -strip all -clobber -fix -o 3 -out C:\Users\Jed\AppData\Local\Temp\2888baec-6cdf-4f75-ae2b-26c683f8f108 C:\Users\Jed\AppData\Local\Temp\07bafa1f-d1b0-4b33-b8e5-42ae80ec44b8
    timedOut: false
    fileName: C:\Users\Jed\Documents\code\github\bootstrap5-boilerplate\src\img\icon.png
    domainEmitter: [object Object]

[18:49:44] 'default' errored after 3.55 s
PS C:\Users\Jed\Documents\code\github\bootstrap5-boilerplate> npm rebuild
rebuilt dependencies successfully
PS C:\Users\Jed\Documents\code\github\bootstrap5-boilerplate> npm run prod
> cross-env NODE_ENV=prod gulp
[19:08:46] Using gulpfile ~\Documents\code\github\bootstrap5-boilerplate\gulpfile.js
[19:08:46] Starting 'default'...
[19:08:46] Starting 'del'...
[19:08:46] Finished 'del' after 63 ms
[19:08:46] Starting 'html'...
[19:08:46] Finished 'html' after 49 ms
[19:08:46] Starting 'css'...
[19:08:47] Finished 'css' after 657 ms
[19:08:47] Starting 'js'...
[19:08:49] Finished 'js' after 2.2 s
[19:08:49] Starting 'img'...
[19:08:49] gulp-imagemin: Minified 0 images
[19:08:49] gulp-imagemin: Minified 1 image (saved 257 B - 20.3%)
[19:08:49] Finished 'img' after 305 ms
[19:08:49] Finished 'default' after 3.28 s
PS C:\Users\Jed\Documents\code\github\bootstrap5-boilerplate>
