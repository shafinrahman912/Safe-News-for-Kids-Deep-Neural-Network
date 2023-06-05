# Safe-News-for-Kids-Deep-Neural-Network
The motto of this research is to make a safer world for children by imposing a filtered or parental control-based online newspaper system. Whenever a child searches for reading news, the newspaper itself wants to learn about the reader’s age and create a personalized reading environment for children.

## The aims of "Safe-News-for-Kids" research work:
- The research aims to create a safer world for children by implementing a filtered or parental control-based online newspaper system.
- The newspaper system aims to personalize the reading environment for each child based on their age.
- The filtering process will be applied with a focus on children initially due to their sensitivity.
- The objective is to filter out toxic and abusive news from online newspapers, ensuring that children can read news freely without negative impacts on their state of mind.
- The initial focus is on Bengali newspapers, with plans to expand the system to cover other languages in the future.
- The main goal is to automate the categorization process of news articles based on the appropriate age-group.
- The research can be implemented in online newspapers to provide children with a reading environment free of abusive content.

## Train / Test Split: We use 90:10 ratio for training and testing data.
- Data for Training: 6300
- Data for Testing: 697

## Model Implementation: 
- For the implementation of the model, we create a class named ‘BagofWordsClassifier’ which is a deep neural network based classifier. We have used two hidden layers with activation functions ReLU and LeakyReLU respectively. We have picked the learning rate of 0.0001 and a batch size of 1000. 
- After passing the tokenized count vector to the model, our model trained according to the training data.
- Lastly, as we have two classes to classify, we have implemented a binary step function to predict our test samples


