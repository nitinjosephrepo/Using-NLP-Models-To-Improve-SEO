# Similarity Score with BERT
Google Helpful content update has again brought in to focus the importance of writing content that is unique and helpful. Content strategy in the past was 
often dictated by volume over quality which now requires reevulation to reasses and remove thin and low quality content from the websites. Similarity score is a
or how close pages are semantically to each other is a good way to identify pages that need to be revisted. 

There are many algorithm to measure content similarity between pages, tools like screaming frog often use older Text Rank based methods or evaluate page simliarity
based on frequency of words. Which are great but do not check for Semantic similarity. 

I decided to write my own Similarity Score checker with Google BERT using Transformers from Huggingface. You will need to install Goose3 which fetches all 
urls supplies in the list.

<img width="1104" alt="Screenshot 2023-02-24 at 10 32 13 PM" src="https://user-images.githubusercontent.com/80999165/221334594-c67413d5-c3df-4074-9aee-248585fed1de.png">
