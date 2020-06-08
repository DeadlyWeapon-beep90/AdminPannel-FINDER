# AdminPannel-FINDER





### Usages



- Check all paths with php extension
```
python Deadlyweapon -u example.com --type php
```
- Check all paths with php extension with threads
```
python Deadlyweapon -u example.com --type php --fast
```
- Check all paths without threads
```
python Deadlyweapon -u example.com
```
- Adding a custom path. For example if you want all paths to start with /data (example.com/data/...) you can do this:
```
python Deadlyweapon -u example.com --path /data
```
<b>Note: </b> When you specify an extension using <b>--type</b> option, Deadlyweapon includes paths of that extension as well as paths with no extensions like <b>/admin/login</b>

