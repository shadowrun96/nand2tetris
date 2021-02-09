# ALU notes

I browsed xtcom's solution because I was hitting a particular wall with circuit switching.
The problem was that I was looking how to create separate circuits for every function and then select their execution via Muxes.
The solution in different, and that is due to the particular nature of hardware description languages in general I guess.
All functions are built as circuits, so signals pass through them whether they have been selected or not.
The out signal is then determined by the Mux, and not before. 


