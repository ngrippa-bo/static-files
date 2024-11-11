# Static Hosting for UserFlow Templates

## Structure

The respective flows are in dev, test and prod and should only differ in the redirect URL at the bottom.
When developing, one can of course only change dev in order to check on changes first.

The two files at root level are legacy files for bohandwerker.at and can be deleted, when the switch is complete.

## Deploy

Just push the changes, the files are instantly served via the static github cdn.
Note that it might take a couple of minutes (up to an hour) for the actual user flow to reflect the changes. Clearing browser cache can help there. This is due to azure and not under our control.
