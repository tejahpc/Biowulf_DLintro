# Biowulf Deep Learning Intro

Deep learning examples based on Laurence Moroney's excellent Coursera course which introduces deep learning in a concise, practical manner. The jupyter notebooks are self-explainatory and will guide you through samples of deep learning codes. Pytorch examples (Work in Progress) are designed to match the Tensorflow examples. Some examples are also extended and modified to be run on Biowulf. 

## Getting Started

After logging-in to Biowulf, allocate an sinteractive session with the --tunnel option (https://hpc.nih.gov/apps/jupyter.html). In the interactive session:

```
module load python/3.6
git clone https://github.com/tejahpc/Biowulf_DLintro.git
cd Biowulf_DLintro
jupyter notebook --ip localhost --port $PORT1 --no-browser
```
 

