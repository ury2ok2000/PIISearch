
# PIISearch
SharePoint PII Search script/program
![PII Search](https://github.com/ury2ok2000/PIISearch/blob/2cfa1d25f629d06870417ab2d7979a4db7ebf571/PIISearch1.PNG)

# Requirements

*SharePoint Online (may work or partially work with older versions) (The below use **CDN**, so they will be pulled automatically from the web)*

 - Jquery.js
- DataTables.js
- Jquery Modal.js
- Chosen.js
- W3.css
- Font Awesome.css
* - pure-css-nav.css (https://github.com/adamculpepper/pure-css-navigation) : this is the only one that i could not find in a CDN so it has to be downloaded to a location and referenced.

# Purpose/Use
With the WebPart on a page, a Site Administrator can click on the PII Search button (only visible to them if the WebPart "Target Audience" Advanced setting is used). A Modal Window will pop up and display the results of a PII Search. The Site Administrator can click on the Title field to open the source item in a new window, or click on the Path field to open up the location where the item is stored. Once reviewed, the Site Administrator can click on the Reviewed radio button. Once all reviews are done, Save Results can be clicked. This will save the results of the search (which ones were reviewed), as well as log the results to the PII Dashboard (and the Modal will close).



