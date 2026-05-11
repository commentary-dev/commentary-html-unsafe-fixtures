# Commentary HTML Unsafe Fixtures

Baseline branch for public HTML sanitization fixtures.

This repository is safe for manual testing, demos, and read-only automation under `commentary-dev`. It is not for comment creation or mutating refresh/provider-sync tests.

The fixture branch covers sandboxed/restricted rendering, blocked scripts, stripped event handlers, unsafe URL removal, active embed blocking, and malformed HTML recovery.

After publishing, use:

- PR review: `/review/github/commentary-dev/commentary-html-unsafe-fixtures/pull/1?file=public%2Funsafe.html`
- Direct document: `/review/github/commentary-dev/commentary-html-unsafe-fixtures/document?branch=fixture%2Funsafe-html&file=public%2Funsafe.html`
