# Pipenv Test Case 3: Pipfile with python_version

## What This Tests
Tests detection of Python version from Pipfile using the `python_version` field (major.minor format).

## Expected
3.11 found through PipfilePythonVersion

## Files
- `Pipfile` - Contains `python_version = "3.11"` in requires section

## Expected Behavior
Your version detection tool should detect **Python 3.11** from Pipfile.

## Priority
This is the **third priority** detection method for Pipenv projects (after .python-version and .tool-versions).

## Note
The `python_version` field typically contains major.minor versions like "3.11" without the patch version.
