**Languages:** [English](./README.md) · [简体中文](./README.zh-CN.md) · [Español](./README.es.md) · [日本語](./README.ja.md) · [Français](./README.fr.md)

# OutlineSave — ChatGPT Outline, Search & Export to HTML & PDF (Community Edition)

OutlineSave is a browser extension for making long AI conversations easier to navigate, search, annotate, and save. It helps turn conversations into structured knowledge you can return to instead of endlessly scrolling through chat history.

This repository contains an **early, limited, source-available ChatGPT demo**. It is not the source code for the current commercial extension, and its implementation does not represent the latest product release. The full OutlineSave extension is distributed separately through the Chrome Web Store.

**[Install OutlineSave from the Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[Explore the interactive HTML export demo](https://wisteriasoftware.uk/demo)** · **[Product details](https://wisteriasoftware.uk/outline-pro)**

![ChatGPT Outline community demo](./jump-ezgif.com-crop.gif)

> **Community demo limitation:** Only the first 15 outline entries support jumping. The search, annotation, export, and other full-extension features described below belong to the separately installed commercial version of OutlineSave.

## What the community demo includes

- A clickable outline for ChatGPT conversations
- Automatic outline refresh as the conversation grows
- Left- or right-side outline positioning
- A lightweight way to explore conversation navigation

The 15-entry jump limit applies to this repository's demo build only. It is not a limit of the full OutlineSave extension.

## Explore the full OutlineSave extension

The full browser extension supports conversations on **ChatGPT, Gemini, Claude, and DeepSeek**. Feature availability and interactions can vary by AI platform.

### ChatGPT Outline — two-level navigation for long conversations

The full extension organizes a conversation into a two-level outline: user questions at the first level and headings from AI responses at the second. Search outline titles and jump to the relevant part of a conversation without manually scrolling through every message.

For very long ChatGPT conversations, the outline can load progressively. Loading time and completeness depend on the source platform and the conversation.

### Search — find the right part of a conversation

Search question and response-heading titles in the live conversation outline. When a conversation is exported to HTML, use full-text search to find words and passages in the saved content.

### Export to HTML — save a searchable, offline knowledge page

Export a conversation as a self-contained, responsive HTML file. Open it locally without returning to ChatGPT or waiting for the original conversation to load.

The HTML export can preserve:

- The conversation outline and navigation
- Full-text search
- Existing highlights, underlines, notes, and bookmarks
- Bookmark and highlight-color filtering
- Code blocks, mathematical formulas, and Mermaid diagrams

**[Try the interactive HTML export demo](https://wisteriasoftware.uk/demo)**

### PDF export

PDF export is under development. It is **not yet part of the published Chrome Web Store build** as of this README update. Check the [Chrome Web Store listing](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj) for the capabilities available in the current release.

### Highlights, notes, bookmarks, Markdown, and JSON

Mark important passages with four highlight colors, underline text, add notes, and bookmark useful sections. Markdown and JSON export options are also available in the full extension.

### Local-first conversation handling

OutlineSave processes AI conversation content locally by default and does not upload conversation text to Wisteria Software's servers. No OutlineSave user account is required. Activation and operational data may be processed for licensing and product operation; optional Google Drive backup is initiated by the user and sends the selected backup data to the user's own Drive. See the [Privacy Policy](https://wisteriasoftware.uk/privacy) for details.

### Optional workflow with Inbox Local

[Inbox Local](https://github.com/sunny314woo/wisteria-suite/tree/main/apps/inbox-local) is a separate local-first knowledge workspace. It can help organize Markdown and rich HTML content exported from OutlineSave. It is an optional companion product, not part of this community demo.

## Community demo vs. full OutlineSave

| Capability | Community demo in this repository | Full OutlineSave extension |
|---|---|---|
| ChatGPT conversation outline | Yes | Yes |
| Click-to-jump navigation | First 15 entries only | Full outline navigation |
| Two-level outline | Not included | Yes |
| Search outline titles | Not included | Yes |
| Full-text search in exported HTML | Not included | Yes |
| Highlights, underlines, notes, and bookmarks | Not included | Yes |
| Offline HTML export | Not included | Yes |
| Markdown and JSON export | Not included | Yes |
| Gemini, Claude, and DeepSeek support | Not included | Yes |
| PDF export | Not included | In development; check the store listing for release status |

## Frequently asked questions

### How do I add an outline to a long ChatGPT conversation?

Install the full OutlineSave extension from the [Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj). The community demo in this repository is limited to 15 jumpable entries.

### Can I search a ChatGPT conversation?

The full extension searches outline titles in the live conversation. After exporting to HTML, you can also search the saved conversation text.

### Can I export a ChatGPT conversation as an offline HTML file?

Yes. The full extension exports a standalone, responsive HTML file with an outline, full-text search, and supported saved annotations. You can open the file locally without an active ChatGPT session.

### Does OutlineSave upload my conversations?

Conversation text is processed locally by default and is not uploaded to Wisteria Software's servers. Optional backup and product-operation services have separate data flows; see the [Privacy Policy](https://wisteriasoftware.uk/privacy).

### Is OutlineSave free?

The full extension offers free functionality as well as trial and paid options. Export allowances and license details can change, so check the [official product page](https://wisteriasoftware.uk/outline-pro) for current terms.

### Can I read an exported HTML file on my phone?

The exported HTML is responsive and can be transferred to a phone and opened in a compatible browser. It does not require the original ChatGPT conversation to be loaded.

## Run the community demo locally

1. Open **chrome://extensions** in Chrome.
2. Enable **Developer mode**.
3. Select **Load unpacked**.
4. Choose this repository folder.

## License and source availability

This repository is a **source-available community demo** under the custom license in [LICENSE](./LICENSE); it is not licensed under MIT or Apache-2.0. Public access to this demo's source code does not grant rights to the commercial extension, product branding, server-side services, or other proprietary materials. See [NOTICE](./NOTICE) for details.

**[Install OutlineSave from the Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[Explore the interactive HTML export demo](https://wisteriasoftware.uk/demo)**

**Languages:** [English](./README.md) · [简体中文](./README.zh-CN.md) · [Español](./README.es.md) · [日本語](./README.ja.md) · [Français](./README.fr.md)
