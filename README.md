# PHP Core Exercises

A small collection of standalone PHP exercises for practicing core language features. Each script demonstrates a topic with sample data and runnable output; the calculator also provides a simple browser form.

## Why use this project?

- Explore PHP arrays, functions, loops, constants, type conversions, and arithmetic.
- Run each example independently and inspect its output.
- Use the examples as a starting point for learning and experimentation.

## Project contents

| File | Demonstration |
| --- | --- |
| [`arithmetic_operations.php`](arithmetic_operations.php) | A numeric calculator form, arithmetic, type conversions, and large-number checks. |
| [`array_utils.php`](array_utils.php) | Array intersections, duplicate removal, type filtering, sorting, and string conversion. |
| [`config_manager.php`](config_manager.php) | Constants, array constants, scope, and constant error handling. |
| [`grade_management.php`](grade_management.php) | Student grade averages, top performers, and rankings. |
| [`student_information.php`](student_information.php) | Functions, loops, variable scope, and a static counter. |

## Getting started

### Requirements

- PHP CLI. PHP 7.0 or later supports the language features used in these examples.
- A web browser to try the calculator form.

No dependency manager or third-party packages are required.

### Run the command-line examples

From the project directory, run any script with PHP:

```sh
php array_utils.php
php grade_management.php
php config_manager.php
```

The scripts print demonstrations using their included sample data. `student_information.php` also includes HTML line-break tags in its output, so view it in a browser for formatted output.

### Try the calculator in a browser

Start PHP's built-in development server from the project directory:

```sh
php -S 127.0.0.1:8000
```

Open [http://127.0.0.1:8000/arithmetic_operations.php](http://127.0.0.1:8000/arithmetic_operations.php), enter two numeric values, and submit the form. Use a nonzero second value because the example also calculates division and modulus.

## Help and support

For questions or to report a problem, [open an issue](https://github.com/VoidLance/course-files-php-core-exercises/issues) with the relevant script name and the command or steps you used.

## Maintainers and contributions

This repository is maintained by its project contributors. Contributions are welcome: open an issue to discuss a proposed change, then submit a pull request with a focused update and a description of how you tested it. Run the affected PHP script(s) before submitting.

There is no separate contribution guide in this repository yet.
