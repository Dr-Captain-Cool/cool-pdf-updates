# Cool PDF updates

Signed Cool PDF installers, one GitHub release per version, each with a `latest.json`.

Installed copies of Cool PDF read
`https://github.com/Dr-Captain-Cool/cool-pdf-updates/releases/latest/download/latest.json`
every hour (the hidden "Cool PDF Update" scheduled task) and, while Cool PDF is closed,
install a newer version silently. They install only installers signed with Cool PDF's
update key, for exactly the version named.

Releases are made by `app/scripts/release.mjs` in the Cool PDF repository; don't add them by hand.
