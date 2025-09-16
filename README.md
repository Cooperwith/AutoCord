# AutoCord

This Python script automates sending messages to a Discord channel using content from `messages.txt`. It mimics human-like behavior with configurable delays, random offsets (1–8s), and automatic splitting of long texts (2000 character limit).

## Installation

1. Clone the repository or download the code as a zip file and extract it to a folder.

2. Navigate to the project directory in your terminal:
   
    ```bash cd /Downloads/AutoCord/```

4. Customize the message content by editing messages.txt.

## Usage

Run the script with:

    python auto.py
    
During execution, you’ll be prompted to specify the duration in seconds between each message and the sleep interval after each cycle.

## Options

The script provides these options:

* --config : Configure user info (user ID, Discord token, channel URL, and channel ID).

    ```bash python auto.py --config```

* --setC : Set the channel for message delivery (provide channel URL and channel ID).

    ```bash python auto.py --setC```

* --help : Show all available commands and usage details.

    ```bash python auto.py --help```
##Contributing

If you encounter bugs or want to suggest features, open an issue on GitHub. Pull requests are welcome. ⭐ the project if you find it useful!
