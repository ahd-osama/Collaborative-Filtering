{\rtf1\ansi\ansicpg1252\cocoartf2761
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Recommender System Project\
\
This project implements a **Collaborative Filtering Recommender System** using **User-based** and **Item-based** collaborative filtering. Collaborative filtering is one of the most widely used techniques for building recommendation systems, which helps predict the preferences of users based on the preferences of similar users or items.\
\
Collaborative filtering works on the principle that if users agree on one thing, they will likely agree on other things as well. It has two main types:\
\
### 1. **User-based Collaborative Filtering**:\
   - This method recommends items based on the users that are similar to the target user. The idea is that if user A and user B have similar preferences for several items, then user A will like the items that user B has liked. This method computes the similarity between users using metrics like **Cosine Similarity**.\
   \
### 2. **Item-based Collaborative Filtering**:\
   - This method recommends items based on their similarity to other items that the user has liked. If a user likes a certain item, the system looks for other items that are similar to it and recommends those items.\
\
### To install the dependencies:\
\
pip install -r requirements.txt\
}