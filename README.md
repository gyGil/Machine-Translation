# Project: Machine Translation #

Project: Machine Translation
Machine translation is a popular topic in research with new papers coming out every year. Over the years of research, different methods were created, like rule-based, statistical, and example-based machine translation. With all this effort, it’s still an unsolved problem. However, neural networks have made a large leap forward in machine translation.
In this notebook, you will build a deep neural network that functions as part of an end-to-end machine translation pipeline. Your completed pipeline will accept English text as input and return the French translation.

## Blog
- Please, check my blog for more details and explanation.
https://gygil.github.io/natural%20language%20processing/Machine-Translation/

### How to use ###

```
git clone https://gygil@bitbucket.org/gygil/machine_translation.git

// create conda env
conda create --name aind-nlp-capstone python=3.5 numpy 
source activate aind-nlp-capstone
pip install tensorflow==1.1 -U
pip install keras -U
KERAS_BACKEND=tensorflow python -c "from keras import backend"

// local machine
jupyter notebook --no-browser
// AWS EC2
jupyter notebook --ip=0.0.0.0 --no-browser
```
