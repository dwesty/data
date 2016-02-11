f0 = integrated brightness
f1 = local brightness
f2 = distance to Center of Mass
f3 = moment of inertia around synapsin maxima
f4,f5 are features that I forget what they are.. would need to ask brad.
i would throw them out, I did so in my kohonen code (which you have, its in matlab).



Excitatory presynaptic: ‘Synap’, ‘Synap’, ‘VGlut1’, ‘VGlut1’, ‘VGlut2’,
Excitatory postsynaptic: ‘psd’, ‘glur2’, ‘nmdar1’, ’nr2b’, ’NOS’, ’Synapo’ (but further away than PSD, gluR2, nmdar1 and nr2b)
Inhibitory presynaptic: ‘gad’, ‘VGAT’, ‘PV’,
Inhibitory postsynaptic: ‘Gephyr’, ‘GABAR1’, ‘GABABR’, ’NOS’,
At a very small number of inhibitory: ‘Vglut3’ (presynaptic), ’CR1’(presynaptic),
Other synapses:‘5HT1A’, ‘TH’, ’VACht’,
Not at synapses: ‘tubuli’, ‘DAPI’.


look http://viz.neurodata.io/kristina15/
