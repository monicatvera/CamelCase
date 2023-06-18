# Kata CamelCase
In this kata we are asked to implement a pure function that converts a text, whose words are delimited by dashes, both leading and trailing hyphens, and spaces, in camel case format.

Within the camel case style, there are two, mainly: the UpperCamelCase, better known as PascalCase, which occurs when the first letter of each of the words is uppercase, and lowerCamelCase, which is the same as the previous one with the exception that the first letter is lowercase.

In our case we are going to implement the first one, the PascalCase style.

## Test list

- [ ] An empty string must be returned as is. Ex: “”⇒””
- [ ] For a word with the first letter capitalized the result should be the same. Ex: “Foo” ⇒ “Foo”
- [ ] For a text containing words with the first letter capitalized, separated by spaces, we return the joined words in the camel case format. Ex: “Foo Bar” ⇒ “FooBar”
- [ ] For a text that contains words with the first capital letter, separated by hyphens, you must return the joined words. Ex: “Foo_Bar-Foo” ⇒ “FooBarFoo”
- [ ] For a word with the first letter in lowercase the result should return the same word with the first letter in uppercase. Ex: “foo” ⇒ “Foo”
- [ ] For a text that contains lowercase words you must transform each word to uppercase and join them. “foo_bar foo-bar” ⇒ “FooBarFooBar”