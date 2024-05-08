# Marketplace Recommendation System

### Introduction

 * When shopping for clothing and apparel online, many consumers find themselves having to maneuver to multiple webpages and landing sites to find items they like for comparison.

 * Our objective is a reduce consumer hassle of browsing to different pages by developing a recommender system based on consumer’s current product image and providing similar recommendations and links to direct them to their desired page.

 * Image based recommendation will help to recommend the most similar product based on customers browsing behaviors. To provide such product recommendations to deliver the most revelent contents and improve customers engagement on the platform, so that it can help business to boost sales and revenue and maintain brand experiences.

### Amazon Product Dataset
The dataset downloaded from Amazon Berkeley Objects Dataset, it contains Product meta data, Catalog image, 360º Images and 3D Models.

For this project, we will only use the Product meta data and Catalag image.

 * Product meta data contains 147,702 product listing, includes 28 product features. For this project, we will only use the following features brand, color, item_id, item_name, product_type, country, marketplace, main_image_id.
 * Catalog image contains 398,212 images, it is a gzip-compressed comma-separated value (CSV) file with the following columns: image_id, height, width, and path.

We will download the data directly from https://amazon-berkeley-objects.s3.amazonaws.com/index.html#
