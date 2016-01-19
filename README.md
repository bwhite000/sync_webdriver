Dart Sync WebDriver
===================

Installing
----------

This library depends on https://github.com/google/dart-sync-socket which uses
a native extension. After doing a pub get or upgrade, you must build the native extension
by running:
```
  # ./packages/sync_socket/../tool/build.sh
```

Projects that use Sync WebDriver should include the following in their
pubspec.yaml:

```
sync_webdriver: '^1.2.0'
```
