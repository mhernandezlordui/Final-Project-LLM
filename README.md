# Determination of Profiles between the Autism Disorder and ADHD Disorder for Diagnostic Support using Large Language Models

# General Objective
To develop a Clinical Natural Language Processing (NLP) system specialized in the psychiatric domain to identify symptoms and perform differential diagnoses for Autism Spectrum Disorder (ASD) and Attention-Deficit/Hyperactivity Disorder (ADHD) based on clinical narratives.

The three modules developed are described below:

1. gene_data.ipynb Module. It obtains augmented
data with a conversational narrative, incorporating
symptoms of both disorders.  The steps of the script
are shown in Fig. 1.

![image1](img/Fig1.png)

2. The training.ipynb Module. The script performs the classification
   and fine-tuning. The model will learning to recognize
   symptoms in a conversation with a user.
   The steps of the script are shown in Fig. 2.

![image2](img/Fig2.png)

3. inferences.ipynb Module. The script uses the ClinicalBERT
   language model previously fine-tuned as an embedding extractor
   to obtain a clinical vector from a user narrative. Using the
   "ground truth" vectors and the symptom vectors,
   it calculates the cosine similarity and the comorbidity
   diagnosis between ASD and ADHD. The steps of the script are shown in Fig. 3.

![image3](img/Fig3.png)
