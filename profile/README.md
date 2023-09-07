# Casava 
  Put your own AI in the driving seat

## Goals
:cyclone: Build scalable AI applications faster. 

:shipit: Lower cost, lower latency, more secure. 

:godmode: Cloud Agnostic


LLM technology brings together many classic fields in computer science, such as compilers,
compression, machine learning and efficient hardware use. Having been, and still being, a
student and fan of all three fields makes this an exceptionally exciting area to think about. There
is a special sort of buzz when you manage to install a GPU to a motherboard, download open
source weights, and have your own stable diffusion producing amazing output free of charge
(minus electricity costs).
To me, the last few months have felt like the beginning of humanity's conversation with AI.
Although prior architectures allowed us to achieve sub-verbal communication with neural
networks, the emergence of GPT-3 turned this verbal, greatly increasing the bandwidth of
AI-human conversation and potential applications.
This is obviously a rapidly evolving field, making any general statements of knowledge difficult,
but I'd like to speak a bit about my views from a technical standpoint, to hopefully initiate some
interesting conversations.
Building a well-designed codebase that backs an application breaks down to two stages;
instructing how the model should produce output, and parsing this same output. This second
stage can be viewed as the exact sort of problem traditional programming-language to
machine-language compilers have been designed to solve efficiently, and much of the theory
involved carries over when thinking about how to write software that compiles natural language
to LLM input, or LLM output to a data structure. I believe that building successful new LLM

software will depend on how well we can build the necessary compilers to translate between
LLMs and our software, and vice versa.
From a business standpoint, it's not clear to us yet where the value will accrue.
Will it be the underlying APIs, or the apps built on top of them?
The best models or the best model serving infrastructure?
I feel that this quote from Ankur Goyal elegantly summarises some of the challenges this
technology will present to us. This nature of interplay between optimizing model output versus
building out more advanced, smarter infrastructure that surrounds the models is one of the core
conundrums I tend to wrestle with when thinking about how to proceed best when working with
LLMs, and may even strike at the heart of the larger questions around LLM alignment.
