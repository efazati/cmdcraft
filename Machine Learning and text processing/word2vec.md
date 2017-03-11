#Wordtvec

./word2phrase -train data.txt -output data-phrase.txt -threshold 200 -debug 2

./word2phrase -train data-phrase.txt -output data-phrase2.txt -threshold 100 -debug 2

./word2vec -train data-phrase2.txt -output vectors.bin -cbow 1 -size 500 -window 10 -negative 10 -hs 0 -sample 1e-5 -threads 40 -binary 1 -iter 3 -min-count 10

