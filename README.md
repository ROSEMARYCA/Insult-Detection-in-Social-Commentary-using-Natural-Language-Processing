# Detection of Insults in Social Commentary

*Insults in social media and public forums is a serious problem which can destroy user experience and possibly ruin the reputation of the forum. In this project, we attempt to solve this problem by building a system which can detect insults in social media commentary and labeling them appropriately. Based on these labels, the website owners or the site moderators can take appropriate action against those problematic
users.*
				 
### Main Project Folders/File Descriptions: Contains entire codebase related to project processing, datasets, python files along with other resources

* Project\_preprocess\_data.py : File containing which cleans, preprocesses the data. For detailed information, see the project report.

* Train_data.py : Contains the entire training and modelling code.

* Plot.ipynb : Contains the code for the visualisation of graphs and charts.

* train : Training data

* test : Test data

* train\_clean : Preprocessed data from Project_preprocess_data.py

* test\_clean : Preprocessing the test data.

* Contributors : Members involved in the project

* full\_list\_of\_bad\_words : Google bad words list used.


* .png and .jpg files : Graphs and plots generated dynamically


>Pre requisites:
>   * Install Jupiter ipython for the functioning of plot.ipynb (This includes graphs for understanding of data)

>Steps to Run:
> 1.	Run train_data.py to see the results and the learning curves (This is the main code which trains the data)
>		It will take some time to train all the data based on five models, print the results.
>		At the end, a pkl will will be generated on basis of the best configuration (which is a part of submission)
>		and can be used as a model for future classifications.
>
> 2.	Run test_script.py to test the model. In case if you don't want to make any changes to the model, just skip
>		step 1 and run this file. It takes a sentence as an input and tells you whether it is an insult or not.



