# Text Complexity DE

_TextComplexityDE_ dataset consists of 1000 sentences in the German language with subjective complexity rating, collected 
from German learners in level B, and 250 sentences with a native speaker's simplification.
We selected 23 articles from Wikipedia and 2 articles in simple language. The articles from Wikipedia are from three 
genres: society, economy, and history. 

## Repo details

A technical description of the dataset is given in this paper:
* [Subjective Assessment of Text Complexity: A Dataset for German Language](https://arxiv.org/pdf/1904.07733.pdf)
Babak Naderi, Salar Mohtaj, Kaspar Ensikat, Sebastian Möller, 2019.

The dataset includes:
* Source text: `TextComplexityDE19/source.csv` 1019 sentences from encyclopedia (23 articles from Wikipedia in 3 genres), and 100 sentences from 
Leichte Sprache. 

* Subjective ratings: `TextComplexityDE19/ratings.csv` 901 sentences from the `source` are rated in three scales (complexity,
 understandability, and lexical difficulty) by 267 non-native German learners. On average each sentence got 9.5 valid 
 ratings. Columns `Votes_*`: number of valid ratings, `MOS_*`: Mean Opinion Score over the valid votes , `Std_*`: The 
 Standard Deviation. 

* Normal-Simple German Parallel Corpus: `TextComplexityDE19/parallel_corpus.csv` 250 sentences from above set are 
simplified by 75 native German speakers. Subjective ratings on complexity of simplified sentences are provided as well.

* `TextComplexityDE19/TextComplexityDE19.xlsx` complete dataset in one file.
 
## Citation
For the datasets:

```BibTex
@article{naderi2019subjective,
  title={Subjective Assessment of Text Complexity: A Dataset for German Language},
  author={Naderi, Babak and Mohtaj, Salar and Ensikat, Kaspar and M{\"o}ller, Sebastian},
  journal={arXiv preprint arXiv:1904.07733},
  year={2019}
}
```

## License
MIT License

Copyright (c) Quality and Usability Lab, Technische Universität Berlin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
