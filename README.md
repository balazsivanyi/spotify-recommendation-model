
# Session-aware music recommendation ML algorithm on Spotify datasets

A session-based music recommendation algorithm with Spotify API. It was identified in recent studies that deep learning-based “neural” approaches tend to perform worse in classical session-based recommendation tasks than simpler algorithms, such as kNNs. The purpose was to evaluate a kNN session-based recommendation, and compare to state of the art DL-based recommendation system benchmarks, on Spotify's Million Playlist Dataset. 

I quickly realised that kNNs are not gonna be enough, so I looked into Decision Trees, Gradient Boosted Trees specifically. After testing the model with the new features and the optimised hyperparameteres, I managed to achieve 80.6% accuracy. This can be considered as a decent result given the scope of the problem, and the leaderboard at the skip prediction challange.

However, I believe that my implementation can be still somewhat overfitting, which can be found out after another round of hyperparameter tuning, and a more detailed evaluation of the results.
