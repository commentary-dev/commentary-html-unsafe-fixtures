# Commentary HTML Unsafe Fixture Branch

This branch verifies static HTML previews block scripts, event handlers, unsafe URLs, and active embeds while recovering visible content from malformed HTML.

Expected Commentary behavior:

- scripts are not run by default
- event handlers and dangerous URLs are removed
- active embeds are blocked
- malformed visible content still gets a usable preview or safe fallback
- safety status copy explains sandboxing/restrictions without implying full browser fidelity

Commentary URLs after publishing:

- Unsafe PR review: `/review/github/commentary-dev/commentary-html-unsafe-fixtures/pull/1?file=public%2Funsafe.html`
- Malformed direct document: `/review/github/commentary-dev/commentary-html-unsafe-fixtures/document?branch=fixture%2Funsafe-html&file=public%2Fmalformed.html`
