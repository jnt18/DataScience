### Embedding the mind of a worm

C. Elegans is a transparent roundworm of about 1mm length. It is one of the most famous model organisms and has been studied extensively since the 1960s. 
Research is still very much ongoing with the C. Elegans conference taking place every two years (2023 in Glasgow). 
C. Elegans has a complex behavioural repetoire which includes touch sensitivity, egg laying, feeding, exploration and escape behaviour, all whith only 302 neurons (Chatterjee & Sinha, 2007). 
Not only has it's whole genome been sequenced, C. Elegans was the first animal to have the connectome of its nervous system fully described (White et. al 1987).
The dataset used for this project (https://braingraph.org/cms/c-elegans/) is a digitised version of the origianal description of the connectome by White et. al (1987). 

The aim is to explore the relationship between the function of a neuron and its place within the network. This will be done by embedding each neuron in a 20-dimensional space that preserves the graph structure. 
Classifiers will be trained to predict a neuron's function (sensory, motor or interneuron) and its links to other neurons, using only their position in the embedding space. 
These classifiers will then be used to investigate a subset of synapses whose descriptions in the original dataset were deemed questionable after review due to misprints. 
An expert might be helped by a tool like this to make a descion about what description of the synapse is most likely correct. 
Since there are only about 8000 chemical synapses it is important that everything is described correcly.
