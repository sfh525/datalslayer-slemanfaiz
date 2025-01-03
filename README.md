# Data Slayer 2.0 Competition by Telkom University
Data Slayer is a natioanl competition held by Telkom University, where participants across many different universities in Indonesia compete in a Kaggle competition for a prize money. 
The competition consist of 2 phases: qualifying and the final. The top 10 teams from qualifying will have a go at the final. In total there were around 200+ teams, each consisting of 2-3 people. 

# Dataset
The dataset itself consists of images where they are organized based their subcategories. The file structure itself is provided in the "File Structure.pdf," where based on this structure, the 
images are labelled for prediction. But in short, teams are supposed to make a machine learning or deep learning algorithm to predict whether a given image belongs to "fall" category (1) or 
"non_fall" category (0). Essentially, it is a binary classification task. The metric that was used is accuracy, which follows this formula: 

$$
Accuracy = \frac{\text{Number of Correct Predictions}}{\text{Total Number of Observations}}
$$

# SlemanFaiz: The Team
We are a team consistsing of 3 people from Gadjah Mada University in Yogyakarta, Indonesia. Here are the names that contribute in our work:
* Tristan Khayru Abiyudha as the Team Leader.
* Salman Faiz Hidayat as a Member.
* Adam Maulana Haq as a Member.

# Summary and Result of Our Work
Our team managed to make it into the 12th spot out of 222 teams that participated. We opted for a deep learning model named InceptionV3, with an accuracy score of 97%. Other attempts of using 
other models such as ResNet50 and Pose Detection yielded a 91.8% and 88% respectively. 

# How to Run Our Notebooks:
It is important to note that our main environment was Kaggle notebooks, so the steps explained below will be better suited 
for it. However, you may choose to run our notebooks can be run locally with only little adjustments such as the file 
directories. Kaggle was chosen because it provides cloud computing resources (such as GPU) that not all members of team 
may have. Furthermore, it allows for better tracking of versions, and allows our notebooks to be run even when our 
laptops/computers are off. Here are the steps of running our notebooks in Kaggle environment: 

1. **Open Kaggle**: Navigate to kaggle.com, and create an account if you have not already.  
2. **Create a Kaggle Notebook**: Click on the large "+ Create" button around the top left part of your screen. Then, click "New Notebook." You can rename the notebook as needed by double clicking the randomly generated title on the top left corner of your screen.
3. **Upload the Dataset**: You can enter the following command in the code cell: **kaggle competitions download -c data-slayer-2-0-machine-learning-competition**. Or, you can manually upload the zip file from the competition by clicking "Upload" on the right hand side of your screen. Then, click "New Dataset". You can then simply drag and drop the zip file and name your dataset. Wait for everything to finish uploading then click "Create."
4. **Import our Notebook**: Import any one of our notebooks that you would like to run into the Kaggle environment. Click "File" (on the top left part of your screen) -> "Import Notebook" -> drag and drop our notebook.
5. **Adjust the File Directory**: Make sure to change any directories in the notebook to match the name of your dataset.
