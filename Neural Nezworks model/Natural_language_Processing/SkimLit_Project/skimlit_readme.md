# Skimlit Project :
Skimlit is an advanced Natural Language Processing (NLP) model designed to automate the generation of structured titles for scientific documents. With a focus on enhancing document readability and organization, the model transforms lengthy abstracts into concise and informative titles, specifically categorizing content into sections such as Objective, Methods, Results, and Conclusion.

![Screenshot 2024-01-14 133736](https://github.com/jeevasam30/Neural_Network_Projects/assets/69844137/ca99c0f4-f5fc-4610-9236-77d9d0986f5b)
![Screenshot 2024-01-14 133817](https://github.com/jeevasam30/Neural_Network_Projects/assets/69844137/94162a35-c632-488a-a44f-a8663f789482)

## Project Foundation

### Dataset Source

The core of my project lies in the PubMed 200k RCT dataset, a treasure trove of over 200,000 medical abstracts. This dataset serves as the fundamental building block for training my neural network, offering a diverse collection of medical literature.

**Reference:** [PubMed 200k RCT](https://arxiv.org/abs/1710.06071)

### Architectural Inspiration

inspiration was from the revolutionary work detailed in the research paper titled "Neural Networks for Joint Sentence Classification in Medical Paper Abstracts" ([Read Paper](https://arxiv.org/pdf/1612.05251.pdf)). The authors crafted a neural network architecture with two Bidirectional LSTM layers, incorporating both token and character embeddings. This innovative approach enhances the model's ability to classify medical abstracts with nuanced precision.

### Implementation Snapshot

![Project Snapshot](https://github.com/jeevasam30/Neural_Network_Projects/assets/69844137/d43c1ad8-eb5a-4ede-b027-1b2a8a2206db)

This snapshot captures a pivotal moment, showcasing the convergence of diverse embeddings and architectural elements. It serves as the foundation for my model's prowess in classifying medical abstracts with a focus on joint sentence classification.

# Aim
My aim is to try to achieve a similar model as mentioned in this paper starting with baseline model builidng up to similar model by obtaining the concept of transfer learning at last i have also trained bert modle which usses Pubmed 200k and has pretrained embedding as well.
### Prerequisites:

1. **TensorFlow Basics:**
   Understand fundamental TensorFlow concepts, including tensors and neural network structures.

2. **NLP Proficiency (SpaCy):**
   Familiarity with NLP, focusing on SpaCy for tasks like tokenization and named entity recognition.

3. **Transfer Learning Understanding:**
   Grasp transfer learning principles, especially in the context of pre-trained models like BERT.

   https://github.com/jeevasam30/Neural_Network_Projects/tree/main/Neural%20Nezworks%20model/Natural_language_Processing/fundamentals_NLP

Ensure a solid foundation in these areas to navigate the complexities of the project effectively.

# Models and Evaluation Metrics:
Baseline:
A naive baseline model serving as a reference.

Custom Token Embed Conv1D:
Utilizes Conv1D model with token embeddings.

Pretrained Token Embed:
Employs Universal Sentence Encoder for pretraining.

Custom Char Embed Conv1D:
Incorporates character embeddings and Conv1D.

Hybrid Char Token Embed:
Combines both character and token embeddings.

Tribrid Pos Char Token Embed:
Implements positional, character, and token embeddings following the referenced paper.

BERT Model:
Applies BERT model pretraining for enhanced performance.
| Model                           | Accuracy (%) | F1 Score (%) | Recall (%) | Precision (%) |
|---------------------------------|--------------|--------------|------------|---------------|
| Baseline                        | 72.18        | 69.89        | 72.18      | 71.86         |
| Custom Token Embed Conv1D        | 77.96        | 77.66        | 77.96      | 77.60         |
| Pretrained Token Embed           | 71.46        | 71.15        | 71.46      | 71.47         |
| Custom Char Embed Conv1D         | 65.11        | 64.14        | 65.11      | 65.23         |
| Hybrid Char Token Embed          | 73.43        | 73.19        | 73.43      | 73.45         |
| Tribrid Pos Char Token Embed     | 83.16        | 83.06        | 83.16      | 83.09         |
| BERT Model                       | 88.20        | 88.12        | 88.20      | 88.11         |


![Screenshot 2024-01-14 170247](https://github.com/jeevasam30/Neural_Network_Projects/assets/69844137/845b0a8e-a408-431f-938d-8b53dd05ec56)

# Package Used:
scikit-learn (sklearn)<br/>
Matplotlib<br/>
NumPy<br/>
Pandas<br/>
spaCy<br/>
TensorFlow<br/>
tensorflow_text<br/>
tensorflow_hub<br/>

# Observation 
The observed performance graph indicates that the baseline model outperformed certain other models. This observation raises the possibility of data-related factors influencing the results. Further investigation into the data characteristics is warranted to gain deeper insights and refine the models accordingly.

# Reference: 
https://github.com/mrdbourke/tensorflow-deep-learning

https://www.cloudskillsboost.google/course_sessions/7311196/documents/437740

https://1drv.ms/o/s!AuA8xiztJceqgUkjso-pPc6QsjgO?e=MhVDpk (the last is my notebook where i have put some links to NLP stuff)

Wishing you all the best !
