# APPAREL-RECOMMENDATION-USING-TEXT-AND-IMAGE-SIMILARITY
RECOMMENDING SIMILAR PRODUCTS/APPAREL BASED ON PRODUCT TITLE AND PRODUCT IMAGE USING NLP(BOW,IDF &amp; W2VEC) AND CNN(VGG16).)

1.DATA : Can be downloaded from amazon's product api 
link :https://docs.aws.amazon.com/AWSECommerceService/latest/DG/ItemSearch.html
## data had both product title and images.
2. Built NLP models like BOW, TFIDF and W2VEC models to recommend similar products based on product title(Didn't use product description)
3.The weighted W2VEC model by assigning weights to product brand and color gave better recommendations compared to others.
4.Also developed simple CNN(VGG16) image similarity recommendations using Keras.
