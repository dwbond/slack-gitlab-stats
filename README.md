# slack-gitlab-stats
Queries a running instance of GitLab's API for information about recent commits and posts them to Slack.

![Example slack post](http://i.imgur.com/I4WSwhO.jpg)

As an added bonus, it will post open issues per project if no commits have been made.

# Running the project

Install node by following the directions [at the node js website](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions).

Begin by entering `npm install` to install the required packages.

Copy config.json.template to config.json, and add your keys for [Slack](https://api.slack.com/apps?new_app=1) and [Gitlab](https://docs.gitlab.com/ee/user/profile/personal_access_tokens.html).
For Gitlab, you will need all three available scopes.

Run `node app.js` to launch the program.

---

Created at VTHacks, so pls excuse shitty hackathon code.
