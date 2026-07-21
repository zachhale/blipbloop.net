# blipbloop.net

Static archive of Blip Bloop, Zach Hale's music blog (2006–2012).

The original WordPress site ran on Heroku until its ClearDB MySQL database was
retired in 2024 with no surviving backup. This copy was reconstructed in July
2026 from the Internet Archive's Wayback Machine (latest good capture of each
page) and is served via GitHub Pages.

Audio (mixtapes, radio archives) is served from the `media.blipbloop.net` S3
bucket, referenced as `https://s3.amazonaws.com/media.blipbloop.net/...` so it
loads over HTTPS.
