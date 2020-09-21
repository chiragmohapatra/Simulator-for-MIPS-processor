# Simulator-for-MIPS-processor

Takes as input mips code and simulates them using pipelines . Stalls and forwarding have also been implemented in the processor .

Each instruction follows the standard 5 steps:
1. Instruction Fetch
2. Instruction Decode
3. Execution
4. Memory access
5. Write Back

The instructions supported are:
add , sub , sll , srl , blez , bne , beq , bgtz , j , jal , jr

Register names are supported in mips format like $ra , $t0 etc or in general number form like $2 , $24 etc
