# Mark Studios research data

Open data behind the original studies published at **https://www.markstudios.com/research**. `studies.csv` lists every study with its theme, page, files and the date it was added. Each folder holds the per-row CSV of one study; the page linked below has the full write-up, method, validation and limitations, and is the source of truth.

### The most-visited websites (6)

| Folder | Study | What one row is |
|---|---|---|
| `data/homepage-video-study` | [Homepage Video Study](https://www.markstudios.com/research/homepage-video-study) | One of the 1,000 most-visited domains (Tranco list ZJ8PG): whether its homepage showed video, where, how and from which host, plus background-loop file size |
| `data/website-social-media-links-study` | [Website Social Media Links Study](https://www.markstudios.com/research/website-social-media-links-study) | One working homepage: which of 18 social networks it links to a profile on |
| `data/homepage-seo-study` | [Homepage SEO Study](https://www.markstudios.com/research/homepage-seo-study) | One working homepage: title and meta description length, canonical, lang, Open Graph, H1 count, JSON-LD types |
| `data/website-third-party-tools-study` | [Website Third-Party Tools Study](https://www.markstudios.com/research/website-third-party-tools-study) | One working homepage: which of 43 outside tools it loaded in its first 10 seconds, its chat widget, other domains contacted |
| `data/ai-crawler-robots-txt-study` | [AI Crawler Robots.txt Study](https://www.markstudios.com/research/ai-crawler-robots-txt-study) | One working homepage of the Tranco top 1,000: which AI crawlers its robots.txt blocks for the homepage (RFC 9309 reading), and whether it serves llms.txt |
| `data/website-fonts-study` | [Website Fonts Study](https://www.markstudios.com/research/website-fonts-study) | One working homepage: the font its body text and first heading render in, the web fonts it loads, and the font type (brand, open-source, system) |

### YouTube and captions (13)

| Folder | Study | What one row is |
|---|---|---|
| `data/youtube-metadata-study` | [YouTube Tags, Titles and Descriptions Study](https://www.markstudios.com/research/youtube-metadata-study) | One video or Short from the most-subscribed YouTube channels: tag count and characters, title and description length, links, hashtags, chapters, uploaded captions, translations, paid promotion and made-for-kids flags, likes per 1,000 views |
| `data/youtube-shorts-length-study` | [YouTube Shorts Length Study](https://www.markstudios.com/research/youtube-shorts-length-study) | One Short (and one channel) from the most-subscribed YouTube channels: length, resolution, upload date |
| `data/youtube-thumbnail-study` | [YouTube Thumbnail Study](https://www.markstudios.com/research/youtube-thumbnail-study) | One thumbnail (and one channel): faces, face size, headline text, overlap with the title |
| `data/youtube-upload-time-study` | [YouTube Upload Time Study](https://www.markstudios.com/research/youtube-upload-time-study) | One upload (and one channel): exact publish time, minute, hour and day in the channel's time zone |
| `data/youtube-engagement-rate-study` | [YouTube Engagement Rate Study](https://www.markstudios.com/research/youtube-engagement-rate-study) | One upload (and one channel): views, likes and comments read on Oct 30, 2026, engagement rate, type, YouTube category, length, age when read and made-for-kids setting |
| `data/youtube-creator-comments-study` | [YouTube Creator Comments Study](https://www.markstudios.com/research/youtube-creator-comments-study) | One recent upload from the most-subscribed channels: views, comments, top threads read, whether the creator's own comment is first, own comments and replies shown |
| `data/sp500-youtube-study` | [S&P 500 on YouTube Study](https://www.markstudios.com/research/sp500-youtube-study) | One S&P 500 constituent: sector, whether its homepage links to or embeds YouTube, the company channel, subscribers, uploads and Shorts in 12 months |
| `data/podcasts-on-youtube-study` | [Podcasts on YouTube Study](https://www.markstudios.com/research/podcasts-on-youtube-study) | One show on Apple's top 100 U.S. podcasts: genre, publisher, its YouTube channel and subscribers, full episodes or clips matched, feed-to-YouTube gap |
| `data/youtube-view-count-change-study` | [YouTube View Count Change Study](https://www.markstudios.com/research/youtube-view-count-change-study) | One upload (and one channel and type): views, likes and comments before (Jun 1-Aug 23, 2026) and after YouTube's Aug 24, 2026 view count change |
| `data/youtube-video-length-study` | [YouTube Video Length Study](https://www.markstudios.com/research/youtube-video-length-study) | One recent video (and one channel) from the 100 most-subscribed channels: length in minutes, views when listed |
| `data/youtube-dubbing-study` | [YouTube Dubbing Study](https://www.markstudios.com/research/youtube-dubbing-study) | One recent video (and one channel): original language, the channel's own dubbed audio tracks and YouTube's automatic dubs |
| `data/youtube-auto-caption-accuracy-study` | [YouTube Auto Caption Accuracy Study](https://www.markstudios.com/research/youtube-auto-caption-accuracy-study) | One video with creator-uploaded English captions: word error rate of YouTube's automatic captions against them (and one channel: caption types) |
| `data/caption-reading-speed-study` | [Caption Reading Speed Study](https://www.markstudios.com/research/caption-reading-speed-study) | One captioned video or course: words per minute, characters per second, shares of captions over reading-speed and line-length limits |

### Video editing work, apps and careers (5)

| Folder | Study | What one row is |
|---|---|---|
| `data/video-editing-software-wikipedia-study` | [Video Editing Software on Wikipedia Study](https://www.markstudios.com/research/video-editing-software-wikipedia-study) | English Wikipedia human pageviews of 18 video editors' articles plus redirects: a per-editor summary (last 12 months vs five years earlier, per billion English Wikipedia views) and monthly views 2016-2026 |
| `data/video-editing-apps-app-store-study` | [Video Editing Apps on the App Store Study](https://www.markstudios.com/research/video-editing-apps-app-store-study) | One video editing app with 1,000+ U.S. App Store ratings: ratings, update dates, chart ranks, the lowest listed weekly, monthly, yearly and lifetime prices and every in-app purchase Apple lists; `google-play.csv`: the app's Google Play listing and install band where we could match it to Android |
| `data/ai-video-generator-apps-app-store-study` | [AI Video Generator Apps on the App Store Study](https://www.markstudios.com/research/ai-video-generator-apps-app-store-study) | `apps.csv`: one AI video generator app with 1,000+ U.S. App Store ratings: ratings, update dates, chart ranks, the lowest listed weekly, monthly, yearly, credit-pack and lifetime prices and every in-app purchase Apple lists; `labels.json`: the hand labels and the rule |
| `data/film-school-earnings-study` | [Film School Earnings Study](https://www.markstudios.com/research/film-school-earnings-study) | `film-programs.csv`: one film/video and photographic arts program (CIP 50.06) in the College Scorecard field-of-study file: institution, credential, median earnings 1 and 5 years after completing, graduates above a high school graduate's earnings, median federal debt; `fields.csv`: one field and credential level, medians compared with 10 fields |
| `data/video-editor-pay-by-state-study` | [Video Editor Pay by State Study](https://www.markstudios.com/research/video-editor-pay-by-state-study) | One state with a published BLS OEWS May 2025 estimate for film and video editors: employment, median and mean pay, location quotient, BEA 2024 regional price parity and the median in national prices |

### Company filings and government records (6)

| Folder | Study | What one row is |
|---|---|---|
| `data/creator-economy-sec-filings-study` | [Creator Economy in SEC Filings Study](https://www.markstudios.com/research/creator-economy-sec-filings-study) | One term and filing year: 10-K filings mentioning TikTok, YouTube, Instagram, influencers, creators and related terms, 2019-2025 (and a 60-filing sample of 2025 TikTok mentions by topic) |
| `data/deepfakes-in-sec-filings-study` | [Deepfakes in SEC Filings Study](https://www.markstudios.com/research/deepfakes-in-sec-filings-study) | Yearly counts of 10-K filings mentioning deepfakes, voice cloning, synthetic media and generative AI, 2018-2026; every 10-K mentioning deepfakes (company, CIK, SIC, document link; 2026 rows with the 10-K item, topics and shared-clause flag); 2025-2026 rates by industry |
| `data/federal-video-production-contracts-study` | [Federal Video Production Contracts Study](https://www.markstudios.com/research/federal-video-production-contracts-study) | `awards.csv`: one U.S. federal contract award coded PSC T006 (film/video production) made in fiscal 2021-2025: agency, vendor, net obligations, competition, offers, small-business status, place of performance, USAspending link; `fiscal-years.csv`: one fiscal year, 2008-2026, net obligations (nominal and FY2025 dollars), new awards, vendors and shares |
| `data/gsa-video-production-rates-study` | [GSA Video Production Rates Study](https://www.markstudios.com/research/gsa-video-production-rates-study) | One labor category on one GSA Multiple Award Schedule contract, classed into a video production role (or graphic designer or photographer for comparison): job title, vendor, contract, hourly ceiling rate, experience, education, business size, worksite |
| `data/federal-advertising-contracts-study` | [Federal Advertising Contracts Study](https://www.markstudios.com/research/federal-advertising-contracts-study) | `fiscal-years.csv`: one fiscal year, 2008-2026, of U.S. federal contract obligations coded advertising (PSC R701) and public relations (R708), nominal and FY2025 dollars; `largest-awards.csv`: the 10 largest awards of fiscal 2021-2025 with funder, vendor, obligations, description and USAspending link |
| `data/federal-video-workforce-study` | [Federal Video and Public Affairs Workforce Study](https://www.markstudios.com/research/federal-video-workforce-study) | `headcount.csv`: one OPM employment snapshot (Sep 2015 to Aug 2026): federal civilian headcount in series 1071, 1084, 1060, 1035 and 1082 and in the whole workforce; `public-affairs-departments.csv`: one department's public affairs headcount in Dec 2024 and Aug 2026 |

### Own measurements behind statistics pages (7)

| Folder | Study | What one row is |
|---|---|---|
| `data/healthcare-video-statistics` | [Healthcare Video Statistics](https://www.markstudios.com/research/healthcare-video-statistics) | One of the 200 largest U.S. nonprofit hospitals (IRS Form 990): homepage video, YouTube and TikTok links, virtual-care link; and one upload from their YouTube channels |
| `data/product-demo-video-statistics` | [Product Demo Video Statistics](https://www.markstudios.com/research/product-demo-video-statistics) | One of the 145 largest software publishers filing with the SEC: homepage demo, trial and contact-sales buttons and where the demo button leads; and one upload from their YouTube channels |
| `data/nonprofit-video-statistics` | [Nonprofit Video Statistics](https://www.markstudios.com/research/nonprofit-video-statistics) | One of the 200 largest U.S. charities by private contributions (IRS Form 990): homepage video and social links |
| `data/music-video-statistics` | [Music Video Statistics](https://www.markstudios.com/research/music-video-statistics) | One music channel among the 100 most-subscribed: uploads, Shorts, video length and titles in October 2026 |
| `data/fitness-video-statistics` | [Fitness Video Statistics](https://www.markstudios.com/research/fitness-video-statistics) | One upload (and one channel) from the biggest fitness YouTube channels: type, length, counts, YouTube topic tags |
| `data/home-services-video-statistics` | [Home Services Video Statistics](https://www.markstudios.com/research/home-services-video-statistics) | One upload (and one channel) from 37 home-improvement, DIY and trades channels: type, length, counts, chapters, captions |
| `data/financial-advisor-video-statistics` | [Financial Advisor Video Statistics](https://www.markstudios.com/research/financial-advisor-video-statistics) | One SEC-registered investment adviser's latest Form ADV: the social media and website addresses it lists (plus a yearly series); and one adviser YouTube channel's activity |

The 11 folders added on 2026-10-31 were copied from the site that day; `federal-video-production-contracts-study`, `gsa-video-production-rates-study`, `federal-advertising-contracts-study`, `federal-video-workforce-study`, `film-school-earnings-study`, `ai-video-generator-apps-app-store-study` and `video-editor-pay-by-state-study` were added on 2026-11-01.

Files were copied from the site on 2026-10-30 (Shorts length and upload time studies: edition 1.1) and resynced the same day after the site corrected the ranks of the eight channels after Karla Bustillos (#92 in the Wikipedia revision cited) in the YouTube studies to 93-100. One cell differs from the site copy: the homepage video study's `final_url` for reddit.com had a one-time bot-challenge query string, removed here. The studies are rerun on the schedule each page states.

## Licence

CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Reuse with attribution to Mark Studios and a link to the study page. Websites, channels and tools named in the data belong to their owners.

## Citation

See `CITATION.cff`, or cite the study page, for example: Mark Studios. "Homepage SEO Study." https://www.markstudios.com/research/homepage-seo-study
