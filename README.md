# JAEHYUN GLOBAL — Video Archive

Cream & Brown fan-made video archive inspired by the supplied What We Watch reference.

## Files
- `index.html` — public archive page
- `videos.json` — video data
- `admin.html` — browser-based content editor (export updated JSON)

## Deploy as a separate Cloudflare Pages project
1. Create a new GitHub repository for this archive.
2. Upload all three files to the repository root.
3. In Cloudflare Pages, create a separate Pages project connected to that repository.
4. Framework preset: None. Build command: leave blank. Build output directory: `/`.
5. After deployment, add the custom domain `watch.jaehyunglobal.dev` in the Pages project.
6. In Cloudflare DNS, follow the Pages custom-domain instructions.

## Updating videos
Open `/admin.html`, add/edit/delete entries, then download `videos.json`. Replace the repository's `videos.json` with the downloaded file and commit the change. Cloudflare Pages will redeploy automatically if GitHub integration is enabled.

The editor is not a secured, server-backed CMS. It exports the JSON file for publishing; it does not directly change the live site.

## Video source
The initial two videos use YouTube thumbnails and embeds from the official SMTOWN channel:
- JAEHYUN 'Smoke' MV — https://www.youtube.com/watch?v=lJGCD3H9xcg
- JAEHYUN 'Dandelion & Roses' MV — https://www.youtube.com/watch?v=0nPxb9zMBtE

Only add videos that you have verified and have permission to embed. This is an unofficial fan-made archive and is not affiliated with SM Entertainment.
