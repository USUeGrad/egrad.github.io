# How to Run Locally

1. Follow these steps with preferred OS Guide: https://jekyllrb.com/docs/installation/
2. After installing dependencies outlined on the guide above: 
```bash
# install bundler
gem install bundler

# clone the project
git clone https://github.com/usuegrad/egrad-wiki
cd egrad-wiki

# run jekyll with dependencies
bundle exec jekyll serve
```
# How to create a post

1. Edit `\_data\docs.yml`
2. Create Entry within structure:
```
- title: Getting Started
  docs:
  - home
  - themes
  - customization
  - newpage #new entry
```
3. Creat Markdown File within `\docs\` with the same name as the entry: 
    `\docs\newpage.md` or within appropriate directory
4. Give it a title and link:
```MD
---
title: New Page
permalink: /docs/newpage/
---
```
5. Write away!



