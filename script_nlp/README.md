# Little Women Screenplay NLP Analysis

The Little Women (2019) screenplay written by Greta Gerwig is exceptional because it's not another staid, linear adaptation of a popular novel. Instead, thematic groupings and emotional beats drive scene placement, resulting in a film that weaves back and forth through time and feels full of new life. My excitement about the film (the writing! the cast! Greta!) coincided with learning more about Natural Language Processing, so I decided if I could discern the main themes. 

To do so, I extracted the dialogue lines and accompanying speaker and scene information from a html copy of the script and stored the data in MongoDB.

Then, I performed topic modeling using Non-Negative Matrix Factorization and discovered four topics, which I labeled childhood, family, aspiration, and writing. 

My friends and I enjoyed discussing which March sister we are most like, so it would be fun to expand this project, such that a user could enter text into a simple Flask app and then the character that text is most similar to would be returned. When I had a little extra time prior to my project deadline, I began training classification models to predict the speaker of a given line of dialogue.
