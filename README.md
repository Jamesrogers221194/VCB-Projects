A collection of logic circuits I've built in VCB. There are not many right now but I plan to make a lot more :D. I am trying to make useful modules for people to use so feel free to use them in your projects!

# RGS-C00
An 8-bit computer with very limited functionality, but very compact. The demo project in the repo has the CPU host a game of Simon says. Give it a go! :) (for the demo, make sure to run it at about 600TPS)  
  
Features:  
  -6 general purpose registers  
  -an ALU that can add/subtract/N/Z/C/P  
  -1 input port  
  -1 output port  
  -256 lines of 8-bit program memory  
  -9 operations: add, subtract, compare, load, move, input, output, jump, conditional jump  

# RGS-C10
My second CPU, this time 12-bit. I added a more feature packed ALU with 8 operations, the ability to load/store values to Vmem from the registers, an extra output port, and a return address register to allow for easier subroutines. For the demo I coded up a pong game, play at ~100K tps and see what score you can get!
  
Features:  
  -10 general purpose registers  
  -An ALU that can add/subtract/shift left/shift right/or/and/transfer/not/N/Z/C/P  
  -1 input port  
  -2 output port  
  -4096 lines of 12-bit program/variable memory  
  -17 operations: add, subtract, or, and, not, transfer, shift left, shift right, load constant, move, jump, jump if, load return address, return, load from Vmem, store to Vmem, end program
