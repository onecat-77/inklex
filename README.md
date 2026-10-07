# InkLex

English vocabulary lookup, highlighting, word cards, and learning workflows for Obsidian.

The Community plugin provides **InkLex Free**. Free can be used without purchasing InkLex Pro and is not a time-limited trial.

## Free features

- English word and sentence lookup
- Word cards and word books
- Markdown vocabulary highlighting
- Hover review of word cards
- Basic AI-assisted definitions and card filling
- Patterns, collocations, and ordinary contexts
- Mastery tracking
- Word and sentence pronunciation
- CSV and Markdown vocabulary import

AI-assisted features require you to configure an AI service. Available pronunciation depends on your device and pronunciation settings.

## InkLex Pro and payments

InkLex Pro is an **optional paid upgrade**, provided separately from the Community Free edition. It adds advanced lexical analysis, AI word formation, structured study, practice and review, Markdown article practice, source-backed context learning, customized reading, and desktop local MDX/MDD dictionary support.

InkLex Free can be used without purchasing InkLex Pro. Some third-party AI services you configure may separately require their own account or payment.

## Source code

InkLex is closed-source, proprietary software. This public repository contains Community listing materials and release assets; release binaries are attached to GitHub Releases rather than stored on the default branch.

The source used to build the Community Free release is maintained in a separate private repository and is made available to the Obsidian Community review system through its official GitHub App for source and build verification.

Use of InkLex is governed by [LICENSE](LICENSE). Third-party attribution and license references are in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Third-party data

InkLex Free includes lexical evidence derived from **Open English WordNet 2025**, which is based on **Princeton WordNet**. Attribution and applicable license information are provided in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Network use

- **AI features:** When you configure and use an AI feature, InkLex sends the data needed for that request directly to your chosen AI service. Depending on the feature, this can include the queried word or sentence, the relevant prompt and reading context, and lexical evidence or source labels when required. Your API key authenticates requests to that service; it is not sent to an InkLex server.
- **AI connection test:** The Settings connection test sends a small test request to the AI endpoint you configured.
- **Online word pronunciation:** If you configure an HTTP(S) audio URL template, InkLex sends the current word to that endpoint to request audio when online pronunciation is selected, or as a fallback when System TTS is unavailable. The provider can receive the requested word and normal network request information.
- **Sentence pronunciation:** Complete English sentences use System TTS and are never sent to the online word pronunciation template. If System TTS is unavailable, sentence pronunciation is unavailable. System speech services are controlled by your device and operating system.
- **Free licensing:** InkLex Free does not connect to the InkLex License Server and does not require an InkLex License Key.

External support links open their destination when you choose to follow them.

## External file access

InkLex Free does not provide local MDX/MDD dictionary access. When you explicitly choose a CSV or Markdown import file, InkLex reads that selected file to import vocabulary. The selected file may be outside your Vault.

## Privacy

InkLex has no client-side telemetry or hidden usage analytics. It does not upload your vocabulary library or notes for telemetry. Network requests occur only for the disclosed user-triggered or configured features; AI requests may include the relevant content described above.

Free Settings includes a fixed introduction to InkLex Pro. This is the plugin's own product upgrade information, not dynamic third-party advertising.

## Installation

When InkLex is available in the Obsidian Community directory:

1. Open **Settings → Community plugins → Browse**.
2. Search for **InkLex**.
3. Select **Install**, then **Enable**.

## Support

- Author: **OneCat**
- Xiaohongshu: **一猫七七** · ID: **onecat77** · [Profile](https://xhslink.cn/o/3mXd5G6AAdB)
- Email: [onecat77@163.com](mailto:onecat77@163.com)
- Technical issues: GitHub Issues on this repository.

Please do not include API keys, license keys, or private notes in public issue reports.
