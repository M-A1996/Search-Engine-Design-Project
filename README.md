# Advanced Search Engine for Academic Research

## Description
This project focuses on the development of a sophisticated search engine tailored for academic research. It systematically indexes Wikipedia articles, providing precise and efficient information retrieval. Utilizing the Vector Space Model (VSM) and K-means clustering, this engine optimizes search capabilities for a large corpus of textual content. Additionally, it includes a comparison of the VSM and BM25 models to highlight their strengths and areas for improvement.

## Key Features

### 1. Structured Dataset
Our search engine operates on a well-organized dataset comprised of Wikipedia articles, each tagged with unique identifiers such as ID, URL, title, and body text.

### 2. Efficient Search Models
At the core of our search engine is the Vector Space Model (VSM), which has proven to outperform the BM25 model in our evaluations, providing faster search speeds and more relevant search results.

### 3. Advanced Text Processing
The system includes several text preprocessing techniques to enhance the search capabilities:
   - Tokenization
   - Normalization
   - Stop word removal
   - Stemming
   - TF-IDF vectorization
   - Dimensionality Reduction (Truncated Singular Value Decomposition (SVD))

### 4. Clustering for Enhanced Precision
By employing K-means clustering, our search engine categorizes articles into relevant clusters, greatly improving both search precision and speed.

### 5. Evaluation Metrics
- **Silhouette Coefficient**: Measures the quality of clustering by assessing how similar an object is to its own cluster compared to other clusters.
- **Performance Metrics**: Includes indexing accuracy and retrieval effectiveness, with key indicators like Query Response Efficiency and Ranking Effectiveness. The Vector Space Model shows a superior Mean Average Precision score of 0.8764, compared to the 0.8556 achieved by the BM25 model.

## Conclusion
The development of this search engine marks a significant advancement in the field of academic research tools, particularly with the implementation of the Vector Space Model. It enhances both the efficiency and effectiveness of scholarly article retrieval.

## Installation
1. **Clone the repository:**
2. **Navigate to the project directory:**
3. **Install required libraries:**

## Usage
1. **Start the application:**
2. **Use the interface to submit queries and retrieve results.**

## Technologies
- **Programming Language:** Python
- **Libraries:** NLTK, NumPy, Scikit-learn

## Contributors
- Abhishek Vijaykumar Mane
- Andrew Graham Porter
- Mohammad Asghar
- Shreya Murigendra Pattanashetti

## Comparison of VSM and BM25 Models
Detailed comparison of the Vector Space Model (VSM) and BM25 model, evaluating time efficiency and effectiveness for different query types can be found within the presentation and code files. This analysis aids in understanding the practical applications and limitations of each model in academic search contexts.

