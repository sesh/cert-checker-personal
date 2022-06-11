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
| 2022-07-13 | runrandomly.com |
| 2022-07-13 | www.runrandomly.com |
| 2022-08-08 | dockerwatch.net |
| 2022-08-22 | utils.brntn.me |
| 2022-08-22 | login-required.brntn.me |
| 2022-08-22 | bookmarks.brntn.me |
| 2022-08-22 | hn500.brntn.me |
| 2022-08-28 | brntn.me |
| 2022-08-28 | www.brntn.me |
| 2022-10-08 | news.ycombinator.com |
| 2022-10-28 | fastmail.com |
| 2023-03-14 | example.com |
| 2023-05-22 | abc.net.au |
