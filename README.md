# Determination of Profiles between the Autism Disorder and ADHD Disorder for Diagnostic Support using Large Language Models
#### Read the full article at [Texto del Enlace](URL_del_PDF)

# General Objective
To develop a Clinical Natural Language Processing (NLP) system specialized in the psychiatric domain to identify symptoms and perform differential diagnoses for Autism Spectrum Disorder (ASD) and Attention-Deficit/Hyperactivity Disorder (ADHD) based on clinical narratives.

The three modules developed are described below:

1. gene_data.ipynb Module. It obtains augmented
data with a conversational narrative, incorporating
symptoms of both disorders.  The steps of the script
are shown in Fig. 1.

<img width="110" height="380" alt="image" src="https://github.com/user-attachments/assets/15fe9e81-4414-461e-9ac2-618545406dcb" />
Fig.1

2. The training.ipynb Module. The script performs the classification
   and fine-tuning. The model will learning to recognize
   symptoms in a conversation with a user.
   The steps of the script are shown in Fig. 2.
   
<img width="120" height="400" alt="image" src="https://github.com/user-attachments/assets/3d7e0dc3-1397-4737-a673-a9e66725b8de" />
Fig. 2

3. inferences.ipynb Module. The script uses the ClinicalBERT
   language model previously fine-tuned as an embedding extractor
   to obtain a clinical vector from a user narrative. Using the
   "ground truth" vectors and the symptom vectors,
   it calculates the cosine similarity and the comorbidity
   diagnosis between ASD and ADHD. The steps of the script are shown in Fig. 3.
   
<img width="150" height="500" alt="image" src="https://github.com/user-attachments/assets/ea86c8ca-dc56-49bd-b6b8-62f471690ff9" />
Fig. 3.

