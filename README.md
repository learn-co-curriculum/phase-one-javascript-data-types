# Data Types in JavaScript

## Learning Goals

- Identify the different data types in JavaScript
- Identify JavaScript's 7 primitive data types
- Learn how to use the `typeof` operator

## Introduction

Computer programs can be boiled down into one simple purpose - handling,
manipulating, and analyzing information. In the programming world, we refer to
the information that computer programs work with as "data". Our job as
programmers is to write a set of instructions - a "program" - telling a computer
how its supposed to handle data.

In order for a progamming language to meet the needs of modern applications, it
needs to distinguish between differen types of data. If you've ever used a word
processor, like Microsoft Word or Google Docs, you were using a program that new
how to handle text - that's a certain type of data. If you've ever used a
calculator before, you were using a program that understood how to use numbers -
another type of data.

In addition to data like text and numbers, which programs might receive from the
outside world, programming languages also have types of data that are used to
run the program itself. Should a program choose to run one operation or another?
How do we represent an absence of data? How do we represent data that should be
grouped together? We have different data types that we can use to solve these
problems within our program.

At this point it might seem like we'd need tons of different data types to build
anything useful. In reality, we need very few! JavaScript itself only has 8 data
types, and it's one of the most widely used programming languages in the world!

In this lesson, we'll cover JavaScript's different data types, including its 7
"primitive" datatypes, its compound data type, "object", which can be used to
build complex data structures, as well as the `typeof` operator, which we can
use to analyze the data types of the different pieces of information we use in
our programs.

## The 7 Primitive Data Types

What is a "primitive" data type? We can think of primitive data types as the
build blocks of our programs - they are the simplest possible pieces of
information that we'll work with when writing code.

In other words, there is no "extra" data attached to any of our primitive data
types, as there is with complex data structures and data types - what you see is
what you get!

### Strings

We mentioned a "text" data type earlier, that might be used in programs like a
word processor or a news website displaying articles. JavaScript uses the
`string` data type to represent text.

We use quotation marks to create strings in JavaScript. We can using single
quotation marks, double quotation marks, and backticks to declare strings.

```JavaScript
"I am a string!"

'I am also a string!'

`I am a string too!`
```

JavaScript allows us to perform a variety of operations with strings, including
combining two strings together using the `+` operator:

```JavaScript
"Together, we make" + "an entire string!"
```

But what if we need to include something like an apostrophe within one of our
strings? Let's see what happen's if we use single quotes:

```JavaScript
'I didn't think I'd need an apostrophe when I started writing this string.'
```

Uh-oh - we wanted to make one string, but we ended up creating two strings and
left out a portion of our string. JavaScript thought our apostrophes were
instructions to end the string!

A similar problem occurs if we use double quotation marks and want to include a
quote within our string:

```JavaScript
"Here is my quoted text: "Why did the chicken cross the road?" Truly, one of the most compelling quotes in recorded history."
```

There are a couple ways we can avoid this - mix and match single quotes and
double quotes within our strings, or use the escape character `\` to tell
JavaScript that we don't want the string to end just yet:

```JavaScript
"Now I'm able to use apostrophes with ease."

"Another great quote: \"Knock knock, who's there?\" Who is there? Why are they there? So many unanswered questions..."
```

In general, it's convention to use double quotes when declaring a string.
Different style guides dictate different rules, but consistency is the most
important thing to follow. Many programmers use tools called "linters", which
analyze code and give styling instructions to maintain consistency. A popular
JavaScript tool is **ESLint**. You can [install it as a VS Code
extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
to more easily write clean, consistent programs.

#### String Interpolation



## Topic 2

Discuss the topic of the reading. Break into sections and sub-sections as
appropriate to help with the reader's orientation with the material and future
referencing.

## Conclusion

A short one or two paragraph summary of the contents of the lessons, recapping
the learning goals.

## Resources

- [Resource Link 1](example.com)
- [Resource Link 2](example.com)
