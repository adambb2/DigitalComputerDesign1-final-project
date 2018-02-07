# DigitalComputerDesign1-final-project
This project required the student (me) to design his/her own 8 bit multiplier which would be approved by the professor and then coded into VHDL and tested again using Quartus II. 

The 8 bit multiplier had to be designed using a limited parts list to recieve full credit. My design approach was to use primarily full-adders and a vectorized multiplexer (the purpose of the vectroized multiplexer was bit shifting). Mathematical operations in binary tend to only involve simple addition/subtraction paired with bit shifting. 

For the 8-bit processor, we were allowed to copy the VHDL code from our book "Fundamentals of Digital Logic with VHDL Design" 3rd edition. The processor in the book was composed of a control circuit, a data bus, four 8 bit storage registers, an add function, a subtract function, a load function, and a move function. The load and move function control data coming into the storage registers. 

Two different codes for the processor were presented in our book. One used tri-state buffers to control the data bus. The other used multiplexing to control the data bus. I chose multiplexing merely because I was more familiar with it.

Adding the 8 bit multiply function to the processor was a very time intensive and thought provoking process. You had to thooughly understand how the processor worked and was coded to make the change without disrupting anything else. A large portion of the processor's control circuit file had to be edited. 

My processor in its current state will not preform the mutliply function because the binary input is failing to be stored in the storage registers. However, I believe the project to be 95% done. There is likely a very small error somewhere in the code that is disrupting the data from entering in the registers, and I believe the processor would work 100% correctly if this issue was resolved.

I hope to correct this project soon and get it in working order when I find the time and find a mentor who has experience with VHDL. I switched my major from Electrical Engineering to Computer Engineering primarily because I enjoyed working with digital circuitry in VHDL. The code for my project can be found in a word document in this repository. Each seperate file is highlighted a different color.

