# Python Trading Robot

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Support These Projects](#support-these-projects)

## Overview

Current Version: **0.1.0**

A trading robot written in Python that can run automated strategies using a technical analysis.
The robot is designed to mimic a few common scenarios:

1. Maintaining a portfolio of multiple instruments. The `Portfolio` object will be able
   to calculate common risk metrics related to a portfolio and give real-time feedback
   as you trade.

2. Define an order that can be used to trade a financial instrument. With the `Trade` object,
   you can define simple or even complex orders using Python. These orders will also help similify
   common scenarios like defining both a take profit and stop loss at the same time.

3. A real-time data table that includes both historical and real-time prices as they change. The
   `StockFrame` will make the process of storing your data easy and quick. Additionally, it will be
   setup so that way you can easily select your financial data as it comes in and do further analysis
   if needed.

4. Define and calculate indicators using both historical and real-time prices. The `Indicator` object
   will help you easily define the input of your indicators, calculate them, and then update their values
   as new prices come.

## Setup

**Setup - Local Install:**

If you are planning to make modifications to this project or you would like to access it
before it has been indexed on `PyPi`. I would recommend you either install this project
in `editable` mode or do a `local install`. For those of you, who want to make modifications
to this project. I would recommend you install the library in `editable` mode.

If you want to install the library in `editable` mode, make sure to run the `setup.py`
file, so you can install any dependencies you may need. To run the `setup.py` file,
run the following command in your terminal.

```console
pip install -e .
```

If you don't plan to make any modifications to the project but still want to use it across
your different projects, then do a local install.

```console
pip install .
```

This will install all the dependencies listed in the `setup.py` file. Once done
you can use the library wherever you want.

**Setup - PyPi Install:**

The project can be found at PyPI. To **install** the library,
run the following command from the terminal.

```bash
pip install python-trading-robot
```

**Setup - PyPi Upgrade:**

To **upgrade** the library, run the following command from the terminal.

```bash
pip install --upgrade python-trading-robot
```

## Usage

Update will be made
