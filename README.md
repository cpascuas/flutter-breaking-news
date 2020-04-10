[![License](https://img.shields.io/static/v1?label=Licence&message=MIT&color=lightgrey)](https://img.shields.io/static/v1?label=Licence&message=MIT&color=lightgrey)

| Gitlab CI | Code Coverage | Coverage with codecov.io |
|--------------------|-------|------------------|
|[![pipeline status](https://gitlab.com/bwnyasse/flutter-breaking-news/badges/master/pipeline.svg)](https://gitlab.com/bwnyasse/flutter-breaking-news/commits/master)| [![coverage report](https://gitlab.com/bwnyasse/flutter-breaking-news/badges/master/coverage.svg)](https://gitlab.com/bwnyasse/flutter-breaking-news/commits/master) |[![codecov](https://codecov.io/gl/bwnyasse/flutter-breaking-news/branch/master/graph/badge.svg)](https://codecov.io/gl/bwnyasse/flutter-breaking-news) |

| Platform | Deploy to Firebase App Distribtion | Tests |
|--------------------|-------|------------------|
| [![Flutter](https://img.shields.io/static/v1?label=Flutter&message=ANDROID-IOS&color=informational?style=plastic&logo=flutter&logoColor=blue)](https://img.shields.io/static/v1?label=Flutter&message=ANDROID-IOS&color=blue&logo=flutter&logoColor=blue)| [![Codemagic build status](https://api.codemagic.io/apps/5e8a523364e0bd58fe01acbe/5e8a523364e0bd58fe01acbd/status_badge.svg)](https://codemagic.io/apps/5e8a523364e0bd58fe01acbe/5e8a523364e0bd58fe01acbd/latest_build) | [![Codemagic build status](https://api.codemagic.io/apps/5e8a523364e0bd58fe01acbe/5e8a523364e0bd58fe01acbd/status_badge.svg)](https://codemagic.io/apps/5e8a523364e0bd58fe01acbe/5e8a523364e0bd58fe01acbd/latest_build) |


# flutter_breaking_news

Stack Labs Open Source project
to display how to build a complete flutter breaking news application.


## Getting Started


[Understand Flutter Flavors](https://medium.com/@animeshjain/build-flavors-in-flutter-android-and-ios-with-different-firebase-projects-per-flavor-27c5c5dac10b)
[Adding way to switch app name on ISO](https://www.buddybuild.com/blog/running-multiple-schemes-of-ios-apps)
[Copy to right file](https://www.tengio.com/blog/multiple-firebase-environments-with-flutter/)
TODO.

flutter build apk --release -t lib/main_qa.dart --build-name=1.0.0 --build-number=1 --flavor qa

flutter build ios --no-codesign --release -t lib/main_qa.dart --build-name=1.0.0 --build-number=1 --flavor qa

