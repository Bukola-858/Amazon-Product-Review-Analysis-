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
2. How many products are listed under each category? 
3. What is the total number of reviews per category?  
4. Which products have the highest average ratings? 
5. What is the average actual price vs the discounted price by category? 
6. Which products have the highest number of reviews? 
7. How many products have a discount of 50% or more? 
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)? 
9. What is the total potential revenue (actual_price × rating_count) by category? 
10. What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)? 

