# BBC-news-classification

This is a code for BBC news classification. The database is included five classes: business, entertainment, politics, sport, and tech. Consists of 2225 documents from the BBC news website.

Dataset: http://mlg.ucd.ie/datasets/bbc.html

this is a sample of one of the documents with class of business: 

""" Yukos unit buyer faces loan claim

The owners of embattled Russian oil giant Yukos are to ask the buyer of its former production unit to pay back a $900m (£479m) loan.

State-owned Rosneft bought the Yugansk unit for $9.3bn in a sale forced by Russia to part settle a $27.5bn tax claim against Yukos. Yukos' owner Menatep Group says it will ask Rosneft to repay a loan that Yugansk had secured on its assets. Rosneft already faces a similar $540m repayment demand from foreign banks. Legal experts said Rosneft's purchase of Yugansk would include such obligations. "The pledged assets are with Rosneft, so it will have to pay real money to the creditors to avoid seizure of Yugansk assets," said Moscow-based US lawyer Jamie Firestone, who is not connected to the case. Menatep Group's managing director Tim Osborne told the Reuters news agency: "If they default, we will fight them where the rule of law exists under the international arbitration clauses of the credit."

Rosneft officials were unavailable for comment. But the company has said it intends to take action against Menatep to recover some of the tax claims and debts owed by Yugansk. Yukos had filed for bankruptcy protection in a US court in an attempt to prevent the forced sale of its main production arm. The sale went ahead in December and Yugansk was sold to a little-known shell company which in turn was bought by Rosneft. Yukos claims its downfall was punishment for the political ambitions of its founder Mikhail Khodorkovsky and has vowed to sue any participant in the sale."""

# Method
The preprocessing part includes: tokenizing, stemming, stopwords and punctuation removal, lowering, etc., the vectorizer ic CountVectorizer and the classifier is MultinomialNB. 

# Results
Train:	 accuracy: 0.997431	  precision: 0.997431	  recall: 0.997431	 f1: 0.997431

Test:	   accuracy: 0.976048	  precision: 0.976048	  recall: 0.976048	 f1: 0.976048

I gained very high results for the train and test stages, indicating that the preprocessing stage was so effective.
