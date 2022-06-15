# localization
localization: to translate the website to other languages.

So, you can add one or more language to translate you website to be seen by different users from all over the world.

## steps to translate a page:
1. go to setting --> locales --> press `ADD A LOCALE` button.
2. from the dropdown list select the language/s that you want to translate to it.
3. select `CREATE` button.
4. then go to the page that you want to translate it.
5. select more, and from the dropdown list select `Translate`
6. select the target language, and click `SUBMIT` button.
<h4 style="color:red">important notes</h4>
- if your page has a child page/s don't mess to check `Include subtree` option.
- if you add another child page to your main page it will automatically create a one for your alias page (The page you translated)

7. now it will create an alias page with your chosen translation language from the page you translated.
8. finally, you have to go for all pages that translated and change its content to the chosen language (for example: from English to Arabic content).

**the link will be something like this:**
- localhost:8000/en for English site 
- localhost:8000/ar for Arabic site

## steps to translate a navbar:
- go to settings --> Menu [(docs)](documents/adding_navbar.md)

- at `CONTENT` section add `Link title arabic` field for each block.

## steps to translate a footer:
- go to settings --> Footer setting [(docs)](documents/adding_footer.md)
- at `MAIN ADDRESS ARABIC` field add Arabic address.
- at `GOOGLE MAP LOCATION` section add `Title arabic` field.