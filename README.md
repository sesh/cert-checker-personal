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
| 2026-01-10 | utils.brntn.me |
| 2026-01-10 | hn500.brntn.me |
| 2026-01-15 | example.com |
| 2026-02-07 | news.ycombinator.com |
| 2026-02-10 | basehtml.xyz |
| 2026-02-10 | www.basehtml.xyz |
| 2026-02-23 | runrandomly.com |
| 2026-02-23 | www.runrandomly.com |
| 2026-02-23 | requestheaders.dev |
| 2026-02-23 | www.requestheaders.dev |
| 2026-03-02 | fastmail.com |
| 2026-03-07 | brntn.me |
| 2026-03-07 | www.brntn.me |
| 2026-09-24 | abc.net.au |
| LookupFailed | loginwith.space |
| LookupFailed | www.loginwith.space |
| LookupFailed | django-up.com |
| LookupFailed | www.django-up.com |
| LookupFailed | dockerwatch.net |
| LookupFailed | www.dockerwatch.net |
| LookupFailed | delta-v.club |
| LookupFailed | webdevctf.com |
| LookupFailed | www.webdevctf.com |
| LookupFailed | clues.webdevctf.com |
| UnknownSSLFailure | bookmarks.brntn.me |
