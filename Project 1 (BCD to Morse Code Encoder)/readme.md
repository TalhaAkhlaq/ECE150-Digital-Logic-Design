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

![Truth Table](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Truth%20Table).png)

**Karnaugh Maps & Boolean Algebra:**

![Karnaugh Maps & Boolean Algebra (1)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Karnaugh%20Maps%20%26%20Boolean%20Algebra)%20(1).png)

![Karnaugh Maps & Boolean Algebra (2)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Karnaugh%20Maps%20%26%20Boolean%20Algebra)%20(2).png)

![Karnaugh Maps & Boolean Algebra (3)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Karnaugh%20Maps%20%26%20Boolean%20Algebra)%20(3).png)

**Final Expressions:**

![Final Expressions](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Final%20Expressions).png)

**Gates and Chips:**

![Gates and Chips](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Gates%20and%20Chips).png.png)

**NAND Only Derivation:**

![NAND Only Derivation](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(NAND%20Only%20Derivation).png)

**Gates and Chips (NAND Only):**

![Gates and Chips (NAND Only)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201(Gates%20and%20Chips%20(NAND%20Only)).png)

## Circuit Diagrams

**Circuit (Sum of Products):**

![Circuit (Sum of Products)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Circuit%20(Sum%20of%20Products)).png)

**Circuit (NAND Only):**

![Circuit (NAND Only)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Circuit%20(NAND%20Only)).png)

**Bubble Pushing (R1):**

![Bubble Pushing (R1)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Pushing%20(R1).png
)

**Bubble Pushing (R1) (NAND Only):**

![Bubble Pushing (R1) (NAND Only)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Pushing%20(R1)%20(NAND%20Only)).png)

**Bubble Pushing (G1):**

![Bubble Pushing (G1)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Pushing%20(G1).png
)

**Bubble Pushing (G1) (NAND Only):**

![Bubble Pushing (G1) (NAND Only)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Bubble%20Pushing%20(G1)%20(NAND%20Only)).png)

## Bill of Materials

**Cost of SOP:**

![Cost of SOP](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Cost%20of%20SOP).png)

**Cost of NAND Only:**

![Cost of NAND Only](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Cost%20of%20NAND%20Only).png)

**Total Cost:**

![Total Cost](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Total%20Cost).png)

## TinkerCAD

[NAND Only (TinkerCAD Link)](https://www.tinkercad.com/things/5qz1x1EX0hI-nand-only-project-1/editel?returnTo=%2Fdashboard%3Fcollection%3Ddesigns&sharecode=3EE7p7VWXoC4babMxV6vZnEBQwvb64EWLbs2GbcB8XI)

![TinkerCAD (NAND Only)](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(TinkerCAD).png)

## Image of Circuit

![Image of Circuit](https://github.com/TalhaAkhlaq/ECE150-Digital-Logic-Design/blob/main/Project%201%20(BCD%20to%20Morse%20Code%20Encoder)/Project%201%20(Image%20of%20Circuit).png)




