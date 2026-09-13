# sources

A community-maintained list of manga sources, in the format the Kuma reader
understands. One-tap install: **https://yomibako.github.io/sources/**

Or paste this address into Kuma, under **More › Sources**:

```
https://raw.githubusercontent.com/yomibako/sources/main/community.json
```

## What this is

`community.json` is a manifest: for each source, a name, a language, the address
of the site it reads, the bundle that knows how to read it, and that bundle's
SHA-256. The bundles are plain JavaScript. They run in a sandbox with no file
system and no browser APIs — they can make HTTP requests and parse HTML, and
nothing else.

Many sources share one bundle. The four largest files drive most of the list
between them, because most manga sites run one of a handful of website engines.

## What this is not

This list is **unsigned**. A reader that installs it will label every source
unverified, and that label is correct — nobody has vouched for these.

This is not Kuma. Nobody who works on Kuma operates this list, endorses it, or
is responsible for what any listed site hosts.

Nothing here stores, mirrors, caches or serves any manga. These files describe
how to read sites that already exist; requests go from a reader's device
straight to those sites.

No warranty of any kind. Sites break, disappear and change hands without notice.

## A source is broken

Open an issue. Include the source name and what you saw — an empty shelf, a
chapter that won't open, missing artwork.
