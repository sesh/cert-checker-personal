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
| 2023-07-25 | utils.brntn.me |
| 2023-07-25 | hn500.brntn.me |
| 2023-07-25 | runrandomly.com |
| 2023-07-25 | www.runrandomly.com |
| 2023-07-25 | django-up.com |
| 2023-07-25 | www.django-up.com |
| 2023-07-27 | brntn.me |
| 2023-07-27 | www.brntn.me |
| 2023-07-27 | bookmarks.brntn.me |
| 2023-07-27 | dockerwatch.net |
| 2023-07-27 | www.dockerwatch.net |
| 2023-07-27 | delta-v.club |
| 2023-08-05 | webdevctf.com |
| 2023-08-05 | www.webdevctf.com |
| 2023-08-18 | requestheaders.dev |
| 2023-08-18 | www.requestheaders.dev |
| 2023-08-19 | loginwith.space |
| 2023-08-19 | www.loginwith.space |
| 2023-09-06 | clues.webdevctf.com |
| 2023-09-07 | basehtml.xyz |
| 2023-09-07 | www.basehtml.xyz |
| 2023-09-25 | news.ycombinator.com |
| 2023-11-02 | fastmail.com |
| 2024-02-13 | example.com |
| 2024-05-03 | abc.net.au |
