# SpaceX Falcon 9 Capstone — Results Bundle

This package is based on `spacex_capstone_outputs.zip` supplied by the user.

## Included
- `data/`: staged datasets, web-scraped launch-history data, cleaned data, dashboard and geospatial data
- `outputs/`: SQLite database, SQL result CSVs, EDA charts, Folium map HTML, model comparison, confusion matrix, summary JSON
- `SpaceX_Capstone_Completed_Report.pdf`: report based on the supplied measured outputs
- `SpaceX_Capstone_Completed_Presentation.pdf`: 12-slide presentation based on the supplied measured outputs

## Key results
- Main dataset: 90 rows
- Labelled landing outcomes: 69 (60 successful, 9 unsuccessful)
- Best model by supplied held-out F1: K-Nearest Neighbors (F1 0.923, accuracy 0.857)
- Confusion matrix: [[0, 2], [0, 12]] for actual classes [0,1] by predicted classes [0,1]. The classifier predicted all test samples as successful and did not correctly identify any unsuccessful landing.

## Important gaps before final submission
- The uploaded archive does not contain a Dash app source file or a screenshot of the running dashboard.
- It does not contain API request logs or evidence screenshots for the SpaceX API collection lab.
- The Folium HTML map is included, but no screenshot of the rendered map is included.
- The report and slides accurately distinguish available artifacts from missing evidence. Do not claim the missing steps were demonstrated.
- Verify the source repository and course-specific rubric requirements before submission.

## Provenance
The uploaded `outputs/summary.json` names `https://github.com/Ahmed-Nezar/IBM-Data-Science-Capstone-SpaceX` as the dataset source repository.
