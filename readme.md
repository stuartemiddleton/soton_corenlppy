# soton_corenlppy project

soton_corenlppy is a Python NLP library containing a body of open source research code being continually developed at the University of Southampton, UK. its release is intended to support ongoing research and commercial applications involving the University of Southampton.

soton_corenlppy works with Python 3.7 and has been tested on Windows 10 and Ubuntu 18.04 LTS.

Feature suggestions and/or bug reports can be sent to {sem03}@soton.ac.uk. We do not however offer any software support beyond the examples and API documentation already provided.

The software is copyright University of Southampton, UK. It has been supported over a multi-year period by the following grants: EU FP7 TRIDEC (258723), EU FP7 REVEAL (610928), EU H2020 project GRAVITATE (665155), ESRC FloraGuard (ES/R003254/1), DSTL CYShadowWatch (ACC2005442), InnovateUK LPLP (104875), NERC GloSAT (NE/S015604/1). This software can only be used for research, education or evaluation purposes. A free commercial license is available on registration request to {sem03}@soton.ac.uk. The University of Southampton is open to discussions regarding [collaboration](https://www.southampton.ac.uk/~sem03/engagement.html) in future research projects relating to this work.

# soton_corenlppy documentation resources

soton_corenlppy [API](https://www.southampton.ac.uk/~sem03/soton_corenlppy/api/index.html)
soton_corenlppy example code on [github](https://github.com/stuartemiddleton/soton_corenlppy)

# Python libs needed (earlier versions may be suitable but are untested)

Python libs: psycopg2 >= 2.8, nltk >= 3.4, setuptools >= 46

You will need to download NLTK corpra before running soton_corenlppy:

```python
python
import nltk
nltk.download()
==> install all or at least stopwords, names and wordnet
```

# Installation

python3 -m pip install soton_corenlppy
