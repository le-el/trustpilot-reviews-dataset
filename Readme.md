# Trustpilot Company Review Dataset | Customer Reviews Data for Analytics & Research

A comprehensive **Trustpilot reviews dataset** containing structured customer feedback, ratings, and review metadata from multiple companies across various industries. This dataset is ideal for **customer experience analytics**, **sentiment analysis**, **NLP research**, **market research**, and **academic studies**.

## 🎯 What is This Dataset?

This repository provides a **preview** of a large-scale **Trustpilot customer reviews dataset** with structured review data including:
- **Customer reviews** with full text and ratings
- **Review metadata** (dates, verification status, languages)
- **Consumer information** (location, review history)
- **Company data** with Trustpilot metrics and sector classifications
- **Excel format** (.xlsx) for easy analysis

Perfect for researchers, data scientists, marketers, and businesses looking for **real customer feedback data** for analysis, training machine learning models, or conducting market research.

> 📧 **Need the full dataset?** Contact: **a.corradini0215@gmail.com** | 💬 Telegram: **[@buddior](https://t.me/buddior)**

---

## 📂 Dataset Overview & Features

### Key Information

- **Source:** Public customer reviews from **Trustpilot** (trustpilot.com)
- **Data Type:** Customer reviews dataset, review analytics data, sentiment analysis dataset
- **Scope:** Company-level customer feedback across multiple industries and sectors
- **Full Dataset Size:** Large-scale dataset (2135 MSCI list companies of 1.31GB)
- **Format:** Excel files (.xlsx) - ready for Excel, Python pandas, R, or any data analysis tool
- **Content Type:** Review metadata, star ratings (1-5), and free-text customer feedback
- **Status:** Latest collected version at time of creation
- **Preview Size:** 10 companies, **2,207 customer reviews** across 10 review files

### Who Can Use This Dataset?

This **Trustpilot reviews dataset** is designed for:

- **Customer Experience (CX) Analytics** - Measure satisfaction, identify pain points, benchmark performance
- **Sentiment Analysis & NLP Research** - Train models for sentiment classification, opinion mining, text analysis
- **Market Research & Competitive Analysis** - Understand customer perceptions, complaints, and preferences
- **Machine Learning & AI Training** - Fine-tune LLMs, build recommendation systems, train classifiers
- **Academic Research** - Consumer behavior studies, trust in brands, cross-cultural analysis
- **Business Intelligence** - Track review trends, analyze customer feedback, improve products/services 

---

## 📁 Repository Contents & File Structure

This GitHub repository includes **only a preview** of the full dataset. The preview contains:

### Review Files (`Reviews/` folder)

- **10 Excel files** (.xlsx format) with individual company reviews
- Each file contains **approximately 200-400 customer reviews**
- **22 columns** of detailed review data per file
- Includes review text, ratings, timestamps, consumer information, and company details
- Files are named by company identifier (e.g., `AEA000201011.xlsx`)

### Company Overview File

- **`TrustPilot_Company_Overview.xlsx`** - Summary file with company metadata
- Contains information for **10 companies**
- **21 columns** including:
  - Company names and identifiers
  - Trustpilot metrics (review count, trust score, average rating)
  - Sector classifications (5 levels)
  - Geographic data and location information
  - Matching scores and status

> **Note:** The preview is intentionally limited. For access to the complete dataset with thousands of companies and reviews, please contact us.

### Data Format & Compatibility

- **Format:** Microsoft Excel (.xlsx) - compatible with Excel, Google Sheets, Python pandas, R, SPSS, and most data analysis tools
- **Encoding:** UTF-8 compatible
- **Structure:** Tabular data, one row per review

---

## 🧱 Dataset Schema

### Review Files Schema (22 columns)

Each file in the `Reviews/` folder contains the following columns:

**Review Information:**
- `Type` – Company type/identifier code
- `Name` – Name of the company being reviewed
- `Review ID` – Unique review identifier
- `Review Title` – Short summary/title of the review
- `Review Text` – Full free-text body of the review
- `Rating` – Star rating (1–5 scale)
- `Is Verified` – Boolean indicating if the review is verified
- `Is Pending` – Boolean indicating if the review is pending approval
- `Likes` – Number of likes the review received
- `Language` – Language code of the review (e.g., `en`, `de`, `fr`)
- `Review Time` – Timestamp when the review was posted (ISO format)
- `Experience Time` – Date when the customer experience occurred
- `Reply Text` – Company's reply to the review (if available)

**Consumer Information:**
- `Consumer ID` – Unique identifier for the reviewer
- `Consumer Name` – Name of the reviewer
- `Consumer Review Count` – Total number of reviews by this consumer
- `Consumer Country` – Country code of the reviewer (e.g., `AE`)
- `Consumer Is Verified` – Boolean indicating if the consumer is verified
- `Consumer Review Count Same Domain` – Number of reviews by this consumer for the same company
- `Consumer Image` – URL to the consumer's profile image

**Company Information:**
- `Company Domain` – Website/domain of the company
- `Locale` – Locale code (e.g., `en-US`)

### Company Overview File Schema (21 columns)

The `TrustPilot_Company_Overview.xlsx` file contains:

**Company Identification:**
- `Type` – Company type/identifier code
- `NAME` – Company name
- `Glassdoor Name` – Matching name from Glassdoor (if available)

**Sector Classification:**
- `LEVEL2 SECTOR NAME` – Level 2 sector classification
- `LEVEL3 SECTOR NAME` – Level 3 sector classification
- `LEVEL4 SECTOR NAME` – Level 4 sector classification
- `LEVEL5 SECTOR NAME` – Level 5 sector classification
- `GEOGRAPHIC DESCR.` – Geographic description/location

**Trustpilot Metrics:**
- `TP_company_id` – Trustpilot company identifier
- `TP_name` – Trustpilot company name
- `TP_domain` – Company domain on Trustpilot
- `TP_review_count` – Total number of reviews on Trustpilot
- `TP_trust_score` – Trustpilot trust score
- `TP_rating` – Average rating on Trustpilot
- `TP_categories` – Business categories on Trustpilot
- `TP_website` – Company website URL
- `TP_city` – Company city location
- `TP_country` – Company country location
- `TP_request_id` – Request identifier
- `TP_status` – Matching status (e.g., `MATCHED`)
- `TP_matched_score` – Matching confidence score

---

## 💡 Use Cases & Applications

### Customer Experience Analytics
- **CX metrics analysis** - Measure customer satisfaction scores, NPS calculations
- **Pain point identification** - Discover common customer complaints and issues
- **Benchmarking** - Compare company performance across industries and sectors
- **Trend analysis** - Track customer sentiment over time

### Natural Language Processing & Machine Learning
- **Sentiment analysis** - Classify reviews as positive, negative, or neutral
- **Aspect-based opinion mining** - Extract insights about delivery, support, pricing, quality, etc.
- **Topic modeling** - Discover main themes and topics in customer feedback
- **Text classification** - Train models to categorize reviews automatically
- **LLM fine-tuning** - Use real customer feedback to improve language models
- **Named entity recognition** - Extract company names, products, locations from reviews

### Market Research & Business Intelligence
- **Competitive analysis** - Compare customer perceptions across competitors
- **Product research** - Identify feature requests and improvement opportunities
- **Brand monitoring** - Track online reputation and brand sentiment
- **Customer journey analysis** - Understand touchpoints and experience quality

### Academic & Research Applications
- **Consumer behavior studies** - Analyze factors influencing customer satisfaction
- **Trust and brand research** - Study how reviews affect brand perception
- **Cross-cultural analysis** - Compare review patterns across countries and languages
- **Social media research** - Understand online review behavior and patterns

---

## 🔑 Get Access to the Full Dataset

The full dataset is **not** stored in this repository. This preview contains only a sample of the complete dataset.

### What's Available in the Full Dataset?

- **Thousands of companies** across multiple industries
- **Hundreds of thousands of reviews** with complete metadata
- **Multiple countries and languages** for global analysis
- **Extended time periods** for longitudinal studies
- **Custom filtering options** by industry, country, date range, rating, etc.

### Request Custom Data Subsets

We can provide:

- **Full dataset access** - Complete Trustpilot reviews collection
- **Filtered subsets** - Specific countries, languages, industries, or time windows
- **Custom formats** - CSV, JSON, Parquet, or database exports
- **Additional processing** - Pre-processed data, cleaned text, extracted features
- **API access** - Real-time or scheduled data delivery

### How to Request Access

> 📧 **Email:** **a.corradini0215@gmail.com**  
> 💬 **Telegram:** **[@buddior](https://t.me/buddior)**

**Please include in your request:**
- Your intended use case (research, commercial, academic, internal analytics)
- Desired data scope (industries, countries, time period, number of reviews)
- Preferred format and delivery method
- Any specific requirements or custom processing needs

We'll respond with pricing, licensing terms, and delivery options tailored to your needs.

---

## ⚖️ Legal & Compliance Notice

- This repository provides a **preview** for evaluation, research, and demonstration purposes.
- Any use of the full dataset must comply with:
  - Applicable **data protection and privacy laws** in your jurisdiction  
  - Your organization’s internal policies  
  - The **terms and conditions of Trustpilot** and any other relevant platforms

By using this dataset or preview, you acknowledge that **you are responsible** for ensuring that your use is lawful and compliant and that you have the appropriate rights and permissions for your specific use case.

---

## 🔍 Keywords & Search Terms

This dataset is relevant for searches including:
- Trustpilot reviews dataset
- Customer reviews data
- Review analytics dataset
- Sentiment analysis data
- Customer feedback dataset
- Online reviews data
- Trustpilot data export
- Review sentiment dataset
- CX analytics data
- NLP training data
- Customer experience dataset
- Brand monitoring data
- Review mining dataset
- Consumer feedback data

---

## 📞 Questions & Support

If you have questions about:
- Dataset structure and schema
- Use cases and applications
- Data format and compatibility
- Custom data requests
- Licensing and terms

Feel free to reach out via email or Telegram. We're happy to help you find the right data solution for your needs.

**Contact:**
- 📧 Email: **a.corradini0215@gmail.com**
- 💬 Telegram: **[@buddior](https://t.me/buddior)**
