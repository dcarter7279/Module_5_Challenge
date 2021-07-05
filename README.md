# Module_5_Challenge
Part 1 is a financial planner for emergencies for memebers of a credit union. Members will be able to visualize their current savings, ti determine if they have enough reserves for an emergency fund.

Part 2 is a financial planner for retirement. The planner will forecast the performance of their retirement portfolio over 30 years. The planner will make an API call via the Alpaca SDK to get historical price data for use in the Monte Carlo Simulations.

Technologies

This project leverages python 3.3.8.5

Installation Guide

Install the following dependencies before running the application
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
%matplotlib inline

Alpaca API:
btc_url = "https://api.alternative.me/v2/ticker/Bitcoin/?convert=USD"
eth_url = "https://api.alternative.me/v2/ticker/Ethereum/?convert=USD"


Contributors
Brought to you by Donell Carter email: dcarter7279@gmail.com



