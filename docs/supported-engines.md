# Supported Search Engines

If you want a search engine added, please [raise an issue](template).

Feel free to submit a PR if you want to add one yourself, or if you have fixed a broken engine.

TODO: Check if DDG / Brave search bangs overwrite ours, and if they do, add notes

Symbol | Meaning
---|---
✅ | Fully working
🟡 | Working with some problems
❌ | Does not work

## Chrome & Firefox

Search Engine | Supported | Notes
---|---|---
google.com | ✅ |
bing.com | ✅ |
duckduckgo.com | ✅ |
search.brave.com | ✅ |
metager.org | ✅ |
mojeek.com | ✅ |
searx.tiekoetter.com | ✅ |

## Only Chrome

Search Engine | Supported | Notes
---|---|---
qwant.com | ✅ | Weird behaviour if you "go back" to the search results page
startpage.com | ❌ | Searches don't change the URL which this extension uses to detect the query (possibly due to the search happening in a background POST)
ecosia.org | 🟡 | Multi-URL redirects cause duplicate new tabs
searx.be | ❌ | Same reason as startpage.com

## Only Firefox

Search Engine | Supported | Notes
---|---|---
qwant.com | ❌ | Because it GETs https://api.qwant.com/v3/search/web?q= in the background, redirecting that doesn't redirect the actual page the user is loading. Works if you then refresh the page
startpage.com | ✅ |
ecosia.org | ✅ |
searx.be | ✅ |
