# Query Processor for Comparative Analysis Ad Hoc Retrieval System

Overview:<br>
This project implements a query processing pipeline designed for technology product comparisons in a retreival system that comapres tech products.
It can processes queries like "X vs Y" or "X vs Y for features" into structured search queries for the retreival system to use to look for relevant documents.

The components of this query processor are:
- Query Preprocessing - Text normalization & spell checking
- Query Splitting - Entity/feature separation
- Entity Recognition - Product name identification
- Contextual Enhancement - Entity context enrichment
- Feature Expansion - Expand feature with similar terms
- N-gram Generation - Search query construction

Implementation Details:
- Python implementation using NLTK, SpaCy, WordNet
- WikiData API integration
- Edit distance for spell checking
- Hybrid entity recognition (rule-based + NLP)

Example:
Input: "iPhone vs Samsung for battery life and camera"<br>
Output: Structured queries with expanded terms & context
