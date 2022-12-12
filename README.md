# MIL-Team-Complex-Transformers-NLP

**Description**

You have two tasks to deal with. Better do them consiquently, because you are going to use results of the first stage for the second stage. Descriptions, recomendations and requirements related to the particular tasks are listed down below under the corresponding headings. Please read `General requirements` section carefully since these are criterions you will be rated under. 

**General requirements**

The overall requirement is to write clean and readable Python code, which refers to the following points:
1. Write your solution in python-scripts: core components of your solution should be python-scripts, jupyter notebooks are allowded only for experiments; 
2. Use style guides (you can refer to [Google's style guide](https://google.github.io/styleguide/pyguide.html));
3. Pack your solution as a github repository with comprehensive README.md file. We should reach your repo, so you make either public or private one with invitation;
4. Your repo must include:
   - README.md file, requirements for the content see below;
   - Python-scripts that represent your solution;
   - Jupyter notebooks for experiments and trials;
   - requirements.txt file;
   - Other stuff you consider necessary for your solution; 
5. Your README.md must include the following:
   - Obtained results;
   - Description of the methods and approaches you took to get these results, feel free to write down hypothesis and trials that did not succeed;
   - Steps we should proceed to launch your solution and get same results as you did;
   - Everything else you would like to mention for us to better understand your solution;


## Task 1. Implement your own efficient Transformer.
Transformer architecture is known for its superior performance in various NLP domains alongside with quadratic time and memory complexity. In this task you are suggested to write efficient Transformer in terms of time and memory requirements. 

For quick start you can refer to [this](https://arxiv.org/abs/2103.13076), [this](https://arxiv.org/abs/2006.16236) and [this](https://arxiv.org/abs/2009.14794). You are not limited to the ideas listed in these papers, your goal is to write faster version of Transformer no matter which approach you are using. 

Note there are existing implementations and you may use them as an inspiration, but you are not allowed to just copy-past somebody's code. In the README.md file while describing your solution you must write down following passages:
1. The overall idea and where did it come from? 
2. What is time and memory complexity of your solution? Prove it with equations.
3. Which parts of the architecture correspond to the pefrormance (time / memory complexity) gains? 
4. How does your solution affect vanilla architecture of the Transformer? 
5. Which benefints and which probable downsides may your solution experience? 

## Task 2. Hit the GLUE!
This task is about finetuning your efficient Transformer on the GLUE tasks. Find two-three tasks among others, which you consider the most demonstrative, and list corresponding performance of your models. You can run your experiments in notebooks. Try to reach as best performance as you can on each of your task, but we do not ask you to do SOTA. Here is the things your report of stage two must include:
1. Description of the chosen tasks: brief overview, metrics and SOTA;
2. Task metrics (efficient Transformer);
3. Reference task metrics (vanilla Transformer);
4. Latency benchmarks;

NOTE: you can choose any architecture of the Transformers family and modify it so it is efficient. Next you measure performance (metrics and latency) of the source version and your optimized version. Your particular task here is to find the way you will be presenting the results so that we can understand performance gains and that is was obtained on the regular basis and not by accident (this refers both to metrics and latency). 
