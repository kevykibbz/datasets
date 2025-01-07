# Amazon Reviews 2023

For more details, loading scripts, and preprocessed benchmark files, please visit [amazon-reviews-2023.github.io](https://amazon-reviews-2023.github.io/).

## What's New?

**[April 7, 2024]** Two useful files have been added:
- `all_categories.txt`: Contains 34 lines (33 categories + "Unknown"), with each line listing a category name.
- `asin2category.json`: A mapping between `parent_asin` (item ID) and its corresponding category name.

---

## About the Dataset

The Amazon Reviews 2023 dataset, collected by McAuley Lab, is a large-scale dataset with rich features, including:

- **User Reviews:** Ratings, review text, helpfulness votes, etc.
- **Item Metadata:** Descriptions, price, raw image data, etc.
- **Links:** Graphs for user-item interactions and "bought together" relationships.

---

## Key Features of Amazon Reviews 2023

- **Larger Dataset:** 
  - Contains **571.54M reviews**, a **245.2% increase** from the last version.
  
- **Newer Interactions:** 
  - Includes interactions from **May 1996** to **September 2023**.

- **Richer Metadata:** 
  - Includes more descriptive features in item metadata.

- **Fine-grained Timestamp:** 
  - Interaction timestamps available at the second or finer levels.

- **Cleaner Processing:** 
  - Improved item metadata processing compared to previous versions.

- **Standard Splitting:** 
  - Standardized data splits to encourage benchmarking for recommender systems (RecSys).

---

Explore and utilize the dataset for your research and applications!
