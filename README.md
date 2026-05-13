# Outlook Tab
Unofficial Outlook add-on for Thunderbird, it adds a button in Spaces that opens a Outlook (web version)) tab in Thunderbird.
The [home page](https://addons.mozilla.org/thunderbird/addon/outlooktab/) of the extension contains some pictures and reviews.

#### Installing 
A new Outlook icon should appear in the Spaces Toolbar of Thunderbird. Click to open.

#### Installing from sources
Download the repository, zip it, rename it to Gmail-Tab.xpi and choose install addon from file in Thunderbird.

In linux the xpi file can be created with the following commands
* `git clone https://github.com/feranick/Thunderbird-Outlook-Tab`
* `cd ./Thunderbird-Outlook-Tab`
* `VERSION=$(cat ./manifest.json | jq --raw-output '.version')`
* `zip -r "../Outlook-Tab-${VERSION}-tb.xpi" *`
