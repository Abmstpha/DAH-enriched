# DAH (DAtaset Hassaniya)

## Project Overview

**DAH (DAtaset Hassaniya)** is the first publicly available, open-source dataset for Hassaniya Arabic. Hassaniya is a dialect of Arabic spoken in Mauritania. Despite its widespread use, the language is not well-represented in digital resources.

The primary goal of the DAH project is to bridge this gap. By creating a high-quality dataset, we aim to facilitate:

1.  **Machine Translation:** The development of accurate translation tools between English and Hassaniya. This is crucial for improving technologies like online translators and other AI-driven language models.
2.  **Linguistic Research:** Providing researchers with a structured dataset to study the grammar, vocabulary, and nuances of the Hassaniya dialect.
3.  **Language Preservation:** Documenting Hassaniya in a digital format that is accessible to both the Hassaniya-speaking community and a global audience.


***

## Dataset Details

The DAH dataset is structured as a parallel corpus, meaning that each entry consists of a sentence in English paired with its translation in Hassaniya.

| Component | Description |
| :--- | :--- |
| `english` | The source sentence in English. |
| `hassaniya-ar` | The Hassaniya translation written in the traditional Arabic script. |
| `hassaniya-lat` | The Hassaniya translation written in a Latin-based script, often referred to as "Arabizi." |

*   **Source:** The sentences are adapted from the Tatoeba Project, a large, community-based collection of sentences and translations.
*   **Quality:** All entries have been reviewed by the founders of the Hassan-IA community to ensure accuracy.
*   **License:** The dataset is released under the CC-BY-4.0 license, which allows for open use and adaptation, provided that appropriate credit is given.
*   **Creators:**
  - Ahlam Abdelkader  
  - Emani Babe  
  - Oumoukelthoum Sidenna  

***

## The Hassaniya Latin Script

To maintain consistency for machine learning applications, a standardized transliteration system is used to convert Hassaniya from the Arabic script to the Latin script (`hassaniya-lat`). This system employs a combination of Latin letters and numbers to represent Arabic sounds that do not have a direct equivalent in the English alphabet.

| Arabic Letter | Latin Equivalent | Description (Approximate Pronunciation) |
| :--- | :--- | :--- |
| **ح** (Ḥa) | **7** | A hard 'h' sound produced deep in the throat. |
| **خ** (Khā) | **5** | A 'kh' sound, similar to the 'ch' in the Scottish word *loch*. |
| **ذ** (Dhāl) | **4** | A soft 'th' sound, as in the English word *this*. |
| **ط** (Ṭa) | **6** | An emphatic 't' sound. |
| **ظ** (Ẓa) | **8** | An emphatic 'z' or 'dh' sound. |
| **ق** (Qāf) | **9** | A hard 'q' sound, deeper than a standard 'k'. |
| **ع** (ʿAyn) | **3** | A distinctive guttural sound, known as a voiced pharyngeal fricative. |
| **غ** (Ghāyn) | **gh** | A sound similar to the French 'r'. |
| **ض** (Ḍad) | **dh** | An emphatic 'd' sound. |
| **گ** (Gāf) | **G** | A hard 'g' sound, often used in Hassaniya in place of the classical 'q'. |

**A Note on Vowels:** The dataset intentionally includes variations such as "ou" and "u" for the same sound. This reflects the actual usage of the language in digital contexts, particularly among younger speakers.

***

## How to Contribute

DAH is a collaborative project, and contributions are welcome. Your involvement can help preserve and promote the Hassaniya language in the digital age.

The project repository is available on GitHub: [https://github.com/hassan-IA/DAH.git](https://github.com/hassan-IA/DAH.git)

### Contribution Steps

1.  **Fork** the repository to create your own copy.
2.  Navigate to the `data/contributions/` folder, where you will find new sentences awaiting translation or review.
3.  Select a CSV file to work on. Each file contains approximately 100 entries.
4.  Translate, review, or correct the entries, ensuring that they adhere to the transliteration guidelines.
5.  Commit your changes and submit a **Pull Request (PR)** for review.

We appreciate your interest in contributing to this important resource <3 .
