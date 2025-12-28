# 🌫️ Delhi AQI Local Guide — Powered by Kiro

This project is a **custom Local Guide for Delhi**, focused on air quality (AQI), seasonal pollution patterns, safety recommendations, and emergency medical facilities.  
The guide is built using **Kiro**, which relies on a custom context file (`product.md`) to understand Delhi-specific environmental nuances.

This project demonstrates how Kiro can be taught hyper‑local knowledge using a `.kiro/product.md` file and then respond accurately to user questions based on that context.

---

## 📁 Project Structure

```
delhi-aqi-local-guide/
│
├── .kiro/
│   └── product.md        # Custom local knowledge for Kiro
│
├── main.py               # Placeholder script (optional)
│
├── screenshots/          # Kiro responses during testing
│   ├── sc1.png
│   ├── sc2.png
│   ├── sc3.png
│
└── README.md
```

---

## 🧠 What Kiro Learns from `product.md`

The `.kiro/product.md` file teaches Kiro:

- Delhi’s **AQI patterns** across seasons  
- **Pollution hotspots** (East Delhi, Anand Vihar, etc.)  
- **Winter smog behavior** and stubble burning impact  
- **Safety tips** for children, elderly, and sensitive groups  
- **Emergency hospitals** for respiratory issues  
- Practical, local insights for residents and visitors  

This file acts as the **single source of truth** for Kiro’s responses.

---

## 🧪 Testing the Local Guide in Kiro

Kiro was instructed to:

- **Disable web search**  
- **Use ONLY the knowledge from `.kiro/product.md`**  
- **Answer questions strictly from the custom context**  

### Example questions asked:

1. **What is the AQI pattern in East Delhi during winter?**  
2. **What is the least polluting place I can visit in Delhi now?**  
3. **I have breathing-related problems and I am in Connaught Place. Where can I seek medical help?**

All responses were generated **directly from the custom context**, not from the internet.

---

## 🖼️ Screenshots

Below are the screenshots of Kiro responding using the custom context from `.kiro/product.md`.

| Screenshot | Question Asked |
|-----------|----------------|
| `sc1.png` | **What is the AQI pattern in East Delhi during winter?** |
| `sc2.png` | **What is the least polluting place I can visit in Delhi now?** |
| `sc3.png` | **I have breathing-related problems and I am in Connaught Place. Where can I seek medical help?** |

All screenshots are available in the `screenshots/` folder.

---

## 🚀 How to Use This Project

1. Clone this repository  
2. Open the folder in **Kiro**  
3. Ensure `.kiro/product.md` is detected  
4. Ask Delhi AQI‑related questions  
5. Kiro will answer using the custom context  

---

## 📝 Blog Post

A detailed write‑up of the project, including screenshots and explanation of the workflow, is available in the AWS Builder Center blog https://builder.aws.com/content/37U234mFFhdUoaVAM7iVwVYPMVj/the-local-guide-delhis-aqi-local-guide-powered-by-kiro

---

## 📜 License

MIT License

