# PyANN Toolbox - ultimate solution for neural modeling
PyANN Toolbox is an unified engine for different neural network-based models. It has a consistent interface for a total of 4 ANN models. TGA model is meant to calculate biomass properties based on output data from Thermogravimetric analysis. Vineyard model is trained to forecast energetic value, and associated emission from waste from the cultivation of grapevines. Pellets model predict efficiency of catalytic combustion of different biomass pellets. Raspbery model is comparable to the Vineyard, with the exception that in this case raspberry cultivation waste is used.
![App GUI1](Screenshot_GUI_Toolbox.png?raw=true "PyANN Toolbox - Selection Screen")
The input required by the model, and the modeled output depends on selected model. Results are presented both in graphical and plaintext form. Details about exact unit, as well as explanations of abbreviations can be find under "Nomenclature".
![App GUI2](Screenshot_GUI_Toolbox2.png?raw=true "PyANN Toolbox - Calculation Results")
Additional details about the models and author can be find after clicking "Help/About" button.
![App GUI3](Screenshot_GUI_Toolbox3.png?raw=true "PyANN Toolbox - About Window")

## Files description
* [Release](https://github.com/kar-pos/PyANN_Toolbox/releases) version of App with full GUI (see screenshot above), recommended for most users.
* Release.zip - it is a mirror of above attached release
* Resources - this folder includes raw models (without GUI) of all ANNs used in the Toolbox. The models are optimized to run under C# language. Onnx releases can also be use in any compatible environment.

# Related articles
Postawa, K., Gaze, B., Knutel, B., Kułażyński, M., 2024. Application of triple-branch artificial neural network system for catalytic pellets combustion. Journal of Environmental Management 366, 121678. https://doi.org/10.1016/j.jenvman.2024.121678

Postawa, K., Klimek, K., Maj, G., Kapłan, M., Szczygieł, J., 2024. Advanced dual-artificial neural network system for biomass combustion analysis and emission minimization. Journal of Environmental Management 349, 119543. https://doi.org/10.1016/j.jenvman.2023.119543

Postawa, K., Fałtynowicz, H., Pstrowska, K., Szczygieł, J., Kułażyński, M., 2022. Artificial neural networks to differentiate the composition and pyrolysis kinetics of fresh and long-stored maize. Bioresource Technology 364, 128137. https://doi.org/10.1016/j.biortech.2022.128137
