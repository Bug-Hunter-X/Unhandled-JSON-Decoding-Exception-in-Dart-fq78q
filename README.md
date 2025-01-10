# Unhandled JSON Decoding Exception in Dart

This repository demonstrates a common error in Dart applications involving network requests and JSON decoding.  The initial `bug.dart` file showcases code that fails to handle `FormatException` exceptions that can occur when `jsonDecode` encounters invalid JSON data.  The solution, provided in `bugSolution.dart`, illustrates robust error handling to prevent application crashes.