# Amazon Product Review 
This project will analyze the Amazon product dataset containing information about various electronics products, primarily focusing on cables and accessories. The dataset includes product details, pricing, ratings, reviews, and customer feedback.

## **Dataset Description**
The dataset contains **42 product listings** with the following key attributes:
- **Product Information**: ID, name, category, image link, product link.
- **Pricing Details**: Discounted price, actual price, discount percentage.
- **Customer Feedback**: Rating (1-5), number of ratings, user reviews.
- **Product Specifications**: Descriptions, compatibility, warranty information.

### **Key Categories**
1. **Cables & Accessories** (USB-C, Micro USB, Lightning, HDMI)
2. **Smart TVs** (OnePlus, Samsung, LG, Acer, MI)
3. **Networking Devices** (WiFi adapters)

## Data cleaning 
1. Convert "actual_price" and "rating" columns to numeric types.
2. Convert "discount_percentage" from decimal to percentage (multiply by 100).
3. Handle missing values in "rating_count" by filling or removing.
4. Extract the primary category from the "category" column for easier grouping.
5. Check for any other inconsistencies or necessary conversions.

## Analysis Task
1. What is the average discount percentage by product category?
   - Computers & Accessories: ~58%
   - Electronics: ~48%
   - Networking Devices: ~48%
2. How many products are listed under each category?
   - Computers & Accessories: 342 products
   - Electronics: 85 products
   - Networking Devices: 39 products
3. What is the total number of reviews per category?
   - Computers & Accessories: 384,588 reviews
   - Electronics: 149,188 reviews
   - Networking Devices: 30,795 reviews
4. Which products have the highest average ratings?
   - Duracell USB Lightning Apple Certified cable
   - AmazonBasics USB 2.0 Extension Cable
   - AmazonBasics USB 2.0 A-Male to B-Male Cable
5. What is the average actual price vs the discounted price by category?
   - Computers & Accessories: Avg actual ₹1,024, discounted ₹428
   - Electronics: Avg actual ₹21,374, discounted ₹14,999
   - Networking Devices: Avg actual ₹1,268, discounted ₹668
6. Which products have the highest number of reviews?
   - AmazonBasics Flexible Premium HDMI Cable (426,973 reviews)
   - TP-Link USB WiFi Adapter (179,691 reviews)
   - AmazonBasics USB 2.0 A-Male to B-Male Cable (107,687 reviews)
7. How many products have a discount of 50% or more?
   - 602 products
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)?
   - 3.9
   - 4.0
   - 4.1
   - 4.2
   - 4.3
   - 4.4
   - 4.5
9. What is the total potential revenue (actual_price × rating_count) by category?
   - Computers & Accessories: ₹393,819,912
   - Electronics: ₹3,190,311,620
   - Networking Devices: ₹39,017,805
10. What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)?
11. How does the rating relate to the level of discount? 
   - Generally, higher-rated products tend to have moderate discounts (40-60%), while lower-rated products have either very high or very low discounts.
12. How many products have fewer than 1,000 reviews? 

13. Which categories have products with the highest discounts? 
    - Computers & Accessories
    - Electronics
14. Identify the top 5 products in terms of rating and number of reviews combined. 
    - AmazonBasics Flexible Premium HDMI Cable
    - TP-Link USB WiFi Adapter
    - AmazonBasics USB 2.0 A-Male to B-Male Cable
    - OnePlus 80 cm Smart Android TV
    - MI 108 cm Full HD Android LED TV

## Tools used
   - Microsoft Excel 
   - Pivot Table

## Recommendations for Further Analysis:
1. **Detailed Sentiment Analysis**: Perform comprehensive sentiment analysis on all reviews to identify common positive/negative themes.
2. **Price Elasticity**: Analyze how discounts affect sales volume (if sales data were available).
3. **Brand Comparison**: Compare average ratings and prices across different brands.
4. **Product Lifetime Analysis**: Investigate how long products typically last based on review timelines.
5. **Competitive Analysis**: Compare Amazon's private label (AmazonBasics) products with other brands.

## Conclusion 
This analysis reveals that **price, discounts, and product quality** significantly influence customer choices in Amazon’s electronics market.
