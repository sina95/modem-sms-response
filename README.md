# SMS Handler Demo

## Overview

This Python script is a demo application that handles incoming SMS messages using a GSM modem. It listens for incoming SMS messages, displays the sender's number and message content, and replies with a confirmation message.

## Features

- **Receive SMS:** Listens for incoming SMS messages.
- **Display Message:** Shows the sender's number, message content, and timestamp.
- **Reply to SMS:** Sends a reply message saying "SMS received."

## Requirements

- Python 3.x
- `gsmmodem` library (for GSM modem interaction)

## Configuration

1. **Port and Baud Rate:**
   - `PORT`: Set to the serial port your GSM modem is connected to (e.g., '0001').
   - `BAUDRATE`: The baud rate for the serial connection (default is 115200).

2. **SIM Card PIN:**
   - `PIN`: Set to your SIM card PIN if applicable (default is `None`).

## Installation

1. **Install Dependencies:**
   Ensure you have the required Python library by installing `gsmmodem`:
   ```bash
   pip install gsmmodem
