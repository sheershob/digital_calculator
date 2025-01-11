## Problem Statement: 
Binary calculation is the fundamental operation of digital computers.
It is used in a wide variety of applications, such as arithmetic processors, communication
systems, and cryptography. However, binary addition can be complex and time-consuming to
implement, especially for large numbers.

## Background: 
Binary addition is the addition of two binary numbers. It is performed by
adding the corresponding bits of each number, starting from the least significant bit (LSB)
and working towards the most significant bit (MSB). If the sum of two bits is greater than or
equal to 2, a carry is generated and added to the next bit.

In **subtraction** using 1’s complement, it is done by taking the 1's complement of the
subtrahend and adding it to the minuend. If there is a carry out from the most significant bit,
then it is added to the least significant bit.

In **multiplication**, Multiply each digit of the multiplier by each digit of the multiplicand,
starting from the LSB. Write the product of each multiplication below the multiplicand,
aligned with the corresponding digit of the multiplier. Shift each product down by one place,
depending on the position of the digit in the multiplier. Add the products together, ignoring
any leading zeros. This is called **‘Shift and Add Multiplier’**.

The implementation of these circuits will utilize integrated circuits (ICs), which are small
electronic devices that encapsulate numerous transistors. We have used **XOR gate (IC 7486)**, **AND gate (IC 7408)**, and **OR gate (IC 7432)**.

This is an image of the adder cum subtractor breadboard model

![1701496791579 (1)](https://github.com/user-attachments/assets/ba1c723a-c4da-46d1-bf90-439fe6184a8d)
