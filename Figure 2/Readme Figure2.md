The instructions in this file will assist in running the code to replicate figure 2 in the modeling study entitled “Dendritic distributions of L-type Ca<sup>2+</sup> and SK<sub>L</sub> channels in spinal motoneurons: A simulation study” by Mohamed H. Mousa and Sherif M. Elbasiouny.

# Steps:
1. Compile the .mod files
2. Run the simulation by running "Auto_Fig2.hoc". This will create the patch model and insert voltage clamp with 4 stages. The default settings are with a pre-pulse of 1000ms, pulse width = 500ms. The panels show the patch voltage at the top, and the other panels show the Ca inward current.
3. Change the duration and amplitude of the voltage clamp to generate all the panels in Figure 2 as shown in the paper.

* <b>Note</b>: Please note that the random variable generator is turned on, thus each simulation will be different. To turn the random variable generator off, please comment the RNG function in the CaDen mod file.

