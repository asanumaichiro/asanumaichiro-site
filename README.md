# asanumaichiro-site

Static files exactly as served at the public site (baseline 2026-09-26, exported from the live server).
Languages: English at the root, Japanese in /ja/, Russian in /ru/ (where present).
Every change to main goes through a pull request; name the Work Board ID in each commit and pull request.
No passwords, keys or server configuration belong in this repository.

## How changes are made
1. A change is requested and given a Work Board ID.
2. The AI author (asanuma-ai-author) prepares the change on a branch and opens a pull request naming that ID.
3. Ichiro Asanuma reviews and approves the pull request.
4. After merge, the site is deployed from a tagged release, and the tag is the record of what was live.
