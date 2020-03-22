The dataset consists of a portion of our one-day traffic. 
The first column is the label: 1  indicates a purchase, -1 otherwise. 
The second column is the unique ID of the user session. 
The third and forth columns indicate the timestamp (in seconds) of the visit activity and the purchase one, respectively.

There are 10 features taking integer values (mostly count features, denoted by the prefix N) 
12 categorical features (denoted by the prefix C. Nb: they were not consecutively ordered). The values of the categorical features have been HASHED onto 32 bits for anonymization purposes. The semantic of these features is undisclosed. Some features may have missing values.

YOU CAN freely ADD more features or REMOVE any features that seem unnecessary!