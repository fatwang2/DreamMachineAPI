# Dream Machine API

A Python script to generate videos using the Dream Machine API and fetch the latest generated video link.

## Features

- Generate videos via Dream Machine API.
- Asynchronously check for video generation status.
- Output the latest generated video link.

## Prerequisites

- Python 3.7+
- `requests`
- `aiohttp`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/danaigc/DreamMachineAPI.git
    cd DreamMachineAPI
    pip install -r requirements.txt
    ```
   You need to replace the value of the access_token variable to make sure the project works   

   login https://lumalabs.ai/dream-machine/

   Get your access_token here
  ![WechatIMG4170.jpg](https://s2.loli.net/2024/06/13/Cd6gQ4AaZKGNb3r.png)
2. Run Script:
    ```bash
    python main.py
    ```