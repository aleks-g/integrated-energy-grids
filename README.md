# Integrated Energy Grids

This repository includes relevant tutorials and solutions to problems proposed in the MSc course [Integrated Energy Grids](https://kurser.dtu.dk/course/2025-2026/46770?menulanguage=en) at DTU. This course and base repository was initially created by [Marta Victoria](https://martavictoria.org) for the Spring semester 2025. This repository and the course website was update for the Spring 2026 edition taught by [Aleksander Grochowicz](https://github.com/aleks-g) and [Parisa Rahdan](https://github.com/ParisRa).

If you detect any errors, please [open an issue](https://github.com/aleks-g/integrated-energy-grids/issues) and we will try to fix it. Ideally, you can also pull request the fix. 

## Usage

You can find the solutions of the problems [here](https://aleks-g.github.io/integrated-energy-grids/intro.html) (or following the web address displayed on the top right corner of this repository) after they have been presented at the lectures.

Following the link, you will also find instructions on how to install Python, learn the packages used to solve the problems and read the solutions in [Jupyter notebooks](https://jupyter.org/).

If you don't want to install anything on your computer, you will also find instructions on how to use [Google colab](https://colab.google/) to run the scripts online.


## Building the html version of this repository
If you want to build/modify the html version of this repository:

1. Clone this repository
> git clone https://github.com/aleks-g/integrated-energy-grids
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. Run `jupyter-book clean integrated-energy-grids/` to remove any existing builds
4. Run `jupyter-book build integrated-energy-grids/`



## Contributing

We welcome and recognize all contributions. If you'd like to contribute to the project by providing feedback, identifying a bug or working on a new feature, check out the [contributing guide](CONTRIBUTING.md) to get started.

You can see a list of current contributors in the [contributors tab]([https://github.com/martavp/integrated-energy-grids/graphs/contributors](https://github.com/aleks-g/integrated-energy-grids/graphs/contributors)).

## Acknowledgements

This template was inspired and made possible by the [Cookiecutter project](https://github.com/cookiecutter/cookiecutter) and the [Jupyter Book project](https://github.com/executablebooks/jupyter-book).
