# 🚴 Giro d'Italia 2023 - Dataset 🇮🇹

This repository contains a comprehensive dataset for all stages of Giro d'Italia 2023. The dataset provides detailed information on rankings, general classifications, points classifications, and mountain classifications for each stage.

## Data Source

The data has been collected from [procyclingstats.com](https://www.procyclingstats.com/), a renowned platform for cycling results. Procyclingstats.com provides extensive information on various races, including Giro d'Italia.

## Dataset Content

The dataset includes the following information for each stage:

### Giro-d'Italia-stages-Info-2023.csv

| Field                   | Description                                           |
|-------------------------|-------------------------------------------------------|
| stage_name              | Name of the stage                                     |
| stage_date              | The date of the stage                                 |
| stage_start             | Start time                                            |
| stage_avg_speed         | Average Speed in km/h                                 |
| stage_distance          | Distance of Stage in km                               |
| stage_profile_score     | Profile Score according to [this calculation](https://www.procyclingstats.com/info/profile-score-explained)            |
| stage_elevation         | Elevation in m                                        |
| stage_avg_temperature   | Average Temperature in                                |
| stage_departure         | location of the stage start                           |
| stage_arrival           | location of the stage finish                          |

### Giro-d'Italia-STG-2023.csv

| Field                   | Description                                           |
|-------------------------|-------------------------------------------------------|
| stage_name              | Name of the stage                                     |
| stage_date              | The date of the stage                                 |
| stage_length            | Distance of the stage                                 |
| stage_rank_name         | stage ranking                                         |
| stage_rank_rider        | Name of rider                                         |
| stage_rank_team         | Name of Rider's Team                                  |
| stage_rank_points       | Points for rank                                       |
| stage_rank_time         | Finish time                                           |

### Giro-d'Italia-GC-2023.csv

| Field                   | Description                                           |
|-------------------------|-------------------------------------------------------|
| stage_name              | Name of the stage                                     |
| stage_date              | The date of the stage                                 |
| stage_length            | Distance of the stage                                 |
| stage_GC_rank           | stage ranking                                         |
| stage_GC_rider          | Name of the rider                                     |
| stage_GC_time           | Finish time                                           |
| stage_rank_team         | Points for rank                                       |


### Giro-d'Italia-PNT-2023.csv

| Field                   | Description                                           |
|-------------------------|-------------------------------------------------------|
| stage_name              | Name of the stage                                     |
| stage_date              | The date of the stage                                 |
| stage_length            | Distance of the stage                                 |
| stage_PNT_rank          | stage ranking                                         |
| stage_PNT_rider         | Name of rider                                         |
| stage_PNT_team          | Name of Rider's Team                                  |
| stage_PNT_points        | Points for rank                                       |

### Giro-d'Italia-KOM-2023.csv

| Field                   | Description                                           |
|-------------------------|-------------------------------------------------------|
| stage_name              | Name of the stage                                     |
| stage_date              | The date of the stage                                 |
| stage_length            | Distance of the stage                                 |
| stage_KOM_rank          | stage ranking                                         |
| stage_KOM_name          | Name of rider                                         |
| stage_KOM_team          | Name of Rider's Team                                  |
| stage_KOM_points        | Points for rank                                       |

### Giro-d'Italia-TEAM-2023.csv

| Field                   | Description                                           |
|-------------------------|-------------------------------------------------------|
| stage_name              | Name of the stage                                     |
| stage_date              | The date of the stage                                 |
| stage_length            | Distance of the stage                                 |
| stage_TEAM_rank         | Team Ranking                                          |
| stage_TEAM_class        | Team Status Class                                     |
| stage_TEAM_time         | Finish time of whole Team                             |
| stage_TEAM_time         | Team Name                                             |


## Usage of the Dataset

The dataset can be used for various purposes, including:

- Analysis of race developments and rider performances
- Creation of visualizations and graphics
- Statistical analysis
- Development of prediction models

Please note that the data should be used for non-commercial purposes only, and proper attribution to "procyclingstats.com" should be provided.

## Contribution to the Database

If you discover any issues or errors in the dataset, please open an issue on the repository's issue tracker. Provide a clear description of the problem, including steps to reproduce if applicable. Screenshots or examples are also helpful in identifying and resolving the issue.

If you would like to contribute changes to the dataset, please follow these steps:

1. Fork the repository and create a new branch for your changes.
2. Make the necessary modifications or additions to the dataset.
3. Ensure that the changes maintain the overall structure and format of the dataset.
4. Test your changes to ensure their accuracy and integrity.
5. Commit your changes with a clear and descriptive commit message.
6. Push your changes to your forked repository.
7. Submit a pull request to the main repository, detailing the changes you have made.

## To-Do List 📝

- [x] split the Dataset in seperate Sets
- [ ] add a Dataset for Youth Rating
- [ ] adapt Variable naming
- [ ] Cleaning Script

## License

The dataset is available under the [MIT License](LICENSE.md). Please adhere to the terms of the license when using or distributing the dataset.
