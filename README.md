# CRAYFIS Translations

Translator instructions: please fork this repository, and then edit the `django.po` for your locale. The file format is very simple and it is probably easiest to learn from the examples which are already in the file. Basically for each English `"msgid"`, put your translation in the following `"msgstr"`. When you're done, open a pull request. Your translations will eventually be copied onto the website after the pull request has been merged.

## Site

For a locale, e.g. `de`, running the below will add any strings from HTML templates into the message file to be translated. This must be run using the `manage.py` from the site; note that this is in a different repository.

```
python manage.py makemessages -l de -e html
```

Links to location codes https://developer.chrome.com/webstore/i18n
