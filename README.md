# MSSE-Jupyter

My completed Jupyter notebooks from "Python for Engineers", part of the MSSE module in my Electrical and Electronic Engineering degree.

## Notebooks

| Notebook | Topic |
| --- | --- |
| Lab A: Python Foundation | Variables, keywords, data types, operators and casting |
| Lab B: Python Foundations | Dictionaries, tuples and classes |
| Lab C: Python Foundations | List comprehensions |
| Lab 1 and 2: Modelling a Full-Wave Rectifier | Functions and conditionals, then using them to model a rectifier and its ripple voltage |
| Lab 3: Modelling a 32-bit ALU | Logic gates, multiplexers and half and full adders, built up to a 32-bit adder and subtraction |

The lab worksheets themselves were written by the module's teaching staff (credited inside each notebook). My contribution is the completed exercises.

## Running them

```bash
python3 -m venv .venv && . .venv/bin/activate
pip install jupyterlab numpy
jupyter lab MSSE/
```

## What I learnt

- Python as an engineering tool rather than just a programming language: modelling a circuit numerically is often quicker than building it.
- Building something complex from small, tested functions: lab 3 starts with single logic gates and ends with a 32-bit adder made from them.
- The ALU lab was my first time building arithmetic from logic gates, which led on to the VHDL processor in [Microprocessor.HDL](https://github.com/sabrina553/Microprocessor.HDL).

## What I would do better

- Fill in the reflection sections properly. Several were left as placeholder text.
- Clear outputs before committing, so diffs show code changes rather than regenerated output.
- Pin package versions in a `requirements.txt` so the notebooks still run years later.
