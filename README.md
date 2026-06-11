# Hi there, I'm xiaopao1990 👋

Welcome to my GitHub profile! Below is a showcase of my active projects, featuring full self-service systems, AI-powered conversational tools, interactive educational apps, and database integrations.

---

## 🚀 Projects Showcase

### 1. Church Library Self-Service System 📚
A responsive React + Vite self-service kiosk system designed for church libraries. Patrons can easily search the catalog, borrow books, process returns, and receive AI-powered semantic recommendations.

*   **Key Features:**
    *   **Self-Service Borrowing & Returns:** Quick lookup by Call Number, Title, or Borrower Name to submit transactions.
    *   **Gemini AI Assistant:** RAG-powered semantic search that answers queries like "books about spiritual growth" based on the library catalog.
    *   **Google Sheets Backend:** Utilizes Google Sheets as a database and Google Apps Script as the API backend for live catalog updates.
*   **Usage Screenshots:**
    *   **Book Search & Catalog:**
        ![Search View](./LibSelfServiceTool/screenshot/searchview.png)
    *   **Confirm Return / Checkout:**
        ![Confirm View](./LibSelfServiceTool/screenshot/Confirm.png)
    *   **AI Librarian Recommendations:**
        ![AI Assistant View](./LibSelfServiceTool/screenshot/AIView.png)

---

### 2. AgentYT - AI-Powered YouTube Assistant 🤖📺
An intelligent, conversational web app that acts as your personal YouTube assistant, leveraging Gemini 2.5 Flash to search for videos, explore subscriptions, and provide personalized suggestions in natural language.

*   **Key Features:**
    *   **Natural Language Search & Subscriptions:** Search videos and query subscription activities using conversation.
    *   **Bilingual Chat Engine (i18n):** Automatically detects user languages (English/Chinese) and adjusts interface and AI responses.
    *   **Bespoke Web Player & Simulator:** Watch videos directly inside a custom viewport or simulate down-streaming workflows.
*   **Usage Screenshots:**
    | 💬 Chat Initialization | 🤖 Agent Response & Search | ⚙️ API Configuration |
    |:---:|:---:|:---:|
    | ![Chat Init](./AgentYT/screenshots/chat_init.jpg) | ![Chat Robot](./AgentYT/screenshots/chat_robot.jpg) | ![Setting](./AgentYT/screenshots/setting.jpg) |

---

### 3. Learn Chinese Daily 🐼
A fun, interactive, and mobile-responsive web application designed to help children learn, write, and review simplified Chinese characters daily.

*   **Key Features:**
    *   **Interactive Writing Board:** A large drawing canvas optimized for mouse, stylus, or touch inputs to practice writing.
    *   **Handwriting Recognition:** Integrates Google Input Tools API to recognize handwritten strokes dynamically.
    *   **Review & Quiz Modes:** Tracing mode stencils previous characters in the background; Quiz mode tracks remembered characters using a "Bingo" pile.
*   **Usage Screenshots:**
    | 🗓️ Dashboard | ✏️ Review Mode (Tracing) | 🧠 Quiz Mode |
    |:---:|:---:|:---:|
    | ![Dashboard](./LearnChineseCharactorForKids/screenshots/dashboard.png) | ![Review Mode](./LearnChineseCharactorForKids/screenshots/review.png) | ![Quiz Mode](./LearnChineseCharactorForKids/screenshots/quiz.png) |

---

### 4. 4C Room Reservation AI Assistant ⛪🤖
A bilingual (English/Chinese) AI scheduling assistant that wraps around the 4C Church Room Reservation System, providing natural language access to room availability and booking slots.

*   **Key Features:**
    *   **Integrated Sidebar Widget:** An animated, slide-in interface on desktop layouts that dynamically shifts main content.
    *   **ReAct Agent Pattern:** Uses Gemini 1.5 Flash to call tools, querying real-time database endpoints for room capacity and conflicts.
    *   **Secure Session Authentication:** Integrates and syncs with the existing web app's passcode session cookie.
*   **Usage Screenshots:**
    *   **AI Sidebar View:**
        ![AI Assistant Sidebar](./room-reservation-AI-tool/screenshots/AIToolView.png)
    *   **Booking Grid View:**
        ![Booking View](./room-reservation-AI-tool/screenshots/bookView.png)
    *   **Reservation Data Table:**
        ![Room Reservation Table](./room-reservation-AI-tool/screenshots/bookTable.png)

---

## 🛠️ Skills & Technologies
*   **Frontend:** HTML5, CSS3, JavaScript (ES6+), React, Vite
*   **Cloud & Backend:** Google Apps Script, Python (FastAPI), Firebase, Cloud Functions, Google Cloud Firestore
*   **AI & ML Integration:** Gemini API (1.5 Flash, 2.5 Flash, embedding-001, function calling, RAG)
