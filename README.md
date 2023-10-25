# Flutter Legacy Plugins

This repository is used to support some old codebases which require versions of flutter plugins that are no longer supported. Small ajustments are made to keep the plugins working with newer OS versions (for now).

## image_picker

The `image_picker` plugin is at version v0.6.7+22 and has been adjusted to support the new permissions required by Android 13 (`READ_MEDIA_VIDEO`, `READ_MEDIA_IMAGES`). 

Use image_picker like this:
```
dependencies:
  image_picker:
    git: git@github.com:Siarl/flutter_legacy_plugins.git
    ref: image_picker-v0.6.7+22-1
    path: packages/image_picker/image_picker
```

---

# Flutter plugins

[![Build Status](https://api.cirrus-ci.com/github/flutter/plugins.svg)](https://cirrus-ci.com/github/flutter/plugins/master)

This repo is a companion repo to the main [flutter
repo](https://github.com/flutter/flutter). It contains the source code for
Flutter first-party plugins (i.e., plugins developed by the core Flutter team).
Check the `packages` directory for all plugins.

Flutter plugins enable access to platform-specific APIs. For more information
about plugins, and how to use them, see
[https://flutter.dev/platform-plugins/](https://flutter.dev/platform-plugins/).

These plugins are also available on
[pub](https://pub.dev/flutter/packages).

## Issues

Please file any issues, bugs, or feature requests in the [main flutter
repo](https://github.com/flutter/flutter/issues/new).

## Contributing

If you wish to contribute a new plugin to the Flutter ecosystem, please
see the documentation for [developing packages](https://flutter.dev/developing-packages/) and
[platform channels](https://flutter.dev/platform-channels/). You can store
your plugin source code in any GitHub repository (the present repo is only
intended for plugins developed by the core Flutter team). Once your plugin
is ready you can [publish](https://flutter.dev/developing-packages/#publish)
to the [pub repository](https://pub.dev/).

If you wish to contribute a change to any of the existing plugins in this repo,
please review our [contribution guide](https://github.com/flutter/plugins/blob/master/CONTRIBUTING.md),
and send a [pull request](https://github.com/flutter/plugins/pulls).

## Plugins
These are the available plugins in this repository.

| Plugin | Pub | Points | Popularity | Likes |
|--------|-----|--------|------------|-------|
| [android_alarm_manager](./packages/android_alarm_manager/) | [![pub package](https://img.shields.io/pub/v/android_alarm_manager.svg)](https://pub.dev/packages/android_alarm_manager) | [![pub points](https://badges.bar/android_alarm_manager/pub%20points)](https://pub.dev/packages/android_alarm_manager/score) |  [![popularity](https://badges.bar/android_alarm_manager/popularity)](https://pub.dev/packages/android_alarm_manager/score) | [![likes](https://badges.bar/android_alarm_manager/likes)](https://pub.dev/packages/android_alarm_manager/score) |
| [android_intent](./packages/android_intent/) | [![pub package](https://img.shields.io/pub/v/android_intent.svg)](https://pub.dev/packages/android_intent) | [![pub points](https://badges.bar/android_intent/pub%20points)](https://pub.dev/packages/android_intent/score) | [![popularity](https://badges.bar/android_intent/popularity)](https://pub.dev/packages/android_intent/score) | [![likes](https://badges.bar/android_intent/likes)](https://pub.dev/packages/android_intent/score) |
| [battery](./packages/battery/) | [![pub package](https://img.shields.io/pub/v/battery.svg)](https://pub.dev/packages/battery) | [![pub points](https://badges.bar/battery/pub%20points)](https://pub.dev/packages/battery/score) | [![popularity](https://badges.bar/battery/popularity)](https://pub.dev/packages/battery/score) | [![likes](https://badges.bar/battery/likes)](https://pub.dev/packages/battery/score) |
| [camera](./packages/camera/) | [![pub package](https://img.shields.io/pub/v/camera.svg)](https://pub.dev/packages/camera) | [![pub points](https://badges.bar/camera/pub%20points)](https://pub.dev/packages/camera/score) | [![popularity](https://badges.bar/camera/popularity)](https://pub.dev/packages/camera/score) | [![likes](https://badges.bar/camera/likes)](https://pub.dev/packages/camera/score) |
| [connectivity](./packages/connectivity/) | [![pub package](https://img.shields.io/pub/v/connectivity.svg)](https://pub.dev/packages/connectivity) | [![pub points](https://badges.bar/connectivity/pub%20points)](https://pub.dev/packages/connectivity/score) | [![popularity](https://badges.bar/connectivity/popularity)](https://pub.dev/packages/connectivity/score) | [![likes](https://badges.bar/connectivity/likes)](https://pub.dev/packages/connectivity/score) |
| [device_info](./packages/device_info/) | [![pub package](https://img.shields.io/pub/v/device_info.svg)](https://pub.dev/packages/device_info) | [![pub points](https://badges.bar/device_info/pub%20points)](https://pub.dev/packages/device_info/score) | [![popularity](https://badges.bar/device_info/popularity)](https://pub.dev/packages/device_info/score) | [![likes](https://badges.bar/device_info/likes)](https://pub.dev/packages/device_info/score) |
| [e2e (Discontinued, use integration_test)](./packages/e2e/) | [![pub package](https://img.shields.io/pub/v/e2e.svg)](https://pub.dev/packages/e2e) | [![pub points](https://badges.bar/e2e/pub%20points)](https://pub.dev/packages/e2e/score) | [![popularity](https://badges.bar/e2e/popularity)](https://pub.dev/packages/e2e/score) | [![likes](https://badges.bar/e2e/likes)](https://pub.dev/packages/e2e/score) |
| [espresso](./packages/espresso/) | [![pub package](https://img.shields.io/pub/v/espresso.svg)](https://pub.dev/packages/espresso) | [![pub points](https://badges.bar/espresso/pub%20points)](https://pub.dev/packages/espresso/score) | [![popularity](https://badges.bar/espresso/popularity)](https://pub.dev/packages/espresso/score) | [![likes](https://badges.bar/espresso/likes)](https://pub.dev/packages/espresso/score) |
| [flutter_plugin_android_lifecycle](./packages/flutter_plugin_android_lifecycle/) | [![pub package](https://img.shields.io/pub/v/flutter_plugin_android_lifecycle.svg)](https://pub.dev/packages/flutter_plugin_android_lifecycle) | [![pub points](https://badges.bar/flutter_plugin_android_lifecycle/pub%20points)](https://pub.dev/packages/flutter_plugin_android_lifecycle/score) | [![popularity](https://badges.bar/flutter_plugin_android_lifecycle/popularity)](https://pub.dev/packages/flutter_plugin_android_lifecycle/score) | [![likes](https://badges.bar/flutter_plugin_android_lifecycle/likes)](https://pub.dev/packages/flutter_plugin_android_lifecycle/score) |
| [google_maps_flutter](./packages/google_maps_flutter) | [![pub package](https://img.shields.io/pub/v/google_maps_flutter.svg)](https://pub.dev/packages/google_maps_flutter) | [![pub points](https://badges.bar/google_maps_flutter/pub%20points)](https://pub.dev/packages/google_maps_flutter/score) | [![popularity](https://badges.bar/google_maps_flutter/popularity)](https://pub.dev/packages/google_maps_flutter/score) | [![likes](https://badges.bar/google_maps_flutter/likes)](https://pub.dev/packages/google_maps_flutter/score) |
| [google_sign_in](./packages/google_sign_in/) | [![pub package](https://img.shields.io/pub/v/google_sign_in.svg)](https://pub.dev/packages/google_sign_in) | [![pub points](https://badges.bar/google_sign_in/pub%20points)](https://pub.dev/packages/google_sign_in/score) | [![popularity](https://badges.bar/google_sign_in/popularity)](https://pub.dev/packages/google_sign_in/score) | [![likes](https://badges.bar/google_sign_in/likes)](https://pub.dev/packages/google_sign_in/score) |
| [image_picker](./packages/image_picker/) | [![pub package](https://img.shields.io/pub/v/image_picker.svg)](https://pub.dev/packages/image_picker) | [![pub points](https://badges.bar/image_picker/pub%20points)](https://pub.dev/packages/image_picker/score) | [![popularity](https://badges.bar/image_picker/popularity)](https://pub.dev/packages/image_picker/score) | [![likes](https://badges.bar/image_picker/likes)](https://pub.dev/packages/image_picker/score) |
| [integration_test](./packages/integration_test/) | [![pub package](https://img.shields.io/pub/v/integration_test.svg)](https://pub.dev/packages/integration_test) | [![pub points](https://badges.bar/integration_test/pub%20points)](https://pub.dev/packages/integration_test/score) | [![popularity](https://badges.bar/integration_test/popularity)](https://pub.dev/packages/integration_test/score) | [![likes](https://badges.bar/integration_test/likes)](https://pub.dev/packages/integration_test/score) |
| [in_app_purchase](./packages/in_app_purchase/) | [![pub package](https://img.shields.io/pub/v/in_app_purchase.svg)](https://pub.dev/packages/in_app_purchase) | [![pub points](https://badges.bar/in_app_purchase/pub%20points)](https://pub.dev/packages/in_app_purchase/score) | [![popularity](https://badges.bar/in_app_purchase/popularity)](https://pub.dev/packages/in_app_purchase/score) | [![likes](https://badges.bar/in_app_purchase/likes)](https://pub.dev/packages/in_app_purchase/score) |
| [ios_platform_images](./packages/ios_platform_images/) | [![pub package](https://img.shields.io/pub/v/ios_platform_images.svg)](https://pub.dev/packages/ios_platform_images) | [![pub points](https://badges.bar/ios_platform_images/pub%20points)](https://pub.dev/packages/ios_platform_images/score) | [![popularity](https://badges.bar/ios_platform_images/popularity)](https://pub.dev/packages/ios_platform_images/score) | [![likes](https://badges.bar/ios_platform_images/likes)](https://pub.dev/packages/ios_platform_images/score) |
| [local_auth](./packages/local_auth/) | [![pub package](https://img.shields.io/pub/v/local_auth.svg)](https://pub.dev/packages/local_auth) | [![pub points](https://badges.bar/local_auth/pub%20points)](https://pub.dev/packages/local_auth/score) | [![popularity](https://badges.bar/local_auth/popularity)](https://pub.dev/packages/local_auth/score) | [![likes](https://badges.bar/local_auth/likes)](https://pub.dev/packages/local_auth/score) |
| [package_info](./packages/package_info/) | [![pub package](https://img.shields.io/pub/v/package_info.svg)](https://pub.dev/packages/package_info) | [![pub points](https://badges.bar/package_info/pub%20points)](https://pub.dev/packages/package_info/score) | [![popularity](https://badges.bar/package_info/popularity)](https://pub.dev/packages/package_info/score) | [![likes](https://badges.bar/package_info/likes)](https://pub.dev/packages/package_info/score) |
| [path_provider](./packages/path_provider/) | [![pub package](https://img.shields.io/pub/v/path_provider.svg)](https://pub.dev/packages/path_provider) | [![pub points](https://badges.bar/path_provider/pub%20points)](https://pub.dev/packages/path_provider/score) | [![popularity](https://badges.bar/path_provider/popularity)](https://pub.dev/packages/path_provider/score) | [![likes](https://badges.bar/path_provider/likes)](https://pub.dev/packages/path_provider/score) |
| [plugin_platform_interface](./packages/plugin_platform_interface/) | [![pub package](https://img.shields.io/pub/v/plugin_platform_interface.svg)](https://pub.dev/packages/plugin_platform_interface) | [![pub points](https://badges.bar/plugin_platform_interface/pub%20points)](https://pub.dev/packages/plugin_platform_interface/score) | [![popularity](https://badges.bar/plugin_platform_interface/popularity)](https://pub.dev/packages/plugin_platform_interface/score) | [![likes](https://badges.bar/plugin_platform_interface/likes)](https://pub.dev/packages/plugin_platform_interface/score) |
| [quick_actions](./packages/quick_actions/) | [![pub package](https://img.shields.io/pub/v/quick_actions.svg)](https://pub.dev/packages/quick_actions) | [![pub points](https://badges.bar/quick_actions/pub%20points)](https://pub.dev/packages/quick_actions/score) | [![popularity](https://badges.bar/quick_actions/popularity)](https://pub.dev/packages/quick_actions/score) | [![likes](https://badges.bar/quick_actions/likes)](https://pub.dev/packages/quick_actions/score) |
| [sensors](./packages/sensors/) | [![pub package](https://img.shields.io/pub/v/sensors.svg)](https://pub.dev/packages/sensors) | [![pub points](https://badges.bar/sensors/pub%20points)](https://pub.dev/packages/sensors/score) | [![popularity](https://badges.bar/sensors/popularity)](https://pub.dev/packages/sensors/score) | [![likes](https://badges.bar/sensors/likes)](https://pub.dev/packages/sensors/score) |
| [share](./packages/share/) | [![pub package](https://img.shields.io/pub/v/share.svg)](https://pub.dev/packages/share) | [![pub points](https://badges.bar/share/pub%20points)](https://pub.dev/packages/share/score) | [![popularity](https://badges.bar/share/popularity)](https://pub.dev/packages/share/score) | [![likes](https://badges.bar/share/likes)](https://pub.dev/packages/share/score) |
| [shared_preferences](./packages/shared_preferences/) | [![pub package](https://img.shields.io/pub/v/shared_preferences.svg)](https://pub.dev/packages/shared_preferences) | [![pub points](https://badges.bar/shared_preferences/pub%20points)](https://pub.dev/packages/shared_preferences/score) | [![popularity](https://badges.bar/shared_preferences/popularity)](https://pub.dev/packages/shared_preferences/score) | [![likes](https://badges.bar/shared_preferences/likes)](https://pub.dev/packages/shared_preferences/score) |
| [url_launcher](./packages/url_launcher/) | [![pub package](https://img.shields.io/pub/v/url_launcher.svg)](https://pub.dev/packages/url_launcher) | [![pub points](https://badges.bar/url_launcher/pub%20points)](https://pub.dev/packages/url_launcher/score) | [![popularity](https://badges.bar/url_launcher/popularity)](https://pub.dev/packages/url_launcher/score) | [![likes](https://badges.bar/url_launcher/likes)](https://pub.dev/packages/url_launcher/score) |
| [video_player](./packages/video_player/) | [![pub package](https://img.shields.io/pub/v/video_player.svg)](https://pub.dev/packages/video_player) | [![pub points](https://badges.bar/video_player/pub%20points)](https://pub.dev/packages/video_player/score) | [![popularity](https://badges.bar/video_player/popularity)](https://pub.dev/packages/video_player/score) | [![likes](https://badges.bar/video_player/likes)](https://pub.dev/packages/video_player/score) |
| [webview_flutter](./packages/webview_flutter/) | [![pub package](https://img.shields.io/pub/v/webview_flutter.svg)](https://pub.dev/packages/webview_flutter) | [![pub points](https://badges.bar/webview_flutter/pub%20points)](https://pub.dev/packages/webview_flutter/score) | [![popularity](https://badges.bar/webview_flutter/popularity)](https://pub.dev/packages/webview_flutter/score) | [![likes](https://badges.bar/webview_flutter/likes)](https://pub.dev/packages/webview_flutter/score) |
