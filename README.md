# BIL468-Painters-Paintings-Project

Data for this project can be found in and downloaded from the following links:

https://www.kaggle.com/code/paultimothymooney/collections-of-paintings-from-50-artists
https://paperswithcode.com/dataset/wikiart

Note 1: This project's CNN and transfer learning models are not in the Github page due to its size. They are in the following Google Drive link:
https://drive.google.com/drive/folders/189Oz2sv51IdIU27YkFFMwb_BlYQxpF0A
These models should be included in the models folder as it can be seen in the main page of Github for local files.

Note 2: If there are '.DS_Store' files in the train or test folders, the methods may not work. So, they should be removed from these locations.

Note 3: The accuracy results can be seen from the ipynb files' each segment. They are not saved in any text files or something like that except for method 2's results.

The main structure of the files are like this:
->code: In this, there are codes of training and feature extractions etc. belonging to the specific method named file. For example, for method 1's codes that include the training process of that is in the file 'method1.ipynb'.
->data: 
->features: There are txt files that include the results of the feature extraction processes of the method 2.
->models: There are models that are already trained and saved to test any images.
->results: There are txt files that are results from method 2's ML models' accuracy and classification reports.

For model 2's ML models, 

For model 3's CNN models, the structure of the test data should be as the train data. In detail, in 'train' folder, there are each painters' names as folders' names. So there are 50 painter names in the folder 'train'. Then, in each of these folders, there are images that are each a painting of that specific painter. Test should also be like that.

