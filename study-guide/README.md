# React Interview Study Guide

A static, locally runnable study checklist for the 354 questions in the main table of the repository README. It puts a curated high value shortlist first, keeps the remaining questions available by priority, and saves checked items in browser local storage.

## Run locally

From the repository root:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/study-guide/>. Your checklist is saved in this browser on this device. It does not sync between browsers or devices.

## Publish with GitHub Pages

The repository includes a GitHub Actions workflow that publishes this folder as the Pages site whenever `study-guide/` changes on `master`. On a fork, enable **Settings → Pages → Build and deployment → GitHub Actions** if Pages is not already enabled. The Pages URL will be `https://<your-github-username>.github.io/reactjs-interview-questions/`.

Browser storage remains local to each visitor and browser; completion state does not sync between devices.

## Ranking notes

“Start here” is the curated shortlist of core concepts, current React usage, and common implementation tradeoffs. “Next” adds useful depth. “Optional” includes narrower library, platform, legacy API, and repeated questions. This is a study order, not a claim that any company will ask a particular question. The source question bank predates some React 19.3 additions, so check the current React docs for newer APIs. The answer links point back to the original repository README.
