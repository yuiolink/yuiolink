yuio.link
=========
Redirect links and host text.

Intended features
=================
* Redirect: any link like http/https/spdy/mailto/spotify
* Pastebin: host text with syntax highlighting
* Account: manage your links
* Encryption: optional for all links

[Namespaces](../../wiki/Namespaces)
==========
* Numbers
* Characters
* Shoutkey
* Unicode/Emoji
* Custom

Properties
==========
* Permanent: not guaranteed during development
* Expiring/Ethereal: by time or uses, whichever comes first
* Valid after: inactive until specified condition
* Preview/Cloaked: require interaction for redirect or before displaying paste
* Encrypted: protected with password

Workflows
=========
## Use link
* Open `yuio.link/<namespace>`.
* *Encrypted?* Input password and continue.
* Redirect or display paste.

Example [routes](../../wiki/Routes).

## Create link
* Open `yuio.link`.
* Type or paste any type of link or general text. (identify whether user intends a paste or redirect, show which will occur and offer the opposite if user insists)
* Select settings and customize to preference.
* Continue and recieve `yuio.link/<namespace>` selected—(low priority UX improvement:)—immediately while a spinner in the submit button rotates until the link is online and the UI turns from gray to green.
* Display text if used as pastebin.

Quotes
======
“Think redirects, not URLs.” — jooize
