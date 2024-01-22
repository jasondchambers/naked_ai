## Naked AI

Way back in 1999, a new cooking show in the UK launched called ["The Naked Chef"](https://en.wikipedia.org/wiki/The_Naked_Chef) starring [Jamie Oliver](https://en.wikipedia.org/wiki/Jamie_Oliver). The name comes from the style of cooking where the methods were stripped down to the bare essentials.

I like the approach of getting down to the basics to begin the learning journey for something as complicated and seemingly magical as AI. I have used this approach successfully before to learn networking and the TCP/IP stack. 

If we were to strip AI (deep learning specifically) down to the bare essentials, what might we find? If we were to put AI under a microscope, what would we be looking at? If you are looking to better understand things like ChatGPT under the covers, where do you even start? The field of AI began approximately 80 years ago - who has time to study the history and read all the papers to understand how we got where we are today?

As I began my journey to learn this technology, I was not getting what I needed just by following [PyTorch](https://pytorch.org/) or [TensorFlow](https://www.tensorflow.org) tutorials. Although I was able to get things working, I remained curious as to what is actually happening underneath the covers. I also felt initially overwhelmed and bored with the concepts, the theories and the dizzying amount of algorithms related to how machines learn. For me at least, I need to learn by doing.

The intent here is to provide you with a good yet very basic understanding of an artificial neural network (ANN). Consider it a place to start your learning. We will not cover training - we will assume the network is already trained. In fact, we won't even go into neural networks at all - we will go deeper and see what a stand-alone artificial neuron does. This is focused on helping developers learn AI, and so I will be using code to demonstrate the concepts. Specifically, I'm using Python - if you are not familiar with Python, don't worry - it should be fairly easier to understand if you are familiar with other programming languages. I use Python because it has emerged as the standard programming language for machine learning.

If you want to learn more, I recommend the "MIT Introduction to Deep Learning" available for free on [YouTube](https://www.youtube.com/watch?v=QDX-1M5Nj7s&list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI) - under the [Alexander Amini channel](https://www.youtube.com/@AAmini).

In addition, I really like the "Introduction to Neural Networks" which is part of [Brilliant's](https://brilliant.org/home/) "CS & Programming" course. 

So, let's get started!

### Installation

Essentially, you need Python, Jupyter Notebook, NumPy installed. These instructions are for Linux, but it should pretty similar for macOS and Windows.

```
$ conda create --name=naked_ai python=3.12
$ conda activate naked_ai                 
(naked_ai) ➜  ~ pip install -r requirements.txt
(naked_ai) ➜  ~ jupyter notebook 
```

Within Jupyter, load "Naked AI.ipynb".



