# cs2-montage — public pages

The application home page and privacy policy for the `cs2-montage` Google
OAuth client, hosted on GitHub Pages.

They live here rather than in the main repository for one reason: GitHub Pages
needs a **public** repo on a free account, and the main repository is not
something to publish. Only these two files are public.

`index.html` and `privacy.html` are copies of `docs/oauth/` in the main
project, which is where they are edited. **If the OAuth scopes change, the
privacy policy has to change with them** — it names `drive.file` specifically
and says it cannot reach anything the app did not create, which stops being
true the moment a broader scope is requested.
