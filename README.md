# Machine_Learning_for_Texts
## *This was a Machine Learning using Texts project for TripleTen. 👩🏽‍💻*
This project supports the Film Junky Union, a new online community for classic movie lovers, by developing a system to automatically classify movie reviews as positive or negative. The goal was to build a sentiment analysis model that could help the platform moderate and organize user-submitted content. Using a large, balanced dataset of over 47,000 IMDb reviews, the project aimed to achieve an F1 score of at least 0.85 on the test set.

Multiple models were developed and evaluated, ranging from traditional natural language processing techniques to advanced transformer-based architectures:

* Model 1 combined NLTK preprocessing, TF-IDF vectorization, and Logistic Regression, performing well on the test set (F1 = 0.88) but failing to generalize (F1 = 0.67 on final review set).
* Model 2 showed similar trends with slightly lower scores overall.
* Model 3 had lower F1 scores throughout but demonstrated better consistency across datasets.
* Model 4, built with a pretrained BERT transformer, proved the most reliable—achieving an F1 score of 0.81 on the test set and 0.75 on the final review set, showing strong generalization and consistent performance.<br><br>


While Model 4 did not fully reach the 0.85 benchmark, its stability across different review samples makes it the most viable candidate for real-world deployment. Given the dynamic nature of a community-driven platform like Film Junky Union, this model offers a solid foundation for scalable, automated review moderation and enhanced user experience.
## Skills Highlighted
🤖 Machine Learning for Texts
➡️ Text Vectorization, including Lemmatization, Regular Expressions, Bag-of-Words, N-Gram, & TF-IDF
🥰 Sentiment Analysis
🤟🏻 Language Representations, including Word Embeddings, Word2vec, Embeddings for Classification, & BERT
## Installation & Usage
* This project uses math, numpy, pandas, matplotlib, seaborn, tqdm.auto, and nltk.  It requires python 3.11.7.
* Due to file size limitations, the data set is not uploaded here.  It contains IMDB reviews from Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts. (2011). Learning Word Vectors for Sentiment Analysis. The 49th Annual Meeting of the Association for Computational Linguistics (ACL 2011)
