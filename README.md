# IROS 2026 Talks and Discussions

A bilingual, topic-organized guide to 26 public IROS 2026 videos, with speaker links, video embeds, and Korean/English notes. English is the default; the language selector saves a preference in the browser.

## Use

Open the site at https://gisbi-kim.github.io/iros-2026-talks/. Open a speaker or event title to see notes, or select a video thumbnail to play it. The source links lead to videos published by IEEE Robotics and Automation Society. Video thumbnails and playback are provided by YouTube and require a network connection.

For local development, serve the directory over HTTP, e.g. `python -m http.server 8000`, then open `http://localhost:8000/`. YouTube may block embedded playback from a local `file:` URL; in that case, the thumbnail opens the original YouTube page.

## Content and limitations

Notes were prepared from English automatic captions, which may misrecognize names, numbers and terminology. English text was translated automatically and may contain errors. Detailed full-talk notes are available for six videos; other detailed notes do not yet cover the full transcript. The page does not redistribute transcripts. Categorization is editorial and a video can fit multiple topics. Speaker affiliations and links are snapshots that can change.

The site is a single `index.html` with embedded CSS, translations and JavaScript. No server-side processing or account is used. Browser local storage retains the language preference; YouTube and its image host receive requests when content is loaded or played.
