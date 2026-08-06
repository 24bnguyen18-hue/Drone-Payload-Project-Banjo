 Drone-Payload-Project-TeamName
MATLAB drone payload capacity and structural design analysis project.
This project analyzes drone arm designs and materials to maximize payload capacity while maintaining structural safety.

Project Files
- DroneDesign_StudentProjectTemplate.mlx: Main MATLAB Live Script
- droneArmMaterials.mat: Material property data
- CADFilesForCode: CAD files for drone arm designs
- main_drone_analysis.mlx: Code for Thrust-to-Weight Analysis and Finite Element Analysis
- Final_Live_Script.pdf: PDF of the Final Live Script
- Maincodedrone_analysis.mlx: Final Live Script with analysis of the code and results.
- Team_Agreement_Banjo.pdf: Team Agreement for Team Banjo
- Thrust-To-Weight and FEA Code: PDF of TWR and FEA results.
  

  
  
How to Run the Project
1. Drone-Payload-Project-Banjo.
2. Open MATLAB--->MATLAB Live Script.
3. Set the MATLAB Current Folder to the main project folder.
4. Make sure the required files are included:
   - Download droneArmMaterials.mat
   - CADFilesForCode/--> Download Design1, Design2,Design3. STL files for the drone arm designs    
5. Open Maincode_drone_analysis.mlx --> copy all the code using copy and paste into MATLAB Live Script.
6. Check that the STL file names in the code match the file names in the CADFilesForCode folder.
7. Run the Live Script from the top using Run All.
8. The code will load the material data, run the thrust-to-weight analysis, import the CAD files, run FEA, and generate result tables and plots.
9. Wait about 1–2 minutes for the simulations to finish.
10. Review the output tables and graphs for:
    - Maximum payload
    - Thrust-to-weight ratio
    - Maximum displacement
    - Maximum von Mises stress
    - Factor of safety
    - FEA status
    - Cost per arm
    - Total cost for four arms.
11. Keep the folder structure the same so MATLAB can find the .mat file and STL files correctly.
12. After the code finishes, MATLAB will display result tables and generate comparison plots for factor of safety, displacement, stress, and cost for all 3 design.

