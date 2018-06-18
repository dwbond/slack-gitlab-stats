# slack-gitlab-stats
Queries a running instance of GitLab's API for information about recent commits and posts them to Slack.

![Example slack post](http://i.imgur.com/I4WSwhO.jpg)

As an added bonus, it will post open issues per project if no commits have been made.

# Running the project

Install node by following the directions [at the node js website](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions).

Begin by entering `npm install` to install the required packages.

Copy config.json.template to config.json, and add your keys for the Slack and Gitlab.

Run `node app.js` to launch the program.

---

Created at VTHacks, so pls excuse shitty hackathon code.
