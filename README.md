## [Check our Zero To Deep Learning 5 day bootcamp. New dates are out!](https://www.zerotodeeplearning.com)

----


# Global Artificial Intelligence Keras training

Santa Clara, January 17th 2018

### Slides:

- [Introduction](https://www.slideshare.net/FrancescoMosconi/introduction-to-keras-global-artificial-intelligence-conference-santa-clara-2018)
- [Advanced](https://www.slideshare.net/FrancescoMosconi/advanced-keras-global-artificial-intelligence-conference-santa-clara-2018)


## Get started guide

#### Download and Install Miniconda Python 3.6

https://conda.io/miniconda.html

#### Open a terminal and change dir to this folder

```
cd Global_AI_Conf_2018_01_17
```

#### Create the environment

```
conda env create
```

wait for the environment to be created.

#### Activate the environment (Mac/Linux)
```
source activate globalai
```

#### Activate the environment (Windows)
```
activate globalai
```

Check that your prompt changed to

```
(globalai) $
```

#### Launch Jupyter Notebook

```
jupyter notebook
```

#### Open your browser to

```
http://localhost:8888
```

The notebooks are in the `labs` folder



#### Troubleshooting installation
If for some reason you don't see `Houston we are go!`, the simplest solution is to delete the environment and start from scratch again.

To remove the environment:

- close the browser and go back to your terminal
- stop jupyter notebook (CTRL-C)
- deactivate the environment (Mac/Linux):

```
source deactivate
```

- deactivate the environment (Windows 10):

```
deactivate globalai
```

- delete the environment:

```
conda remove -y -n globalai --all
```

- restart from environment creation and make sure that each steps completes till the end.

#### Updating Conda

One thing you can also try is to update your conda executable. This may help if you already had Anaconda installed on your system.

```
conda update conda
```
