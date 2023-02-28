# DATA606_Capstone

## my flowchart


```mermaid
graph TD;
    A[Collect Yelp dataset]-->B[Preprocess Data];
    B-->C[Build Text Classification Model];
    C-->D[Build Sentiment Analysis Model];
    D-->E[Build Recommender System];
    E-->F[Deploy System];
    F-->G[Interact with User];
    G-->H[User Input];
    H-->I[Text Classification];
    I-->J[Sentiment Analysis];
    J-->K[Recommendation];
    K-->L[Output Recommendation];
    L-->M[User Feedback];
    M-->N[Update Recommender System];
    N-->I;
    N-->D;
    ```
