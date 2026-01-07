# pcb_designs_2026
Repository for SPEAR 2026 PCB designs. KiCad is used as the PCB design software.
## Setup Instructions
Before opening any KiCad projects in this repository, the SPEAR_PCB_2026_DIR environment variable must be set as follows:

1. In the top toolbar, click "Preferences" then click "Configure Paths..." in the dropdown menu that appears as shown in figure 1.

<img width="214" height="130" alt="image" src="https://github.com/user-attachments/assets/fa395654-5228-43ba-8f75-850e26363b91" />

**Figure 1**: Configuring KiCad file paths.

2. In the window that shows up, press the "+" button at the bottom left as shown in figure 2. This adds a new empty environment variable at the bottom of the environment variables list.

<img width="311" height="142" alt="image" src="https://github.com/user-attachments/assets/d1a6fa25-0af1-4eb2-97d3-4cf9e0ead4de" />

**Figure 2**: Adding a new environment variable.

3. Edit the name of the environment variable to be "SPEAR_PCB_2026_DIR" and edit the path to be the pcb_designs_2026 git repository. Setting the path can be done by clicking the folder button to the right of the path entry box with the entry box selected. The end result must look like figure 3.

<img width="310" height="141" alt="image" src="https://github.com/user-attachments/assets/aa8ad61b-951e-4f06-9220-a563b9d97a4e" />

**Figure 3**: Creating the SPEAR_PCB_2026_DIR environment variable.

4. Next, press "OK" to finalize the changes. Now your KiCad is ready to open projects in the repository.
