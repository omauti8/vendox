IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies
This repository documents the capstone project completed during the IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies. This program is a collaborative initiative by the Edunet Foundation, AICTE, and IBM SkillsBuild.

The internship's primary goal is to provide hands-on experience in emerging technologies, enhancing employability and confidence by solving real-world challenges using the IBM SkillsBuild and IBM Cloud platforms.

# 🧠 AI-Powered Digital Assistant for Street Vendors

This project is an AI-driven solution to help local hawkers and micro-entrepreneurs become digitally visible and financially empowered using **IBM Watsonx**, **Granite Foundation Models**, and a **manual RAG (Retrieval-Augmented Generation)** setup.

## 🚀 Objective

Build a low-code AI Assistant that:
- Understands vendor needs via natural language (e.g., “I sell fruits in Pune Camp”)
- Retrieves relevant insights from pre-curated PDFs
- Responds with tips for pricing, UPI setup, online listings, and digital growth
- Delivers output in local languages using IBM Granite-13B-chat model

## 🛠️ Tech Stack

| Technology | Usage |

| IBM Watsonx Prompt Lab | LLM-based natural language responses |
| Granite-13B-chat | Foundation model for contextual generation |
| GitHub | PDF knowledge source for RAG |
| IBM Cloud (Lite Plan) | Cloud infrastructure (Free tier) |
| Manual RAG | Prompt-time document grounding |

🧠 How It Works

1)📄 Upload relevant PDFs to GitHub (or any public link)
2)⚙️ Copy text chunks from PDFs into the Context section of Watsonx Prompt Lab
3)🗣️ Create user query like:
        “I sell fruits in Pune Camp. Suggest pricing tips, online platforms, and QR setup.”
4)🤖 Granite model responds with localized, document-aware advice

📸 Sample Prompt

## 📂 Project Structure

📁 /knowledge-base/
    ├── fruit_pricing_pune.pdf
    ├── upi_setup_guide.pdf
    ├── local_seo_tips.pdf
    └── msme_scheme_info.pdf

📁 /screenshots/
    └── prompt_lab_usage.png

💡 Key Features

Retrieval-Augmented Generation using public PDFs (manual context)
IBM Granite 13B-chat for high-quality multilingual response
No-code deployment using Prompt Lab
Zero server or API cost — runs entirely on IBM Cloud Free Tier    

📈 Impact
Helps informal vendors digitize their business
Provides access to UPI onboarding, MSME schemes, SEO tools
Ready for extension into voice, WhatsApp, or Android chatbot integrations


🔮 Future Scope
Automate document retrieval and embedding using vector DB (e.g., FAISS, ChromaDB)
Integrate with WhatsApp API or Android App for real-time user access
Enable speech-to-text and local language translation for broader adoption

🙌 Acknowledgments

IBM Watsonx & Granite Foundation Models
Indian MSME Digital India Initiatives
UPI & ONDC Ecosystem Guidelines
📄 README.md

