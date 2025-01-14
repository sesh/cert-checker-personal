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
| 2025-02-20 | basehtml.xyz |
| 2025-02-20 | www.basehtml.xyz |
| 2025-02-28 | runrandomly.com |
| 2025-02-28 | www.runrandomly.com |
| 2025-02-28 | requestheaders.dev |
| 2025-02-28 | www.requestheaders.dev |
| 2025-03-15 | utils.brntn.me |
| 2025-03-15 | hn500.brntn.me |
| 2025-03-29 | news.ycombinator.com |
| 2025-04-02 | brntn.me |
| 2025-04-02 | www.brntn.me |
| 2025-11-03 | fastmail.com |
| 2025-11-25 | abc.net.au |
| 2026-02-14 | example.com |
| LookupFailed | loginwith.space |
| LookupFailed | www.loginwith.space |
| LookupFailed | dockerwatch.net |
| LookupFailed | www.dockerwatch.net |
| LookupFailed | delta-v.club |
| LookupFailed | webdevctf.com |
| LookupFailed | www.webdevctf.com |
| LookupFailed | clues.webdevctf.com |
| SSLConnectionFailed | django-up.com |
| SSLConnectionFailed | www.django-up.com |
| UnknownSSLFailure | bookmarks.brntn.me |
