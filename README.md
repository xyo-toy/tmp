# Transformation Docx vers Markdown
Via Pandoc :
```
$ myfilename="example"
$ pandoc \
-t markdown_strict \
--extract-media='./attachments/$myfilename' \
$myfilename.docx \
-o $myfilename.md
```
