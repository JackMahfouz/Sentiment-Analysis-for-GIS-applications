this is a modeule for sentiment classification.

1 - oftware requirement:
1.1 install the followning libraries using pip (pandas, numpy, nltk {corpus, tokenizer, stem}, scikit-learn, re, jolib)
1.2 Data must have the following attributes (text, aspect, x, y):
    text: is the text be to classified
    aspect: i.e. the company to checked
    x, y: the location where date was published
1.3 the return type is a data frame with (aspect, x, y, sentiment)

2 - user manuale
just import the sentiment_classifier and pass it the data frame import using the following line from Modules.utils import sentiment_clossifier, also not that the Modules must be in the same directory as your source file or change the path