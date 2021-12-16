# PREDICTIVE-ANALYSIS
BINARIZATION USING THE LOGISTIC REGRESSION:
What is Binarization?
Binarization is the process of transforming data features of any entity into vectors of binary numbers to make classifier algorithms more efficient. In a simple example, transforming an image’s gray-scale from the 0-255 spectrum to a 0-1 spectrum is binarization.


How is Binarization used?
In machine learning, even the most complex concepts can be transformed into binary form. For example, to binarize the sentence “The dog ate the cat,” every word is assigned an ID (for example dog-1, ate-2, the-3, cat-4). Then replace each word with the tag to provide a binary vector. In this case the vector: <3,1,2,3,4> can be refined by providing each word with four possible slots, then setting the slot to correspond with a specific word: <0,0,1,0,1,0,0,0,0,1,0,0,0,0,0,1>. This is commonly referred to as the bag-of-words-method.



Since the ultimate goal is to make this data easier for the classifier to read while minimizing memory usage, it’s not always necessary to encode the whole sentence or all the details of a complex concept. In this case, only the current state of how the data is parsed is needed for the classifier. For example, when the top word on the stack is used as the first word in the input queue. Since order is quite important, a simpler binary vector is preferable.
