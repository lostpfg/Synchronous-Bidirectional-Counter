# Synchronous-Bidirectional-Counter
A synchronous 4-bit Up/Down Counter using D flip-flops with asynchronous Reset, Enable Count and Parallel load signals. 
Counter is consisted by 4 D flip-flops. A The flip-flop design has a negative triggered asynchronous clear signal. 

## Main Features
1. Clock output.
2. Positive edge Enable Signal.
3. Negative edge Reset Signal.
4. Asychronous positive edge parallel load function.
5. Bidirectional count based on Mode Signal.

## Top level design 
                 _ _ _ _ _ _ _ _                                           
     (Inputs)   |               |  (Output)                   
      clock  -> |               |       
      ~reset -> |               | -> Dout[0:3]
     enable  -> |               |
    Up/~Down -> |               |
    Din[0:3] -> | Counter 4-bit |                  
                 _ _ _ _ _ _ _ _                      
                                                                     
