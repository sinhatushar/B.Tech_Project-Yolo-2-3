1. Wiki Full Crawl : Summary of about 8000 wikipedia pages crawled from DBpedia 500K dataset.
2. Sample1 : About 500 crawled pages selected from Wiki full crawl.
3. Sample1SentenceSplit : All the files from Sample 1 are split sentence by sentence. This leads to 2217 files each having one 
sentence each. 
4. Sample1OpenIE : OpenIE is run separately on each of the the files from Sample1SentenceSplit(each file has one sentence only).
5. Selected-triple : The first RDF triple from each file having confidence > 0.9 is selected and stored in the corresponding file.
6. Sentences-train : Same as Sample1. Sentences from this folder are used for training.
7. 1982-train-images-416*416 : 416*416 image representation of sentences made using vector embeddings.
8. 339-train-images.tar.gz : 64*320 image representation of sentences made using vector embeddings.
