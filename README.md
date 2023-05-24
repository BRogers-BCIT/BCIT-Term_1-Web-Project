# 1. 2800-202310-DTC16
DTC-16 Team Project Repository - ChessMind.AI


## 2. Project Description
ChessMind.AI is a chess analysis tool to help players improve their board analysis skills using AI to recommend and explain the best possible moves.

## 3. Technologies Used
### Frontend
- EJS
- JQuery
- Bootstrap
- HTML
- CSS

### Backend
- Node.JS
- Firebase

(TODO: Add links to all Node modules) (links found online)
- OpenAI API: https://platform.openai.com/docs/introduction/key-concepts
- express: https://expressjs.com/
- nodemon: https://www.npmjs.com/package/nodemon
- body-parser: https://www.npmjs.com/package/body-parser
- dotenv: https://www.npmjs.com/package/dotenv
- ejs: https://ejs.co/


- 

## 4. File Contents
```
ª   app.js                          // All middleware
ª   install_packages.bat            // Install all packages
ª   package-lock.json               // Node.JS
ª   package.json                    // Node.JS
ª   run_test_server.bat             // Run test server with Nodemon
ª   server.js
ª              
+---public                          // All browser files
ª   +---bars                        // HTML for headers and footer
ª   ª       footer.html
ª   ª       nav_after_login.html
ª   ª       nav_b4_login.html
ª   ª       nav_index.html
ª   ª       
ª   +---img                         // Images
ª   ª       add.png
ª   ª       bbishop.png
ª   ª       bking.png
ª   ª       bknight.png
ª   ª       bpawn.png
ª   ª       bpbishop.png
ª   ª       bpknight.png
ª   ª       bpqueen.png
ª   ª       bprook.png
ª   ª       bqueen.png
ª   ª       brook.png
ª   ª       chessmind-logo-small.png
ª   ª       delete.png
ª   ª       egg.png
ª   ª       eggLogo.png
ª   ª       empty.png
ª   ª       logo.png
ª   ª       move.png
ª   ª       reset.png
ª   ª       wbishop.png
ª   ª       wking.png
ª   ª       wknight.png
ª   ª       wpawn.png
ª   ª       wpbishop.png
ª   ª       wpknight.png
ª   ª       wpqueen.png
ª   ª       wprook.png
ª   ª       wqueen.png
ª   ª       wrook.png
ª   ª       
ª   +---pages                       // HTML pages loaded on frontend
ª   ª       404.html
ª   ª       analysis.html
ª   ª       board.html
ª   ª       egg.html
ª   ª       enterFenString.html
ª   ª       index.html
ª   ª       login.html
ª   ª       openBoard.html
ª   ª       profile.html
ª   ª       saved.html
ª   ª       
ª   +---scripts                     // Frontend Javascript
ª   ª       analysis.js
ª   ª       authentication.js
ª   ª       chess.js
ª   ª       chessboard_class.js
ª   ª       eggLink.js
ª   ª       eggLinkafterlogin.js
ª   ª       eggLinkb4login.js
ª   ª       firebaseapi.js
ª   ª       logout.js
ª   ª       profile.js
ª   ª       saved.js
ª   ª       skeleton.js
ª   ª       
ª   +---style                       // Frontend CSS
ª           analysis.css
ª           board-dev-controls.css
ª           board-medium.css
ª           board-mobile.css
ª           board-ultrawide.css
ª           board-wide.css
ª           board.css
ª           font.css
ª           index.css
ª           login.css
ª           nav.css
ª           profile.css
ª           save.css
ª           saved.css
ª           Urbanist-VariableFont_wght.ttf
ª           
+---views                           // Backend render template
        analysis.ejs                // Used to send user OpenAI responses
```

## 5. Installation

(WIP)

## 6. Usage

Our web application has five pages: index, profile, board editor, previous boards, and board analysis.

On the index page, users are able to sign up, log in, or they can choose to continue without logging in and head straight to the board editor.

On the profile page, users can view their profile, as well as edit and update the profile fields. If needed, they are able to reset the password aswell. 

Users can use the chessboard in the board editor page to configure the pieces on the chessboard. Pieces can be moved, deleted, or added to the board. Pawns have the ability to be promoted to their respective legal promotions; queen, rook, bishop, knight. The knight is the only piece that is unable to be deleted from the board. The board is also able to reset to the board's starting positions.

Any board configuration that a user creates can be saved or analyzed using the buttons above the chessboard. 

Previous board states can be found on the previous boards page. Each board a user has saved displays as a card that the user can click on. Users can edit and update the board name and description, or they can choose to open this saved board card into the board editor or board analysis page. Finally, users can delete the board if they no longer need it saved. Users can also use the search bar to find previous boards they have saved.






## 7. Credits, References, Licenses
N/A


## 8. Use of AI in product

We use OpenAI API to enable having ChatGPT as a feature for users to ask ChatGPT to recommend the best possible move to make. 
We used Github Co-pilot and ChatGPT to help code the board editor, board analysis, and saved board pages.

We did not use AI to create/clean data sets, nor did we encounter any limitations using AI.


## 9. Contact Information
DTC-16 developers can be contacted via their emails:

Gurjeet Bhangoo: gurjeetbhangoo@yahoo.com
Braden Rogers: brogers42@my.bcit.ca
Arsam Aminzadeh: aaminzadeh@my.bcit.ca
Sarah Ortega: lsortega551@gmail.com