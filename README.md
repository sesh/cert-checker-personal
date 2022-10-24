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
| 2022-12-01 | django-up.com |
| 2022-12-01 | www.django-up.com |
| 2022-12-05 | dockerwatch.net |
| 2022-12-19 | utils.brntn.me |
| 2022-12-19 | login-required.brntn.me |
| 2022-12-19 | hn500.brntn.me |
| 2022-12-20 | bookmarks.brntn.me |
| 2022-12-22 | loginwith.space |
| 2022-12-22 | www.loginwith.space |
| 2022-12-26 | brntn.me |
| 2022-12-26 | www.brntn.me |
| 2023-01-08 | runrandomly.com |
| 2023-01-08 | www.runrandomly.com |
| 2023-03-14 | example.com |
| 2023-05-11 | basehtml.xyz |
| 2023-05-11 | www.basehtml.xyz |
| 2023-05-22 | abc.net.au |
| 2023-09-25 | news.ycombinator.com |
| 2023-11-02 | fastmail.com |
| LookupFailed | www.dockerwatch.net |
