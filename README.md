# Vending Machine using Verilog HDL

This project implements a vending machine controller using a single-process Finite State Machine (FSM) in Verilog HDL. The machine accepts ₹5 and ₹10 coins, dispenses a product when the required amount is reached, and returns change when necessary.

## Features
- Single-process FSM design
- Supports ₹5 and ₹10 coin inputs
- Product dispensing logic
- Change return mechanism
- Three operating states (S0, S1, S2)
- Asynchronous reset
- Sequential state and output updates

## States
- S0 : ₹0 balance
- S1 : ₹5 balance
- S2 : ₹10 balance

## Inputs
- 00 : No coin
- 01 : ₹5 coin
- 10 : ₹10 coin

## Outputs
- dispense : Dispenses the product
- change : Returns the remaining balance
