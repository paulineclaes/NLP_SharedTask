## NLP 2021 Shared Task: Native Language Identification and Proficiency Level Identification 

This is the repository for the 2021 Shared Task of the Natural Language Processing course at the University of Antwerp. It consists of three folders, a system discription paper, and this README file.

- `NLP_SharedTask_paper`: the system description (academic) paper in PDF.
- **Visualization**-folder: contains two confusion matrices that are also demonstrated in the system description paper, `Confusion_NLI` for the Native Language Identification task, and `Confusion_PLI` for the Proficiency Level Identification task
- **Code_notebooks**-folder: contains five Jupyter Notebook (.ipynb) files: 
    - `best_classifiers`: this notebook contains the code for the **best** classifiers selected for the NLP shared task, one for Native Language Identification and one for Proficiency Level Identification. These are the models that were used for the predictions on the test set. The same models can also be found in the `NLI_notebook` and `PLI_notebook`, but were inserted in another notebook just for clarity.
    - `NLI_notebook`: this contains the code for the preprocessing of the data and for the models used for the task of Native Language Identification, except for the BERT baseline.
    - `NLI_BERT_baseline`: this notebook contains the code for the BERT baseline for the task of Native Language Identification.
    - `PLI_notebook`: this notebook contains the code for the models used for the task of Proficiency Level Identification
    - `PLI_BERT_baseline`: this contains the code for the BERT baseline for the task of Proficiency Level Identification
- **Slides**-folder: there are two .pdf files containing slides: 
    - `NLP_SharedTask_presentation` contains the presentation slides for the presentation given in class on 11 May
    - `NLP_pitch` contains the slides for the pitch given in class on 18 May.
