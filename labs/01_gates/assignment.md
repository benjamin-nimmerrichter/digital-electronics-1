# Lab 1: Benjamin Nimmerrichter

### De Morgan's laws

1. Equations of all three versions of logic function f(c,b,a):

Function:

![Logic function](https://github.com/benjamin-nimmerrichter/digital-electronics-1/blob/main/labs/01_gates/equations.png)

Figure:

![Figure](https://github.com/benjamin-nimmerrichter/digital-electronics-1/blob/main/labs/01_gates/NAND%20and%20NOR.png)

2. Listing of VHDL architecture from design file (`design.vhd`) for all three functions. Always use syntax highlighting, meaningful comments, and follow VHDL guidelines:

```vhdl
architecture dataflow of demorgan is
begin
    f_org_o  <= (not(b_i) and a_i) or (not(c_i) and not(b_i));
    f_nand_o <= -- WRITE YOUR CODE HERE
    f_nor_o  <= -- WRITE YOUR CODE HERE
end architecture dataflow;
```

3. Complete table with logic functions' values:

| **c** | **b** |**a** | **f(c,b,a)_ORG** | **f(c,b,a)_NAND** | **f(c,b,a)_NOR** |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 0 | 0 | 0 | 1 | 1 | 1 |
| 0 | 0 | 1 | 1 | 1 | 1 |
| 0 | 1 | 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 | 0 | 0 |
| 1 | 0 | 0 | 0 | 0 | 0 |
| 1 | 0 | 1 | 1 | 1 | 1 |
| 1 | 1 | 0 | 0 | 0 | 0 |
| 1 | 1 | 1 | 0 | 0 | 0 |

### Distributive laws

1. Screenshot with simulated time waveforms. Always display all inputs and outputs (display the inputs at the top of the image, the outputs below them) at the appropriate time scale!
    
Function:

   ![Function](https://github.com/benjamin-nimmerrichter/digital-electronics-1/blob/main/labs/01_gates/distributive_f.png)
   
Figure:

   ![your figure](https://github.com/benjamin-nimmerrichter/digital-electronics-1/blob/main/labs/01_gates/distributive.png)

2. Link to your public EDA Playground example:

   [EDA Playground](https://www.edaplayground.com/x/nP23)


Link to your public EDA Playground example:

https://www.edaplayground.com/x/nP23
