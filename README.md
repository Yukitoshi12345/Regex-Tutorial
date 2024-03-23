<h1 align = "center"> Regex Tutorial </h1>

A **regex**, which is short for **regular expression**, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid email address:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.

My Regex Tutorial is published in my [Github Gist](https://gist.github.com/). Link [here!](https://gist.github.com/Yukitoshi12345/27923d704247fd749572fec721b433ed/)

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
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

## License

This project is licensed under the [MIT License](https://github.com/Yukitoshi12345/Regex-Tutorial/blob/main/LICENSE).
