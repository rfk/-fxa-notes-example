
A small work-in-progress example of using the FxA Scoped Keys flow
to authenticate and (eventually) access your Firefox Notes.

Did I mention it's a work in progress?  Right now it just does the
key-fetching part.

Since the OAuth dance requires a live redirect URI, you'll have to
serve this on http://localhost:3033 in order to run it successfully.
A simple way to do that for local testing is:

```
python -m SimpleHTTPServer 3033
```
