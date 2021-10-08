# newsletter
<hr>Subscribe to my newsletter<hr>

Made with:
<br><br>
<img alt="NodeJS" src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge" />
<img alt="Mailchimp" src="https://img.shields.io/badge/Mailchimp%20API-yellow?style=for-the-badge" />

Link:<br><br>
[![Hits](https://img.shields.io/badge/newsletter-white?style=for-the-badge)](https://enigmatic-thicket-99001.herokuapp.com/)
<hr>

## Want to setup your own newsletter ?

First clone and initialise the project. Then, Install the required modules.

```sh
git clone https://github.com/A12N4V/newsletter.git
cd newsletter
npm init -y
npm i
```

Make a ```.env``` file and a mailchimp account. After making the mailchimp account create a new api key by visiting [API Page](https://us6.admin.mailchimp.com/account/api/) and pressing 'create a key' button . Then fill the ```.env``` file  with the following 

```sh
AUTH="<MAILCHIMP USERNAME>:<API KEY>"
```
The API key can be founded [API Page](https://us6.admin.mailchimp.com/account/api/)

Finally type the command
```sh
node app.js
```
and visit localhost:8080 or localhost:<PORT>
