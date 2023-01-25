# Project 3

This is an **individual assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

Project 2 is due Wednesday, December 7 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/459156/assignments/5426774) in the Canvas assignment.

## Dataset 1: Flower Species Dataset

The flower species dataset is available for [download here](https://ufl.instructure.com/courses/459156/files/folder/Project%203/Dataset%201%3A%20Flower%20Species%20Classification).

## Dataset 2: Object Detection Dataset

The object detection dataset is available for [download here](https://ufl.instructure.com/courses/459156/files/folder/Project%203/Dataset%202%3A%20Object%20Detection).

# Edit this READ-ME

Please edit this read-me file with information about your project. There are no requirements for this readme file, but you can find a [template here](https://github.com/catiaspsilva/README-template).





# Project Information


## Preliminary Files

Description: Files needed in order to run code


- Folder: 'flower_species_classification': Inlcudes (4) data test and train npy files
- Folder: 'car_detection_dataset': Includes all associated train and test images and bboxes file
- 'training.ipynb': Imports Shopping Data for preprocessing. Generates Machine Learning Models for evaluating the data. Exports 10 files to the working directory.
- 'test.ipynb': Imports all files that were exported in 'training.ipynb'. Runs Machinine Learning Models on Data and evaluates performance.


## Secondary Files

Description: Files exported/imported through the Preliminary Files. 

Note, these files will be generated/overwritten once 'training.ipynb' has been run. These files have also been uploaded to the repository, however, none are needed to run 'training.ipynb' or 'test.ipynb', as they will be generated in the process.

- 'flower_model.h5': Tuned classification Model for classifiying flower images
- 'car_clf_model.h5': Tuned classification Model for classifiying car images
- 'car_clf_box.h5': Tuned Model for performing regression of bounding box verticies
- 'training_all.pkl': Array of all training image filenames for car dataset
- 'image_list.pkl': Array of all car training data images

https://www.dropbox.com/scl/fo/q4no0dsigz73fsylhlrh0/h?dl=0&rlkey=jc0lqaamy5j30kckvzc7w1x5g

## Instructions

1) Download Preliminary Files.
*Note: The specified URL contains a '.zip' file with the flower and car data folders as well as all secondary files. Ensure these files are downloaded and extracted prior to advancing to the next step.

URL: https://www.dropbox.com/scl/fo/q4no0dsigz73fsylhlrh0/h?dl=0&rlkey=jc0lqaamy5j30kckvzc7w1x5g

2) Ensure all Preliminary Files are in the same working directory i.e. the same folder
3) 'Run' all cells, in order, within the 'training.ipynb' Jupyter Notebook (Kernel --> Restart & Run All)
	Note: Running this program will export all of the specified 'Secondary Files' to the working directory
4) 'Run' all cells, in order, within the 'test.ipynb' Jupyter Notebook (Kernel --> Restart & Run All)
	Note: Running this program will import all of the specified 'Secondary Files' to the working directory
5) All Machine Learning Model/Algothrim Performance Results are displayed within the 'test.ipynb' file


## Additional Note
- Due to the computational cost, the models implemented require the use of the UF HiperGator in order to effectivley run and operate the code. The memory allocation with the standard HiperGator parameters is often insufficent to completley run the model. Therefore, sections of the code may have to be run manually in the instance the HiperGator kernel crashes.