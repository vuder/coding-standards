Coding Standards
================

Date Created: 2016-10-07  
Last Modified: 2014-10-07 

These are the general coding standards for [TechArk][techark] Projects and any other resources which may be helpful in that respect.

Currently they fall into 8 categories:

1. [TechArk Software Development Fundamentals](techark_software_development_fundamentals.md)
2. [Git Guidelines and Best Practices](git_guidelines.md)
3. [C\# Coding Standards](csharp_coding_standards.md)
4. [HTML5/CSS3](html_css_coding_standards.md)
5. [JavaScript Coding Standards](javascript_coding_standards.md)
6. [Software Versioning Guidelines](software_versioning_guidelines.md)
7. [Unit Test Guidelines and Best Practices](unit_test_guidelines.md)


## Installation

Installation is as easy as checking out the repository to the correct location

	git clone https://github.com/TechArk/coding-standards.git

## Terminology & Definitions

|Term | Definition                                                |
|-------------| ----------------------------------------------------------|
|Access Modifier | keywords public, protected, internal, and private declare the allowed code-accessibility of types and their members. Although default access modifiers vary, classes and most other members use the default of private. Notable exceptions are interfaces and enums which both default to public.|
|Camel Case | A word with the first letter lowercase, and the first letter of each subsequent word-part capitalized. (e.g. **customerName**) |
|Pascal Case | A word with the first letter capitalized, and the first letter of each subsequent word-part capitalized. (e.g. **CustomerName**) |
| Magic Number | Any numeric literal used within an expression (or to initialize a variable) that does not have an obvious or well known meaning. This usually excludes the integers 0 or 1 and any other numeric equivalent precision that evaluates as zero. |
| Identifier | A developer defined token used to uniquely name a declared object or object instance. Example: `public class MyClassNameIdentifier { … }` |


[techark]: http://www.gotechark.com
