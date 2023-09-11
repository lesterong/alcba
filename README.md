# Alcba

## Updating Content

The data for each page is stored within the `src/content` folder as JSON files. Other files such as images and PDF documents are stored within the `public` folder.

### Home Page

Some information on the home page can be updated using the JSON file found in `src/content/home/home.json`. The format is as follows:

| Key         | Value                                                                                              |
| ----------- | -------------------------------------------------------------------------------------------------- |
| title       | The title of the page                                                                              |
| description | The description on the page                                                                        |
| imageUrl    | The file name of the profile image<br/> <ul><li>Image should be placed in the `public` folder</li> |

### Research Page

The list of publications and working papers can be updated using the JSON files found in `src/content/research/publications.json` and `src/content/research/workingpapers.json` respectively. The format is as follows:

| Key               | Value                                                                                                                |
| ----------------- | -------------------------------------------------------------------------------------------------------------------- |
| title             | The title of the paper                                                                                               |
| publication       | The journal or book where the paper is published                                                                     |
| authors           | The authors of the paper                                                                                             |
| pdfUrl (optional) | The link to the PDF file, must end with a `.pdf` file extension. The PDF file should be located in `public/research` |

### Teaching page

The information on the teaching page can be updated using the JSON file found in `src/content/teaching/teaching.json`. The format is as follows:

| Key        | Value                                            |
| ---------- | ------------------------------------------------ |
| philosophy | The description of teaching philosophy           |
| courses    | A title and optional description for each course |

### Team page

The list of teams members and alumni on the teams page can be updated using the JSON files found in `src/content/team/team.json` and `src/content/team/alumni.json` respectively. The format is as follows:

| Key                    | Value                                                                                             |
| ---------------------- | ------------------------------------------------------------------------------------------------- |
| name                   | The name of team member                                                                           |
| role                   | The role of the team member                                                                       |
| description (optional) | A short description of the team member                                                            |
| website (optional)     | The website of the team member                                                                    |
| imageUrl               | The file path to the profile image for the team member, should be placed in `public/team` folder. |

### Social Links

The social links can be updated using the JSON file found in `src/content/social/social.json`.

| Key           | Value                                                                          |
| ------------- | ------------------------------------------------------------------------------ |
| googleScholar | A URL to the Google Scholar page, must begin with `https://scholar.google.com` |
| email         | An email                                                                       |
| twitter       | A URL to the Twitter page, must begin with `https://twitter.com`               |
| github        | A URL to the GitHub page, must begin with `https://github.com`                 |

## Developer Guide

### Getting Started

This project is built with Astro + TailwindCSS.

1. Clone this repository
2. Install dependencies `yarn install`
3. Run `yarn dev` to serve the application

### Deploying the Application

See [Astro documentation](https://docs.astro.build/en/guides/deploy) for deployment instructions.

### Other Notes

ESLint and Prettier are set up in this project to lint and format code. This project also uses pre-commit hooks to run ESLint and Prettier on every commit.
