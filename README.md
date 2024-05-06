<h1 align = "center"> Regex Tutorial </h1>

A **regex**, which is short for **regular expression**, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid email address:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.

My Regex Tutorial is published in my Github Gist. Link [here!](https://gist.github.com/Yukitoshi12345/27923d704247fd749572fec721b433ed/)

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Central Grader Comments](#central-grader-comments)
- [License](#license)

## User Story

```
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines
```

## Acceptance Criteria

```
GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile
```

## Installation

The project was uploaded to [GitHub Gist](https://gist.github.com/) at the following repository:
[https://gist.github.com/Yukitoshi12345/27923d704247fd749572fec721b433ed/](https://gist.github.com/Yukitoshi12345/27923d704247fd749572fec721b433ed/)

## Central Grader Comments

Grade: 100/100

Hello Yukitoshi,

Great job at this challenge attempt! You were tasked with building a Gist on a regular expression. For your topic, you selected an email matching regex and wrote up a tutorial utilizing markdown to break up the expression into its components. Most of the time, we do not see people utilize tables but it really adds a level of polish that shows you took the time to make something you should be proud of! The tutorial features a functioning table of contents, breaks down your specific expression into its individual components with the code snippets that relate to the section, and finally, includes examples of passing test code for the expression. Overall, the tutorial has a great level of detail and polish that would help anyone understand an email regex expression in a beneficial way. This challenge introduces a non-conventional networking tool and with the quality of this tutorial I would highly recommend sharing this through channels available to you and consider writing more topics! These guides can be very handy for other developers starting out but you can choose any topic that you think may be worthy of a write up. Great job!

- QP, Centralized Grading.

## License

This project is licensed under the [MIT License](https://github.com/Yukitoshi12345/Regex-Tutorial/blob/main/LICENSE).
