Let's build computers

A. Introduction

Like a Jedi has to build his own light-sword, a computer scientist needs to build his own computer system.

As a former instructor in Computer Science and Structured Computer Organisation I always wanted to create a large (guided) practicum where students would build there own computer. But there are already many handbooks using this approach. So I decided to write something more generic. 
First of all it will be a series of articles instead of a book. This has become a hobby project so I work on parts of this text whenever I like, and turn to a different part as my interest changes.
Second I will limit theory to a bare minimum, but give references to existing texts for more information.
Third I will incorperate some other hobbies of mine, like retro computing. As we can build a computer, why not one of those faboulous 8-bit machines of the 80's. So we will not build one computer but many. And I hope the reader will add his own projects.
Fourth, I will use an abstract approach, so that something build for one system will also work on another system.
And at last, the techniques presented here can be used to build your own system. And this can be done in your head, on paper, in a simulator, as an emulator or in real hardware (preferable in a FPGA).  

B. What is a computer ?

1. A computer is a 'mechanism' for executing calculations.

experiment 1: a very simpel calculator

- Take a measuring can and fill it with 4 units of water. 
- Pour the water in an other recipient.
- Put 2 units of water in the measuring can.
- Put the water from the other recipient back in the measuring can.
- Read the number of units in the measuring can. It reads 6 units.

We made a very simple adder. 

We used the property that the volume of water can be added.
Our computer is said to be working 'by analogie' of some physical phenomenom.
Hence we call this computer an 'analogue computer'.
I chose watervolume as an example, but there are lot's of other physical analogies that can be used.

properties of analogue computers:
- values can be any real value.
- precision is exact but limited by the used measuring instruments.

experiment 2: another very simple computer

- Take 4 marbles (obviously you have to count them) and put them in a box.
- Take 2 marbles and put them in another box.
- Put the content of the two boxes in a third box.
- Count the number of marbles in the third box. You have 6 of them.

Again we made a very simple adder.

Here we didn't use the analogy of a physical phenomenom, we just counted things.
- For the first box we counted 4 items. It represent the number '4'.
- The second box represents the number '2'. (since we counted 2 items)
- The third box represents the number '6'. (since we counted 6 items)

Since this computer is based on the property of counting things to get numbers,
we call it numerical or digital (since a number is represented by a series of digits).

a more interesting example of a digital computer is the abacus.

Properties of digital computers:
- values can only be cardinal numbers (but this can be extended by specific agreements, combining numbers or specific notations e.g. saying that 1 marble is 1/100 of the desired unit)
- precision is limited to 1 item (but can be extended - in the example of 1 marble equal 1/100 unit the precision is 1/100. But it will always be discrete)

In this series we will only consider digital computers

2. A computer is automated

The above examples are in fact techniques to calculate.
These techniques can be described as algorithms (an alghoritm is an imperative series of instructions). 
A computer is a machine that execute those algoritms (an algoritm that is executed is called a process). Humans can provide the input and obtain the output (in a digital computer in the form of digits), but should be freed of executing the process.
Processing machines (processors) can be build using mechanical, hydraulical, pneumatical or electrical principples. Future techniques may use light. Practical computers use electricity. that's why a simple introduction to electricity will be given in the next chapter.

3. A computer is an general machine

A general computer is not limited to one process. The computer should be able to be fed with user made algorithms.
In a digital computer this is done by feeding the computer with a series of digits called 'programs'.

A general machine is a programmable machine.
  


 
