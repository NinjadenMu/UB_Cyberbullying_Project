# Detecting Cyberbullying in Visual Content: A Large Vision-Language Model Approach

This repository provides the data and code for the paper Detecting Cyberbullying in Visual Content: A Large Vision-Language Model Approach, accepted in IEEE International Conference on Machine Learning and Applications (ICMLA) 2024.

### Data
Full dataset annotated with visual features and labeled as cyberbullying/non-cyberbullying are in ./data.  When running notebooks, change the dataset path to the location of the extracted zip file.

### Methodology
A general zero-shot prompt (GP.ipynb), a general zero-shot prompt with a definition (GP.ipynb, set with_def to True), a 10-shot prompt, and a CoT (CoT.ipynb) prompt are evaluated.  Our methodology is compatible with current popular aligned Large Vision Language Models, such as GPT-4V, LLaVA, Gemini

### CyberbullyingCoT
Our CoT prompt combines examples annotated by humans identifying and explaining each visual factor and classification in the image (few-shot component), and structured reasoning pathways based on visual factors.


