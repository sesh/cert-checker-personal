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
| 2023-02-07 | webdevctf.com |
| 2023-02-07 | www.webdevctf.com |
| 2023-02-19 | requestheaders.dev |
| 2023-02-19 | www.requestheaders.dev |
| 2023-02-20 | loginwith.space |
| 2023-02-20 | www.loginwith.space |
| 2023-03-11 | clues.webdevctf.com |
| 2023-03-14 | example.com |
| 2023-03-27 | utils.brntn.me |
| 2023-03-27 | hn500.brntn.me |
| 2023-03-27 | runrandomly.com |
| 2023-03-27 | www.runrandomly.com |
| 2023-03-27 | django-up.com |
| 2023-03-27 | www.django-up.com |
| 2023-03-28 | brntn.me |
| 2023-03-28 | www.brntn.me |
| 2023-03-28 | delta-v.club |
| 2023-03-29 | bookmarks.brntn.me |
| 2023-03-30 | dockerwatch.net |
| 2023-03-30 | www.dockerwatch.net |
| 2023-05-11 | basehtml.xyz |
| 2023-05-11 | www.basehtml.xyz |
| 2023-05-22 | abc.net.au |
| 2023-09-25 | news.ycombinator.com |
| 2023-11-02 | fastmail.com |
