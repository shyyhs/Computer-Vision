# Computer Vision course in Kyoto University

### This is the first assignment.

/*
When I read all the powerpoints I thought it is very easy and began it in the last few days but there is a bug which is realated to the EigenVector computed by Numpy.
I should have began it ealier.
*/


## Description:

In this project, you will learn about homography matrices and use them to warp planar regions in images. The project consists of two major parts: rectification of a single planar region, and compositing of one planar region onto another. 

Download the attached Jupyter notebook, implement the assignment (you can choose to use the skeleton code and fill in the blanks), and upload the notebook. You can upload your downloaded Jupyter notebook to Google Drive and run it with Colaboratory. Note that we will only look at the notebook and run it on Colaboratory (Google Drive), so include everything in there including your images, data points, and experimental results. You are required to demonstrate rectification and compositing on at least one (pair of) image(s) of your own.  

Your grade will be based on code that you add to complete the attached skeleton file. Though it should not be necessary, you are free to add additional functions as you see fit to complete the assignment. You are NOT, however, allowed to import additional libraries especially those that directly provide the solution (e.g., compute homography) or submit separate code files. Everything you will need has been included in the skeleton. If you choose not to use the skeleton code, you are on your own, but again you are not allowed to use external libraries that directly provide the solution.

You will need to compute the eigendecomposition of real-valued symmetric matrix. Numpy provides such as function: Numpy Eigendecomposition. Note that this function returns the eigenvectors as columns, not rows as one might expect. The i'th eigenvector is evecs[:,i].

## Environment

### 1.The easiest way:
Google colabotory: https://colab.research.google.com/

Download it and upload it to google colaborary.  

### 2.Ipython
You can open it in Ipython in anywhere but make sure the libaries are installed already including:

  google.colab
  cv2
  numpy
  matplotlib
  
## Usage
  Open it and run it from begin to end.
  You can upload your own images, surely.

