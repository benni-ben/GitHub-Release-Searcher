# GitHub Release Searcher
## Index
  - [Overview](#overview) 
  - [Getting Started](#getting-started)
  - [Authors](#contributing--authors)

## Overview

GitHub Release Searcher is useful for finding repositories and applications, datamining, crawling, and repository discovery. It uses the [REST API](https://docs.github.com/rest) to search for repositories, and runs fully in your browser. It is portable, easy to move, runs on any browser, and easy to use. 

## Getting Started

To use this, you will first need a GitHub account. This is required because GitHub's REST API needs token authentication. Dont worry though, it is pretty easy to make an account. 

After you are done making the account, you will need to get your token. You can get one by going [here](https://github.com/settings/personal-access-tokens). Once you go there, you must `Generate a new token`. After that, input a token name(it can be whatever you want). After you enter the name, copy the token. Input the token into the `GitHub Token` field in the website, and you should be ready to start searching! 

>>> *Please note that GitHub limits you to 5000 requests per hour, although this may be increased for GitHub Enterprise Cloud accounts.*

## Searching Features

Searching with this tool is similar to searching on GitHub. Boolean search operators are supported(OR, NOT, AND, etc.), but there can only be 5 or less in one search. You also cannot have a search longer than 256 characters(not including the operators or qualifiers). 

Searching by username, date, and more is also supported. 

## Contributing & Authors

For suggestions, open an issue. I will try to respond to all of them.
 - Ben(benni-ben)