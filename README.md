# V2X-ndnSIM

This project attempts to simulate an ad-hoc communication environment between vehicles and infrastructure. The SUMO traffic simulator and ns-3 based ndnSIM simulator cannot be linked to simulate in real time so SUMO simulations must first be run and the generated trace files loaded into the ndnSIM simulation files. To download and compile ndnSIM refer to ndnSIM.net. The scenarios included are stored in the /ns-3/src/ndnSIM/examples folder and run using ./waf, with paths to the trace files given as command line arguments.
