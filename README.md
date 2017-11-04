<p align="center">
    <img src="https://cloud.githubusercontent.com/assets/1342803/24797159/52fb0d88-1b90-11e7-85a5-359fff0496a4.png" width="320" alt="MySQL">
    <br>
    <br>
    <a href="http://beta.docs.vapor.codes/getting-started/hello-world/">
        <img src="http://img.shields.io/badge/read_the-docs-92A8D1.svg" alt="Documentation">
    </a>
    <a href="http://vapor.team">
        <img src="http://vapor.team/badge.svg" alt="Slack Team">
    </a>
    <a href="LICENSE">
        <img src="http://img.shields.io/badge/license-MIT-brightgreen.svg" alt="MIT License">
    </a>
    <a href="https://circleci.com/gh/vapor/mysql">
        <img src="https://circleci.com/gh/vapor/mysql.svg?style=shield" alt="Continuous Integration">
    </a>
    <a href="https://travis-ci.org/vapor/api-template">
    	<img src="https://travis-ci.org/vapor/api-template.svg?branch=master" alt="Build Status">
    </a>
    <a href="https://swift.org">
        <img src="http://img.shields.io/badge/swift-3.1-brightgreen.svg" alt="Swift 3.1">
    </a>
</center>

``` sh
swift --version
# Apple Swift version 4.0.2 (swiftlang-900.0.69.2 clang-900.0.38)
# Target: x86_64-apple-macosx10.9

brew info vapor
# vapor/tap/vapor: stable 3.1.2
# /usr/local/Cellar/vapor/3.0.3 (4 files, 16.7MB)
#  Built from source on 2017-10-17 at 11:16:19

vapor new TemplateApiTest --template=api
cd TemplateApiTest/

swift package tools-version
# 4.0.0

rm Package.resolved
vapor update

vapor --version
# Vapor Toolbox: 3.1.2
# Vapor Framework: 2.3.0
```

There are about 44 new deprecation warnings of the same type at this time.

> 'characters' is deprecated: Please use String or Substring directly".

This project did build and run OK (0 errors) with Xcode 9.1 (9B55) + Vapor 2.3.0 + Swift 4.0.2.

