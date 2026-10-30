# The Money Stickman — Shorts Studio

This folder contains a free, GitHub Actions-based Shorts renderer. It creates a vertical MP4 with animated scenes and a Kokoro American male voiceover. No paid API keys are required.

## First Short
Topic: 5 realistic ways to make money online (without fake income promises).

## Run
1. Open the repository's **Actions** tab.
2. Select **Render The Money Stickman Short**.
3. Click **Run workflow** (or wait for the automatic push run).
4. When it completes, open the run and download the `money-stickman-short` artifact.

The renderer downloads the open Kokoro model at runtime. GitHub-hosted runner time and artifact retention are subject to GitHub's free-tier limits. The video is a draft and should be reviewed before publishing.

## Voice
Kokoro `am_michael` (American English male). The project generates narration locally in the GitHub Actions runner; no external paid TTS service is used.
