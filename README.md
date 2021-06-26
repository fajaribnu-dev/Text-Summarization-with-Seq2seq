# Text-Summarization-with-Seq2seq
My master's degree final project. Code are adopted from various sources and documentation. 

This project is about doing text summarization using seq2seq architecture and attention mechanism. I used 2 datasets which are Amazon Food Text Reviews and News Summary. You can get the dataset from here https://github.com/sunnysai12345/News_Summary/blob/master/news_summary_more.csv and https://www.kaggle.com/snap/amazon-fine-food-reviews.

As text summarization core knowledge derived from neural machine translation. There are many tutorials that you can follow but my main sources are from here https://towardsdatascience.com/neural-machine-translation-nmt-with-attention-mechanism-5e59b57bd2ac and https://www.analyticsvidhya.com/blog/2019/06/comprehensive-guide-text-summarization-using-deep-learning-python/. Also for the Attention you can find it here https://github.com/thushv89/attention_keras.
 
I was not able to implement the BLEU and ROUGE score to evaluate my result, instead I used loss validation and training time.

I only used 150,000 rows of data after appending the 2 datasets because I'm limited to my computing resources. You can try using the whole appended dataset but you need to have the computing power.

It was an interesting project and you can improve it to the next step.
