# license headers #
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

This if fork of [Sbt header](https://github.com/sbt/sbt-header) with sbt part stripped off.

Add to your build.sbt:
```
libraryDependencies += "com.github.rockjam" %% "license-headers" % "0.0.1"
```

or to your build.sc:
```
def ivyDeps = 
  super.ivyDeps ++ Seq(ivy"com.github.rockjam::license-headers:0.0.1")
```

## Contribution policy ##

Contributions via GitHub pull requests are gladly accepted from their original author. Along with any pull requests, please state that the contribution is your original work and that you license the work to the project under the project's open source license. Whether or not you state this explicitly, by submitting any copyrighted material via pull request, email, or other means you agree to license the material under the project's open source license and warrant that you have the legal authority to do so.

## License ##

This code is open source software licensed under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html).
