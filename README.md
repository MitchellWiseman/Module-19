## Unit 19 Homework: Cryptocurrency Wallet

![An image shows a wallet with bitcoin.](Images/19-4-challenge-image.png)

![Clients address and balance.](Images/Clients_address_and_Balance.png)

![Ganache account balance](Images/Account_balance.png)

![Proof of transaction](Images/Transaction.png)

#Installation Gudie/ Imports

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy


