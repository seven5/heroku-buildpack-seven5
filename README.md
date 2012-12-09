# Heroku Buildpack: Seven5 Go Projects

This is a [Heroku buildpack][buildpack] for Seven5 projects.

This is shamelessly stolen from Keith Rarick, who wrote the original
Go buildpack.

This buildpack assumes your code is laid out like a standard Seven5 project.

```
//For project foo, the default layout is:
// foo/
//    Procfile
//    .godir
//    dart/
//    				foo/
//					      web/
//					      			assets/
//                pubspec.yaml
//                pubspec.lock
//                packages/
//                ...
//    db/
//    go/
//         bin/
//         pkg/
//         src/
//               foo/
//                     runfoo/
//                     				main.go
```


[buildpack]: http://devcenter.heroku.com/articles/buildpacks
[quickstart]: http://mmcgrana.github.com/2012/09/getting-started-with-go-on-heroku.html
