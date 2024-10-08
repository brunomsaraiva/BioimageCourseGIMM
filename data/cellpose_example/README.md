# Instructions for cellpose GUI environment creation

## 1. Open the terminal 

## 2. Make the day 1 conda installation the source
```bash
condaon
```
or 
```bash
source ~/miniforge3/bin/activate
```

## 3. Create a new cellpose_gui environment with the yml file

```bash
conda env create -n cellpose_gui --file BioimageCourseGIMM/data/cellpose_example/cellpose_pyqt5.yml
```

-- Wait for installation to finish --


## 4. Activate the environment

```bash
conda activate cellpose_gui
```

## 5. Run cellpose_gui

```bash
cellpose
```

