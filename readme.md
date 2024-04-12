Ski Resorts is a map that shows the user how many ski resorts are in each state while also categorizing them by level of difficulty. I got the point data from https://gist.github.com/Ewiseman/b251e5eaf70ca52a4b9b10dce9e635a4#file-ski_resort_stats-csv which I then converted into a geoJson file and inserted it into the project. I categorized them into different difficulties by comparing the number of acres the resort alloted to green runs, blue runs, and black runs. If the resort had more acres of green than blue and black then it was classified as a beginner and so on. I also got area level data of the 50 states from https://eric.clst.org/tech/usgeojson/ and converted it into a geoJson that I could edit. I did this because I needed to add a property that said how many ski resorts were in each state and then I added it to the map. The user can click on the different points and see the name of the resort as well as which state it is in. Finally I found an appropriate basemap (ESRI.WorldTopoMap) from leaflet providers demo.