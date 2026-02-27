# Ulta-Women-s-Frangrance-Analysis

## 1. Research Question
Do higher-priced fragrances use different marketing language in their product description, and does it relate to product ratings?

## 2. Data
- 500 women's fragrances scraped from Ulta
- Features:
- Price
- Rating
- Review count
- Product description

## 3. Method
- Price segmentation
Devided into Low / Mid / High using quantiles
- Sentiment Analysis
Used VADER compound score
- Keyword Comparison
TF-IDF comparison between Low and High price groups
- Classification Model
Random Forest to predict high-rated products
Features: price, sentiment score, word count, brand

## 4. Results
- High price group had slightly higher average sentiment
- Luxury products use "eau", "parfum"
- Budget products use "body", "mist"
- Model accuracy: 75%
- Price was strongest predictor

## 5. Conclusion
Marketing language differs across price segments
Price remains the strongest predictor of high ratings
