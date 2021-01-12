# Hashtag-Counter
The aim of this project is to implement a system to find the n most popular hashtags that appear on the social media. For the scope of the project, the hashtags are given from an input file. The output is written to an output file or the console as per the arguments given.
The program uses the following data structure for the implementation of the project.

1. Max Fibonacci heap – keeps the track of the frequencies of hashtag.
2. Hash table – stores the hashtags as keys and the pointer to the corresponding node as the value.

The program is designed in such a way that it can run for a million hashtag inputs with accuracy and in efficient running time. Max Fibonacci heap data structure is used because it has an amortized complexity of O(1) for the increase key operation which is performed number of time when any repeated hashtag is encountered.
