# 🧳 Luggage Locator Pro

A lightweight, offline-first, mobile web application designed to help you organize and instantly locate items packed across multiple bags, suitcases, and compartments.

Built entirely with standard web technologies (HTML, CSS, Vanilla JS) in a single file, it requires no build tools, no servers, and no app store downloads.

## ✨ Features

- **Instant Search:** O(N) filtering lets you find exactly which pocket your items are in as you type.
- **100% Offline Capable:** Uses the browser's `localStorage` to save your data. It works on airplane mode and in dead zones.
- **Full CRUD Database:** Add items, edit details, and create or delete custom luggage categories directly from the UI.
- **Mobile-First UI:** Styled to look and feel like a native mobile settings app.
- **No Code Setup:** Can be hosted entirely for free via GitHub Pages.

---

## 🚀 How to Set Up Your Own Tracker

You don't need to know how to code to use this. Just follow these steps to get your own offline packing app on your phone.

### Step 1: Fork or Copy the Code

1. Create a GitHub account if you don't have one.
2. Fork this repository, or simply create a new repository and copy the contents of `index.html` into a new file of the same name.

### Step 2: Add Your Packing List

By default, the app comes with a sample packing list. You can change this by editing the `defaultData` JSON object located near the bottom of the `index.html` file inside the `<script>` tag.

Here is the required JSON structure for your custom data:

```json
[
  {
    "category": "Main Suitcase",
    "items": [
      {
        "id": "item1",
        "name": "T-Shirts",
        "description": "3 casual, 1 formal",
        "count": 4
      },
      {
        "id": "item2",
        "name": "Jeans"
      }
    ]
  },
  {
    "category": "Carry-on Backpack",
    "items": [
      {
        "id": "item3",
        "name": "Laptop",
        "description": "Work laptop + charger",
        "count": 1
      }
    ]
  }
]
```
