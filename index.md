# This is Header 1
## This is Header 2
### This is Header 3
#### This is Header 4
##### This is Header 5
###### This is Header 6

This is to test for headings in Markdown


![Image of Yaktocat](https://github.com/sileola/images/blob/main/markdown-image.png?raw=true 'Image of Yaktocat')

``` yaml
#!/bin/bash
# Use this for your user data (script from top to bottom)
# install httpd (Linux 2 version)
yum update -y
yum install -y httpd
systemctl start httpd
systemctl enable httpd
echo "<h1>Hello World from $(hostname -f)</h1>" > /var/www/html/index.html
```
