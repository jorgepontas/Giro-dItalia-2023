# 🚴 Giro d'Italia 2023 - Dataset 🇮🇹

This repository contains a comprehensive dataset for all stages of Giro d'Italia 2023. The dataset provides detailed information on rankings, general classifications, points classifications, and mountain classifications for each stage.

## Data Source

The data has been collected from [procyclingstats.com](https://www.procyclingstats.com/), a renowned platform for cycling results. Procyclingstats.com provides extensive information on various races, including Giro d'Italia.

## Dataset Content

The dataset includes the following information for each stage:

| Field                   | Description                                           |
|-------------------------|-------------------------------------------------------|
| stage_name              | The number of the stage                               |
| stage_date              | The date of the stage                                  |
| stage_length            | Profile and distance of the stage                      |
| stage_rank              | Rankings of the riders                                 |
| stage_rider             | General classification (overall standings)             |
| stage_team              | Points classification (sprinters' standings)           |
| stage_points            | Mountain classification (climbers' standings)          |
| stage_time              | The number of the stage                               |
| GC_rank                 | The date of the stage                                  |
| GC_rider                | General classification (overall standings)             |
| GC_team                 | Points classification (sprinters' standings)           |
| GC_time                 | The number of the stage                               |
| PNT_rank                | The date of the stage                                  |
| PNT_rider               | General classification (overall standings)             |
| PNT_team                | Points classification (sprinters' standings)           |
| PNT_time                | The number of the stage                               |
| PNT_points              | Mountain classification (climbers' standings)          |
| KOM_rank                | The date of the stage                                  |
| KOM_rider               | General classification (overall standings)             |
| KOM_team                | Points classification (sprinters' standings)           |
| KOM_points              | Mountain classification (climbers' standings)          |


## Usage of the Dataset

The dataset can be used for various purposes, including:

- Analysis of race developments and rider performances
- Creation of visualizations and graphics
- Statistical analysis
- Development of prediction models

Please note that the data should be used for non-commercial purposes only, and proper attribution to "procyclingstats.com" should be provided.

## Contribution to the Database

Contributions to enhance the dataset, such as adding missing information or updating results, are welcome. If you find any errors or would like to make additions, please follow the contribution guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## To-Do List 📝

- [ ] some "team" values have integers instead of team names
- [ ] GC, PNT and KOM values are in separate rows
- [ ] Variable names must be adapted
- [ ] Cleaning Script

## License

The dataset is available under the [MIT License](LICENSE). Please adhere to the terms of the license when using or distributing the dataset.
