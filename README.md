Make sure you are in the same directory as this repository before running these commands. So you may need to do this:
```
cd ~/Sites
```
To start up the web server, do this
```
./dev-server
```
You should now be able to hit the site on localhost:8000. You will need to hit Ctrl-C if you want to stop it.

To work on the scss, you need to run the following command:
```
./make-css
```
This will watch the scss folder for changes and output the results to the css directory. Link the css files in your html.

To deploy the site:
```
./deploy
```
