### Data Description:

MovieLens data sets were collected by the GroupLens Research Projectat the University of Minnesota. [Data Source](https://grouplens.org/datasets/movielens/100k/)

### Context:

The GroupLens Research Project is a research group in the Department of Computer Science and Engineering at the University of Minnesota.The data is widely used for collaborative filtering and other filtering solutions.

### Objectives:

- Exploratory Data Analysis
- Visualization using Python (Seaborn, Matplotlib)
- Pandas

### Steps and tasks:

- Download and Extract the zip file [Here](https://grouplens.org/datasets/movielens/100k/) and you will find a folder named  ml-100k. 
- Go through the README file, you will find the information about the attributes of the three datasets.
- You will need to import 3 files from the folder as data frames  into your Jupyter notebook.
    - u.data 
    - u.item
    - u.user
- Display univariate plots of the attributes: 'rating', 'age', 'release date', 'gender' and 'occupation', from their respective data frames.
- Visualize how popularity of Genres has changed over the years. From the graph one should be able to see for any given year, movies of which genre got released the most.
- Display the top 25 movies by average rating, as a list/series/dataframe.Note:-Consider only the movies which received atleast a 100 ratings.
- Verify the following statements (no need of doing a statistical test. Compare absolute numbers):
    - Men watch more drama than women
    - Men watch more Romance than women
    - Women watch more Sci-Fi than men

### Solution: [Visualization_using_pythton.ipynb](https://github.com/jimohola/Visualization_Using_Python/blob/50367f2c9ff5de57f3f7a1dbf75ca7b9f534558c/Visualization_using_python.ipynb)

