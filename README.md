# Introduction

The purpose of this project is to expand on the work done by Demirkiran et. al. on the paper *An Ensemble of Pre-trained Transformer Models For Imbalanced Multiclass Malware Classification*.

The paper, published in June of 2022, only explored using CANINE and BERT LLMs to create a Random Forest for Malware Classification by capturing sequence relationships among API calls.

Generative AI has since gained significant traction and resources and methodologies have significantly improved.

Since LLMs are so large, we explore performing Paramter Efficient Fine-Tuning (PEFT) using Low-Rank Adaptation (LoRA).
By using more and newer LLMs, we hope to increase the model performance while also lowing the training time of the models.

The models proposed to be added to the Randome Forest are
- LlaMa 2 (from Meta)
- BERT (from Google)
- GPT (from OpenAI)
- XLNet (made in collaboration between CMU & Google)

