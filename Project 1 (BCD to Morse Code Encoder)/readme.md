# Morse Code to Binary Encoder

## Overview  
This project involves designing a combinational logic circuit that converts Morse code for the first ten unique letters of "The Cooper Union" into binary outputs using red LEDs for dots and green LEDs for dashes. The circuit uses four input channels to represent the letters “T,” “H,” “E,” “C,” “O,” “P,” “R,” “U,” “N,” and “I,” with LEDs activated through combinations of AND, OR, and NOT gates based on a simplified truth table.

## Circuit File Download Instructions  
To download and open the circuit file in Logisim-Evolution, follow these steps:

1. **Download the Circuit File:** Click on the Circuit File Link
2. **Save the File:** Save the downloaded .circ file to a location where you can easily access it, like your Desktop or a designated project folder.
3. **Open Logisim-Evolution:** Launch Logisim-Evolution on your computer. If you don't have Logisim-Evolution installed, you can download it from [Logisim-Evolution’s official website](https://github.com/logisim-evolution/logisim-evolution).
4. **Load the Circuit File:** In Logisim-Evolution, go to the top menu, click **File**, and then select **Open**. Navigate to the location where you saved the .circ file and select it to open.

Once opened, you can view, modify, and simulate the circuit as needed.

## Theory

**Truth Table:**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Truth%20Table).png" alt="Truth Table">
</div>

**Karnaugh Maps & Boolean Algebra:**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Karnaugh%20Maps%20%26%20Boolean%20Algebra)%20(1).png" alt="Karnaugh Maps & Boolean Algebra (1)">
</div>

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Karnaugh%20Maps%20%26%20Boolean%20Algebra)%20(2).png" alt="Karnaugh Maps & Boolean Algebra (2)">
</div>

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Karnaugh%20Maps%20%26%20Boolean%20Algebra)%20(3).png" alt="Karnaugh Maps & Boolean Algebra (3)">
</div>

**Final Expressions:**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Final%20Expressions).png" alt="Final Expressions">
</div>

**Gates and Chips:**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Gates%20and%20Chips).png.png" alt="Gates and Chips">
</div>

**NAND Only Derivation:**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(NAND%20Only%20Derivation).png" alt="NAND Only Derivation">
</div>

**Gates and Chips (NAND Only):**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201(Gates%20and%20Chips%20(NAND%20Only)).png" alt="Gates and Chips (NAND Only)">
</div>

## Circuit Diagrams

**Circuit (Sum of Products):** [Logisim File (Sum of Products)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Circuit%20(Sum%20of%20Products)).circ)

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Circuit%20(Sum%20of%20Products)).png" alt="Circuit (Sum of Products)">
</div>

**Circuit (NAND Only):** [Logisim File (NAND Only)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Proejct%201%20(Circuit%20(NAND%20Only)).circ)


<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Circuit%20(NAND%20Only)).png" alt="Circuit (NAND Only)">
</div>

**Bubble Pushing (R1):** [Logisim File (R1)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Push%20(R1)).circ)


<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Pushing%20(R1).png" alt="Bubble Pushing (R1)">
</div>

**Bubble Pushing (R1) (NAND Only):**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Pushing%20(R1)%20(NAND%20Only)).png" alt="Bubble Pushing (R1) (NAND Only)">
</div>

**Bubble Pushing (G1):** [Logisim File (G1)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Push%20(G1)).circ)

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Pushing%20(G1).png" alt="Bubble Pushing (G1)">
</div>

**Bubble Pushing (G1) (NAND Only):**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Pushing%20(G1)%20(NAND%20Only)).png" alt="Bubble Pushing (G1) (NAND Only)">
</div>

## Bill of Materials

**Cost of SOP:**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Cost%20of%20SOP).png" alt="Cost of SOP">
</div>

**Cost of NAND Only:**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Cost%20of%20NAND%20Only).png" alt="Cost of NAND Only">
</div>

**Total Cost:**

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Total%20Cost).png" alt="Total Cost">
</div>

## TinkerCAD

[NAND Only (TinkerCAD Link)](https://www.tinkercad.com/things/5qz1x1EX0hI-nand-only-project-1/editel?returnTo=%2Fdashboard%3Fcollection%3Ddesigns&sharecode=3EE7p7VWXoC4babMxV6vZnEBQwvb64EWLbs2GbcB8XI)

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(TinkerCAD).png" alt="TinkerCAD (NAND Only)">
</div>

## Image of Circuit

<div align="center">
    <img src="https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Image%20of%20Circuit).png" alt="Image of Circuit">
</div>




