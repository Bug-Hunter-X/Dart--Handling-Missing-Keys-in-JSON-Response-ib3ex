# Dart: Handling Missing Keys in JSON Response

This repository demonstrates a common error in Dart when handling JSON responses: attempting to access keys that might not exist.  The `bug.dart` file shows the problematic code, while `bugSolution.dart` provides a corrected version.

The bug arises when the application assumes the presence of certain keys in the JSON response, leading to runtime exceptions if those keys are missing. The solution introduces robust error handling and checks for key existence before access.

## How to run
1. Clone this repository.
2. Run the files using a Dart compiler or IDE.