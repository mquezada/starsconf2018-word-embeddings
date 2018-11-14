# Mini-workshop: Representaciones vectoriales de palabras basadas en redes neuronales

Esta página describe los requisitos y los enlaces de descarga para el "mini-workshop" de la [Starsconf 2018](https://www.starsconf.com/).

## Requisitos

- Python 3.x
- gensim
- Jupyter Notebook

Una forma sencilla de cumplir con estos requisitos es instalando [Anaconda](https://www.anaconda.com/download/) 
o [Miniconda](https://conda.io/miniconda.html) (Miniconda es mucho más liviano).
Verifica tener el `$PATH` correcto, y luego instala las dependencias usando `conda`:

```
conda install gensim jupyter
```

## Datos

Word embeddings de palabras en español [1] computados con [fastText](https://github.com/facebookresearch/fastText):

- 100K vectores (94 MB): [http://dcc.uchile.cl/~jperez/word-embeddings/fasttext-sbwc.100k.vec.gz](http://dcc.uchile.cl/~jperez/word-embeddings/fasttext-sbwc.100k.vec.gz) 
- 300K vectores (281 MB): [http://dcc.uchile.cl/~jperez/word-embeddings/fasttext-sbwc.300k.vec.gz](http://dcc.uchile.cl/~jperez/word-embeddings/fasttext-sbwc.300k.vec.gz) 
- 855K vectores (801 MB): [http://dcc.uchile.cl/~jperez/word-embeddings/fasttext-sbwc.vec.gz](http://dcc.uchile.cl/~jperez/word-embeddings/fasttext-sbwc.vec.gz) 

## Referencias

[1] Word embeddings de palabras en español: [https://github.com/uchile-nlp/spanish-word-embeddings](https://github.com/uchile-nlp/spanish-word-embeddings)