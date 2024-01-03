# flutter-djangoflow ✨

Welcome to the world of Flutter modules for DjangoFlow! This repository contains a collection of modules designed to enhance your Flutter development experience when working with DjangoFlow.

## Available Modules

| Module                         | Description                                                                                                                                                                                                                                                                                                                                                                                                           | Link                                                                                                                              |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| djangoflow_analytics           | djangoflow_analytics is a library for tracking analytics with multiple Analytics providers in Flutter applications. It is built on top of [analytics](https://pub.dev/packages/analytics/) package.                                                                                                                                                                                                                   | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_analytics/djangoflow_analytics)             |
| djangoflow_facebook_analytics  | djangoflow_facebook_analytics is a library built on top of the [analytics](https://pub.dev/packages/analytics/) and [facebook_app_events](https://pub.dev/packages/facebook_app_events/) packages for Flutter. It provides an easy and organized way to implement Facebook Analytics for your Flutter apps.                                                                                                           | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_analytics/djangoflow_facebook_analytics)    |
| djangoflow_firebase_analytics  | djangoflow_firebase_analytics is a library built on top of the [analytics](https://pub.dev/packages/analytics/) and [firebase_analytics](https://pub.dev/packages/firebase_analytics/) packages for Flutter. It provides an easy and organized way to implement Firebase Analytics for your Flutter apps.                                                                                                             |
| djangoflow_mixpanel_analytics  | djangoflow_mixpanel_analytics is a library built on top of the [analytics](https://pub.dev/packages/analytics/) and [mixpanel_flutter](https://pub.dev/packages/mixpanel_flutter/) packages for Flutter. It provides an easy and organized way to implement Mixpanel Analytics for your Flutter apps.                                                                                                                 | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_analytics/djangoflow_mixpanel_analytics)    |
| djangoflow_app                 | A simple, opinionated, and minimal Flutter application structure for quick start and easy maintenance.                                                                                                                                                                                                                                                                                                                | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_app)                                        |
| djangoflow_auth                | Your ultimate Flutter authentication companion, packed with DjangoFlow backend API support.                                                                                                                                                                                                                                                                                                                                   | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_auth)                                       |
| djangoflow_auth_apple          | Embrace the magic of Apple Sign-In within your Flutter app using djangoflow_auth!                                                                                                                                                                                                                                                                                                                                                           | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_auth/djangoflow_auth_apple)                 |
| djangoflow_auth_discord        | Bring the power of Discord authentication to your Flutter app with DjangoFlow backend API support!                                                                                                                                                                                                                                                                                                                                    | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_auth/djangoflow_auth_discord)               |
| djangoflow_auth_facebook       | Add a touch of Facebook magic to your Flutter app with DjangoFlow API support.                                                                                                                                                                                                                                                                                                                                                | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_auth/djangoflow_auth_facebook)              |
| djangoflow_auth_google         | The Google authentication provider for the djangoflow_auth package with backend API support.                                                                                                                                                                                                                                                                                                                                                   | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_auth/djangoflow_auth_google)                |
| djangoflow_chat (WIP)          | A complementary Flutter module for django-df-chat.                                                                                                                                                                                                                                                                                                                                                                    | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_chat)                                       |
| djangoflow_deep_link_interface | This package provides interface to implement handling deep-link in flutter applications.                                                                                                                                                                                                                                                                                                                              | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_deep_link/djangoflow_deep_link_interface)   |
| djangoflow_app_links           | This package is a concrete implementation of the djangoflow_deep_link_interface package which provides abstract classes for handling app links. It uses the app_links package, which provides a simple way to handle links on both Android and iOS.                                                                                                                                                                   | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_deep_link/djangoflow_app_links)             |
| djangoflow_emoji_rain          | Flutter package for creating a delightful rain of emojis on your screen.                                                                                                                                                                                                                                                                                                                                              | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_emoji_rain)                                 |
| djangoflow_local_notification  | A streamlined and flexible local notification solution for Flutter mobile apps on top of flutter_local_notifications.                                                                                                                                                                                                                                                                                                                                       | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_local_notification)                         |
| djangoflow_error_reporter      | DjangoFlow Error Reporter is a library that provides an easy and flexible way to handle errors in your flutter application. It allows you to add multiple error reporters and provides a singleton for managing them all. It also provides basic functionality for initializing, reporting and updating user information.                                                                                             | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_error_reporters/djangoflow_error_reporter)  |
| djangoflow_sentry_reporter     | DjangoFlow Sentry Reporter is a library that allows you to report errors to `Sentry` using the `DjangoFlowErrorReporter` class. It is built on top of the `sentry_flutter` package and provides a simple and easy to use class for reporting errors to Sentry.                                                                                                                                                        | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_error_reporters/djangoflow_sentry_reporter) |
| djangoflow_openapi             | An auto-generated package that contains API client details and models necessary to bridge the flutter and django app                                                                                                                                                                                                                                                                                                  | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_openapi)                                    |
| djangoflow_openapi_extensions  | djangoflow_openapi_extensions is a Flutter package that empowers your Dio error handling in DjangoFlow OpenAPI projects with style and ease. It has built in djangoflow related dio error transformer and nice scripts to boost productivity related to `djangoflow_openapi`                                                                                                                                          | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_openapi_extensions)                         |
| djangoflow_fcm                 | A Dart package that provides a simple and easy-to-use solution for handling Firebase Cloud Messaging (FCM) functionality in a Flutter app using Bloc. Can be extended to use with any other notification providers.                                                                                                                                                                                                   | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_push_notification/djangoflow_fcm)           |
| djangoflow_remote_config       | A Flutter package for managing remote configurations in your Flutter applications, designed to work seamlessly with [django-df-remote-config](https://github.com/djangoflow/django-df-remote-config). It can cache or load data from network on the go make the flutter apps be more dynamic.                                                                                                                         | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_remote_config)                              |
| djangoflow_scrollable_column   | A Flutter package that provides the `DjangoFlowScrollableColumn` widget, allowing you to create a vertically scrollable column of widgets with ease.                                                                                                                                                                                                                                                                  | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_scrollable_column)                          |
| djangoflow_websocket           | The project offers a set of classes and utilities to simplify WebSocket communication in Flutter applications. The core component is the DjangoFlowWebsocketCubit, which manages the WebSocket connection, emits DjangoFlowWebsocketState objects to represent the WebSocket state, and provides methods to connect and disconnect from the server. It handles automatic reconnection in case of connection failures. | [Link](https://github.com/djangoflow/flutter-djangoflow/tree/main/packages/djangoflow_websocket)                                  |

## Planned modules

- [ ] djangoflow_video_player: A flutter package that will provide ease to use Video Player widgets based on [video_player](https://pub.dev/packages/video_player/)
- [ ] djangoflow_survey: A flutter package that will facilate DjangoFlow API to render surveys on top of [survey_kit](https://pub.dev/packages/survey_kit) and [survey_flow](https://pub.dev/packages/survey_flow)

## Contribution Guideline

1. Fork the repository and create a new branch for your changes.
2. Make your changes and commit them using the following commit message format:

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

3. Push your changes to your branch and open a pull request.

## Melos Commit Patterns

[Melos](https://pub.dev/packages/melos) uses the following commit patterns to manage the versioning of your monorepo:

- `feat`: Introduces a new feature.
- `fix`: Fixes a bug.
- `docs`: Updates the documentation.
- `style`: Code style changes (no functionality changes).
- `refactor`: Refactors the code.
- `test`: Adds or updates tests.
- `chore`: Routine tasks, maintenance etc.
- `revert `: A change that reverts a previous commit.
- `perf`: A change that improves performance.

Example commit messages:

```
feat(auth): add user registration
fix(auth, ui): resolve layout issue on smaller screens
docs(analytics): update contribution guidelines
```

When you commit changes to the repository following these types of commit patterns, Melos will automatically generate changelogs and bump the version of the affected packages. More details about conventional commits, [click here](https://www.conventionalcommits.org/en/v1.0.0/#specification)

Here are some additional tips for contributing to your monorepo:

- Make sure your changes are well-tested.
- Use descriptive commit messages.
- Follow the coding style of the project.
- Be respectful and polite in your interactions with other contributors.
