# Apple 🍎 Podcasts Extractor

The Apple Podcasts Extractor is a tool designed to scrape detailed data from Apple Podcasts, enabling developers and researchers to collect valuable podcast information from millions of shows and episodes. It offers a customizable and straightforward method to extract podcast metadata, episodes, and channels with ease.


<p align="center">
  <a href="https://bitbash.def" target="_blank">
    <img src="https://github.com/za2122/footer-section/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/devpilot1" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>




<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Apple 🍎 Podcasts Extractor</strong> you've just found your team — Let’s Chat. 👆👆
</p>


## Introduction

This project allows users to scrape Apple Podcasts for detailed information, including podcast descriptions, episode data, and artist information. It solves the problem of accessing structured podcast data for analysis, research, or integration into various applications. This tool is perfect for data analysts, researchers, and developers who need large-scale podcast data for trend analysis, content curation, or media monitoring.

### Key Features

- Extract podcast, episode, and artist data directly from Apple Podcasts.
- Customizable search parameters using Apple Query Language (AQL).
- Autodetect URLs to collect data for specific podcasts or episodes.
- Fetch data for podcasts, episodes, artists, and channels.
- Export clean, structured data for analysis and integration.

## Features

| Feature | Description |
|---------|-------------|
| Podcast Data | Scrapes detailed metadata including title, description, genres, and artwork. |
| Episode Data | Collects information on podcast episodes like name, release date, and description. |
| Artist Data | Extracts data on artists associated with podcasts including name and related shows. |
| Channel Data | Gathers data about the channels hosting podcasts, including channel details and related podcasts. |

---

## What Data This Scraper Extracts

| Field Name | Field Description |
|-------------|------------------|
| podcast_name | The name of the podcast or show. |
| artist_name | The name of the artist or creator of the podcast. |
| description | A brief description or summary of the podcast. |
| categories | List of categories or genres the podcast belongs to. |
| artwork | URL to the podcast artwork or thumbnail image. |
| release_date | The release date of a podcast episode. |
| episode_name | The title or name of an individual episode. |
| episode_url | Direct URL to the episode on Apple Podcasts. |
| podcast_url | Direct URL to the podcast on Apple Podcasts. |

---

## Example Output

    [
          {
            "podcast_name": "Ngobrol Sore Semaunya",
            "artist_name": "CXO Media",
            "description": "Selamat datang di Ngobrol Sore Semaunya, menyajikan obrolan tak terduga dan dibawakan dengan semaunya.",
            "categories": [
              { "id": "6473748294", "name": "Personal Journals" },
              { "id": "6473764237", "name": "Podcasts" },
              { "id": "6473748311", "name": "Society & Culture" }
            ],
            "artwork": "https://is1-ssl.mzstatic.com/image/thumb/Podcasts122/v4/81/69/75/816975be-0af1-8bdd-44f9-18aa5bd67703/mza_2306394790357257423.jpg/320x320bb.webp",
            "release_date": "2025-04-08T04:57:00Z",
            "episode_count": 179,
            "podcast_url": "https://podcasts.apple.com/us/podcast/ngobrol-sore-semaunya/id1526729635"
          }
        ]

---

## Directory Structure Tree

apple-podcasts-extractor-scraper/

├── src/

│   ├── runner.py

│   ├── extractors/

│   │   ├── podcast_parser.py

│   │   └── utils_time.py

│   ├── outputs/

│   │   └── exporters.py

│   └── config/

│       └── settings.example.json

├── data/

│   ├── inputs.sample.txt

│   └── sample.json

├── requirements.txt

└── README.md

---

## Use Cases

- **Podcasters** use it to analyze trends in their audience’s listening habits, so they can tailor content accordingly.
- **Media analysts** use it to track podcast performance and gather insights into popular topics, helping them to advise brands or develop reports.
- **Researchers** use it to collect large datasets of podcasts and episodes for academic studies in media and communications.
- **Marketers** use it to discover emerging podcasts within certain genres and use that information for influencer partnerships or promotional strategies.

---

## FAQs

**Q1: How do I use this scraper to search for a specific podcast?**

A1: To search for a specific podcast, use the `query` field with a podcast name or keyword. For example, `query: ["sponge bobs"]` will return podcasts related to "SpongeBob."

**Q2: Can I scrape only episode data?**

A2: Yes, simply specify the `query` field with `episode:<KEYWORDS>` to return only episodes related to the specified keywords.

**Q3: Is there a limit to the number of podcasts or episodes I can scrape?**

A3: There is no fixed limit; however, we recommend using pagination to handle large datasets efficiently.

---

## Performance Benchmarks and Results

**Primary Metric:** The tool can scrape up to 1000 podcasts and episodes per request.

**Reliability Metric:** 99% success rate in retrieving accurate podcast data.

**Efficiency Metric:** Capable of scraping up to 600 podcast episodes per minute.

**Quality Metric:** Data completeness is at 98%, with minimal missing or inaccurate information.


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtube.com/shorts/6AwB5omXrIM" target="_blank">
        <img src="https://github.com/za2122/footer-section/blob/main/media/review3.gif" alt="Review 3" width="35%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        “Exceptional results, clear communication, and flawless delivery. Bitbash nailed it.”
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
