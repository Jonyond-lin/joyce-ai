# Joyce Academic Homepage

This repository contains a public GitHub Pages academic homepage for Joyce.

The site is based on an AcademicPages / Minimal Mistakes-style Jekyll template,
with a single-page academic profile, sidebar profile card, anchor navigation,
news, research interests, publications, education, and research experience.

## Privacy Notes

- The public site uses the display name `Joyce`.
- The site does not publish home address, phone number, original CV PDF, or
  formal identity details.
- `robots.txt` and the page `<head>` request `noindex,nofollow,noarchive`.
  This reduces search discoverability, but it is not access control.

## Deploy With GitHub Pages

1. Create a public GitHub repository named like `joyce-research.github.io` or
   `<your-github-username>.github.io`.
2. Push this repository to GitHub.
3. In GitHub, open `Settings -> Pages`.
4. Set source to `Deploy from a branch`.
5. Select the `main` branch and `/ (root)`.
6. Wait for GitHub Pages to publish the site.

For a user site named `<your-github-username>.github.io`, the public URL will be:

```text
https://<your-github-username>.github.io/
```

For a project site named `joyce-research`, the public URL will usually be:

```text
https://<your-github-username>.github.io/joyce-research/
```

## Local Preview

```bash
bundle install
bundle exec jekyll serve
```

Then open:

```text
http://127.0.0.1:4000/
```

## Template Credits

This site is adapted from the academic homepage style used by AcademicPages and
Minimal Mistakes-compatible Jekyll templates.
