1) Install Dependencies:

 You will need to install the necessary libraries for web scraping and text analysis. Key libraries include requests or BeautifulSoup for web scraping and nltk for natural language processing tasks. You can install these libraries via pip:

	pip install requests beautifulsoup4 nltk pandas numpy re string

 Additionally, you may need to download NLTK resources. Run the following Python script after installation:

	import nltk
	nltk.download('punkt')
	nltk.download('averaged_perceptron_tagger')

2) open the "mehul_task_data_extraction_and_analysis.ipynb" file in jupiter notebook and run all cell. make sure all the folders and files are downloaded as it is.

3) output is saved in "output data structure.xlsx"

4) note : a pdf version of solution is saved in "pdf-solution-format.pdf" .


** My approach of solving: 
1) To solve the problem, I created separate files named URL_ID.txt and saved them in the Txt-Output Folder, following the instructions in objective.docx. That txt file contains all of the articles individually.


2) Following that, I was able to retrieve the article data more efficiently by employing exception handling techniques. 2 of the provided links do not contain any posts.

3) The next step involved removing punctuation and stopwords. Organisations contributed stopwords in seven separate text files.

4) I developed a list of both positive and negative terms. This was also included in the txt file provided by the organisation.


5) Creating functions for all of the variables specified was a difficult effort because I attempted to implement everything on my own, despite having decent file handling skills. 

6) Later, I saved all of the variables in the output file concurrently (column by column).

7) I made a pie chart for visualization.

