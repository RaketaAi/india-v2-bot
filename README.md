# india-v2-bot

The contact page named in the `User-Agent` of an automated client that requests published
documents from Indian financial market publishers:

```
india-v2-bot/1.0 (+https://raketaai.github.io/india-v2-bot/)
```

The page is served from this repository by GitHub Pages at
<https://raketaai.github.io/india-v2-bot/>. It is here, in a repository of its own, for three
reasons.

**It has to outlive the machines.** A publisher who wants this program stopped reads that address
weeks or months after the request that prompted it, and the program runs on two small rented machines. An
address that dies with a box is worse than none.

**It must not be served by the machine that fetches.** That would tie the identity to a
replaceable box, and it would put the address a publisher uses to complain behind the machine they
are complaining about.

**What the page said on a date is provable.** It is a static file in a git repository, so a
publisher asking what this program claimed to be at the time it made a request gets an answer with
a commit under it, rather than whatever the page says today.

## If this program has reached your site

Read the page. It states one exception: to NSE and BSE, which refuse any client that is not a
browser, it presents as one, and says so there. In short: refuse `india-v2-bot` in your `robots.txt` and it stops; or write to
<contact@raketa.ai>; or open an issue here. No reason is needed.

## What is not here

The research platform this serves is private and is not in this repository. Nothing about it is
published here beyond what the page states.
