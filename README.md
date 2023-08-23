# test-aggregation-plugin-error-repro

Empty Gradle project demonstrating this issue from the `gmazzo/gradle-android-test-aggregation-plugin` repo:
https://github.com/gmazzo/gradle-android-test-aggregation-plugin/issues/45


Run `./gradlew tasks` to reproduce the following error: 
```
FAILURE: Build failed with an exception.

* Where:
Build file '/Users/mitch.ware/Desktop/Workspace/test-report-repro/build.gradle' line: 23

* What went wrong:
An exception occurred applying plugin request [id: 'io.github.gmazzo.test.aggregation.results', version: '1.1.1']
> Failed to apply plugin 'io.github.gmazzo.test.aggregation.results'.
   > Cannot add a ReportSpec with name 'testAggregateTestReport' as a ReportSpec with that name already exists.
```
