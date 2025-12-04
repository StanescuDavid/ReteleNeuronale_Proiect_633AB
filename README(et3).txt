# README 

**Disciplina:** Rețele Neuronale  
**Instituție:** POLITEHNICA București – FIIR - SIA
**Student:** Stanescu David-Gabriel 
**Data:** 20.11.2025

## Introducere

##  1. Structura Repository-ului GitHub

ReteleNeuronale-Proiect-633AB/
├──docs
│   └── datasets/
├── data/
│   ├── raw/   
│         └──apples
│                └──fresh
│                └──rotten
│         └──melons    
│                └──fresh
│                └──rotten      
│   ├── processed/
│         └──apples
│                └──fresh
│                └──rotten
│         └──melons  
│                └──fresh
│                └──rotten 
│   ├── train/    
│         └──apples
│                └──fresh
│                └──rotten
│         └──melons   
│                └──fresh
│                └──rotten
│   ├── validation/    
│   └── test/    
├── src/
│   ├── preprocessing/     
│   ├── data_acquisition/  
│   └── neural_network/    
├── config/                
└── requirements.txt 

##  2. Descrierea Setului de Date

### 2.1 Sursa datelor

* **Origine:** Sursele datelor vor fi foldere impartite in doua alte foldere de imagini, unul pentru fructele sanatoase si unul pentru fructele stricate
* **Modul de achiziție:**  Fișiere externe 
* **Perioada / condițiile colectării:**

### 2.2 Caracteristicile dataset-ului

* **Tipuri de date:** Imagini
* **Format fișiere:** PNG

##  3. Analiza Exploratorie a Datelor (EDA) – Sintetic

### 3.1 Analiza calității datelor

* **Detectarea imaginilor neclare**
* **Identificarea caracteristicilor redundante sau puternic corelate**

##  4. Preprocesarea Datelor

### 4.1 Curățarea datelor

* **Eliminare duplicatelor**
* **Convertirea imaginilor in format adecvat**

### 4.2 Transformarea caracteristicilor

* **Normalizare:** Standardizare

### 4.3 Structurarea seturilor de date

**Împărțire recomandată:**
* 80% – train
* 10% – validation
* 10% – test

### 4.4 Salvarea rezultatelor preprocesării

* Date preprocesate în `data/processed/`
* Seturi train/val/test în foldere dedicate

##  5. Fișiere Generate în Această Etapă

* `data/raw/` 
* `data/processed/`
* `data/train/`, `data/validation/`, `data/test/`
* `src/preprocessing/` 
* `data/README.md`











