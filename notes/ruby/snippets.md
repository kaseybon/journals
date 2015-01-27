#Snippets

**Open and edit a file:**
```
File.open(“/path/file.file”, “a”) do |f|
f << “Add some text”
end
```

**Read a file:**

```
print File.read(“/path/file.file”)
```

**See when a file was edited:**

```
File.mtime(‘/path/file.file”)
```

**Creating a method:**

```
def method_name (arguments)

end
```