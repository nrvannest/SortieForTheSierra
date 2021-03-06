# Creation of Visuals for Moran et. al 2021
This repo houses code used to create visualizations of Sortie-ND model input and modeled output in Moran et al. 2021 "Modeling the forest dynamics of the Sierra Nevada under climate change using SORTIE-ND", Annals of Forest Science.     

### Folder Contents:  
  
**Climate Graph** 
- RCP8.5 GCM climate projections for forest plots BBBPIPO, POFLABMA, and UPLOG .
- R-code for creating a graph of projected changes in maximum July temperature, minimum January temperature, and precipitation over time.
- A .png figure of the graph.

**Map creation**
- Information regarding how initial tree and seedling maps were created.
- The subfolders “data”, “output”, and “src” contain actual tree and seedling data for each forest plot, the map files input into SORTIE for the future projection runs, and R-code for creating the input, respectively.

**Validation Runs** 
- Information for the validation runs comparing model output to observed changes in basal area and density for forest plots BBBPIPO, POFLABMA, and UPLOG. 
- The subfolders “data”, “output”, and “src” contain input data, SORTIE output, and R-code for creating the figure from the paper, respectively.

**Runaway Density** 
- Output from “untuned” model, and R-code for creating the figure depicting it found in the paper supplement.

**SEKI**
- Information for creating graphs of future projected forest composition for forest plots SP, SJP, SJ, and SJM.  
- The subfolders “data”, “output”, and “src” contain the SORTIE output for each plot, .png files of the figures included in the paper, and R-code for creating the paper figures, respectively.  

**Future Climate Scenarios** 
- Information for creating graphs of future projected forest composition for forest plots BBBPIPO, POFLABMA, and UPLOG.  
- The subfolders “data” and “src” contain the SORTIE output for each plot, and R-code for creating the paper figures, respectively.
  
  
  
*For comments or questions regarding the code or data visuals, please contact nikolevannest@gmail.com*
