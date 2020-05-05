# Description
Can a K-Means Cluster algorithm identify famous books?
In this repository, I run an experiment to see if a K-Means Clustering Algorithm can correctly group and identify 3 famous authors and book series: Harry Potter, Lord of The Rings, and Game of Thrones.

# Dependencies

1. Python 3.7+
```
pip install pandas;
pip install matplotlib;
pip install sklearn;
pip install nltk;
```

# Book Vectors
Each book has a vector that consists of relative token frequencies. 
Only the tokens with the highest document frequency are included in the vectors. 


# Data Sources

1. GOT txt files: https://www.kaggle.com/muhammedfathi/game-of-thrones-book-files
2. Harry Potter and Lord of The Rings txt files: http://www.glozman.com/textpages.html
