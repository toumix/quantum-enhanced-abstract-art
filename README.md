# How to make you qubits draw

We introduce a framework for the generation of visual art with quantum computers.
Our approach builds on the recent development of quantum natural language processing (QNLP) defined as a structure-preserving translation from grammar to parameterised quantum circuits.
Going from one-dimensional text to two-dimensional drawing, we define a formal grammar for pictorial composition where the two basic rules are horizontal and vertical juxtaposition.
We then encode each application of a grammatical rule as a piece of quantum circuit, so that composing these pieces together results in a quantum circuit that computes an artistic judgement of the composition.
Finally, we train this quantum artistic judgement, i.e. we optimise the parameters of the quantum circuits, via reinforcement learning from human feedback.

Compared to the now mainstream use of classical deep learning for text-to-image generation (e.g. DALL-E, Midjourney, Stable Difusion, etc.) the advantage of our QNLP approach to the generation of visual art is two-fold: expressivity and explainability.
First, we show that quantum computers can in theory be used to express artistic judgements beyond what is possible classically.
Then, we argue that the compositionality of our approach allows to move away from black-box models and gets us closer to explainable artificial intelligence.
Our framework builds upon solid mathematical foundations in terms of category theory and the intuitive concept of string diagram, it also comes with an open source implementation using the DisCoPy library.
