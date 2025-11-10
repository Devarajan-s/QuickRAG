# Vibe Matcher - Fashion Recommendation System

## Project Overview
A semantic search system that matches fashion products to vibe queries using embeddings and cosine similarity.



## Results Summary
- **Dataset:** 10 fashion products with color and vibe tags
- **Model:** Sentence Transformers (all-MiniLM-L6-v2)
- **Queries Tested:** 3 test cases
- **Accuracy:** 3/3 matches with score >0.7
- **Avg Latency:** 0.05 seconds per query

## Key Features
- Semantic embedding generation for product descriptions
- Cosine similarity-based ranking
- PCA visualization of embedding space
- K-means clustering analysis
- Performance metrics tracking

## Reflection & Improvements
- **Scalability:** Integrate Pinecone/Weaviate for production-scale vector search
- **Filtering:** Add metadata filters (price range, brand, availability)
- **Fallback Logic:** Implement confidence thresholds with fallback recommendations
- **Model Upgrade:** Test all-mpnet-base-v2 for higher quality embeddings
- **User Feedback:** Add relevance scoring mechanism for continuous improvement

## 🛠️ Tech Stack
Python • Sentence Transformers • Scikit-learn • Pandas • Matplotlib
