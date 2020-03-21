The Odin Project: Cloning the Google Homepage

-Purpose:

At the end of this porject I intend to master my skills in HTML and CSS to some degree that I'd like to be able to copy any webpage that I see on the web using both conventional HTML/CSS methods and using google developer tools.

-Tools:

The Odin Project Website: theodinproject.com

Google itself: google.com

Almighty GitHub": github.com

Visual Studio Code

Google Chrome and Developer Tools that come with it

Lastly and more importantly, HTML and CSS

Update 1:

-Created the repository itlself, created this README.md file and added the purpose.
-Created the index.html and style.css files and styles folder for css.

Update 1.2:

-Added the Google logo at the center of the page as a div in a parent div. 
-Fixed the parent div at the middle of the page so that everything I place inside this div will go directly to the middle (check .searchbar class in style.css).
-Created a search bar and a voice search button (check div class=search in index.html), set the border for it to 3px and tried to get as close to the original Google search bar color as possible. Deleted the border on the right to stick the voice search button to the search bar seamlessly.
-Set the padding (space around the search text) to 5px and searchbox height to 10px since that felt the closest to Google's original setting. (check .search css for more info)
-Tried to make the searchbox a circle by setting top and left radii to 16px.
-Added a Google Voice Search logo as search button, however neither regular nor the voice search will be non-functional for this project and they stay there as placeholders.

Update 1.3:

-Aligned the logo and the search bar in the middle of the page, a little to the top just like google homepage.
-Added the 'Google Search' and 'I'm Feeling Lucky' buttons. Made their font size one pt bigger than the rest since that's how it looks like in Google homepage.
-Removed all visuals except the text from the buttons and made them gray in color.
-Added a hover animation where it creates a box around the button and prevented the browser from creating a scrollbar/blue box around the buttons. Added a custom 1px blue box animation when the button is clicked and hold.
-Removed the left border as well from the search bar and instead added a magnifier search icon just like on the actual page.

Update 1.4:

-Small cosmetic updates.

Update 1.5:

-Added the hover effect on search bar, voice search and search magnifier boxes. it adds a feathered shadow at the bottom of the boxes and makes the top line even thinner. Achieved the thinness by decreasing the color opacity since the line was already at 1px.

Update 1.6:

-Created the navigation bar on the top right with the Gmail, Images text links and Apps hover link + User settings link with iconic U icon.

Update 1.7 (final):

-Created the left and right footers and styled the links for color and font size. There's also a simple CSS where the links are underlined when hovered over them with the mouse.
-Changed the User icon for a Sign In button and added a CSS where it turns it's color darker when activated.


Known Bugs to Fix:

-Right border of search magnifier box and left border of voice search box are visible when the hover effect applies. Might use JavaScript instead of CSS to fix it.