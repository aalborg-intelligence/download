## Downloading a file with shinyline

The download button works correctly in Firefox on my machine, but not in Chrome (and not in Edge on a colleauges machine).
To reproduce the issue you can clone the repository and run the app the following way:

1. Make sure you have the shinylive package installed. If not, you can install it using:
   ```R
   install.packages("shinylive")
   ```
   
2. Activate the shinylive extension in Quarto, by running this command in the terminal (in your project directory):
   ```bash
   quarto add quarto-ext/shinylive
   ```
   
3. Render the Quarto document `download.qmd`.

4. Open the rendered document in your browser and click the download button (should work in Firefox but not in Chrome etc.).
