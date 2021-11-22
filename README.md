# Audio Process Practice 

This is a repo for recording the reviews about audio processing.
Due to a repo from `stanford-mir`, i was aware of that my knowledge about audio processing needed to review.


## Folder Structure
 ```text
  <audio_process_practice>
   ├── README.md
   ├── audio
   │   └── TechnoDrumMIX.wav
   ├── dockerfile
   ├── notebooks
   │   └── librosa_practice.ipynb
   └── requirements.txt
 ```

## Requirements
See also `requirements.txt`
- pyhton 3.8

## Installation
```bash
$ conda create -n <Your_Env> python=3.8
$ conda activate <Your_Env>
$ pip install -r requirements.txt
``` 
- Note: If you want to export the requirements list
    - Export the list at the conda environment
    ```
    (Your_Env)$
    (Your_Env)$ pip freeze > requirements.txt
    ```

## Resources
- [stanford-mir](https://github.com/bmcfee/stanford-mir): A github repo from a MIR class at Stanford. It contains a series `ipynb` files of audio processing tutorial. 
- [MTG/MIRCourse](https://github.com/MTG/MIRCourse): A github repo from a MIR course at MTG. 

## Others
- How to install the conda env as the kernal in jupyternotebook? 
    - Ref: https://ipython.readthedocs.io/en/stable/install/kernel_install.html
     ```
      $ python -m ipykernel install --user --name audio_process --display-name "audio_process"
     ```
- How to activate the jupyternotebook env?
    ```
    $ jupyter notebook
    ```