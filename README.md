# Heuristics LDM Dataset

Dataset and experiment materials for "Heuristic-Based Incremental Local Domain Model Generation"

## Contents

### CSV Files

The `csv` directory contains:

- **base_heuristics_dataset.csv** - The data and metrics gathered for all participants. Includes model responses, times, clicks, and survey responses.
- **correct_ground_truth_model.csv** - The expected data for a correct LDM.
- **model_error_report.csv** - Generated after parsing the two previous files, contains information about the errors performed by each user.

### Models

The `models` directory contains:

- The base GDM model that all participants started from
- The ground truth correct LDM model
- Individual participant models:
  - Manual models
  - Tags models
  - Retry attempt models

### Materials

The `materials` directory contains:

- **Introduction.pdf** - The introduction text provided during training (complemented by on-site instructor explanations)
- **TeacherApp Task.pdf** - The TeacherApp task requested from users (complemented by on-site instructor explanations)
- **Survey.pdf** - The survey questions provided after completing the experiment
