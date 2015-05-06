This series of examples walks you through the steps to create a 3D plane animation. Originally created for use in Andy Ruina's flight dynamics course.

For the final result, see: "4 Getting fancy> 3 All together > FinalEx.m"

Folders:
1. Figure, axis, and plot objects & changing their properties

2. 3D patch objects - single patches, compound patches, rotating patches, translating patches, adding keyboard controls to patches

3. Camera control - changing camera position, target, orientation, and view angle. Following an airplane 1st person, 3rd person?

4. Stuff to improve viewing:
	- Importing 3d models as patch objects - cessna, A10
	- Adding ground with texture and lightin
	- Adding a horizon to help user keep his bearings
	- Final example incorporating 1,2,3,4

for questions, please email mws262@cornell.edu or come to Upson 247 (preferred) and talk to Matt Sheen.


**** NOTE: I use the "fig.Properties = 'something'" way of changing things. This works on MATLAB 2014b+. If you are using an older version, you will need to use something like set(fig,'Properties','something')
To my knowledge, all other parts are compatible with previous versions.