This project demonstrates a **natural language interface** for querying college attendance using **intent classification** and **slot extraction**. It converts user queries into structured JSON responses from a sample dataset.

---

## 📝 Project Overview

The assistant allows queries like: "Show me attendance of Class B on 3rd Oct"


and returns:

```json
{
  "Date": "2023-10-03",
  "Class": "B",
  "Present": 42,
  "Total": 50
}
```

Key Concepts:

-- Intent classification (attendance queries)
-- Slot extraction (class and date)
-- Mapping user queries to database-like retrieval
-- JSON output for easy integration

Features

-- Simple NLP pipeline for understanding user queries
-- Regex-based slot extraction for dates and classes
-- JSON response formatting
-- Easily extendable to multiple intents or real databases

Technologies Used

-- Python 3.x
-- pandas (data handling)
-- regex (slot extraction)
-- JSON (structured output)
