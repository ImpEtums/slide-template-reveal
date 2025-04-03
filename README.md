# Reveal-md template

## Introduction

This is a minimalist style PPT template based on reveal-md, written in Markdown, supporting math formulas and code highlighting.

## Directions for Use

1. Make sure you have Node.js installed.
2. Install reveal-md globally:
   ```
   npm install -g reveal-md
   ```
3. Run the presentation:
   ```
   reveal-md {markdown_file_name}.md --css {style_name}.css
   ```


## Export to PDF
1. directly export to pdf
   ```
   reveal-md {markdown_file_name}.md --css {style_name}.css --print {output_file_name}.pdf
   ```
2. set the print size in the reveal-md config file
   ```
   reveal-md {markdown_file_name}.md --css {style_name}.css --print-size 1920x1080 --print {output_file_name}.pdf
   ```

