# Northstar Standalone updates

Finished builds of Northstar Standalone, a Mac app for bills, budgets and projects, for the in-app updater in copies
its maker handed out. There's no source code here, and nothing about anyone who uses the app.

- Each release has one file, `Northstar-Standalone.zip`, and is tagged `v<version>-build<number>`.
- A copy installs an update only after the person using it clicks Install, and only if the update is signed with the
  same certificate as the copy already installed. A file changed after publishing, or signed by anyone else, is refused
  before anything is replaced.
- Checking is off until the person turns it on in Settings. A check asks GitHub for the latest release and sends
  nothing else.

These builds aren't notarized by Apple. Only use one if you got Northstar from the person who made it.
