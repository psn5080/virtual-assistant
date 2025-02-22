# VirtualAssistant.py

A Smart Virtual Assistant with two modes: Voice and Text. The Voice mode allows users to run commands directly with speech recognition, while the Text mode allows users to use the assistant through text commands via a command line interface.

The project is open for community suggestions and edits, so feel free to do a pull request!

## Features

- **Voice Mode**: Interact with the assistant using voice commands.
- **Text Mode**: Interact with the assistant using text commands.
- **Web Integration**: Open and search websites like Google, YouTube, Spotify, and more.
- **Games**: Play Connect 4.
- **Device Control**: Lock, shutdown, or restart your device.
- **Cryptocurrency Prices**: Get the latest prices for Bitcoin and Ethereum.
- **Fun Commands**: Get jokes and riddles.
- **Settings**: Customize the assistant's settings.

## List of Commands

1. **Play Music**: `play [song name] on [youtube|spotify|gaana]`
2. **Location Search**: `where is [location]`
3. **Open Websites**: `open [google|twitter|instagram|facebook|youtube]`
4. **Play Connect 4**: `play connect 4`
5. **Send Mail**: `send mail` (WIP Command)
6. **Get Time**: `the time`
7. **Cryptocurrency Prices**: `[bitcoin|ethereum] price`
8. **Fun Commands**: `[joke|riddle]`
9. **Device Control**: `[lock|shutdown|restart] device`
10. **Settings**: `settings`

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/RandomPerson06/VirtualAssistant.py.git
    cd VirtualAssistant.py
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Configure the settings in `settings.py`:
    ```python
    browser = 'path_to_browser'
    username = 'your_email'
    password = 'your_password'
    currency = 'usd'
    voice_setting = 0  # 0 for male, 1 for female
    assistantname = 'Assistant'
    audio = True
    assistant_online = True
    ```

## Usage

### Voice Mode

Run the `VoiceAssistant.py` script to start the assistant in voice mode:
```sh
python VoiceAssistant.py
```

Text Mode
Run the TextAssistant.py script to start the assistant in text mode:
```sh
python TextAssistant.py
```

### Contributing
We welcome contributions! Please open an issue or submit a pull request with your improvements.

### License
This project is licensed under the MIT License. See the LICENSE file for details.