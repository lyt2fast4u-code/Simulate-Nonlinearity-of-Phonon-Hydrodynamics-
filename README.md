# Simulate Nonlinearity of Phonon Hydrodynamics
A little work based on paper "Effects of nonlinearity on phono hydrodynamics in graphite", huge thanks to Wanying Liu and Yangyu Guo for providing the mathematical foundation of nonlinearity in phonon hydrodynamics. 
The entire project uses Fortran rather than Python in order to ensure optimal compatibility with the ShengBTE project. The current code has passed gray-body testing and can correctly simulate the Poiseuille flow phenomenon. However, the compatibility module for interfacing with ShengBTE calculation data is still under testing. If everything goes smoothly, it will be uploaded to the repository soon.

Because the paper on which the simulation is based is one-dimensional, the scope of what can currently be simulated is extremely limited, with Poiseuille flow being one of the few cases. Extending the model to two dimensions would require substantial mathematical work.

At present, this project is mostly just for fun. It only makes it possible to observe certain nonlinear phenomena through code-based simulation. If more detailed simulations of phonon-fluid behavior are desired, the model would need to be extended to two dimensions.

Since my experience with Fortran is very limited, a considerable portion of the work was completed with the help of vibe coding. Thank you for your understanding.
