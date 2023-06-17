# TITLE
design and simulate the logic diagram using verilog

# THEORY
Designing the Circuit:

Identify the logic circuit you want to design, such as an AND gate, OR gate, or a more complex combinational or sequential circuit.
Determine the number and type of inputs and outputs for your circuit.
Write the Verilog code to describe the circuit's behavior. Use modules to define the circuit's components and their interconnections.
Use Verilog operators and built-in functions to model the desired logic operations (e.g., AND, OR, NOT).
Ensure that the Verilog code represents the desired logic behavior accurately.
Simulating the Circuit:

Create a testbench module that instantiates the circuit module(s) and provides input signals while monitoring the output signals.
Define the input signals as reg variables and the output signals as wire variables.
Use the initial or always block in the testbench module to specify the sequence of input values and delays.
Use simulation time advances (#) to introduce delays between input changes and monitor the output changes.
Display the desired signals or variables using $monitor or $display statements.
Compile the Verilog files (circuit module and testbench module) using a Verilog simulator.
Run the simulation and observe the waveform or console output to verify the circuit's behavior matches your expectations.
# LOGIC DIAGRAM
![image](https://github.com/ksagar007/Simulation-project--Digital-Electronics/assets/121165786/6a469f96-d3fb-4ba0-889d-18fc2881a5fd)


# NETLIST DIAGRAM
![image](https://github.com/ksagar007/Simulation-project--Digital-Electronics/assets/121165786/83963b3e-8cfc-4622-94a4-0af3bfb95e7b)



# TIMING DIAGRAM
![image](https://github.com/ksagar007/Simulation-project--Digital-Electronics/assets/121165786/c0bfc493-5633-444d-a9f5-4a9f8f0588b2)


# PROGRAM
```
module www(b1,d1,c1,a1,d,f);
input b1,d1,c1,a1,d;
output f;
wire x,y,z;
and (x,b1,d1);
and (y,c1,b1);
and (z,a1,d);
or (f,x,y,z);
endmodule
```


# REFERENCE
https://github.com/ksagar007/Simulation-project--Digital-Electronics/edit/main/README.md


