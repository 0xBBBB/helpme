# Finding files

You can find files by name using find. The example below finds all files with names ending in .html:

```
find ./ -iname "*.html"
```

If you'd like to search case sensitive, use -name instead of -iname:

```
find ./ -name "*.jpg"
```

To search based on modification time, use -mtime. The example below finds images modified in the last 10 days:

```
find ./ -iname "*.jpg" -mtime -10
```

