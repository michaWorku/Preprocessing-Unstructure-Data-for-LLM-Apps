# **Preprocessing Unstructured Data for LLM Applications**  

This repository contains course materials and code implementations for [**Preprocessing Unstructured Data for LLM Applications**](https://www.deeplearning.ai/short-courses/preprocessing-unstructured-data-for-llm-applications/). The course explores techniques for processing diverse document types—**PDFs, Word, PowerPoint, HTML, tables, and images**—to enhance the accuracy and relevance of **Retrieval-Augmented Generation (RAG)** applications.  


## **📌 Course Overview**  
To improve **RAG system performance**, it's essential to extract, normalize, and enrich unstructured data from various sources. This course covers:  

✅ **Preprocessing Unstructured Data** – Converting text, images, and tables into structured formats for LLMs.  
✅ **Metadata Enrichment** – Enhancing retrieval and search performance.  
✅ **Document Image Analysis** – Applying **layout detection, vision transformers, and table transformers** for better text and structure extraction.  
✅ **Building a Multi-Source RAG Pipeline** – Extending LLMs to process **Excel, Word, PowerPoint, PDFs, and EPUBs**.  

By the end of the course, you'll be able to **build a RAG-powered chatbot** capable of handling diverse document formats. 🚀  


## **📂 Course Contents**  

### **1️⃣ Overview of LLM Data Preprocessing**  
- **Understanding RAG Systems** – How LLMs use structured and unstructured data for enhanced responses.  
- **Document Content & Metadata** – Extracting and organizing document elements (titles, text, lists, tables, images).  
- **Challenges in Preprocessing** – Standardizing different document types, handling extraction variability, and leveraging metadata for search.  

### [**2️⃣ Normalizing the Content**](https://github.com/michaWorku/Preprocessing-Unstructure-Data-for-LLM-Apps/tree/main/L2_Normalizing_the_content)  
- **Format Diversity & Common Format Standardization** – Converting different documents into a structured JSON format.  
- **Benefits of Normalization** – Filtering unwanted elements, chunking content, and reducing processing costs.  
- **Data Serialization** – Using **JSON and JSONL** for structured storage and retrieval.  

### [**3️⃣ Metadata Extraction & Chunking** ](https://github.com/michaWorku/Preprocessing-Unstructure-Data-for-LLM-Apps/tree/main/L3_Metadata_Extraction_Chunking) 
- **Metadata for Hybrid Search** – Extracting document details (filename, filetype, sections) for better retrieval.  
- **Semantic Search with Vector Databases** – Embedding documents for similarity-based search.  
- **Hybrid Search Strategies** – Combining semantic search with filtering and keyword search.  
- **Chunking Techniques** – Splitting documents into meaningful sections to improve retrieval and prompt generation.  

### [**4️⃣ Preprocessing PDFs and Images**](https://github.com/michaWorku/Preprocessing-Unstructure-Data-for-LLM-Apps/tree/main/L4_Preprocessing_PDF_Images)  
- **Document Image Analysis (DIA)** – Extracting structured data from scanned documents and PDFs.  
- **Document Layout Detection (DLD)** – Using computer vision to detect elements in document images.  
- **Vision Transformers (ViTs)** – Converting document images directly into structured JSON outputs.  
- **Comparison of Methods** – Trade-offs between document layout models and vision transformers.  

### [**5️⃣ Extracting Tables from Documents**](https://github.com/michaWorku/Preprocessing-Unstructure-Data-for-LLM-Apps/tree/main/L5_Extracting_Tables)  
- **Table Extraction Challenges** – Handling structured data in unstructured documents.  
- **Table Transformers & OCR Postprocessing** – Extracting tables using deep learning models.  
- **HTML Table Representation** – Preserving table structures for better downstream processing.  

### [**6️⃣ Building Your Own RAG Bot**](https://github.com/michaWorku/Preprocessing-Unstructure-Data-for-LLM-Apps/tree/main/L6_QA_RAG_Bot)  
- **Preprocessing PDFs, PowerPoint Slides, and ReadMe Files**  
- **Loading Documents into a Vector Database**  
- **Building a RAG Chatbot using LangChain**  


## **🛠 Technologies & Tools Used**  
🔹 **Python** – For preprocessing and model implementation.  
🔹 **LangChain** – Building the RAG-powered chatbot.  
🔹 **Vector Databases** – Storing and retrieving embeddings.  
🔹 **OCR & Transformers** – Extracting text and structures from complex documents.  


## **🚀 Getting Started**  

### **Installation**  
```bash
git clone https://github.com/michaWorku/Preprocessing-Unstructure-Data-for-LLM-Apps.git
cd preprocessing-llm-data
pip install -r requirements.txt
```

### **Running the Notebook**  
Run the Jupyter notebook to explore hands-on implementations:  
```bash
jupyter notebook
```

---

## **📖 Conclusion**  
By following this [course](https://www.deeplearning.ai/short-courses/preprocessing-unstructured-data-for-llm-applications/), you'll gain **practical skills** in **data preprocessing for LLMs**, enabling you to build **robust RAG applications** that process diverse document types efficiently. 🌍💡  

Happy coding! 🚀
