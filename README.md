Santa make a wish app
==========================

The app should display a form for children to enter their id and a free text message to santa.

When submitting the form, the server should check that the child is registered (his id is found in the santa API), and that the child is less than 10 years old.\
List of users and user profiles are available from the santa API at /users.json and /userProfiles.json.\
If any of those conditions fail, the app should diaply a basic error page with an error message.\
If all is well, the request should be stored to be sent (storing in memory is fine).\

Every 15s, the app should find all pending requests and send an email to santa with the requests:
- child id
- address
- child's request

Somebody started to work on the app, but it's up to you to complete it.


This was bootstraped from glitch, their README is below:

Welcome to Glitch
=================

Click `Show` in the header to see your app live. Updates to your code will instantly deploy and update live.

**Glitch** is the friendly community where you'll build the app of your dreams. Glitch lets you instantly create, remix, edit, and host an app, bot or site, and you can invite collaborators or helpers to simultaneously edit code with you.

Find out more [about Glitch](https://glitch.com/about).


Your Project
------------

On the front-end,
- edit `public/client.js`, `public/style.css` and `views/index.html`
- drag in `assets`, like images or music, to add them to your project

On the back-end,
- your app starts at `server.js`
- add frameworks and packages in `package.json`
- safely store app secrets in `.env` (nobody can see this but you and people you invite)


Made by [Glitch](https://glitch.com/)
-------------------

\ ゜o゜)ノ
