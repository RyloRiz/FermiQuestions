# Fermi Questions Online Practice Test

[![Stars](https://img.shields.io/github/stars/EricAndrechek/FermiQuestions)](https://github.com/EricAndrechek/FermiQuestions/stargazers)
[![Open Issues](https://img.shields.io/github/issues-raw/EricAndrechek/FermiQuestions)](https://github.com/EricAndrechek/FermiQuestions/issues?q=is%3Aopen+is%3Aissue)
[![Closed Issues](https://img.shields.io/github/issues-closed-raw/EricAndrechek/FermiQuestions)](https://github.com/EricAndrechek/FermiQuestions/issues?q=is%3Aissue+is%3Aclosed)
[![wakatime](https://wakatime.com/badge/github/EricAndrechek/FermiQuestions.svg)](https://wakatime.com/badge/github/EricAndrechek/FermiQuestions)
[![PayPal](https://img.shields.io/badge/PayPal-Donate-green)](https://paypal.me/AndrechekEric)
[![GitHub Sponsors](https://img.shields.io/badge/GitHub%20Sponsors-Donate-green)](https://github.com/sponsors/EricAndrechek)

This project was designed to be a friendly and easy-to-use site for students to practice for the fermi questions Science Olympiad event.

## Adding a Question

To add a question, open the `question-bank.json` file and create a new object inside the `questions` object with a key to identify the source of the question(s) you are adding. Add multiple separate objects with different keys for each different source.

Next, add an object with the same key as the source to the `sources` object. Include the link to your source, the name you would like to be identified by, and the date you have sourced this information on.

An example would look like this:

```json
{
    "questions": {
        "og": {
            ...
        },
        "example": {
            "How many hydrogen atoms are present in 1 mg of aspartame (C<sub>14</sub>H<sub>18</sub>N<sub>2</sub>O<sub>5</sub>), the artificial sweetener?": 19,
            "What is the mass, in grams, of all electrons within a single copper atom?": -26
        }
    },
    "sources": {
        "og": {
            ...
        },
        "example": {
            "link": "https://github.com/EricAndrechek/FermiQuestions#Adding-a-Question",
            "author": "Eric Andrechek",
            "date": "July 29, 2022"
        }
    }
}
```

If you want to be extra helpful, include the changes you are making to the change log and add yourself to the contributors list!

## Changes

-   July 29, 2022 - Added question source information as suggested by @Haadi-Khan
-   July 13, 2022 - Fixed incorrect answer pointed out by @IOnlyShoot3s
-   May 19, 2022 - Migrated from [andrechek.com](https://andrechek.com) to open source codebase and questions all hosted on Github.
-   March 2, 2019 - Open sourced question bank on Google Sheets, with many anonymous contributions from the community. Also added an online leaderboard.
-   February 10, 2019 - First release of website on [andrechek.com/projects/fermi](https://andrechek.com/projects/fermi) with closed source code and question bank.

## Contributors