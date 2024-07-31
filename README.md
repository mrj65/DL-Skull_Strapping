# DL-Skull_Strapping


This project leverages Pytorch defined U-net in order to perform semantic segmentation on MRI scans.  between brain tissues and the skull , providing a reliable mask overlay for medical analysis.

Features
MRI Scan Visualization: Displays the middle slice of each axis (axial, coronal, sagittal) of MRI scans along with the corresponding brain masks.
Slice Distribution: Presents evenly distributed slices along the z-axis of the MRI scan for comprehensive visualization.
Interactive Mask Overlay: An interactive slider that overlays the brain mask on the MRI scan, allowing for detailed inspection.
Evaluation Metrics: Calculation and display of Dice coefficients and accuracy scores to assess the performance of the segmentation model.
Prediction vs. Ground Truth: Visual comparison of the predicted segmentation masks with the ground truth masks to evaluate model accuracy.
Notebooks
The repository includes a Jupyter notebook skullclean.ipynb which contains:

Data loading and preprocessing steps.
Model training and evaluation processes.
Visualization of results and performance metrics.
# Installation
Clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/DL-Skull_Strapping.git;
cd DL-Skull_Strapping;
pip install -r requirements.txt;
```
# Usage
Load the Data: Ensure your MRI data is in the specified directory or update the paths in the notebook.
Run the Notebook: Execute the cells in skullclean.ipynb to preprocess data, train the model, and visualize the results.
 Use the interactive widgets and plots in the notebook to explore the segmentation results.




# Distributed Slices (Z-axis)

![image](https://github.com/user-attachments/assets/c214557c-4864-4a44-86cf-af033a63b671)
![image](https://github.com/user-attachments/assets/f0b11507-e11a-4287-bd64-7d69f9c20706)
![image](https://github.com/user-attachments/assets/a298ffab-e3af-4089-8aa5-5a7f0a6689a9)
![image](https://github.com/user-attachments/assets/01431365-be60-4c62-9a90-e56aa1487aad)
![image](https://github.com/user-attachments/assets/dabb9cb1-8885-4f97-a4cc-2427485ef4f8)

# Middle Slice masks Visualization 
![image](https://github.com/user-attachments/assets/731a8d17-ef79-47a6-a97f-71169aba7fbe)



# Interactive Mask Overlay
![image](https://github.com/user-attachments/assets/d9ff317f-902d-4a0f-9e30-bc5ae7bb3f6b)


# Evaluation Metrics

![image](https://github.com/user-attachments/assets/63d305d8-4374-4ec8-a7e1-4a824cca8a12)


# Prediction vs. Ground Truth


![image](https://github.com/user-attachments/assets/9e999c4d-23ed-4f72-9183-4d6f26a203ac)
![image](https://github.com/user-attachments/assets/71d3eca4-2097-4014-9870-9c99ce540a5e)
![image](https://github.com/user-attachments/assets/f9e1ecd0-2d99-4fe7-bd38-a0efb2fd566b)

![image](https://github.com/user-attachments/assets/9464cc14-6f3d-485b-8ef3-4bc8ac176f8d)
![image](https://github.com/user-attachments/assets/d87587d0-e816-4b5c-aa9b-68fd25dac631)
![image](https://github.com/user-attachments/assets/52c60a20-5729-441d-81de-12083e669f8b)
![image](https://github.com/user-attachments/assets/93832608-aaf9-4c35-9b3d-aef96d9b5eb0)




License
This project is licensed under the MIT License. See the LICENSE file for details.
