# Navigation Precommit
Navigation router demo of precommit handling in RSC

## Run
Once you've cloned the repository, you can install the dependencies and start the example:

    npm install
    npm run dev
	
Then visit http://localhost:5173/ in your browser to see precommit navigation handling in action. 

1. Google Chrome shows the 'X' progress indicator for all navigations just like in MPA. Pressing the 'X' cancels the navigation.
2. The browser history back never shows stale data. Select a person, edit their name then press browser back and the list will show their new name.

https://github.com/user-attachments/assets/2aa8cf63-a412-4ab5-9ef9-c9155abc7c65
