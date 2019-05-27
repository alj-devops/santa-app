Challenge contents:
=================

overview:
-------------
The webapp should display a form for children to enter their id and a free text message to santa.

When submitting the form, the server should check:
 1. that the child is registered
 2. that the child is less than 10 years old.
To this purpose, the server can fetch user and profiles data in JSON format from:
- https://raw.githubusercontent.com/alj-devops/santa-data/master/userProfiles.json
- https://raw.githubusercontent.com/alj-devops/santa-data/master/users.json

If the child is not registered (no match for the user id) or more than 10years old, the webapp should display a basic error page with an error message explaining the problem.\
If the child is registered and less than 10 years old, the server should show a page indicating that the request has been received.

Every 15seconds, the server should send an email with information on all pending requests including:
- child id
- child's address
- request free text as was input in the form
Email sender should be set as do_not_reply@northpole.com, and sent to santa@northpole.com


tips and detailed instructions:
-----------------------------
- somebody started to work on the app, but left it unfinished. It is up to you to complete it. You are allowed to restart from scratch if you prefer.
- the look and feel of the application for this challenge is not the priority. The pages/email do not need to look good, as long as they convey the information effectively.
- you should fetch the JSON data at every form submission (consider it as an API)
- for the sake of the challenge, you do not need to store the requests in a permanent storage, in-memory storage is fine
- feel free to select and add npm packages as needed
- to get an smtp server for emails, go to https://ethereal.email/ and click "Create Ethereal Account".\
This will give you an account (take note of your username and pwd if you need to re-logon later) and smtp server (actual emails do not get delivered).\
Go to https://ethereal.email/messages to see the emails that have been received by the smtp server.

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
