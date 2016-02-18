Compile and run the code (make sure there is no GEF, or delete it)

	make
	./GEF

Change the network and trips in EquilibriumFlow.cpp

For the Braess network, the output should be:

	Tail 	Head 	: 	Volume 	Cost 	;
	1 	3 	: 	4 	40 	;
	1 	4 	: 	2 	52 	;
	2 	3 	: 	0 	inf 	;
	2 	4 	: 	0 	inf 	;
	3 	1 	: 	0 	inf 	;
	3 	2 	: 	2 	52 	;
	3 	4 	: 	2 	12 	;
	4 	1 	: 	0 	inf 	;
	4 	2 	: 	4 	40 	;
	4 	3 	: 	0 	inf 	;
