# Pushchair-Review-Theme-Reporting
A prototype flexdahsboard to report thematic analysis (from Nvivo) of popular pushchair on Amazon

Aim of the project is to analyse the qual data thematically in Nvivo, and then export the results into a Flexdashboard in built in R.

Data was downloaded from Amazon (https://www.amazon.co.uk/Hauck-Pushchair-Foldable-Position-Adjustable/product-reviews/B01LRUWAKY/ref=cm_cr_dp_d_show_all_btm?ie=UTF8&reviewerType=all_reviews) to a .xlsx file. It gives us the first 100 reviews of the pushchair whihc can be viewed in Excel. 

This data can be read directly into NVivo for thematic analysis. Once thematic analysis is complete, a user can create two outputs that can be read into R for prep into a Flexdashboard:
1) An export of their codebook, saved as an .xlsx file;
2) a 'Framework Matrix' with participants on rows and themes (including all sub-themes) in columns. First run 'auto summarise' in the framework matrix to populate it with the text that was coded in each theme. This can then be exported by right-clicking on the top left of the matrix and exporting it to an .xlsx.

Bit of manual work to set up some files in Excel (visNodes and visEdges) and some work may have to be done on the Framework Matrix exported from Nvivo, as there a lots of bugs in NVivo. 

From there thematic analysis can be presented in Flexdashboard following the code within the .rmd file and using the supporting files. 
