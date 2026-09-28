# DECISIONS.md, minzystudios-freebies

## 2026-09-28, This repo stays public on purpose

**Chose:** the GitHub repo `mikebelyea/minzystudios-freebies` stays PUBLIC. This is Mike's ruling, 2026-09-28. It holds the wallpapers and free assets the studio gives away on socials, so public is the point.
**Ruled out:** making it private, and flagging it as a hygiene finding. The studio's rule that repos back up to private GitHub does not apply here.
**Guard:** `.gitignore` excludes `staging/`, so raw, unreleased art never goes public. Only finished, released drops belong in tracked folders. Secrets and signing files (`.env*`, `*.p8`, `*.pem`, `*.keystore`) are ignored too.
**Why:** a future agent auditing repo visibility should not treat this public repo as a leak or change its visibility.
**Reopen if:** the repo starts holding anything other than released giveaways, or Mike decides to host the drops somewhere else.
