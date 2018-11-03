# JLDA
A feature extraction method for two parents with the common children.

------------------------------------------------------------------------

JLDA is a model extended from LDA.

It works better than LDA in the case of there are two factors that affects the word generation, since two factors are in the collaborative learning. When the view from one factor is sparse, the other view can introduce some auxiliary information to it.

------------------------------------------------------------------------

Model:

(1)lda.cpp\\
You can compile lda.cpp to the execution script like lda. Then given the input data in which each line represents a document, e.g., data.txt,
then you can extract the feature vector for each document by ./lda data.txt.

(2) jlda.cpp\\
Similar to the above program, just make sure your input data is that each line represents (factor1_id factor2_id document)

------------------------------------------------------------------------
