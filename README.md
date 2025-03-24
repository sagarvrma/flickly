# Flickly

Flickly is a work-in-progress web app that reimagines photo sharing for serious photographers and enthusiasts. Inspired by platforms like TikTok, Flickly delivers a personalized, scrollable photography feed driven by user interactions—like, save, and skip—to tailor recommendations based on user taste.

## Key Features

- Seamless feed of curated, high-quality photos  
- Smart recommendation system that learns from what you like or skip  
- Filters to browse by camera make, model, lens, subject, and more  
- Like and save photos for later viewing  
- Upload your own work with metadata (e.g., camera, film, edits)  
- "Explore" and "Following" tabs for discovery and connection  
- Clean, modern interface designed for photographers  

## Recommendation System

Flickly uses TF-IDF (Term Frequency–Inverse Document Frequency) and vectorization techniques to build content-based recommendations. User interactions help refine the recommendations by increasing or decreasing the weight of image tags, captions, and metadata.

## Dataset and Database

- The app is powered by a sample of the Unsplash Dataset, which includes metadata like photographer name, camera type, and subject tags.  
- SQLite3 is used as the local lightweight database to store photo metadata, user interactions (likes/saves/skips), and feed state.

## Status

This project is currently under development.  
