# Pitt CS Wiki (Major Work in Progress)

<div align="center">
  <a href="https://pittcswiki.netlify.com/">
    <img src="src/images/logo.svg" alt="Pitt CS Wiki" width="400">
  </a>
  <br>
</div>

## In Development!

Check out brainstorming on the issues page!

## Instructions

Since this fetches data from a Google Sheet, you need a Google Sheets API key to be able to run this. You can ask a CSC Officer to get you this key, which will be a JSON file you can save in the root of this project.

To start, run these commands

```
yarn install
yarn start
```

### Making Sure Wiki and SCI Courses are up to date

```
npm run check_correct_courses
```

If this test fails, follow the instructions in the failed test.

### Learning Gatsby

This uses Gatsby + React. Basically, this precompiles the React and all the data into static HTML and JS. This makes the site load really
fast, since all the data is predownloaded and cached. It is deployed via
Netlify.

Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.org/). Here are some places to start. **Most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.