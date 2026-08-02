# RetroBlast Website
Restored community site (arcade/gameroom reviews, articles, news archives).
- **Live:** https://retroblast.com (Cloudflare R2 bucket `retroblast-site`, custom domain attached).
- **Homepage:** index.html (blue GameRoom theme) — also served as index.php (logo target).
- **Sections:** reviews.html · articles.html · archives.html (original full design, retrostyle.css) + articles/ reviews/ archives/ content.
- **Media on R2 only** (photos/gallery/moreimagesjustincase — too large for git; live on the R2 bucket).
- **Deploy:** upload to R2 bucket `retroblast-site` (account 08d62b215c…) via S3 API; custom domain retroblast.com + www.
- **PENDING:** bare-root `retroblast.com/` needs a Transform Rule (URI path "/" → /index.html) — needs a full-perm Cloudflare token.
