# Windsurf Style Guide
# Language: C#

## Overview
This style guide provides a set of conventions and best practices for writing clean, readable, and maintainable C# code. It is intended for developers working on the Windsurf project, and covers coding conventions, naming standards, and other best practices for C# development.

## Variable Naming Conventions
* Use explicit type names for variable declarations.
* For single-line initialization, use the following format:
SomeClass variable = new();
* For multi-line initialization, use the following format:
SomeClass variable; variable = new SomeClass();
* use _camelCase for private field/property names
* use PascalCase for public or protected field/property names
* Avoid using abbreviations or acronyms unless they are widely recognized.

## Code Formatting
* Use 4 spaces for indentation.
* Use blank lines to separate logical sections of code.
* Use curly braces to enclose code blocks, even if they are single-line.

## Code Organization
* Method Length: Methods should be concise and focused on a single task. Aim for a maximum of 20-30 lines of code per method.
* Break down long methods: If a method is too long or complex, break it down into smaller, more manageable pieces. This makes the code easier to read and maintain.
* Single Responsibility Principle: Each method should have a single responsibility and should not be responsible for multiple, unrelated tasks.

## Class and Method Naming Conventions
* Use PascalCase for class and method names.
* Use descriptive names that indicate the purpose of the class or method.

## Other Conventions
* Use `using` statements instead of fully qualified type names.
* Avoid using `static` classes unless necessary.
