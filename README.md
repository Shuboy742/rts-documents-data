# RTS Mitra 🏛️🤝  
*A Citizen-Friendly AI Assistant for Government Services*  

## 📌 Overview  
**RTS Mitra** is an AI-powered virtual assistant designed to help Indian citizens easily access information about **government departments, services, and required documents**.  
It works in **English** and **Marathi**, providing simple and clear answers in a citizen-friendly tone.  

**n8n** is an open-source workflow automation tool that connects apps, APIs, and services, enabling seamless automation of tasks without coding, enhancing efficiency and productivity.

## ✨ Features  
- ✅ Provides details about **departments** and their services  
- ✅ Lists **required documents** for each service  
- ✅ Supports **English & Marathi** questions  
- ✅ Uses a structured **FAQ dataset** for accurate answers  
- ✅ Polite fallback response when the answer is not available  
- ✅ Automated with **n8n workflows** for seamless citizen query handling  
- ✅ Powered by **Gemini 2.0 Flash model** for fast, contextual, and multilingual responses  

## 🛠️ Tech Stack  
- **Language Model:** Gemini 2.0 Flash (for natural conversation & semantic understanding)  
- **Workflow Automation:** n8n (to automate FAQ retrieval, query handling, and response delivery)  
- **FAQ Dataset (CSV)** – pre-generated with 100+ citizen-friendly Q&A  
- **Fuzzy Semantic Matching** – ensures answers even if citizens make typos  
- **Bilingual Support** – English & Marathi  

## 📂 Data Used  
The assistant uses a curated **FAQ dataset**   
This dataset includes:  
- Department-level questions  
- Service-level questions  
- Document requirement questions  
- General overview questions  


## ⚙️ n8n Automation  
We used **n8n**, an open-source workflow automation tool, to:  
1. Accept citizen queries via chatbot/web form  
2. Process the query and match it against the **FAQ dataset**  
3. Call the **Gemini 2.0 Flash model** for semantic understanding (handles typos, synonyms, intent recognition)  
4. Return the response in **English** or **Marathi**, depending on the user’s language  
5. Log the interaction for future improvements  

This automation ensures:  
- Faster query resolution  
- Reduced manual intervention  
- A smooth citizen experience  

## 🤖 Gemini 2.0 Flash Model  
We integrated **Gemini 2.0 Flash**, which provides:  
- ⚡ Lightning-fast responses for real-time citizen queries  
- 🧠 Deep semantic understanding of Indian government service-related terms  
- 🌐 Multilingual support (English + Marathi, extendable to Hindi and others)  
- 🔎 Context-aware answers even with spelling mistakes or incomplete queries  

## 🚀 Example Usage  

**English Example**  
- **Question:** "Which documents are needed for a caste certificate?"  
- **Answer:** "For the service 'Caste Certificate', the required documents are: Aadhaar Card, Residence Proof, and Birth Certificate."  

**Marathi Example**  
- **प्रश्न:** "H-13 कुत्रा/मांजर परवाना नूतनीकरणासाठी कोणती कागदपत्रं लागतात?"  
- **उत्तर:** "‘H-13 कुत्रा/मांजर परवाना नूतनीकरण’ या सेवेसाठी लागणारी कागदपत्रे: आधार कार्ड, रहिवासी पुरावा, आणि परवाना नूतनीकरण अर्ज."  

## 📖 System Instructions  
RTS Mitra follows these rules:  
1. Always give **clear, concise, and citizen-friendly answers**.  
2. Respond in **Marathi** if the question is asked in Marathi.  
3. Never create new departments or services not in the FAQ data.  
4. If the answer is missing, politely say:  
   *"I don’t have the exact information about that. Could you please rephrase your question or ask about departments, services, or required documents?"*  

## 🤝 Contribution  
- Extend the FAQ dataset with more questions & answers.  
- Add support for **Hindi** and other regional languages.  
- Improve fuzzy matching for better accuracy.  
- Extend n8n workflows for advanced citizen services (SMS, WhatsApp, IVR).  

## 📜 License  
This project is for ** citizen support purposes**.  

##  Overview
<img width="1920" height="1020" alt="n1" src="https://github.com/user-attachments/assets/ae59e29d-cc29-4df5-a1ff-6eee0ace3f5b" />
<img width="1920" height="1080" alt="n2" src="https://github.com/user-attachments/assets/d2779314-5566-4bed-9a9a-77443750aeb3" />
<img width="1920" height="1080" alt="n3" src="https://github.com/user-attachments/assets/51398d05-c6bf-47eb-9e40-ef9f812fe844" />
<img width="1920" height="1080" alt="n4" src="https://github.com/user-attachments/assets/26739e96-9198-49af-b9b8-a015e8243a2b" />
<img width="1920" height="1080" alt="n5" src="https://github.com/user-attachments/assets/dbfe4482-8bcd-4a99-8903-d0966179e9b4" />




  
