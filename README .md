# HGS VIDEOS 🎬

A digital archive of HGS memories, legendary moments, inside jokes, and unforgettable videos. Every season tells a story.

## What's inside

- A cinematic landing page for the HGS archive
- Four season cards and individual season detail pages
- A video-player overlay with fullscreen and minimize controls
- A **Watch on YouTube** fallback in case embedded playback is blocked
- Responsive layout for desktop and mobile

## Add or update season videos

1. Open `index.html`.
2. Find `const seasons = [` near the bottom.
3. For each season, replace its `videoId` value with the YouTube video ID. For example, `https://www.youtube.com/watch?v=AbCdEf12345` has the ID `AbCdEf12345`.
4. Update the season's `description`, `what`, `subtitle`, and `mood` as needed.
5. Save and commit the file.

Season 4 currently uses the video ID for **Revisiting the Park**: `_jNmdWmjBK0`. Seasons 1–3 still have placeholder IDs until you add their videos.

> Note: Embedded playback depends on the video's settings and YouTube restrictions. If the player is blocked, use the Watch on YouTube link. GitHub Pages cannot override YouTube's embedding restrictions.

## Publish with GitHub Pages

1. Create a repository named `hgs-videos-archive` (or your preferred name).
2. Upload `index.html` and `README.md` to the repository root. Keep the main HTML filename exactly `index.html`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for GitHub Pages to show your live website URL.

## Storage and privacy

- Keep the website code in GitHub; do not upload multi-GB video files into the repository.
- GitHub Pages is a static website host and does not provide built-in password protection.
- Unlisted YouTube videos can be watched by anyone who has the link; unlisted is not the same as private.
