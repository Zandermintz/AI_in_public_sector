# ai_in_publicsector

Computational analysis &amp; topic modeling of corpus of ~230 journal abstracts on AI in Public Policy using BERT.

corpus_building.ipynb ==> outlines the full pipeline from leveraging OpenAlex API to create a corpus of relevant journal abstracts, to visualizing topic representations produced by fine-tuning a pre-trained BERT model on this corpus

BERT_Topic_Model_Tuning.ipynb ==> final values for relevant hyperparameters after fine-tuning for both the full and reduced BERT models. 

BERT_AI_Policy_topic_model ==> fine-tuned BERT model on full corpus (~230 abstracts)

BERT_AI_Policy_topic_model_reduced ==> fine-tuned BERT model on concentrated corpus (~120 abstracts)


