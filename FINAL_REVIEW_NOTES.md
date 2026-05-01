# Final review notes

This cleanup pass made the site more launch-ready and removed internal placeholder language from public pages.

## Removed

- `B4B8C68F-3C81-4B3B-9211-D9FBCD85627A.jpeg`
- `IMG_6241.jpeg`
- Unused duplicate root image files
- Unused placeholder portrait assets
- Unreferenced root `styles.css`

## Improved

- Replaced the unwanted music-atmosphere asset with the real ensemble performance image.
- Replaced placeholder captions on the About page with public-facing story captions.
- Removed public copy that talked about missing photos or placeholder image slots.
- Reframed Experience, Speaking, Contact, and Technology sections so they read like polished site content.
- Kept Thoughtworks present as a credibility source without making the site primarily about the current job.

## Current launch shape

- Home: personal brand umbrella.
- About: origin story.
- Experience: professional credibility and timeline.
- Technology: Veritas, platform strategy, modernization, and trust.
- Music & Arts: music story, The BeSides, album link, and performance identity.
- Writing: public articles, profiles, Medium, and platform engineering links.
- Speaking: talk topics and workshop positioning.
- Contact: email, LinkedIn, Medium, and external profiles.

## Deployment cleanup

- Removed the duplicate Jekyll Pages workflow so the repo uses the static Pages workflow only.
- Added `.nojekyll` so GitHub Pages treats the project as a plain static site.
