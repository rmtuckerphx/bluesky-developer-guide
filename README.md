# Bluesky Developer Guide


![Bluesky Developer Guide - page 1 of 2](/images/bluesky-dev-guide1.png)

![Bluesky Developer Guide - page 2 of 2](/images/bluesky-dev-guide2.png)

## WebSockets
### Firehose
* `wss://bsky.network/xrpc/com.atproto.sync.subscribeRepos`

### Jetstream
* `wss://jetstream1.us-east.bsky.network`
* `wss://jetstream2.us-east.bsky.network`
* `wss://jetstream1.us-west.bsky.network`
* `wss://jetstream2.us-west.bsky.network`
* `wss://jetstream2.us-east.bsky.network/subscribe?wantedCollections=app.bsky.feed.post`
* `wss://jetstream1.us-west.bsky.network/subscribe? wantedDids=did:plc:xxxxx`
* `wss://jetstream2.us-east.bsky.network/subscribe?wantedCollections=app.bsky.feed.post&wantedCollections=app.bsky.feed.like&wantedDids=did:plc:xxxxx`



## HTTP API
* resolveHandle - https://bsky.social/xrpc/com.atproto.identity.resolveHandle?handle=support.bsky.team
* searchActors - https://public.api.bsky.app/xrpc/app.bsky.actor.searchActors?q=support.bsky.team
* searchActorsTypeahead - https://public.api.bsky.app/xrpc/app.bsky.actor.searchActorsTypeahead?q=support.bsky.team
* getProfile - https://public.api.bsky.app/xrpc/app.bsky.actor.getProfile?actor=support.bsky.team


## Tools
* https://atproto-browser.vercel.app
* https://pdsls.dev/

## Libraries
* skyware - https://skyware.js.org