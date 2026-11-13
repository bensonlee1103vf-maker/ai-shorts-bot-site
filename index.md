---
title: ai-shorts-bot
---

# ai-shorts-bot

**ai-shorts-bot** is a personal automation that publishes short educational videos about trending open-source AI projects on GitHub to a single YouTube channel. It is operated by one person for one channel; there are no users, accounts or sign-ups.

每兩天自動挑出 GitHub 上 48 小時內新增星星最多的 AI 開源專案，產出繁體中文直式短片並上傳到一個 YouTube 頻道。個人專案，沒有使用者、帳號或登入。

- Project repository: <https://github.com/bensonlee1103vf-maker/ai-shorts-bot>
- [Privacy Policy](privacy)
- Contact: the channel's About page on YouTube, or the repository above.

## What it does

1. Reads public GitHub data (repository metadata and README files) to pick topics.
2. Writes a script, renders a vertical video with screenshots of the project page and AI-generated narration.
3. Uploads the video to the owner's YouTube channel through the YouTube Data API, posts one pinned comment with the project link, and reads the channel's own analytics to improve later videos.
