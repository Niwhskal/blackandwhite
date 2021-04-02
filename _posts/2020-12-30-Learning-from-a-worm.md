---
title: "Towards Extreme Generalization"
show_date: True
date: "10th March 2021"
excerpt: "The neuronal system of the Nematode, Caenorhabditis Elegans"
---
In "On the Measure of intelligence"[1][^1], F. Chollet provides a definition of Intelligence that serves as the north star for future ML research. He describes intelligence as that which enables wild generalization across tasks, optimized specifically for flexibility and adaptability. 

Unfortunately trends in ML research today are a far cry from his description, leveraging unlimited priors to showcase superior performance at specific tasks, depicting the intelligence of the person who was involved in creating it rather than that of the algorithm. All of the state of art in ML research today showcases the crystallized output of intelligencebut not the process of intelligence itself. 

This brings us to the question of what the way forward is? Are neural networks the key to superior generalization or do we need a new framework altogether?

In my opinion, neural networks, atleast in the framework of: training, BP and optimization are quite useless to achieve the state of superior generalization.

An agent which serves to generalize across multiple tasks needs to have a sense of uncertainty about it's priors. It must have the ability to reduce/increase that uncertainty on it's own, by a process which is independent of data. In order to escape from the bubble that unlimited training data provides, an agent needs to cut off it's reliance with data. 

The brain is a master of dealing with uncertainty. If we draw a superficial comparison with neural networks and the brain, you can see that they're both connected roughly the same. The complexity of their connections obscure both their dynamics (not for the lack of trying though [2][^2],[3][^3],[4][^4],[5][^5]), so we don't know how an input gets transformed as it passes through several layers. The brain, however, doesn't work on back propagation [6][^6],[7][^7] and has a control over it's experiences. It can assign relevance/determine validity because everything is uncertain, it is too fluid of an entity. Neural networks share the property of intractable dynamics with the brain but, they are forced to behave in a pre-determined way by the means of labels. Hard-coded labels enforce unknown constraints on the network, forcing it to either learn shortcut tricks(textures in images, patterns, etc.). If a network is trained solely to detect pictures of faces, it's behavior is morphed so as to "see" faces, whether it be in patterns, shortcut hacks or some other feature. So when it makes a mistake, it technically isn't a mistake from the perspective of the neural network, but a mismatch in perspective between what is true and what isn't. And this has to do with assigning labels. We need to rethink the way a neural network leans. A more flexible way. One which adapts constantly based on new data or ingrained priors(designed before training).

[^1]: Here's a test footnote [](http://www.google.com)




