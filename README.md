# UFC Decision Win Strategy Analysis

This project analyzes UFC fight data to derive a strategy for maximizing the chances of winning a fight by decision. The analysis focuses on decision wins where fighters won by unanimous, split, or majority decisions. The primary goal is to calculate average performance metrics for successful decision wins and provide insights on how to increase the likelihood of winning by decision.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [Contact](#contact)

## Project Overview
In mixed martial arts (MMA), especially UFC, many fights go the distance and are decided by judges. This project explores historical fight data to determine the average metrics required to win a fight by decision. It provides a statistical breakdown of key performance indicators like:
- Significant strikes landed per minute
- Number of takedowns attempted and landed
- Control time during the fight (in minutes and seconds)

## Dataset
The data used for this analysis is based on UFC fight statistics. The dataset (`fighter_stat.csv`) includes detailed information such as:
- Fight results
- Methods of victory (e.g., Unanimous Decision, Split Decision)
- Significant strikes, takedowns, control time, and other fight statistics.

### Key Columns
- `result`: Indicates whether the fighter won (`1`) or lost.
- `method`: The method of victory, including `U-DEC`, `S-DEC`, and `M-DEC` for decision wins.
- `sig_strikes_landed_per_min`: Significant strikes landed per minute.
- `takedowns_attempts`: Number of takedown attempts.
- `takedowns_landed`: Number of successful takedowns.
- `control`: Total control time (in seconds).

## Methodology
1. **Filtering Data**: The analysis focuses on fights where the result was a decision win. We filtered fights that ended in a decision (`U-DEC`, `S-DEC`, `M-DEC`).
2. **Calculating Metrics**: We calculated key performance metrics, including:
   - Average significant strikes landed per minute
   - Average takedowns attempted and landed
   - Average control time (converted from seconds to minutes and seconds)
3. **Strategy Output**: The averages are used to provide an actionable strategy for fighters aiming to win by decision.

## Usage
### Running the Code
1. Clone the repository or download the project files.
2. Run jupyter notebook localy
3. ensure you have dataframes file with necessary csv files

## Results
This analysis provides actionable insights for UFC fighters looking to improve their chances of winning by decision. By understanding and targeting the average performance metrics from successful decision fights, fighters can adjust their strategy to increase their chances of getting the win on the judges' scorecards.

## Dependencies
This project requires the following Python libraries:

- pandas
- numpy

## Contact
If you have any questions or feedback, feel free to reach out:

Email: daniyar.serik.me@gmail.com

