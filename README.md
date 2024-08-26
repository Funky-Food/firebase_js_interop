Wrappers and tools for composing Firebase Cloud Functions in the Dart language

## Features

### Legend

|     |                 |
| --- | --------------- |
| 🟥  | No interop      |
| 🟧  | Limited interop |
| 🟨  | Partial interop |
| 🟩  | Full interop    |

### Admin

| Service            | Status | Comment              |
| ------------------ | ------ | -------------------- |
| App                | 🟩     |                      |
| App Check          | 🟥     |                      |
| Auth               | 🟥     |                      |
| Credential         | 🟥     |                      |
| Database           | 🟥     |                      |
| Eventarc           | 🟥     |                      |
| Extensions         | 🟥     |                      |
| Firestore          | 🟩     |                      |
| Functions          | 🟥     |                      |
| Installations      | 🟥     |                      |
| Messaging          | 🟧     | Only message sending |
| Project Management | 🟥     |                      |
| Remote Config      | 🟥     |                      |
| Security Rules     | 🟥     |                      |
| Storage            | 🟥     |                      |

## Functions

| Service        | Status |
| -------------- | ------ |
| Alerts         | 🟥     |
| Database       | 🟥     |
| Eventarc       | 🟥     |
| Firestore      | 🟩     |
| HTTPS          | 🟩     |
| Identity       | 🟩     |
| PubSub         | 🟥     |
| Remote Config  | 🟥     |
| Scheduler      | 🟥     |
| Storage        | 🟥     |
| Tasks          | 🟥     |
| Test Lab       | 🟥     |
| Global Options | 🟥     |
| onInit         | 🟥     |

## Future

Interop with the following packages is planned, but not yet implemented:

- [rules-unit-testing](https://github.com/firebase/firebase-js-sdk/tree/main/packages/rules-unit-testing)
- [firebase-functions-test](https://github.com/firebase/firebase-functions-test)

## Getting started

### firebase.json

Add the following ignores

```json
{
  "functions": [
    {
      "ignore": [
        "pubspec.*",
        "src",
        "tool",
        "analysis_options.yaml",
        ".dart_tool"
      ]
    }
  ]
}
```

## Usage

TODO: Include short and useful examples for package users. Add longer examples
to `/example` folder.

```dart
const like = 'sample';
```

## Additional information

TODO: Tell users more about the package: where to find more information, how to
contribute to the package, how to file issues, what response they can expect
from the package authors, and more.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)
