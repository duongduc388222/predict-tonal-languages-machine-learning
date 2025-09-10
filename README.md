# Music as a Mirror: Predicting Tonal Languages with Machine Learning  

## Overview  
Tonal languages utilize **pitch variations** alongside consonants and vowels to convey meaning, making them unique in their phonetic structure. While traditionally studied through a linguistic lens, their **musical dimension remains underexplored**.  

This project investigates the **intersection of music and tonal languages** by applying machine learning to predict whether a song belongs to a tonal language based on pitch-related features.  

The work builds on and improves the research of **Minh Nguyen**, who served as a mentor and guide throughout this project.  
👉 Reference Minh’s original research [here](https://www.pdffiller.com/jsfiller-desk10/?traceparent=00-d51508a91847788079ab4c3d366a043a-c4bc3f877802cce0-00&flat_pdf_quality=high&isShareViaLink=1&lang=en&projectId=1553981139&richTextFormatting=true&jsf-page-rearrange-v2=true&jsf-redesign-full=true&isSkipEditorLoadFrequency=true&jsf-probability-70=true&jsf-socket-io=false&jsf-simplified-modes-iteration-1=true&jsf-offline-mode=false&jsf-heading-bold=true&acc-share-button-in-editor=false&jsf-all-tools-tab=false&jsf-all-tools-tab-branch-b=false&jsf-editor-pdfjs-five=true&jsf-context-menu-to-right-panel=false&jsf-context-menu-to-right-panel-branch-b=false&jsf-disable-autosave=true&jsf-disable-browser-translation=false&jsf-web-mobile-new-filling-experience=false&routeId=e85f7576d3380edbcd74037e41d0aa32#4306f08695a043e5a24cfa2bd8451395).  


## Research Goals  
- Explore whether **musical pitch features** can distinguish tonal from non-tonal languages.  
- Develop and evaluate **machine learning classifiers** using audio features.  
- Investigate potential **applications** in language education, speech recognition, and automated language identification.  



## Dataset  
- **125 songs** collected from tonal and non-tonal languages.  
- Covers diverse **regions, languages, genres, and time periods**.  
- **Feature Engineering**: Extracted pitch contours, harmonic structures, and frequency variation using audio signal processing.  



## Methods  
- **Feature Extraction:** Pitch tracking and signal-processing for musical attributes.  
- **Models Tested:**  
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Random Forest  
  - Neural Networks  
- **Validation:** 10-fold cross-validation with accuracy, precision, and recall metrics.  


## 📊 Results  
| Model               | Cross-Validation Accuracy | Test Accuracy |
|----------------------|---------------------------|---------------|
| Logistic Regression  | **0.65**                  | **0.64**      |
| SVM                  | 0.61                      | 0.60          |
| Random Forest        | 0.59                      | 0.58          |
| Neural Network (MLP) | 0.60                      | 0.59          |  

Findings confirm that **songs in tonal languages exhibit distinct pitch patterns**, paving the way for broader interdisciplinary research at the nexus of **linguistics, music, and AI**.  



## Contributions  
- **Recreated and extended baseline methods** from Minh Nguyen’s research.  
- Expanded dataset collection and **improved feature extraction pipeline**.  
- Enhanced reproducibility through **documented ML workflows and shared code**.  



## Future Work  
- Increase dataset size with multilingual corpora across continents.  
- Implement **deep learning architectures** (CNNs, RNNs, Transformers) for raw audio classification.  
- Explore further applications in **cross-linguistic phonology, musicology, and speech recognition**.  



## Acknowledgments  
Special thanks to **Minh Nguyen**, whose mentorship and foundational research inspired and guided this project.  


