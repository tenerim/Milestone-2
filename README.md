# Project Name: 
Milestone Project 2 - Dan's City Breaks

Dan's City Breaks provides an interactive, practal, meaningful and helpful user experience for anyone looking to take a City Break across a number 
of global locations. Together with our network of partners located around the world, we've carefully selected only the best and most popular countries to visit. 
We've then identified cities where our users could choose to say, with hotels and areas of interest all available to view and to select via our 
Application which is available through the user's web browser, and other platforms.

The Google Maps window provides a very 'real' context through which the user can get a sense of exactly where they'll be staying. By first selecting the
country of their choice, they'll then need to free-type a City of their own particular interest. Once the user starts to free-type their preferred City location
in the City input field, the Application offers the user some options they might not have considered, while also helping ensure the user completes that data field 
correctly. The Application then offers hotel options via the map window, and also via a full list of available hotels immediately below the Google Maps window.  

# UX
I designed the web site with the experienced traveler in mind - someone who is already familiar with travel, and is looking for an easy way to finding hotel 
options, with things to do in a local area during a City break. 

Specific User Stories for this project are:

* As a site user:
  - Easily and quickly select a number of Country locations as options / places to visit
  - To be able to choose from a number of hotels in an area they are interested in traveling to
  - To identify various things to do and places to go in that City
  - To be able to connect directly with someone from the Dan's City Breaks web-site to discuss options and ask questions directly with somoene if necessary

* As a site owner: 
  - Provide a user-friendly web-site that helps users to decide where to travel for their City Break 
  - Make optimal use of the Google Maps API and the functionality available to site owners and to users  

The following wireframes provide the insight and logic into the design and purpose of the site: 

1. https://github.com/tenerim/Milestone-2/blob/9abe9bfc013e4fe0c7bb6ecf0191ccc4ea05d796/assets/Wireframes/WF%20Page%201.JPG 
  - The opening page is simple yet informative. It provides the user with an immediate and simple view with instructions on what 
  the user needs to do to 'choose from a wide selection of popular City locations'.
2. https://github.com/tenerim/Milestone-2/blob/9abe9bfc013e4fe0c7bb6ecf0191ccc4ea05d796/assets/Wireframes/WF%20Page%202.JPG
  - Page 2 offers a list of the hotel options available to the user - this assumes the user is already familiar with the area and might prefer to 
  select from the drop-down list, rather than search for any one particular hotel from the map window in Page 1. 
3. https://github.com/tenerim/Milestone-2/blob/9abe9bfc013e4fe0c7bb6ecf0191ccc4ea05d796/assets/Wireframes/WF%20Page%203.JPG
  - Page 3 offers a number of direct contact options from around the world, along with Social Links, providing the user with options to contact a representative
  of Dan's City Breaks directly. 

# Features
* Feature 1 - The primary feature of the site is that is allows users to openly select country options from the drop-down list in the left window, while
helping them with the auto-population feature when selecting City options in the right window.
* Feature 2 - The availability of the Google Maps window and the ease with which the user can view the georgraphic location of each City
* Feature 3 - The list of hotels within each City that's selected by the user
* Feature 4 - The information available within the Google Map window, with regards to the City that's been selected by the user 

## Additional (future) features might include:
* Links to additonal sites that offer package deals, flight information and car hire for the location selected
* Additional country and City options by continent 
* User feedback from people who have used the site and found it useful 
* A limited drop-down list of Cities in addition to the City free-type field, should people not have a specific City location already in mind
* Fully functioning Social Links which (for the moment) tie back to the Application page only 

# Technologies Used
* html: the base language used to build the web-site
* css: to simplify the format and layout of the web pages by enhancing the code in the html pages 
* jQuery: to simplify DOM manipulation and interact with the Google Maps API
* bootstrap (https://getbootstrap.com/): To use ready-made design templates to enhance the front-end appearance and user-experience of the web-site 
* W3 Schools online web tutorials: https://www.w3schools.com/default.asp I found this useful when looking for alternative descriptions and solutions to bootstrap. 
* font-awesome via the cdnjs libraries (https://cdnjs.com/libraries/font-awesome): To support the 'Social' links in the footer 

# Testing
* The following web sites were used to validate my code: 
  - https://validator.w3.org/ to test and validate my html file <!----------Would be great if we could take a look at this together------->
  - https://jigsaw.w3.org/css-validator/#validate_by_input to test and validate by css file
<!--------Can I test my JS code anywhere?---------->
<!--------How can I use Jasmine (if at all) to test my code?------> 

* The following tests were manual, specifically:  
  - I reloaded each page once I completed a new section.
  - Once I was confident with that view, I opened the page in the browser and ran the page in that view. 
  - The four 'local offices' have telephone numbers and web addresses intentionally left blank. 
  - I tested my website on the different scren sizes where I was able to correct any errors or inconsistencies by adjusting for the column widths within each container.
  - This also ensured the text aligned appropriately for the screen size chosen. 
  - On a smaller screen size the Google Maps window and the picture of Venice sit on top of each other - ensuring the user is still able to 
  see a full screen size of the map on their device. 
  - All images are coded to fit the full width of the screen on any mobile device, and to sit side-by-side on a larger device. 
  - The Social links in the footer tie back to the Application page (as currently intended) and the colour of each changes as appropriate when hovered over.

* User Story Testing:
1. As a user: 
  - The user is able to quickly and easily select from a number of country locations, and is able to choose from various hotels
  in an area they are interested in traveling to
  - Various facilities and ideas for things to do are available in the Google Maps window once the user selects a specific city. More specific detail
  is made available once the user selects a specific hotel to view
  - The ability to connect with a live representative from Dan's City Breaks is not made available 

2. As a site owner: 
  - The application does provide the information that can help users to decide where to travel, for their city break
  - While a number of alternative API's are available via Google Maps I believe optimal use is made of this particular API

* Testing the main function of the Country and City location: 
  1. Click in the Country Location drop-down list to select a preferred country -> the Google Map will change accordingly
  2. Free type a preferred city for that country the the City Location data field -> this field will auto-populate
  3. Pins will drop onto the map to identify hotels in that city -> Select from within the map istelf, or from the list of hotels 
  made available beneath the image of Venice
  4. Once any hotel is selected, a pop-up will appear for that hotel, displaying the name, address, contact information and Hotel Rating, 
  in addition to the hotel's direct web link
  5. Select the hotel name to be taken directly to a closer view of the local area. On this page: 
    - Local facilities are easy to view and select
    - The left-hand panel displays more information about the hotel
    - A booking can be made directly from the left-hand panel
    - Alternative hotel options are also listed for user reference

# Deployment
This project is hosted through GitHub Pages: https://tenerim.github.io/Milestone-2/ 

<!--------Process I followed to deploy the project to a hosting platform?----------> 

All code is saved to the following repository in GitHub: https://github.com/tenerim/Milestone-2 

There are no differences between the deployed version and the development version. 

<!--------Should I explain how to run the code locally?----------> 

# Credits
* Footer
The content for this section was taken from the footer of the 'My Resume' project (the 'Mini Project with Bootstrap 4')
* Media
The photos used in this site, includeing the backdrop of the Golden Gate Bridge, were obtained from: https://coverr.co/search?q=city
* Icons
The icons used in this site were taken from fontawesome.com 
* Acknowledgements
I received inspiration for this project from my family, with support and coaching provided by Precious Ijege. 