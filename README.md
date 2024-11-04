# FFXIV Fish Completion Comparison Tool (fish-compare)

A web-based tool for comparing fishing achievements between two players in Final Fantasy XIV. This tool helps fishers track their progress and compare their catches with friends.

## Features

- Compare fishing completion lists between two players
- Support for both tracker code and Carbuncle Plushy export formats
- Shows unique catches for each player and shared completions
- Displays filter differences when using Carbuncle Plushy exports

## Usage

1. Enter names for both players (optional)
2. Paste the completion data for each player:
   - Can use tracker code format
   - Can use Carbuncle Plushy export format
3. Click "Compare" to see the results
4. Results will show:
   - Fish unique to each player
   - Fish caught by both players
   - Filter differences (for Carbuncle Plushy exports)

## Data Sources

This tool uses fish data from:
- icykoneko/saintcoinach for the fish information database

## Local Setup

1. Clone this repository
2. Ensure `fish_info_data.js` is present in the `static/js/` directory. If not, download from [icykoneko](https://raw.githubusercontent.com/icykoneko/ff14-fish-tracker-app/refs/heads/master/js/app/fish_info_data.js). In the event the data is out of date, information on how to update can be found [here](https://github.com/icykoneko/ff14-fish-tracker-app).
3. Open `index.html` in a web browser

## License

This project uses content licensed under different terms:

- **FINAL FANTASY XIV © 2010 - 2024 SQUARE ENIX CO., LTD.**  
  FINAL FANTASY is a registered trademark of Square Enix Holdings Co., Ltd. All FINAL FANTASY XIV-related content is used under the rights of fair use and belongs to Square Enix.

- **ff14-fish-tracker-app (MIT License)**  
  Portions of this project use data from [ff14-fish-tracker-app](https://github.com/icykoneko/ff14-fish-tracker-app) which is licensed under the MIT License. See [LICENSE](https://github.com/icykoneko/ff14-fish-tracker-app/blob/main/LICENSE) for more details.

### Project License

Unless otherwise stated, the rest of the code in this project is licensed under MIT. See [LICENSE](LICENSE) for more details.

## Credits
    
Created by Oliver Westbrooke(Goblin) for the FFXIV community.

Special thanks to:
- icykoneko/saintcoinach for the fish data
- Neon Potato for the lalachievements tracking page 
