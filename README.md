# hsc_baseline

## Google repo

To sync all RCAR3HPC SDK repos, use repo tool:

  ```bash
  mdkir <sdk_directory>
  cd  <sdk_directory>
  repo init -u git@github.com:HSC-ME/hsc_baseline.git --repo-url=https://gerrit-googlesource.lug.ustc.edu.cn/git-repo -m my_manifest.xml -b <tag or branch>  -g common,windows,linux
  repo sync
  repo forall -c git lfs pull
  ```
