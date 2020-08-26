## OAuth Comparative Analysis

## GitHub

## Research Conducted By:

- Stephen Baldock
- Alex Whan
- Peng Chen
- Tia Low

## Overall Score and Comments

Score (Out of 10): **8**

## General Comments

8/10 points for general ease of use and accessiblity for junior level developers, still oauth-generalized concerns around spread of personal information.

## Pros

- Thorough documentation for how to get started
- Widely-adopted and supported by developer community

## Cons

- Concern around potential for big interests to share ownership of your personal information 
- General con- when sites are connected through one central thing and it's comprimised, you're exposed in a more widespread way, across several sites instead of just one

## Ratings and Reviews

* "From the very moment I laid eyes on GitHub's Oauth documentation, I knew I was in love."  - S. Baldock

## Documentation

Robust documentation through developer.github.com and you don't need to be a GitHub user to read into it. Includes quick start guides as well as more detailed sections. See Docs link below. 

## Systems Requirements

Above and beyond 'node' and 'linux', what dependencies or core requirements exist for this framework? Can it play with AWS/Heroku? Does it require a certain database?

- Works with Heroku

- Works with AWS

- Applications are subject to a security review before being listed on GitHub's marketplace to ensure they follow security best practices (See "*Security Review Process*" documentation).
  - Must have authorization, authenication, and access control
  - Must encrypt data via HTTPS if transferring it over public internet
  - Client ID/Keys must be stored as "secrets" - ideally in a separate environment variable

## Ramp-Up Projections

How long would/should it take a team of mid-junior developers to become productive?

- The process for getting up and running with GitHub OAuth credentials is relatively quick and easy. While we utilized starter code to construct the bones of this application, we estimate the process of building a basic structure, including obtaining OAuth credentials, would take approximately 1 hour. 

## Community Support and Adoption Levels

- Articles easily accessible that support the process of using GitHub Oauth
- As developers, several tools we're utilizing give the option of GitHub Oauth
  - Live Share through VS Code, Heroku, etc
- Well-supported by developer community since it's so relevant (the Oauth itself is through a site the majority of us use, as opposed to something like a social media Oauth)
- GitHub Oauth is trusted, and it's developer's responsiblity to make sure client secret is protected in .env file


---

---

**Stretch Goals Below**

## Links and Resources

framework

- [GitHub Oauth Docs](https://developer.github.com/apps/building-oauth-apps/authorizing-oauth-apps/)

- [Security Review Process for Submitted Apps](https://docs.github.com/en/developers/github-marketplace/security-review-process-for-submitted-apps)

- [Basics of Authentication](https://docs.github.com/en/rest/guides/basics-of-authentication)

examples/tutorials
