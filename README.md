# DOKUWiki USACE Template
*Theme your DOKUWiki site using the US Army Corps of Engineers theming*

## Steps
*These steps assume you have dokuwiki downloaded and placed on your webserver with 
1. Click the green code button and select "Download Zip"
2. Extract the Zip contents
3. Create a directory with the name `usacewiki` in the `lib/tpl/` directory of your dokuwiki install
4. Place the contents of `usacewiki` from the downloaded zip into the `usacewiki` you installed. Make sure it does not create the `usacewiki` directory within the same named directory.
5. Create a symbolic link from your existing district templates (includes) with:
   ```ln -s /path/to/htdocs/includes /path/to/htdocs/wiki/lib/tpl/usacewiki/```
   *Where `wiki` would be the name of your dokuwiki install (might also be `/dokuwiki`)
   **NOTE:** If you do not have the district template already on your T7 you can add those to the `includes` directory of your webserver. Download [here](https://github.com/usace-wm-swd/District-Templates).
6. Load your doku wiki page and see what you get!

Report issues with the template styles/css that are bleeding into dokuwiki installs on the district templates page:
https://github.com/usace-wm-swd/District-Templates/issues