# 🛍️ Myntra Deal Finder using Playwright & Cucumber BDD (Java)

A smart and automated deal-tracking tool built with **Playwright** and **Cucumber BDD** in **Java**. This scraper scans Myntra for discounted products, applies custom filters, gathers product details, and presents the best deals in a clear, sorted format.

This tool:
- 🚗 Automatically navigates through Myntra  
- 🎛️ Applies gender, category, and brand filters  
- 🛒 Collects discounted products from multiple pages  
- 📊 Ranks items by **highest discount**  
- 📝 Outputs a clean summary directly to the console  

---

## ⚡ Key Features

🎯 **Custom Filter Selection**
- Choose Gender: Men / Women / Kids  
- Select Categories: T-Shirts, Shirts, etc.  
- Pick Brands: Nike, H&M, Puma, and more  

🔧 **Dynamic Filtering System**
- Applies selected filters on the fly  

📥 **Data Extraction**
- Captures only items on discount  
- Ignores non-discounted products to optimize results  

📑 **Organized Output**
- Shows original price  
- Discounted price  
- Percentage off  
- Product URL for quick access  

---

## 🛠️ Tech Stack

| Tool             | Purpose                          |
|------------------|----------------------------------|
| ☕ **Java**        | Main programming language        |
| 🥒 **Cucumber**   | BDD framework for scenarios      |
| 🎭 **Playwright** | Browser automation & scraping    |
| 🧪 **JUnit**       | Validation & assertions          |
| 📦 **Maven/Gradle** | Build + dependency management   |

---

## 📁 Project Structure

```bash
project-root/
│
├── features/               # All Cucumber feature files
│
├── steps/                  # Java step definitions
│   └── Myntra.java         # Core scraper workflow
│
├── pom.xml / build.gradle  # Build configuration files
└── README.md               # Main project documentation
```
