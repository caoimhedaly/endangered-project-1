  
  
  ##ENDANGERED:
  
  ##Introduction:
  
  This project is a frontend-only website using technologies learned through my user-centric frontend development module. I chose not to follow the brief provided but instead to develop a website which aims to highlight animal species at risk of extinction. The website provides insight into the main threats to the lives of these endangered animals and information on the remaining populations. As well as documenting five of the most at-risk species globally, the website provides links to charitable organsisations which fight to prevent animal extinction. 
  
  ##UX:
  
  The ENDANGERED website I developed to raise awareness about species endangerment. It provides some information on different at-risk species globally and links to websites of animal protection agencies and charities for users interested in learning more or making a donation. Below are a few potential users:
  
  *Patrick 47yrs: I am an animal lover and recently watched a documentary on rhino poaching. Im interested to learn about the threats to rhinos and other endangered animals and find information and how I might be able to help prevent further species population decline. I found the 'Save the Species' page particulary helpful with links to organisations which battle against animal eradication. 
  
  *Sarah 13yrs: I was given a homework project to make a presentation on a topic that I feel strongly about and i chose animal extinction. Using the Endangered website, I was able to find out statistics on animal populaton decline and details about the main threats posed to these animals. 
  
  ***LINK TO WIREFRAME***
  
  ##FEATURES:
  
  *Navigation bar - each page has a collapsible navbar which allows the user to easily naviagte the website. 
  
  *Footer - each page has a footer which includes icons representing potential links to different media pages. As this website is strictly static, the icons are not acive links. 
  
  *Homepage- the homepage is a striking gallery of colourful images of different animal species. It is designed to be eye catching and to draw attention to the text overlay which provides a short introduction to the website. 
  
  *Most at Risk- this page documents five of the most at risk species globally, details on their population and threats to their existence. Each animal has a striking image with a light overlay hover effect which zooms in from the left side to reveal the species name and population. 
  
  *Save the Species - This page uses bootstrap cards to display the logo of different animal protection organisations as well as a short intro to their work. Again the links to the websites do not work as this is a static website. Instead a modal informs the user that the link is under construction. 
  
  *Contact Us- this page provides a gps location using google maps of the 'Endangered' organisation, set to the address of the ibat building temple bar. A form allows the user to either make a donation, report an issue with the website or enquire for further information. A contact phone number is also provided as well as social media links. 
  
  ##Features to implement:
  
  Ideally if this website were interactive, I would like to set up stripe payments to a charitable organisation. In addition I would activate the media links as well as the links to external websites. 
  
  I would also like to implement a data dashboard demonstratinhg the decline in different species over time using a line chart of time against population. 
  
  
  ##TECHNOLOGIES USED: 
  
  *BOOTSTRAP CDN 4.0.0 <https://getbootstrap.com/> - I used the Bootstrap framework as it allowed me to build a mobile-first, responsive website using html, CSS and JS. 
  
  Cards- on the save the species page, I was able to create a card using bootstrap diplaying a charity icon and a short intro as well as a link to the relevant website. 
  
  FORM- the form on the CONTACT US page I constructed using bootstrap.  
   
   
  *FONT AWESOME <https://fontawesome.com> - I used the font awesome library to insert media icons as potential media links in the footer of each page. 
  
  *HTML- I used Hypertext markup language to give my content structure and meaning by defining headings, paragraphs, images etc. 
  
  *CSS3 - I used CSS to allow me to style my HTML documents. CSS allowed me to style text size, color, position. 
  
  Image gallery- css allowed me to style an image gallery on the home page with an opaque text layover. 
 
  Tooltips- I was able to create a tooltip using css to inform the user that the media icons and form do not work. 
  
  I used css border-radius to create circular images on the contact us page. 
 
  Display - i used the display property on the home page to hide some of the images in the gallery on smaller screens. 
 
  Margins/Borders/padding - this allowed me to create white space on my website for a better user experience and easy using. 
 
  Transitions- using css transitions i was able to transition a text overlay on hover over image on the most at risk page. On smaller screens the user must click to display this text. 
 
  Modal - using just css i was able to create a simple modal box to inform the user that the card links are currently unser construction. 
 
  *Google maps API <https://cloud.google.com/maps-platform/> - using google maps for developers i was able to insert a map with the charity location. 
 
 ##Sources:
 
 W3Schools <https://www.w3schools.com/> - I followed a tutorial on w3schools in order to implement the tooltips. 
 
 JSfiddle <https://jsfiddle.net> - I followed a tutorial on js fiddle to create modals.  
 
 ##Testing:
 
 *Home Page : 
 i.The home page is mobile responsive, the navbar collapses to a dropdown menu accessed via a button button at a width of 990px. 
 ii.Some of the images in the gallery are hidden on a small screen.
 
 *Most at Risk : 
 i. click on the Most at Risk link in the navbar, it takes you to this page. 
 ii. On a large screen, when you hover over each image, white text transitions from the left on a semi-transparent background.
 iii. On smaller screens, the text 'click image' appears at the bottom left corner of each image to inform you that you must click the image to reveal the text. 
 iv. media icons - on hovering over the media icons, a tooltip informs the user that the site is under construction. 
 v. On smaller screens, each article of text lays below the respective image. On larger screens the text lays to the right of the image. 
 vi. Again the dropdown menu functions as a navbar on smaller screens on this page. 
 
 *Save the species : 
  i. click the save the species link in the navbar, this page opens.
  ii. click on each of the links on each card, a modal opens to inform you that the site is under construction. 
  iii. click on the X at the top of the modal box, the modal closes.
  iv. media icons - on hovering over the media icons, a tooltip informs the user that the site is under construction. 
  
 *Contact Us :
 i. click on the contact us link in the navbar to open this page. 
 ii. form - click the dropdown menu on the form to chose you query
          - click the submit button and a modal opens to inform the user that this is under construction. 
 iii. map - zoom in and out on the map 
 iv. media icons - on hovering over the media icons, a tooltip informs the user that the site is under construction. 
 v. on smaller screens, the navbar collapses to a dropdown menu. 
 
 ##Deployment:
 
 ##Credits:
 
 *Content- The text on the home page I adapted from the IUCN website <https://www.iucn.org/>
 
 Text on the Most at Risk page detailing animal populations came from the WWF website <https://www.worldwildlife.org/> 
 
 Information on animal protection agencies found on the Save the Species page came from the respective websites as follows:
 
 WWF - <https://www.worldwildlife.org/>
 IUCN - <https://www.iucn.org/>
 Wildlife act - <https://wildlifeact.com/about-wildlife-act/>
 The great Projects - <https://www.thegreatprojects.com/animal-conservation-volunteering>
 Animals asia - <https://www.animalsasia.org/>
 OneKindPlanet - <https://onekindplanet.org/>
 
 ##Media:
 
 Images used in the home page image gallery and Most at Risk page are taken from the unsplash library of free images 
 <https://unsplash.com/>
 
 
 