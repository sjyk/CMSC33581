# CMSC33581: Topics in Big Data
"The Role of Approximation, Randomization, Distributions in Data Analytics"

We are collecting and storing more data than ever, and in many domains, data is growing faster than the available computational resources. This course starts with the premise that expecting exact computation is unsustainable, and approximation is increasingly necessary. We will deep dive into both the theory and the practice of approximate, randomized, and encoded data structures.

*CMSC Graduate Course Designation*: Data Science Elective

*Grading*: Students will be graded on participation (25% of your grade) and a final course project (75% of your grade).

*Prerequisites*: Statistics/Probability at an advanced undergraduate level and Database Systems/Data Engineering course at an undergraduate level.

## Course Topics

### Unit 1. Information Theory for Data Analytics
* Probability distributions, entropy, conditional entropy, joint entropy, shannon inequalities
* Lossless data compression: dictionary, huffman, and arithmetic coding (and how they relate to entropy)
* Data corruption: error coding, noisy channel model, channel capacity
* Worst-case optimal joins as info theory: what shearer's inequality tells us about join performance (and why!)

### Unit 2. Estimation
* Sampling statistics, independence, exchangeability, limits of distributions, and concentration inequalities
* Stratified sampling, optimal sample allocation, and other advanced sampling ideas
* Histograms and discretization
* Sketches, distinct count, frequency moments, and heavy hitters

### Unit 3. Natural Data Distributions
* Species estimation and rare items
* Beneford's law and multi-scale data
* Preferential attachment, powerlaws, and urn processes
* Rogue waves and other models for outliers

### Unit 4. Randomized Data Structures
* Johnson-Lindenstrauss and Locality Sensitive Hashing
* Understanding metric spaces and their embeddings
* MinHash algorithm and its analysis
* Skip Lists and their analysis
* Bloom Filters
* Differential privacy

## Project Ideas
* Approximate fault tolerance under communication budget
* Optimal data placement to avoid correlated failures
* Deterministic non-uniform sampling with hashing
* Evaluate Beneford's law on data in github
* Learned sketches and learned species estimation
* Optimal promotion probability for skip lists
