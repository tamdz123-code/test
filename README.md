# filestorage

Lightweight GitHub Pages frontend for Supabase Storage.

## Enable GitHub Pages
1. Open Settings → Pages in this repository.
2. Under Build and deployment, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then Save.
4. After GitHub publishes the site, open the Pages URL shown in Settings.

## Storage
Files are uploaded to the public Supabase Storage bucket `files`. Public object URLs are direct URLs; image files are uploaded with their browser-provided MIME type so they can be embedded with `<img src="...">` on other websites. The page offers both direct/embed links and download links.

Current frontend limit: 50 MB per file. Because uploads are anonymous and the bucket is public, add abuse prevention and quotas before wide public sharing.
