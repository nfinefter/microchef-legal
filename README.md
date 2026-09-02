# MicroChef — legal & support pages

Published at **https://nfinefter.github.io/microchef-legal/**

These are the Terms of Service, Privacy Policy and Support pages for the
MicroChef iOS app. They exist as a public site because App Store Connect
requires a publicly reachable Privacy Policy URL and Support URL as mandatory
listing metadata.

## Don't edit these files

Every page here is **generated**. The source of truth is
`src/content/legal.js` in the MicroChef app repo, which also renders the same
content as screens inside the app — that is what users actually read.

To change a document: edit `src/content/legal.js` in the app repo and run
`npm run legal:publish`, which regenerates and pushes here. Editing a page here
directly would make the app and the published document disagree, which for a
legal document is the failure that matters.
