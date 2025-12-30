# 📘 **README — 20th Century Events Project**

## 📌 **Overview**

This project analyzes key geopolitical relationships of the 20th century using a combination of **web scraping**, **natural language processing (NLP)**, **named entity recognition (NER)**, and **network analysis**.  
All tasks were completed using **Python 3**, and every required library is listed in **`requirements.txt`**.

The goal of the project is to extract historical information, process it computationally, and model the geopolitical structure of the 20th century as a network of interacting states.
This Case Study is part of a Data Analysis CareerFoundy Course 
---

## 📂 **Submitted Tasks**

### **1.4 Web Scraping**  
Scraped historical text data from 20th Century key event wikipedia page to build the dataset used for NLP and network analysis.
Scraped Countires list from Wikipedia page to create a list of countires to lookup later in the 20th century text.

### **1.5 NLP (Text Processing)**  
Cleaned, tokenized, and processed the scraped text to prepare it for entity extraction and relationship modeling.

### **1.6 NLP – Named Entity Recognition (NER)**  
Identified countries, leaders, and geopolitical entities mentioned in the text using NER models.

### **1.7 Network Creation & Analysis**  
Constructed a geopolitical network from extracted countries and relationships, then applied community detection and centrality metrics.

---

## 📁 **Exported Files**

Depending on your project structure, this section typically includes:

- **`scraped_20th_century.txt`** — Raw text scraped and cleaned from Wikipedia  
- **`countries.txt`** — original countries file from Wikipedia
- **`Scraped List of Countries.txt`** — scraped and cleaned countries from Wikipedia
- **`entities.csv`** — NER‑extracted entities (countries, leaders, organizations)  
- **`20th_century_countries_relationship.csv`** — Relationship pairs used to build the network  
- **`countries.html`** — Exported network for visualization (e.g., Gephi)  
- **`countries_communities_leiden.html`** — Lyndon community Exported network for visualization 

---

## 🌍 **Main Findings — Network Analysis of 20th‑Century Geopolitics**

This project identifies the structural anchors of the 20th‑century geopolitical network using:

- **Lyndon community detection**
- **Degree centrality**
- **Closeness centrality**
- **Betweenness centrality**

### **🔺 Tri‑Polar Core Structure**

The analysis reveals a **tri‑polar geopolitical core** consisting of:

- **Germany**
- **Soviet Union**
- **Japan**

These three states dominate both **direct influence** and **global information flow**.

---

### **🔗 Community Structure (Lyndon Algorithm)**

- A **high‑density cluster** forms between **Germany, Italy, Japan, and Poland**.  
- This cluster reflects historically aligned political and military relationships.  
- **France** exerts a strong directional influence on **Germany**, indicating significant historical interaction.

---

### **🏛 Centrality Metrics**

| **Metric** | **Leaders** | **Interpretation** |
|-----------|-------------|--------------------|
| **Degree Centrality** | Germany, Japan, Soviet Union | Most direct alliances and interactions |
| **Closeness Centrality** | Soviet Union, Germany, Japan, Poland, France | Most efficient at spreading influence across the network |
| **Betweenness Centrality** | Soviet Union | Acts as the main bridge and gatekeeper of information |

---

### **📌 Interpretation & Historical Accuracy**

- **Soviet Union** leading in *Betweenness* and *Closeness* aligns with its historical role as a **bridge between Eastern and Western blocs**.  
- The **Germany–Italy–Japan–Poland** cluster reflects historically aligned political and military structures.  
- The tri‑polar core (Germany, USSR, Japan) accurately mirrors the major power centers shaping global events during the 20th century.

---

## 🛠 **Dependencies**

All libraries required for all tasks (scraping, NLP, NER, and network analysis) are listed in:

```
requirements.txt
```

## ✔️ **How to Run the Project**

1. Install dependencies:  
   ```
   pip install -r requirements.txt
   ```
2. Run each task script in order (1.4 → 1.7).  
3. Open exported files to inspect results or load the network into Gephi for visualization.
