#  MetaKaggle Doppelgänger Detector (Hackathon Submission)

This project uncovers lookalike Kaggle users based on contribution behavior, ranks, medals, competition scores, and kernel performance. Built for the **Meta Kaggle Hackathon**, it uses Python, pandas, cosine similarity, and visualizations to recommend the top most similar users — or "doppelgängers" — for any given user on Kaggle.

---

##  Goal

To analyze Kaggle user behavior and **find similar users** using engineered features and cosine similarity, creating a system that helps:

- New users discover role models to follow  
- Community builders connect like-minded contributors  
- Kaggle improve user engagement & personalization

---

##  Files Included

| File | Description |
|------|-------------|
| `Meta_Kaggle (2).ipynb` | Complete notebook (cleaning, merging, modeling, visualizing) |
| `final_cleaned_userfeats.csv` | Engineered user features across achievements, competitions, submissions, kernels |
| `top_similar_users.csv` | Final output with top 5 similar users for each Kaggle user |
| `thumbnail.png` | Project banner/thumbnail |

---

##  Features Used

- Account age, country, tier
- Total medals & achievement types
- Submission stats (best public/private scores)
- Kernel contributions & vote scores
- Competition hosting & rewards
- **Cosine Similarity** across normalized features


##  Demo Video

📺 [Watch the full walkthrough on YouTube] ((https://youtu.be/LFTeD_D2U1U?feature=shared))

