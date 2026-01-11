# obsidian-gemini-side-notes
A powerful side panel for capturing notes, thoughts, and annotations that sync bi-directionally with your documents. Features AI-powered note generation using Google Gemini to create summaries, extract key insights, and help you continue writing. Perfect for research, journaling, and content creation.

# Gemini Side Notes - Obsidian Plugin

Bi-directional side notes with AI assistance powered by Google Gemini.

## Features

- 📝 **Bi-directional Sync** - Edit in sidebar or main file, changes sync automatically
- 🔍 **Smart Detection** - Finds your `##### Side Notes` marker in any file
- ✨ **AI Auto-Note** - Generate summaries, action items, and questions from your content
- ✍️ **Continue Writing** - AI helps you overcome writer's block

## Installation

1. Copy `main.js`, `manifest.json`, and `styles.css` to your vault's `.obsidian/plugins/gemini-side-notes/` folder
2. Enable the plugin in Obsidian Settings → Community plugins
3. Add your Gemini API key in plugin settings

## Usage

1. Click the 📄 ribbon icon to open the Side Notes panel
2. Add `##### Side Notes` anywhere in your document
3. Start typing in the sidebar - changes sync to your file
4. Use **Auto-Note** to generate AI-powered notes from your content

## Commands

- `Open Side Notes panel` - Opens the sidebar
- `Generate AI notes for current document` - Creates AI summary
- `Continue writing with AI` - AI continues your text

## Settings

- **Gemini API Key** - Get from [Google AI Studio](https://aistudio.google.com/app/apikey)
- **Marker String** - Customize the section header (default: `##### Side Notes`)
- **Auto-Create Marker** - Automatically add marker to files

## License

MIT
