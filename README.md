# Yelp Restaurant Photo Classification Challenge

At Yelp, there are lots of photos and lots of users uploading photos. These photos provide rich local business information across categories. Teaching a computer to understand the context of these photos is not an easy task. 

In this dataset there are photos that belong to a business and the idea is to to predict the business attributes. There are 9 different attributes in this problem:

0: good_for_lunch

1: good_for_dinner

2: takes_reservations

3: outdoor_seating

4: restaurant_is_expensive

5: has_alcohol

6: has_table_service

7: ambience_is_classy

8: good_for_kids

These labels are annotated by the Yelp community. Your task is to predict these labels purely from the business photos uploaded by users. 

Since Yelp is a community driven website, there are duplicated images in the dataset. They are mainly due to:

users accidentally upload the same photo to the same business more than once (e.g., this and this)
chain businesses which upload the same photo to different branches
Yelp is including these as part of the competition, since these are challenges Yelp researchers face every day. 

To deter hand labeling, Kaggle has supplemented the test set with additional "ignored" businesses. These are not counted in the scoring. 

## File descriptions

**train_photos.tgz** - photos of the training set

**test_photos.tgz** - photos of the test set

**train_photo_to_biz_ids.csv** - maps the photo id to business id

**test_photo_to_biz_ids.csv** - maps the photo id to business id

**train.csv** - main training dataset. Includes the business id's, and their corresponding labels. 

**sample_submission.csv** - sample submission and the test dataset. This is the correct format for your predictions. It should include the business_id and the corresponding predicted labels.

Source: https://www.kaggle.com/c/yelp-restaurant-photo-classification
