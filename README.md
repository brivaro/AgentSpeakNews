<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="80" alt="Python Logo" />
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Microscope.png" height="80" alt="Agent Emoji" />

  <h1>🔍 AgentSpeakNews: Multiagent News Query System</h1>

  <p>
    <img src="https://img.shields.io/badge/Python-3.12.9-blue" alt="Python">
    <img src="https://img.shields.io/badge/SPADE-latest-green" alt="SPADE">
    <img src="https://img.shields.io/badge/Owlready2-latest-yellow" alt="Owlready2">
    <img src="https://img.shields.io/badge/Feedparser-latest-orange" alt="Feedparser">
  </p>
</div>

---

### 💡 Overview
**AgentSpeakNews** is a **multiagent system** implemented in Python using **SPADE**. The core idea is that a **coordinator agent (Agent 1)** handles a **search query** and distributes it to **specialized agents**, each monitoring different **RSS news feeds**. These agents search for relevant news articles matching the query and return their findings to the coordinator, which then compiles a **consolidated summary** for the user.  

In addition, **ontologies** are used to **enhance communication** between agents, making the system more flexible and semantically aware. 
- Used ontology --> [RNEWS](http://dev.iptc.org/files/rNews/rnews_1.0_draft3_rdfxml.owl)
- Used feed news --> [BBC](http://feeds.bbci.co.uk/news/rss.xml), [NYT](https://rss.nytimes.com/services/xml/rss/nyt/HomePage.xml), [CNET](https://www.cnet.com/rss/news/) 

![image](https://github.com/user-attachments/assets/6ff0ba82-659b-4eb1-9e39-497534b8e8de)

---

### 🗳 Features
- **Multiagent Architecture:** Decentralized query processing using multiple agents.  
- **Dynamic News Retrieval:** Users input a search term, and agents return relevant news from various sources.  
- **RSS Feed Integration:** Agents fetch and analyze news articles using `feedparser`.  
- **Ontology-Based Communication:** Agents leverage `Owlready2` to structure knowledge and enhance interoperability.  
- **Easily Expandable:** New agents or additional knowledge structures can be integrated seamlessly.  

---

### 📌 Technologies Used
- **Python** - Primary development language.  
- **SPADE** - Framework for multiagent system implementation.  
- **Owlready2** - Library for ontology management.  
- **Feedparser** - RSS feed parser for retrieving news articles.  

---

## 📖 Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/brivaro/AgentSpeakNews.git
   cd AgentSpeakNews
2. Install Dependencies (conda environment with python 3.12.x):
   ```bash
   pip install spade owlready2 feedparser
3. Run the Project with ipynb or python script. (Ensure your XMPP server is configured, and agent credentials are set up.)

---

### 🤖 Extensions & Future Improvements

- **More Agents:** Add new agents for additional RSS sources.
- **Enhanced Ontologies:** Expand the knowledge model for richer data representation.
- **User Interface:** Implement a GUI for a more interactive experience.

