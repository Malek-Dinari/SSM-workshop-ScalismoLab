# SSM-Workshop-ScalismoLab

This repository contains my work on the **SSM Workshop** with ScalismoLab, focusing on various shape analysis techniques, including deformable forms of scapulae using Gaussian Processes and the implementation of concepts from "Morphable Face Models" (Luethi et al.). 

### Project Structure

- **docs/**  
  Contains the following articles and resources:
  - `TP-SSM-nov24.pdf` – The workshop enoncé.
  - `tutorial-on-PCA.pdf` – A tutorial on Principal Component Analysis (PCA).
  - `morphable face models-luethi.pdf` – An article on morphable face models.

- **datasets-TP/**  
  Contains data files for the workshop exercises, including non-aligned face meshes and landmarks, and aligned faces folder (to use as dataset for our statistical shape models (SSM)).

- **src/**  
  Contains Scala scripts for ScalismoLab experiments, including simplified examples.

- **cr-tp-ssm-malek-sameh-9.docx**  
  A work-in-progress document (compte rendu) detailing the workshop exercises and results.

### How to Use

1. **Install ScalismoLab**  
   ScalismoLab is a powerful library for shape analysis in Scala. To use this repository, you'll need to install ScalismoLab.
   
   - Follow the instructions at the official ScalismoLab [GitHub page](https://github.com/unibas-gravis/scalismo/wiki/scalismoLab) to set it up in your local environment.
   - Ensure you have **Java** and **SBT** installed on your system.

2. **Running the Code**
   - Clone this repository:  
     `git clone https://github.com/Malek-Dinari/SSM-Workshop-ScalismoLab.git`
   - Navigate to the `src` folder and run the Scala scripts using SBT.

3. **Datasets**
   The `datasets-TP/` folder contains the data needed to perform the experiments. The mesh files and landmark data will be used in the workshop exercises.

### Project Goals

- **Rigid Transformation Estimation**  
  Using ScalismoLab, we estimate the best rigid transformation to align 3D meshes based on corresponding landmarks.

- **Morphable Models**  
  I will explore the creation of morphable models for faces and shapes like the scapula, leveraging PCA and Gaussian Processes for deformation.

### Future Work

- **Deformable Scapulae Models**  
  I will implement deformable models of scapulae using Gaussian Processes.
  
- **Article Implementation**  
  I plan to implement the methods discussed in the "morphable face models-luethi.pdf" article, which explores the construction of 3D morphable models for faces.

---

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
