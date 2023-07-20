# TOPIC MODELING USING LATENT DIRICHLET ALLOCATION (LDA)

> In this project we have performed Topic Modeling on unlabeled dataset containing various articles.
We have used an LDA approach for assingning topics to various articles.


## General Information

Latent Dirichlet Allocation (LDA) is a generative probabilistic model used for topic modeling in 
natural language processing (NLP). It assumes that each document in a collection consists of a 
mixture of different topics, and each topic is a distribution over words.

Here's how LDA works:

### Initialization: 
First, we specify the number of topics we want to discover in the collection. Then, 
LDA randomly assigns a topic to each word in each document.

### Iterative process: 
LDA iteratively refines the topic assignments by considering two steps: word-topic
 assignment and topic-document assignment.

### a. Word-topic assignment: 
LDA looks at each word in each document and calculates the probability that
the word belongs to each topic. It considers both the observed word frequency and the topic 
distribution in the document.

### b. Topic-document assignment: 
LDA examines each document and calculates the probability that the 
document exhibits each topic. It considers the observed word-topic assignments in the document 
and the overall distribution of topics across all documents.

### Convergence: 
LDA repeats the word-topic and topic-document assignment steps multiple times until a stable 
state is reached, indicating convergence.

### Result interpretation: 
After convergence, LDA provides two main outputs:

a. Word-topic distribution: LDA gives us the probability distribution of words for each topic. This 
distribution reveals which words are most characteristic of each topic.

b. Topic-document distribution: LDA gives us the probability distribution of topics for each document. 
This distribution tells us which topics are most prevalent in each document.

By analyzing the word-topic and topic-document distributions, we can interpret the discovered topics 
and their prevalence in the collection. LDA allows us to extract meaningful themes and uncover hidden 
patterns in the text data.

In summary, LDA is a statistical model that assigns topics to words and documents based on observed 
word frequencies and their distributions. It iteratively refines the assignments to discover underlying 
topics in the collection, providing word-topic and topic-document distributions as output for interpretation.