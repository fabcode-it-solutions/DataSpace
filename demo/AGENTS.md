# demo/

Local HTML snapshot of the Acme example. Not a public host.

GitHub Pages is retired. The live site is the Vercel deployment. Do
not add a workflow that publishes this folder to `gh-pages`.

`vercel-build` must never invoke `next`. Keep `demo/deck.html`
byte-identical to `content/documents/sample-pitch-deck.html`.
