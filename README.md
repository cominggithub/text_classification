

[Text classification from scratch](https://keras.io/examples/nlp/text_classification_from_scratch/)

# download data
curl -O https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz
tar -xf aclImdb_v1.tar.gz


# sync folder
```bash
rsync -a --delete -e "ssh -p 10122" -P ./test_classification coming@cominghome.asuscomm.com:~/coming/ai/
```