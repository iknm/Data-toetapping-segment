# Data-toetapping-segment
he data in each segment is after low-pass filtering. The file name with f12 is processed with cut-off frequency as 12Hz and the file name does not have f12 is with cut-off frequency as 2.5Hz.

 

Each CSV file includes one segment from lift toe start to the next left toe start.

 

The file name is “group” + “cut-off frequency” + “left/right side” + “task #” + “subject name” + “seg #”.

 

The group can be “nonPD”, “PDgood” and “PD_bad_analyzable”. “PD_bad_analyzable” means there is a patten in the data but bad followed; segmentation still works for some cycles.

 

Loading each CSV file, you will see a 2D array. Each column in order is heel_x_filter, heel_y_filter; heel_z_filter; toe_x_filter; toe_y_filter; toe_z_filter; heel_std; toe_std. 
