# Cert Checker

This tiny project takes a list of domains (`domains.txt`) and checks the certificate expiry. Once that's done, it does two things:

- Adds the list of domains with their SSL certificate expiry to the end of this README
- Creates a new Github Issue if the SSL certificate expires in less than 30 days (if `GITHUB_TOKEN` is present) and again with 15 days remaining.


## Usage

Use this template to create a version of the project in your Github account, then edit `domains.txt` to set up the domains you want to track.


### Optional Steps

- Modify `.github/workflows/run.yml` to configure the frequency you run the bot
- Modify `.github/workflows/run.yml` to update the email address for the bot

## Results

| Expiry    | Domain   |
|-----------|----------|
| 2022-04-24 | brntn.me |
| 2022-04-24 | utils.brntn.me |
| 2022-04-24 | login-required.brntn.me |
| 2022-04-24 | bookmarks.brntn.me |
| 2022-04-24 | hn500.brntn.me |
| 2022-06-01 | abc.net.au |
| 2022-06-03 | runrandomly.com |
| 2022-06-09 | dockerwatch.net |
| 2022-10-08 | news.ycombinator.com |
| 2022-10-27 | fastmail.com |
| 2022-12-09 | example.com |
