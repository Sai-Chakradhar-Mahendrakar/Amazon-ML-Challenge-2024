## Problem Statement: 
### Feature Extraction from Images

In this hackathon, the goal is to create a machine learning model that extracts entity values from images. This capability is crucial in fields like healthcare, e-commerce, and content moderation, where precise product information is vital. As digital marketplaces expand, many products lack detailed textual descriptions, making it essential to obtain key details directly from images. These images provide important information such as weight, volume, voltage, wattage, dimensions, and many more, which are critical for digital stores.

## Dataset: 
The dataset is divided into two main files:

- **train.csv**: Contains over 310,000 image links along with metadata.
- **test.csv**: Contains over 130,000 image links along with metadata.
  
Each dataset has the following columns:

1. **index:** An unique identifier (ID) for the data sample
2. **image_link**: Public URL where the product image is available for download. Example link - https://m.media-amazon.com/images/I/71XfHPR36-L.jpg
3. **group_id**: Category code of the product
4. **entity_name:** Product entity name. For eg: “item_weight” 
5. **entity_value:** Product entity value. For eg: “34 gram”
    Note: For test.csv, you will not see the column `entity_value` as it is the target variable.


## Results

Our model achieved the following results:

- **F1 Score**: 0.523 (highest)
- **Rank**: 93 out of 10000+ teams

## Conclusion 
This hackathon, spanning four days, was the longest we’ve participated in so far. We faced challenges, particularly with the computational resources needed to process such a large volume of data. Processing the test.csv file, which involved downloading over **32 GB** of images and running them through an OCR model, took us collectively more than **20 hours**. Despite these obstacles, it was an invaluable experience to work on a real-world problem faced by Amazon. 

We are extremely grateful to Amazon for hosting such an engaging hackathon and look forward to competing again next year!






