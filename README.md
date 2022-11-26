# english_word_frequency

Have you ever wondered what English word is most frequently used? Do you know if people are talking about dogs or cats, which one is more frequently? This small project should help you answer all these questions.

# Setup
First, you clone this repo:
```
cd ~/code/
git clone https://github.com/kittipatkampa/english_word_frequency.git
```

You will find a new directory `english_word_frequency` created under your current directory `~/code/`. Now, go into the new dir:
```
cd english_word_frequency
```

Now, we will use pipenv to install all the dependencies:
```
pipenv install
```

# Dataset
We will use the English Word Frequency dataset made available by [Rachael Tatman in this Kaggle article](https://www.kaggle.com/datasets/rtatman/english-word-frequency?resource=download). Somehow, I just put the csv file `unigram_freq.csv.zip` in this repo already for our convenience.

So, we will need to unzip the file using this command:
```
unzip unigram_freq.csv.zip
```
which gives you `unigram_freq.csv` in your project directry, which can be verified by:
```
ls -l *.csv
```
and you should see the csv file there:
```
-rw-r--r--@ 1 kittipat.kampa  staff  4956252 Sep 21  2019 unigram_freq.csv
```