# Classifying Stackexchange User Voting Behavior
The data was donated by [stackexchange](https://data.stackexchange.com/) and can be found [here](https://archive.org/details/stackexchange)

After downloading and extracting the data, the [ETL script](https://github.com/jmt7080/ETL-of-stackexchange-data/blob/master/Stackexchange.ipynb) is able to parse all the XML files, then split into questions and answers, specified by their category as chosen by the user. The scalability is depending on the number of categories that the user decides to use. 
