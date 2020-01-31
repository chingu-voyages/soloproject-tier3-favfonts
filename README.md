# Chingu Solo Project - Tier 3 - Favorite Fonts

![Landing Page ScreenShot](./assets/favoriteFontsLanding.png)

## Overview ##

This project is a great opportunity to develop a clean and modern webpage. The *Favorite Fonts* app will be completed accross tiers, with each tier adding a level of complexity. You are currently on the *Tier 3* repo. You'll be responsible for coding the **HTML**, **CSS**, and **JavaScript** to get the structure, styling, and functionality up and running, as well as a back-end, in a stack of your choice, to process the necessary api call and, **if desired**, to allow user authentication and/or persistence functionality.

Ultimately you'll have a great portfolio piece, and will have implemented a number of common and in-demand features.

**You May Use the Stack of Your Choice!**

## Instructions ##

Tier 3 **MUST** include a back-end to make the necessary API calls. If desired, you can also add authentication and/or persistence. Use of localStorage, IDB, CacheAPI, etc., are *not* fill-ins for this project's persistence if you choose to implement the Extra tasks.

General instructions for all Pre-Work Projects can also be found in the Chingu Voyage Handbook (URL posted in the #read-me-first channel on Discord).

**Requirements**

*Structure*
- [ ] Header with minor navigation *(Logo and Catalog/Featured/Articles/About link list)*
- [ ] Nav with Major navigation / page-manipulation *(search, custom text, font-size, dark/light mode, grid/list mode, and reset)*
- [ ] Main section for the font cards
- [ ] Font cards which display the Font Name, the sample text, and an add button (the font creator is not available via the api, so it is **not** required in tiers 2 or 3)
- [ ] Button that allows user to click and scroll back up to the top *(there could be up to 959 fonts displayed, so you need this!)*
- [ ] Footer section with your developer information

*Style*
- [ ] Sample text in each card should be displayed in the corresponding font
- [ ] Buttons/links should be evident (make sure the cursor changes, etc.)
- [ ] Implement a way to handle overflow from sample text in font cards, as the font size is adjustable

*Functionality*
- [ ] Text typed into the custom text (type something) box should immediately change the sample text in each font card
- [ ] The sample text should return to the default sample if the input box (type something) no longer has any input
- [ ] Font size chooser should have at least four sizes and should immediately change the sample text font size in each font card
- [ ] Implement the 'reset' icon on the far right of the major navigation; it should reset the page as if it were reloaded *(do not actaully reload the page)*
- [ ] On load, the page should display fonts sorted by current popularity, as returned by the Google Fonts Developer API *(see below)*; this call should be server-side
- [ ] The search feature should be fully functional and display matching fonts (it's up to you if you want to do this via a 'submit' or through onchange)
- [ ] When the search input is cleared (via reset button or manually), the fonts should automaticaly display sorted by poplarity again
- [ ] Fonts from the Developer API should be retrieved on the back-end and sent to the client *(see below)*
- [ ] StyleSheet requests from the Google Fonts API can be compiled on either the front or the back

*Other*
- [ ] Your repo needs to have a robust README.md
- [ ] Make sure that there are no errors in the developer console before submitting

**Extras (Not Required)**

- [ ] Make your design fully responsive (small/large/portrait/landscape, etc.)
- [ ] Implement the light/dark mode toggle buttons
- [ ] Implement the change display icon so you can flip between a grid layout and a list layout for the font cards
- [ ] User creation and authentication: Add a login button to the page that allows registered users to login, or prompts new users to register. Once a user is authenticated, display somewhere on the page that they are logged in.
- [ ] Add a favorites feature with back-end persistence: one example of this would be to use cookies to point to the user's favorite list in your database. You'll need to add a "see favorites" button somewhere to toggle between the view of the user's favorite fonts and the searches / popularity sort.

## API Information ##

This project utilizes the [**Google Fonts API**](https://developers.google.com/fonts/docs/getting_started) and the [**Google Fonts Developer API**](https://developers.google.com/fonts/docs/developer_api). You will need to register for a free api key in order to complete this project as calls to the developer api are severely capped without one.

The call to the **Google Fonts Developer API** needs to be completed in the backend. How you process that data is up to you.

Use of the Font Loader Library is **not** needed for this project. If you come back to this project after the pre-work, feel free to add the loader library to get more functionality when calling different styles, weights, swaps, etc.

## Example ##
*This example shows all parts of functionality except for the user login and favorites list.*
![Preview Gif](./assets/appPreview.gif)
