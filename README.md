### Replacer for telegram's translation files
Rename multiple strings of your Telegram language in one go!

* edit the find-replace pairs in the code itself<br>
```
REPLACE_DICTIONARY = {
	"members":"kideak",
	"online":"linean",
}
```

`"phrase to find":"phrase to replace",`<br>

* Run the replacer
```
python replacer.py --lang android_lang.xml
```
Case-insensitive translations are noted in `possibilities.log`.

**Note:** Of course, don't rely on this.
