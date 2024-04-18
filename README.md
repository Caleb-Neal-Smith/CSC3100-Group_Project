# SmartCoop
Authors: Alec Jones, Nolen Jensen, Samuel Sims, Mitchell Kiriazes, Caleb Smith, and Christian Scott  
[insert info for readme here]


**navbar branch that mostly works ish**  
dont merge until it's done, cause i dont want it to break everything else

# **changelog**

### 4.18.1
**added**
- none

**changed**
- modified navLogout to have an if statement where depending on the screen it's in, it will close that and logout. Currently it only opens the login screen next to the current one and changes the navbar.

**to do**
- change account button to 3 lines to make it more uniform like a normal webpage
- change account dropdown to only show login or register


### 4.18.0
**added**
- added a return to dashboard function

**changed**
- modified the existing buttons to simply call the returnHome() function


### 4.11.1
**login**  
- added where the email and password fields are cleared after logging out
**dashboard**  
- put the logout commands into its own function so it can be called from any logout buttons, and called it from said buttons
**navbar**  
- changed the account dropdown to show the following when logged in:  (it slightly works atm. needs to be fixed)
    - options to open setting screen
    - button to logout(work in progress)
    
**ideas**
- change dashboard to a grid with icons?
- add additional buttons to navbar?