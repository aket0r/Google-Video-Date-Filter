# Google Video Date Filter

A simple userscript that adds a year-based filter input to Google video search results.

## ✨ Features

- Filters video search results by minimum publish year (e.g. `2020`)
- Input is injected directly into the results page
- Enter `0` to reset and show all videos again
- Works on `https://www.google.com/search*` in any language

## 🔧 Usage

1. Go to [Google Video Search](https://www.google.com/search?q=example&tbm=vid)
2. Look for the small input field near the top
3. Type a year like `2019` and press Enter
4. Videos published before this year will be hidden
5. Enter `0` to reset the filter

## 🌍 Multilingual Support

- Works with both Russian (`г.`) and English (`2022`, `year ago`) date formats.
- Auto-detects last word in the date string that matches a 4-digit year.

## 📦 Installation

Install from [GreasyFork](https://greasyfork.org/) or paste the raw URL into Tampermonkey.

## 👨‍💻 Author

Created by [aket0r](https://github.com/aket0r)
