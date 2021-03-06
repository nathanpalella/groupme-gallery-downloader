# GroupMe Gallery Downloader
Download all of the photos in any group you have access to via the command line.

# What you'll need
* Git and NodeJS installed locally
* GroupMe Developer ID

# Where to get your GroupMe Developer ID
* Go to https://dev.groupme.com/
* Login with your existing GroupMe credentials.
* Generate an access token -- This should be a 40(ish) character string.

# How to run this program (in terminal)
* `cd` to your desktop, or other directory of choice. 
* `git clone https://github.com/TylerK/groupme-gallery-downloader.git`
* `cd groupme-gallery-downloader`
* `npm install`
* `npm start`

You will be prompted for your GroupMe access token. Go ahead and paste it in and press enter. Assuming all went well, you will now be able to select a group you have access to. Select a group and you should see a stream of photos filling up a newly created `photos` folder. 

> Note: There is no "restart from where I left off" feature currently - [It's in the works, I swear!](https://github.com/TylerK/groupme-gallery-downloader/pull/10) - This means that if the download dies for any reason you need to restart. Huge galleries beware.
