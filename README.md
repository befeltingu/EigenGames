# Do you like Eigenvalues? Do you like Games? Oh boy then you are going to love EigenGames!!!

### Description

Just playing around with the ideas from this article https://deepmind.com/blog/article/EigenGame

paper uno: https://openreview.net/pdf?id=NzTU59SYbNq
paper dos: https://arxiv.org/pdf/2102.04152.pdf

### Current State of the show

5/8/21

Currently just working on getting Algorithm 1 going from the first paper. Going to use mnist because why not. 
Algorithm 1 seems to be at least returning a set of ortho eigenvectors but not sure if principle components. 

Can install with

```angular2html
pip install -r requirements.txt
```

Then run on mnist with 

```angular2html
python main.py
```

I have pytest as a requirements. EigenGame/tests - only one test that checks orthogonality right now

TODO:
* Test whether the vectors are actually the principle components
* Reproduce a test or two from paper
* Algorithm 2 - parallel processing

