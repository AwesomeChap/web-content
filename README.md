# The new ReactOS Website

[![Build Status](https://travis-ci.org/ColinFinck/web-content.svg?branch=master)](https://travis-ci.org/ColinFinck/web-content)

This repository manages the entire content of the new [ReactOS](https://reactos.org) Website.
It is powered by the [Hugo](https://gohugo.io) Static Site Generator.

Pages can be created as simple HTML or Markdown files and everyone is free to submit Pull Requests to enhance the website.
Issues are tracked at the [ReactOS JIRA](https://jira.reactos.org).

Website Subsystems written in PHP (such as GetBuilds, RosLogin, Testman, etc.) are continued to be managed in the
[ReactOS Web repository](https://github.com/reactos/web).

## Testing the website locally
1. Download Hugo 0.46 from https://gohugo.io.
2. Open a command prompt in the root of your repository checkout and type `hugo server`.
   The page is now served at http://localhost:1313 and automatically rebuilt and refreshed in the browser on local changes.

   *NOTE* - When working on the style it might be needed to use `hugo server --disableFastRender` instead. 

## Contributing
1. Choose one of the tasks from: [METABUG - New ReactOS Website Tasks before it can go live](https://jira.reactos.org/browse/ONLINE-815)
2. Comment on Jira that you want to work on this feature (to prevent duplication of work).
3. Create a pull request here.


