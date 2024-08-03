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
| 2024-09-10 | news.ycombinator.com |
| 2024-09-16 | utils.brntn.me |
| 2024-09-16 | hn500.brntn.me |
| 2024-10-04 | brntn.me |
| 2024-10-04 | www.brntn.me |
| 2024-10-24 | basehtml.xyz |
| 2024-10-24 | www.basehtml.xyz |
| 2024-11-01 | runrandomly.com |
| 2024-11-01 | www.runrandomly.com |
| 2024-11-01 | fastmail.com |
| 2024-11-01 | requestheaders.dev |
| 2024-11-01 | www.requestheaders.dev |
| 2025-03-01 | example.com |
| 2025-06-05 | abc.net.au |
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
