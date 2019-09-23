# hsc_baseline

## Google repo

To sync all RCAR3HPC SDK repos, use repo tool:

  ```bash
  mdkir <sdk_directory>
  cd  <sdk_directory>
  repo init -u git@github.com:HSC-ME/hsc_baseline.git -b <tag or branch> -m sdk.xml -g common,windows,linux
  repo sync
  repo forall -c git lfs pull
  ```
