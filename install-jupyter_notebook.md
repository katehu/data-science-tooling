## For Beginers
### Install 
There are two ways to install the jupyter notebook:
 1. Install from Anaconda Navigator
     + [Anaconda Navigator](https://docs.anaconda.com/anaconda/navigator/index.html) is a desktop tool to manage data science tools without using command lines
     + Download the free software Anaconda Navigator https://www.anaconda.com/products/distribution and Jupyter Notebook will be automatically installed
     + If you have troubles, follow this [video](https://www.youtube.com/watch?v=nWClCF4gqWA&t=272s&ab_channel=McKayJohns)
 2. Install from python 
     + If you have python installed, open the terminal and on the command line type
     ```
     pip install notebook
     ```
 
### Open Jupyter Notebook 
There are two ways to open the jupyter notebook 
 1. Open the Anaconda Navigator and click on the "Lauch" button for the app Jupyter notebook
 2. Open the terminal and on the command line type 
  ```
  jupyter notebook
  ```
  The jupyter notebook will be launched in your internet browser 
  
### Use Jupyter Notebook with R 
Jupyter is a web application for creating and sharing computational documents. It supports programming languages Python, Java, R, Julia, Matlab, Scala, etc., but it itslef does not provide these languages. To use them, we need to install the corresponding kernel for that language. To install the kernel for R:
- Step 1. Install R 
- Step 2. If you have installed the Anaconda, open the terminal and on the command line type 
   ``` 
   conda activate
   ```
   and 
   ```
   conda install -c r r-irkernel
   ```
Then open the jupyter book. Click on the "New" button and select R. Now you can start write a notebook with R. 
<img width="1180" alt="Screen Shot 2022-05-06 at 1 45 35 PM" src="https://user-images.githubusercontent.com/14019327/167191122-9955ad18-2377-4b64-b950-4d4356287a52.png">

- An alternative to the Step 2. We can also add R to Jupyter in an R console by following the instructions: https://irkernel.github.io/installation/


## For Advanced Users 
### Visual Studio + Jupyter Notebook 
  https://www.youtube.com/watch?v=h1sAzPojKMg&t=3s&ab_channel=VisualStudioCode
