# dvc_testing



- **Init**

​		`dvc init`

- #### add files

  `dvc add data/**area.csv**`

- **Add remote google drive storage. `1_A--ldAkZ1oQ9uFwsr2ArT22FuQItRl1`**

​		`dvc remote add -d -f storage gdrive://1_A--ldAkZ1oQ9uFwsr2ArT22FuQItRl1`

- **add to git commit**

​		`git commit ./dvc/config -m "Configure remote storage"`

- **push**

​		`dvc push`

