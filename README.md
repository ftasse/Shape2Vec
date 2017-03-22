# Shape2Vec
Shape2Vec: semantic-based descriptors for 3D shapes, sketches and images

Datasets used to train Shape2Vec:

### 3D Shapes & Depthmaps
We rendered depth images using the SHREC'14 large scale retrieval benchmark: http://www.itl.nist.gov/iad/vug/sharp/contest/2014/Generic3D/

Download all depth images (6 renderings from random viewpoints for each shape): https://s3-eu-west-1.amazonaws.com/shape2vec-datasets/public/SHREC14LSSTB_TARGET_MODELS_DEPTHMAPS.zip
 
### Sketches
We use the SHREC'14 extended large scale sketch-based shape retrieval benchmark: http://www.itl.nist.gov/iad/vug/sharp/contest/2014/SBR/


### Language model (word2vec)
* Download the original word2vec code here: https://code.google.com/archive/p/word2vec/source/default/source
* Inside word2vec, run word2vec/trunk/demo-train-big-model-v1.sh to create a file vectors.bin which maps words to vectors
