# Typing Speed Test

This Python script allows you to run a typing speed test with customizable parameters. You can specify the number of tests, the number of sentences per test, and whether to enable blind mode.

## Features

- Run multiple typing tests
- Customize the number of sentences per test
- Enable or disable blind mode

## Requirements

- Python 3.x

## Installation

Use following command for installation:

```sh
pip3 install typing-test-sapien
```

## Usage

Run the following command:

```sh
typing-test-sapien
```

### Arguments

- `tests` (optional): The number of tests to run (default: 2).
- `sentences_per_test` (optional): The number of sentences per test (default: 1).
- `blind_mode` (optional): Set to 'y' or 'yes' to enable blind mode (default: no).

### Example

```sh
typing-test-sapien 3 2 yes
```

This command runs 3 tests with 2 sentences per test and enables blind mode.

## Handling Invalid Input

If invalid input is provided, the script will silently fallback to default values.

## Exiting

To exit the test at any time, press `Ctrl+C`.

## License

This project is licensed under the MIT License.