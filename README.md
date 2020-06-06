# gostin: Geoscience Open Source Tie-In


Work in Progress. Check-out

- Channel #t20-gostin on Slack (https://swu.ng/slack)
- The notes https://hackmd.io/@prisae/t20-gostin-ideas

Any contribution welcome, just ping us on Slack!

The following are actively available:

| Project | Name (user name) | Timezone |
|---------|------------------|----------|
|GemPy | Miguel [@Miguel de la Varga], Alex [@Alex [UoA, GemPy]] | Europe |
|PyVista | Bane [@Bane [Kitware - PyVista]] | Eastern US |
|SimPEG | Lindsey [@lindsey]; Dom [@Dom [simpeg]] | Western US/Canada |
|Fatiando | Leo [@leouieda] | UK |
|empymod/emg3d | Dieter [@prisae [TU Delft]] | Europe |
|| Martin [@mtb-za] | South Africa |

## Getting started
To create the environment simply run
```bash
conda env create -f environment.yml
```
This will create a new conda environment called `gostin`.

To activate and deactivate the environment run
```bash
conda activate gostin
conda deactivate
```

To completely remove the environment run
```bash
conda remove --name gostin --all
```
