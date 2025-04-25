# Recommender System Project

This project implements a **Collaborative Filtering Recommender System** using **User-based** and **Item-based** collaborative filtering. Collaborative filtering is one of the most widely used techniques for building recommendation systems, which helps predict the preferences of users based on the preferences of similar users or items.

Collaborative filtering works on the principle that if users agree on one thing, they will likely agree on other things as well. It has two main types:

### 1. **User-based Collaborative Filtering**:
   - This method recommends items based on the users that are similar to the target user. The idea is that if user A and user B have similar preferences for several items, then user A will like the items that user B has liked. This method computes the similarity between users using metrics like **Cosine Similarity**.\
   
### 2. **Item-based Collaborative Filtering**:
   - This method recommends items based on their similarity to other items that the user has liked. If a user likes a certain item, the system looks for other items that are similar to it and recommends those items.

### To install the dependencies:
pip install -r requirements.txt\
