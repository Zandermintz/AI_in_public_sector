# ai_in_publicsector

Using state-of-the-art pre-trained BERT (Bidirectional Encoder Representations from Transformers) model to produce topic representations from a corpus of ~230 journal abstracts on the use of Artifical Intelligence in the Public Sector. 

This computational research is being conducted in conjunction with a forthcoming paper on this topic.

##########################################################################################################################################################################################################

Directory Includes: 

1. corpus_building.ipynb ==> outlines the full pipeline from leveraging OpenAlex API to create a corpus of relevant journal abstracts to visualizing topic representations produced by fine-tuning a pre-trained BERT model on this corpus

2. BERT_Topic_Model_Tuning.ipynb ==> final values for relevant hyperparameters after fine-tuning for both the full and reduced BERT models. 

3. BERT_AI_Policy_topic_model ==> fine-tuned BERT model on full corpus (~230 abstracts)

4. BERT_AI_Policy_topic_model_reduced ==> fine-tuned BERT model on concentrated corpus (~120 abstracts)


