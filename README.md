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
| 2024-01-22 | brntn.me |
| 2024-01-22 | www.brntn.me |
| 2024-02-13 | example.com |
| 2024-03-02 | basehtml.xyz |
| 2024-03-02 | www.basehtml.xyz |
| 2024-03-03 | webdevctf.com |
| 2024-03-03 | www.webdevctf.com |
| 2024-03-06 | runrandomly.com |
| 2024-03-06 | www.runrandomly.com |
| 2024-03-06 | requestheaders.dev |
| 2024-03-06 | www.requestheaders.dev |
| 2024-03-20 | utils.brntn.me |
| 2024-03-20 | hn500.brntn.me |
| 2024-03-20 | django-up.com |
| 2024-03-20 | www.django-up.com |
| 2024-09-10 | news.ycombinator.com |
| 2024-11-01 | fastmail.com |
| 2024-11-26 | abc.net.au |
| LookupFailed | loginwith.space |
| LookupFailed | www.loginwith.space |
| LookupFailed | dockerwatch.net |
| LookupFailed | www.dockerwatch.net |
| LookupFailed | delta-v.club |
| LookupFailed | clues.webdevctf.com |
| UnknownSSLFailure | bookmarks.brntn.me |
