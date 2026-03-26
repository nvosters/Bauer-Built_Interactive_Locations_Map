[README_GitHub_Pages_Setup_with_Clinics.txt](https://github.com/user-attachments/files/26275609/README_GitHub_Pages_Setup_with_Clinics.txt)
GitHub Pages setup with preferred clinics

Files in this package:
- index.html
- Bauer Built Interactive Locations Map.csv
- DMF Per Location-Excel Bauer Built Inc.csv

How to publish:
1. Create or open your GitHub repository.
2. Upload ALL THREE files to the root of the repository.
3. In GitHub, go to Settings > Pages.
4. Under Build and deployment:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
5. Save and wait about 1-2 minutes.
6. Your site will be live at:
   https://YOUR-USERNAME.github.io/REPOSITORY-NAME/

How to update later:
- Replace Bauer Built Interactive Locations Map.csv when location/staff data changes.
- Replace DMF Per Location-Excel Bauer Built Inc.csv when preferred clinic data changes.
- Commit the updated CSV file(s).
- Refresh the website after GitHub Pages republishes.

Important:
- Keep these exact filenames:
  Bauer Built Interactive Locations Map.csv
  DMF Per Location-Excel Bauer Built Inc.csv
- Keep both CSVs and index.html in the same folder.
- Some clinic coordinates are matched to Bauer Built city coordinates when the clinic is in the same city.
- Clinics in other cities are geocoded in the browser once and then cached in localStorage for faster future loads.
