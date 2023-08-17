# immune_subtype_predictor

In computational biology, machine learning is used to make biological phenotype predictions based off of a number of genomic data types. We used these techniques to develop a model capable of making immune response predictions and classifying them into six subtypes: wound healing, IFN-γ dominant, inflammatory, lymphocyte depleted, immunologically quit, and TGF-β dominant. This work is largely based on The Cancer Genome Atlas, a collaborative effort between numerous institutions, researchers, and medical professionals, that compiles comprehensive genetic and molecular data from thousands of cancer samples. 

We trained various machine learning model classes, including RandomForestClassifier, NearestNeighbors, and SupportVectorClassifier, on 109 different gene sets before further refining the ones that yielded the greatest prediction accuracies when scored through five cross fold validations. Our current model has obtained a accuracy rating of 79.7%, and has great potential for improvements to be made. The future hope for this model is to apply it to practical use so that it may one day work in making predictions on new patient data. 
