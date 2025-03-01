# Getting Started with Public folder

## The public folder contains static assets that don’t get processed by Webpack or Babel. These files are directly served to the browser.

Common files inside public/:
# index.html 
The main HTML file. This is the entry point of the React app. 
It contains a <div id="root"></div> where React renders the application.

# favicon.ico 
The small icon displayed on the browser tab.

# manifest.json 
A configuration file for Progressive Web Apps (PWA), 
containing metadata like the app’s name and theme color.

# robots.txt – Instructions for web crawlers (SEO-related).

Purpose: Holds static files that won’t change at runtime, such as images, fonts, and the root HTML file.