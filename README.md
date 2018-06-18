# # Xcode: Swift code snippets

Some convenient code snippets I've created while desiging apps. Code snippets are a great way to become more productive with Xcode. 
If you find yourself writing the same, or similar, piece of code over and over, then it's a good candidate for a user-defined code snippet.   

### All snippets work with **Swift 4** 

## How to create your own snippets

* Write your code snippet down at the code editor and select it.
* Be sure to open the code snippet library view within Xcode.
* Simply drag the selected code to the code snippet library.
* Enter a title and a short description of your snippet.
* Enter a shortcut for your snippet. You can choose any combination of letters but you should use something meaningful and you can remember easily.
* Choose a platform and the corresponding language the code snippet should be available in.
* The completion scope is also very handy to determine in which scopes (methods, class implementations, initializers, …) your code snippet should be available.
* The last step is to enter some placeholders within your code snippet. These placeholders will be shown as blue bubbles within your editor when using the code snippet and you can easily navigate to them by using your tab key. To create a placeholder just enter <#your_placeholder_name#>.

### Placeholder tokens
A placeholder makes it possible to make changes to the specific parts of the snippet at the time the snippet is added to your source code. A code snippet can have one or more placeholders, and you can tab between the placeholders as you modify the snippet in your source code.

To add a placeholder, include <#name#> in the code snippet where "name" is a string value that represents the placeholder. When the code snippet is used in your code, the placeholder will appear as a blue code bubble.

### Requirements:

* Xcode 9.0+
* Swift 3.0+

### Installation:
Code snippets are stored in your ~/Library/Developer/Xcode/UserData/CodeSnippets directory. 
Each code snippet file is a standalone plist file with a universally unique identifier (UUID), which I renamed to my liking, as the file name followed by .codesnippet as the file extension. 
This file-naming convention eliminates the chance of having conflicting file names when sharing snippets with others.

### Developer:

Clint Mejia - [clint_m@clintmejia.com](clint_m@clintmejia.com)


### License:

This project is licensed under the terms of the [MIT license](https://opensource.org/licenses/MIT).
