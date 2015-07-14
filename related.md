# Notes

For now, this file can record notes that might be helpful as we begin to explore the problem space.

## Concepts/Theory

Suggestions for descriptive content about what this project is trying to achieve!

_*Decoupling the messages/threads/channels from the transport/storage mechanisms allows the user agent software maximum flexibility to present information and functionality in a manner that is delightful to the human.*_

There are some other key ideas, currently in no particular order:

* self-hosted: anyone with a linux box (POSIX system?) and a network connection can host
* open semantic API, with backwards and forwards compatability
* distributed: options for federation & peer-to-peer
* Identity (but not necessarily real-name), Authentication/Authorization built-in
* Search/Browse (fts of archived messages, topics, users)
* Text based, with links to filetypes (clients can choose to auto-render links and/or the results of links)
* Messages should be threaded into conversations
* Filtering - positive filtering aids discoverability, negative filtering helps avoid spam. Both Active filtering (human-initiated), such as moderation or per-user/community rulesets and Passive filtering (automated), such as classification, can be either server-side, client-side or both.
* synchronous & asynchronous messaging
* what metadata is required?


## Functionality

Replace me with specific details about how various aspects SHOULD work.

## Implementation notes

Anything related to how to make various aspects actually work.

* self-documenting API: as proposed at [JSON Schema] with an example at [CCAV API]

[JSON Schema]: http://json-schema.org/
[CCAV API]: http://ccav.terranova.org.au/apidocs/#http://ccav.terranova.org.au/api/

## Gateways

Gathering a list of openknot-to-X gateways we should consider and/or build, some of which will be unidirectional (in one direction OR the other) or bidirectional.

* XMPP
* HTTP (both for messaging and for search/browse)
* SMTP
* IRC
* NNTP
* RSS/Atom
* Gopher
* Slack/HipChat

## Related Projects

Items should be added here to show existing efforts that we are aware of that are related in some way such as protocols/services/paradigms with which we should integrate or otherwise support. If nothing else, this is a good place to ensure we're all aware of "prior art".

### Software Projects

### Service Projects

