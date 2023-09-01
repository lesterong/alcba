# Alcba

## Updating Content

### Home Page

Some information on the home page can be updated using the JSON file found in `src/content/home/home.json`. The format is as follows:

| Key         | Value                                                                           |
| ----------- | ------------------------------------------------------------------------------- |
| title       | The title of the page                                                           |
| description | The description on the page                                                     |
| imageUrl    | The file path to the profile image, image should be placed in the public folder |

### Research Page

The list of publications and working papers can be updated using the JSON files found in `src/content/research/publications.json` and `src/content/research/workingpapers.json` respectively. The format is as follows:

| Key               | Value                                                                                                                |
| ----------------- | -------------------------------------------------------------------------------------------------------------------- |
| title             | The title of the paper                                                                                               |
| publication       | The journal or book where the paper is published                                                                     |
| authors           | The authors of the paper                                                                                             |
| pdfUrl (optional) | The link to the PDF file, must end with a `.pdf` file extension. The PDF file should be located in `public/research` |

### Social Links

The social links can be updated using the JSON file found in `src/content/social/social.json`.

| Key           | Value                                                                          |
| ------------- | ------------------------------------------------------------------------------ |
| googleScholar | A URL to the Google Scholar page, must begin with `https://scholar.google.com` |
| email         | An email                                                                       |
| twitter       | A URL to the Twitter page, must begin with `https://twitter.com`               |
| github        | A URL to the GitHub page, must begin with `https://github.com`                 |

## Developer Guide
