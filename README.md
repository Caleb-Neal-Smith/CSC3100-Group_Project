# SmartCoop
Authors: Alec Jones, Nolen Jensen, Samuel Sims, Mitchell Kiriazes, Caleb Smith, and Christian Scott  


## **ideas**
- change dashboard to a grid with icons?
- add additional buttons to navbar?
- add About Us page somewhere maybe?

## **changelog**

### 4.21.3
**added**
- merged all changes alec and I made to splash screen, navbar, and theming

**changed**
- fixed a couple settings errors with navSettings button, and removed redundancy
- changed dropdown buttons to button type

**to do**
- change account button to 3 lines to make it more uniform like a normal webpage
- change smartcoop button to be an icon and not lame  


### 4.21.2
**added**
- added all of christian's settings additions

**changed**
- fixed a couple settings errors


### 4.21.1
**added**
- added splash page -- alec
- consolidate the btnToggle functions onto the main logout() function

**changed**
- changed account dropdown to only show login or register
- integrated splash page with logout() function
    - tweaked logout()
- added more styling - alec

### 4.18.2
**added**
- added padding for navbar so things arent under it when scrolled to top.

**changed**
- modified navbar so that it is fixed -- is frontmost above everything, and also stays fixed on the top instead of disappearing when you scroll.
- fixed navbar when logged out. **If possible, I need help where one of the two dropdown buttons disappears when logged out.**
- changed smartcoop button so it refreshes page.(subject to change)
  
  
### 4.18.1
**added**
- none

**changed**
- modified navLogout to have an if statement where depending on the screen it's in, it will close that and logout.


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
    
