# Task-3-and-4

*Task 3: Constructing the LL(1) Table*

*Description:*
In Task 3, we implemented a Python program to construct the LL(1) parsing table for a given Context-Free Grammar (CFG). The CFG can be static (fixed grammar) or dynamic, allowing you to specify any CFG structure, and the program will generate the corresponding LL(1) table.

*Features:*
- The program takes a CFG as input and constructs the LL(1) parsing table.
- It identifies and calculates the 'First' and 'Follow' sets for each non-terminal in the grammar.
- The LL(1) parsing table is generated based on these sets and the production rules of the CFG.
- The program provides a structured LL(1) parsing table as output.

*Usage:*
1. Specify the CFG of interest by modifying the cfg_rules in the Python code.
2. Run the program, and it will generate the LL(1) parsing table.

*Example Output:*
plaintext
LL(1) Parsing Table:
       a      b      $
S  AB     AB     -
A  a      -      ε
B  -      b      ε


*Note:*
- This program is designed for educational purposes and can be used as a starting point for building more complex LL(1) parsing table generators.
- You can customize the cfg_rules array to define your CFG.
- Make sure to have Python installed to run the program.
