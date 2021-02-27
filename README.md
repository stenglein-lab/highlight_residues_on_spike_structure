# highlight_residues_on_spike_structure

Highlight particular regions and residues on the SARS-CoV-2 spike structure using UCSF chimera

This repository consists of a perl script that will generate Chimera commands that will create an image of the SARS-CoV-2 spike trimer with certain regions and residues colored and highlighted.

Note that you will have to have [UCSF Chimera](https://www.cgl.ucsf.edu/chimera/) installed on your computer (and git and perl).  

### Workflow:

- download this repository to some directory: `git clone https://github.com/stenglein-lab/highlight_residues_on_spike_structure.git`
- change to that directory (`cd highlight_residues_on_spike_structure.git`)
- run this command: `./generate_chimera_commands residues_to_highlight > chimera_commands.cmd`
- open the Chimera software
- open the newly created chimera_commands.cmd file in Chimera.  This should open the model and perform highlighting as specified in the residues_to_highlight.csv file.
- Use File -> Save Image to export the structure as an image file 



### The 6VXX structure

The 6VXX structure was [downloaded from the PDB](https://www.rcsb.org/structure/6VXX) and was described in [this paper](https://pubmed.ncbi.nlm.nih.gov/32155444/).
