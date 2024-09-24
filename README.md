# Counter-Strike 2 Configuration File

Welcome to the **Counter-Strike 2 Config** repository! This repository contains configuration files used to optimize gameplay in **Counter-Strike 2**. You can use this repo to store, share, and update your personalized config files, key bindings, video settings, and other custom preferences for the game.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## About

Counter-Strike 2 allows players to customize their in-game experience through configuration files (like `oelburk.cfg`). These files store settings such as video options, key binds, mouse sensitivity, and network optimizations. This repository serves as a central location for maintaining and distributing configuration files across different setups.

## Features

- **Pre-configured settings:** Optimal settings for both competitive and casual gameplay.
- **Custom Keybindings:** Modify your key layouts for easier and faster inputs.
- **Network Tweaks:** Latency-related adjustments for smoother online gameplay.
- **Performance Optimization:** Configs designed to maximize FPS (frames per second) without compromising gameplay quality.
- **Auto-exec Configuration:** Automatically apply custom settings every time you launch the game.

## Installation

1. **Clone the repository** or download the configuration file manually:
    ```bash
    git clone https://github.com/your-username/cs2-config.git
    ```
   Alternatively, download the `oelburk.cfg` file from the repository.

2. **Locate your CS2 config folder**:
   - On Windows:
     ```
     C:\Program Files (x86)\Steam\userdata\<Your Steam ID>\730\local\cfg\
     ```
   - On Linux (Proton):
     ```
     ~/.steam/steam/userdata/<Your Steam ID>/730/local/cfg/
     ```
   - On macOS:
     ```
     ~/Library/Application Support/Steam/userdata/<Your Steam ID>/730/local/cfg/
     ```

3. **Move the downloaded `oelburk.cfg` file** into the config folder.

4. **Enable autoexec on game startup:**
   - Launch CS2 and go to settings.
   - Under the “Launch Options” add the following:
     ```
     +exec oelburk.cfg
     ```

## Usage

Once the config file is installed:
1. Open Counter-Strike 2.
2. Your custom settings should be automatically applied.
3. If you need to reload the config during gameplay, open the console (`~` key by default) and type:
   ```
   exec oelburk.cfg
   ```

## Customization

Feel free to modify the config file to suit your preferences. Some common customizations include:

- **Mouse Sensitivity:**
  ```cfg
  sensitivity 2.0
  ```

- **Key Bindings:**
  ```cfg
  bind "F" "+use"
  ```

- **Crosshair Settings:**
  ```cfg
  cl_crosshaircolor "5"
  cl_crosshairsize "3"
  ```

To apply changes, save the file and type `exec oelburk.cfg` in the console or restart the game.

## Contributing

Contributions are welcome! If you have improvements, tweaks, or custom settings you'd like to share, feel free to submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/custom-config`).
3. Commit your changes (`git commit -m 'Add custom settings'`).
4. Push to the branch (`git push origin feature/custom-config`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy fragging in **Counter-Strike 2** with your personalized config! 🎮

--- 
