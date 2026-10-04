# Lukewarm Pools & Spas website

Just right every time. Pool care, interiors, repairs, equipment and landscape design from Sydney to Newcastle.

Live site: https://infolukewarmpools-droid.github.io/lukewarm-pools-website/

Call or text 0411 933 189 · info.lukewarmpools@gmail.com

## Security

- Static site: no server, database, logins or third-party scripts.
- Strict Content Security Policy in each page's `<meta>`: only this site's own files run, plus Google Fonts. Inline scripts are allowed by SHA-256 hash, so any edit to a `<script>` block needs its hash in the CSP updated or the script won't run.
- Photos and videos are stripped of location and camera metadata before upload.
- Never commit passwords, API keys, client details or gate codes to this repo. It is public.
