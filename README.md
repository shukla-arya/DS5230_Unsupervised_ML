# DS5110_Unsupervised_ML
Creates a recommender system to suggest movies that align with user taste, discover new and relevant content based on behavioral patterns, and streamline a viewer's selection process.

## Features
* Dataset acquired from Kaggle and contains over 20 million movie ratings across 138,000+ users.
* Movies are suggested through two different methods: user-user and item-item, in addition to use of association rules.
* Algorithms that are utilized include KNNWithMeans, Singular Value Decompisition (SVD), and Collaborative Filtering (CF).

## Tech Stack
* **Language:** SQL, Python  
* **Libraries:** `pandas`, `mysql.connector`, `getpass`
* **Visualization:** `matplotlib`
  
## Requirements

Connect with the Server

```bash
try:
    conn = connect(
        host = "localhost",
        user = input("Enter Username: "),
        password = getpass("Enter Password: "),
        database = "library"
    )

except Error as e:
    print(e)```

