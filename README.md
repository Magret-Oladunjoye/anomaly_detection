# anomaly_detection
As part of an exercise for the 3rd course in the Machine Learning Specialization offered by Stanford online and deeplearning.ai, I created an anomaly detection algorithm to detect anomalous behavior in server computers

Firstly, I loaded a training dataset with just 2 features, the throughput and latency of the server. I then in summary used a gaussian model to detect anomalous examples in my dataset by fitting a gaussian distribution and finding values with low probabilities based on the density of this distribution

Secondly, I ran my anomaly detection algorithm on a more realistic and harder dataset with 11 features, covering many more bases on properties of computer servers

For this realistic dataset, I computed it's optimal epsilon value, best F1 score on it's cross-validation set and found a substantial number of anomalies in the servers 
