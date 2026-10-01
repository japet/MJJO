# MJJO

Historical volunteer band website material. The checkout contains band photos
and a placeholder `index.html` loading jQuery 2.1.3 from Google's CDN. It is not
a completed band website, and current hosting/ownership is unverified.

## Safe local inspection

There is no build or package install step. In this directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://127.0.0.1:8000/> and stop with Ctrl-C. The current placeholder text
is expected; the bundled photos are not linked from that page. Inspect photos
locally without uploading or publishing them. The page requests an external
jQuery script unless external requests are blocked.

## Before resuming

Confirm the current band/site owner, intended content and permission to use the
photos. Review existing [issue #1](https://github.com/japet/MJJO/issues/1) with
that owner, then agree the small site scope and a hosting/update procedure.
No deployment configuration or automated test suite is present. Local preview
does not verify a live site, resolve the issue, or authorize publication.
