# Prompt Templates Used for Dataset Generation

**Context:** These prompt templates were used to generate natural language requests corresponding to the TOSCA references in the 'references_templates' folder.
---

## 🟦 RQ1 – Low Technicality / High Completeness



**Prompt:**  
Formulate a natural language request that could be issued by a non-technical end user. The request should mention all functional needs without referring to the underlying technologies. For example, instead of mentioning a database, the request should describe the need to store data. Based on this request, it should be possible to write the corresponding TOSCA code.

---

## 🟨 RQ2 – Low Technicality / Low Completeness



**Prompt:**  
Formulate a natural language request that could be issued by a non-technical end user. The request should mention the necessary (but not all) functional needs and avoid referring to the underlying technologies. For example, instead of mentioning a database, the request should describe the need to store data. Based on this request, it should be possible to write the corresponding TOSCA code.

---

## 🟧 RQ3 – High Technicality / High Completeness



**Prompt:**  
Formulate a natural language request that could be written by an end user with a good technical background (but not an expert in Tosca). The request should mention all the components involved in the code. By 'components', we mean high-level technologies or systems like OpenStack, MySQL DBMS, etc.

---

## 🟥 RQ4 – High Technicality / Low Completeness



**Prompt:**  
Simulate a request expressed in natural language from an end user with a good technical background (but not an expert in Tosca), in such a way that the following TOSCA code could be written from it.  
Constraints:

- Mention only a few key high-level components (e.g., MySQL, OpenStack), not the complete set used in the code.

---
