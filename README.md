# GA_from_skyline_export
Calculation of percent glycation from the skyline peak areas 

The following columns are exported from the skyline document
1. Protein
2. Peptide
3. Peptide modified sequence
4. Replicates
5. Total area ratio to global standards
6. Total fragment area

procedure to use the code:

Copy the path of the file onto "skylineout=pd.read_csv(r'File path\.......\filename.csv')" eg. skylineout=pd.read_csv(r'C:\Users\Bharath\Dropbox\PC\Desktop\BKR_DATA\221125_BKR_plasma_GA_stability\gAlb_p2_t10_BKR_407GDM_boxallinone.csv')

To save the final result provide the file path for the final report as follows:
Final_report.to_excel(r'File path\.......\filename.xlsx'). eg. Final_report.to_excel(r'C:\Users\Bharath\Dropbox\PC\Desktop\BKR_DATA\221125_BKR_plasma_GA_stability\GA_407GDM_boxallinone.xlsx')



This code calculates the %gALB_kQTALVELVK,	%gALB_AEFAEVSkLVTDLTK,	%gALB_total, and	% Miscleaved
