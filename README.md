# Mark Studios research data

Open data behind the original studies published at **https://www.markstudios.com/research**. Each folder holds the per-row CSV of one study; the page linked below has the full write-up, method, validation and limitations, and is the source of truth.

| Folder | Study | What one row is |
|---|---|---|
| `data/homepage-video-study` | [Homepage Video Study](https://www.markstudios.com/research/homepage-video-study) | One of the 1,000 most-visited domains (Tranco list ZJ8PG): whether its homepage showed video, where, how and from which host, plus background-loop file size |
| `data/website-social-media-links-study` | [Website Social Media Links Study](https://www.markstudios.com/research/website-social-media-links-study) | One working homepage: which of 18 social networks it links to a profile on |
| `data/homepage-seo-study` | [Homepage SEO Study](https://www.markstudios.com/research/homepage-seo-study) | One working homepage: title and meta description length, canonical, lang, Open Graph, H1 count, JSON-LD types |
| `data/website-third-party-tools-study` | [Website Third-Party Tools Study](https://www.markstudios.com/research/website-third-party-tools-study) | One working homepage: which of 43 outside tools it loaded in its first 10 seconds, its chat widget, other domains contacted |
| `data/ai-crawler-robots-txt-study` | [AI Crawler Robots.txt Study](https://www.markstudios.com/research/ai-crawler-robots-txt-study) | One working homepage of the Tranco top 1,000: which AI crawlers its robots.txt blocks for the homepage (RFC 9309 reading), and whether it serves llms.txt |
| `data/website-fonts-study` | [Website Fonts Study](https://www.markstudios.com/research/website-fonts-study) | One working homepage: the font its body text and first heading render in, the web fonts it loads, and the font type (brand, open-source, system) |
| `data/youtube-metadata-study` | [YouTube Tags, Titles and Descriptions Study](https://www.markstudios.com/research/youtube-metadata-study) | One video or Short from the most-subscribed YouTube channels: tag count and characters, title and description length, links, hashtags, chapters, uploaded captions, translations, paid promotion and made-for-kids flags, likes per 1,000 views |
| `data/youtube-shorts-length-study` | [YouTube Shorts Length Study](https://www.markstudios.com/research/youtube-shorts-length-study) | One Short (and one channel) from the most-subscribed YouTube channels: length, resolution, upload date |
| `data/youtube-thumbnail-study` | [YouTube Thumbnail Study](https://www.markstudios.com/research/youtube-thumbnail-study) | One thumbnail (and one channel): faces, face size, headline text, overlap with the title |
| `data/youtube-upload-time-study` | [YouTube Upload Time Study](https://www.markstudios.com/research/youtube-upload-time-study) | One upload (and one channel): exact publish time, minute, hour and day in the channel's time zone |

Files were copied from the site on 2026-10-30 (Shorts length and upload time studies: edition 1.1). One cell differs from the site copy: the homepage video study's `final_url` for reddit.com had a one-time bot-challenge query string, removed here. The studies are rerun on the schedule each page states.

## Licence

CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Reuse with attribution to Mark Studios and a link to the study page. Websites, channels and tools named in the data belong to their owners.

## Citation

See `CITATION.cff`, or cite the study page, for example: Mark Studios. "Homepage SEO Study." https://www.markstudios.com/research/homepage-seo-study
