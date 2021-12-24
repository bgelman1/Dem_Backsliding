# Dem_Backsliding

These R scripts and graphs were developed during an internship for International IDEA, an intergovernmental organization that promotes democracy worldwide. These scripts were written in order to conduct research on the state of democratic backsliding worldwide and to find some potential solutions in the data from countries that have proven democratically resilient. 


Part A: Classification
The "Country Classification" folder contains code (no_recovery.rmd, recovery.rmd) for classifying countries into 4 categories (based on data from 2000 onward):
1. Countries that backslid (declined on certain important democratic characteristics such as Fundamental Rights) and did not recover (backslide.csv).
2. Countries that broke down (became non-democratic regimes such as hybrid or authoritarian regimes) and did not recover (breakdown.csv)
3. Countries that backslid and recovered (backsliding_recovery.csv).
4. Countries that broke down and recovered (breakdown_recovery.csv).

These csvs are used for analysis in the other folders. More detailed descriptions of these categories can be found in Country List.docx.

Part B: Attribute Research

In the attribute_research.Rmd code in the "Attribute Research" folder, I find the most common advancing/declining democratic attributes in each of these groups during their respective periods of decline/recovery. These findings are then graphed in the pdfs.


Part C: Graph Generation

In the final part of the project, I wrote a script, automated_graphs.Rmd, that generates graphs of specific attributes for each of the countries on all 4 lists. 


