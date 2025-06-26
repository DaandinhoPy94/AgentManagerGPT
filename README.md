# AgentManagerGPT - Slimme AI Assistent voor Vastgoed Portfolio Analyse

Welkom bij AgentManagerGPT! Dit project is een geavanceerde AI-agent die is ontworpen om vastgoedportfolio's te analyseren. Het kan zelfstandig beslissen welke gespecialiseerde tool het beste antwoord kan geven op een vraag: een **SQL Archivaris** voor precieze numerieke data en overzichten, of een **RAG Analist** (Retrieval Augmented Generation) voor diepgaande semantische analyses en samenvattingen van documenten.

De app is gebouwd met **Streamlit** voor de gebruikersinterface en **LangChain** voor de orkestratie van de AI-agent en tools, aangedreven door **Groq**'s snelle LLM's.

---

## 🚀 Kenmerken

* **Intelligente Tool Selectie:** De AI-agent kiest automatisch tussen de SQL Archivaris en de RAG Analist, afhankelijk van de complexiteit en aard van de vraag.
* **SQL Archivaris:** Beantwoordt vragen over totale waarden, gemiddelden, aantallen en specifieke eigenschappen van panden uit een gestructureerde database (`portfolio.db`).
* **RAG Analist:** Analyseert en vat informatie samen uit ongestructureerde tekstuele documenten (gesimuleerd via een Chroma vectorstore), ideaal voor risicoanalyses, renovatiemogelijkheden en trends.
* **Gebruiksvriendelijke UI:** Een interactieve webinterface gebouwd met Streamlit, inclusief:
    * Veilige API key invoer.
    * Overzicht van portfolio statistieken en de volledige dataset.
    * Voorbeeldvragen om snel aan de slag te gaan.
    * Live weergave van het denkproces van de Agent in de terminal.
* **Optimalisatie voor Efficiëntie:** Geoptimaliseerd om efficiënt om te gaan met tokenverbruik, met slimme error handling voor API limieten.

---

## 🛠️ Installatie & Gebruik

Volg deze stappen om het project lokaal op te zetten en te draaien:

### 1. Kloon de Repository

Open je PowerShell terminal en kloon dit project:

```powershell
git clone [https://github.com/DaandinhoPy94/AgentManagerGPTmain.git](https://github.com/DaandinhoPy94/AgentManagerGPTmain.git)
cd AgentManagerGPTmain
