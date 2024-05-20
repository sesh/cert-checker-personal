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
| 2024-06-28 | basehtml.xyz |
| 2024-06-28 | www.basehtml.xyz |
| 2024-07-04 | runrandomly.com |
| 2024-07-04 | www.runrandomly.com |
| 2024-07-04 | requestheaders.dev |
| 2024-07-04 | www.requestheaders.dev |
| 2024-07-18 | utils.brntn.me |
| 2024-07-18 | hn500.brntn.me |
| 2024-07-18 | django-up.com |
| 2024-07-18 | www.django-up.com |
| 2024-08-05 | brntn.me |
| 2024-08-05 | www.brntn.me |
| 2024-09-10 | news.ycombinator.com |
| 2024-11-01 | fastmail.com |
| 2025-01-17 | abc.net.au |
| 2025-03-01 | example.com |
| LookupFailed | loginwith.space |
| LookupFailed | www.loginwith.space |
| LookupFailed | dockerwatch.net |
| LookupFailed | www.dockerwatch.net |
| LookupFailed | delta-v.club |
| LookupFailed | webdevctf.com |
| LookupFailed | www.webdevctf.com |
| LookupFailed | clues.webdevctf.com |
| UnknownSSLFailure | bookmarks.brntn.me |
