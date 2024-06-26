# GoogleTimelineMapper
Map and Browse Google Timeline Semantic Location History data.

This single-file web app allows you to load Google Timeline data exported via Google Takeout and map the locations.  You can select individual locations and export all selected locations to a CSV file.
Useful for browsing location history and capturing the items of interest for later.

[Open the app](https://ryangriggs.github.io/GoogleTimelineMapper/index.html) (hosted on Github Pages)

(No data is uploaded to a server: everything runs in the local browser.)

# Usage
 - Export data from your [Google Timeline](https://timeline.google.com) using [Google Takeout](https://takeout.google.com)
 - Extract the Semantic Location History JSON files from the export.
 - Open the index.html file in a browser.
 - Click the Import button and select one or more of the Semantic Location History JSON files
 - They will be mapped on the screen.
 - Click any pin to find that item in the list.
 - Click any list item to find that pin on the map
 - Click the headers to sort by address, date, or duration
 - Check the checkbox to select the desired items for export
 - Enter Notes/Description in the text box.
 - Click the Export Selected Locations button to export all selected locations to a CSV, KML, or GPX format.

# Features
 - Privacy: no data is uploaded to a server: everything is processed only in the local browser
 - Easily visualize and browse your Google Timeline History
 - Export selected Timeline locations to CSV file for records
 - Show sequential travel by linking items with lines in order they were visited
 - Export to multiple formats (CSV, KML, GPX)

# Thanks
 - Thanks to [MueJosh](https://github.com/MueJosh) for adding sequential tracing and additional export formats

If you find this helpful, please consider a [donation](https://www.paypal.com/donate/?hosted_button_id=ME6HPDWXYTVUW).  Thank you!
