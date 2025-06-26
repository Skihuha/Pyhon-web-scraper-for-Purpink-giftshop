# Pyhon-web-scraper-for-Purpink-giftshop
# 🛍️ Purpink Product Scraper (Shopify JSON API)

This Python project is a high-performance scraper designed to extract product listings directly from the [Purpink](https://purpink.co.ke) e-commerce store — specifically from the "Gifts for Her" collection. Unlike traditional browser-based scraping with Selenium or Playwright, this scraper bypasses the frontend entirely and pulls product data via Shopify’s built-in JSON API.

---

## 🚀 Features

- 🔎 Scrapes **all products and variants** from `https://purpink.co.ke/collections/gifts-for-her`
- 📦 Extracts detailed info for each variant:
  - Product title
  - Variant title (e.g. size, color)
  - Price
  - SKU
  - Product link
  - Product image URL
- 🖼 Automatically **downloads product images** to a local `images/` folder
- 💾 Saves all data to a clean CSV file (`purpink_gifts_variants.csv`)

---

## 🧠 Why This Works

Most Shopify stores (like Purpink) expose a hidden but public product API:


This project takes advantage of that endpoint to fetch full product and variant data without needing JavaScript rendering or browser automation.

---

## 📂 Output Files

- `purpink_gifts_variants.csv`: Master file with all product data and variants
- `images/`: Folder containing downloaded product images

---

## ⚙️ Requirements

- Python 3.7+
- Required packages:
  - `requests`
  - `pandas`

You can install them using:

```bash
pip install -r requirements.txt


