#!bin/bash

#File name
markdown_file="README.md"

#Use a heredoc to write Markdown content
cat <<OEF > "$markdown_file"

#Title
My name is **Surprise**.

- List item 1
- List item 2
- List item 3

[Link](https://github.com/sabraboi)

\'\'\'bash 
echo "This is a code block in Bash"
\'\'\'
EOF

echo "Markdown file '$markdown_file' created successfully." 

