# Testing Evidence

1. **Responsive Widths:**       
I included auto-fit and minmax grids and responsive image styling. Used dev-tools to make sure that the containers adjusted width accordingly for different devices. 
2. **200% Zoom:**       
Text is perfectly readable at 200% zoom for headings and body text. Made sure to use no px and only rem/clamp/fluid typography so that there will be no resizing issues as the page adjusts for the device screen. 
3. **Slow Network:**        
Ran a lighthouse report using a slow 4g device and the report came back within the appropriate load time. Converted my pngs to webP too so that it wouldn't bog down the site. Also added a lazy load to the youtube iframe so that it won't load unnecessarily before the user scrolls to that part of the page. 
4. **Image Dimensions:**        
The Project card images (web development/graphic design) are the same size and I used various versions of the images as well to load for specific screen sizes. 
5. **File Sizes:**      
I converted the larger PNGs to WebP so that it would reduce the file size. 
6. **ALT Text:**        
Included the appropriate ALT text for things like the project card images and kept the more decorative things like techstack icons to only short alt texts. Didn't need them for the social icons since those have aria-labels on them. 
7. **Layout-Shift:**        
Made sure the project card images have a specific width/height and 3/2 aspect-ratio container. Youtube video iframe has a 16:9 slot reserved for the iframe to load in. 
8. **AI Use:**  
* I used AI previously to come up with ideas for @ layer utility tokens. 
* Also used AI to generate the collage images of my own prior projects to use as a card image for mobile/tablet devices. 
