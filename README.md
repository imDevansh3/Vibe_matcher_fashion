Vibe Matcher — Mini Fashion Recommender

Vibe Matcher is a simple AI demo that matches fashion products to a user’s vibe (e.g., “cozy minimal home outfit”) using OpenAI embeddings and cosine similarity.



	•	Uses OpenAI’s text-embedding-ada-002 model to convert fashion product descriptions into vector embeddings.
	•	Computes cosine similarity (via scikit-learn) to find the top-3 matching products for a user’s vibe query.
	•	Handles low-confidence queries with a friendly fallback message.
	•	Logs evaluation metrics like best similarity score and latency for each query.
	•	Built as a simple Jupyter notebook prototype to demonstrate AI-driven product recommendation.


TO RUN THIS:

STEPS:

1)  Install dependencies
```bash
pip install openai pandas numpy scikit-learn matplotlib python-dotenv
```

2) Add your OpenAI API key
Create a .env file:
```bash
OPENAI_API_KEY=your_openai_api_key_here
```

or directly in notebook:

```bash
import os
os.environ["OPENAI_API_KEY"] = "your_openai_api_key_here"
```

👨‍💻 Author

Devansh Thakkar
Internship Task — AI Recommender System (Vibe Matcher)
Built using Python, OpenAI API, and Cosine Similarity.
