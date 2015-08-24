# github-api-profile

## Objectives

After completing this assignment, you should be able to:

* Demonstrate understanding of functions, loops/array
* Demonstrate Functional Programming methods
* Demonstrate use of AJAX methods
* Demonstrate ability to update DOM elements and their attributes/innerHTML via JS/JQuery

## Details

### Deliverables

* Github Repo with html, css, and js 

### Requirements

* No JS errors in the browser
* All functions and code should work according to the following description.

## Easy Mode

Recreate the HTML and CSS for the Github tab page (https://github.com/matthiasak?tab=repositories) as your design, and using two AJAX requests, pull your own profile information from Github:

- Your profile: `https://api.github.com/users/<username>`
- Your repos: `https://api.github.com/users/<username>/repos`

After loading data from the Github API, write at least the following information to the DOM:

- name
- blog
- location
- email
- an `<img>` with its source as the avatar_url
- html_url
- for each repo owned by your user, list that repo in a `<ul>`

