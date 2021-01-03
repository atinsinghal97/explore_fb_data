# explore_fb_data
-Facebook Data in Time and Space project for Ethi-

Simple visualization of User Facebook Data using D3.js:
  - Rotating globe and heatmap displaying user's "your places" and daily facebook activity
  
Data displayed: 

    - User's : Facebook "places"
    
    - Daily interactions on Facebook ( eg: posts, comments, messages )
    
Visualisation Code and Data Preprocessing code in their respective folder.

<img src="/media/viz.png" width="500" height="300">


Video : https://youtu.be/pCmPKeypuYg
     
# Installation and Dependencies

Dependencies:
 - D3.js (v3) 
 - topojson 
 - moment.js 
 - Jquery  
 - Bootsrap 
 - Jquery Calendar Heatmap (https://github.com/SeBassTian23/CalendarHeatmap)
 
Import:


      <script src="https://d3js.org/d3.v3.min.js" charset="utf-8"> </script>
      <script src="https://d3js.org/topojson.v3.min.js"></script>     
      <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.24.0/moment.min.js"></script>
      <script src="jquery.CalendarHeatmap.min.js"></script>
      <link rel="stylesheet" type="text/css" href="jquery.CalendarHeatmap.min.css">
     

# Usage

Html will display the visualiation. 

For customisation of user data and custom display :
  - Download user Facebook data from Facebook Profile
  - Run Jupiter Notebook file to clean and format folder for use. This will generate    updated json files.
  - Replace "your_place.json" with your own in the visualisation folder ( if renamed, make sure to correct the path in the code )
  - To display other data on the globe such as "used_ip_addresses.json"/"where_you've_logged_in.json" , uncomment corresponding functions and replace file with your own. You will need to comment out the working "your_places" function.
  
  -Dropdown lists for data files and heatmap years available for optional usage:
  - uncomment, create a div containing the <select id="" ></select> and place in body
  
 # Colours
  - Colours customisables in css section.
  - For HeatMap Customization refer to @SeBassTian23 repository (https://github.com/SeBassTian23/CalendarHeatmap)


