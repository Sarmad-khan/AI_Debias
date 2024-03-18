# Detecting and Mitigating Gender Biases in Pre-trained nlp models for Urdu Language
# Step 1: Generating debaised Urdu Word Embeddings
# Download embeddings at https://drive.google.com/uc?id=1K_4Fbdv9GJDNjR_avLbzKdJPEMVWdYBm&export=download and put them in Embeddings folder.
# To generate debaised embeddings run command: python debias.py ../embeddings/urduvec_140M_100K_300d.bin ../data/urdu_definitional_pairs.json ../data/urdu_gender_specific_full.json ../data/urdu_equalize_pairs.json ../debiased_embeddings_140M_100K_300d.bin
