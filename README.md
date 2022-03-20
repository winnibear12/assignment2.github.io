
# Practical steps for hosting you resume with Markdown and Jekyll
---

## Purpose : To give information about how to host a resume on Github pages to Computer Science students.
   
---
## Prerequisites

1. Prepare your updated resume.
2. The resume must be Markdown formatted.
3. If you are not familiar to Markdown format, here is a good tutorial to learn Markdown.
   [Markdown tutorial](https://www.markdowntutorial.com/)
4. Prepare Markdown editor like Atom, iAWriter or Visual Studio code with markdown plugin.


---
# Instructions: How to make a static website

## Why do we use static website?

- It has faster loading speed than dynamic websites
- It is easier to make a website
- Better security

## What static genrators will use?

In this instruction, we will use [Jekyll](http://jekyllrb.com/). Jekyll is the most popular static site generator and it is designed to make a beautiful, functional documentation website.


## Follow this steps

### Prepare your resume in Markdown format

1. We will use Github Flavored Markdown since we are hosting your resume.md on Github
2. Download if you don't have markdown editors yet  
   [MarkdownPad](http://www.markdownpad.com/) (Windows)  
   [ReText](http://sourceforge.net/projects/retext/) (Linux)    
   [iA Writer](https://ia.net/writer) (macOS)

3. If you are not familiar to Markdown format, here is a good tutorial to learn Markdown.
   [Markdown tutorial](https://www.markdowntutorial.com/)

### Install Jekyll on MacOS

1. Setup [Jekyll](http://jekyllrb.com/) to host a static website.  
   
   There is a requirements before you installing jekyll.

   - Ruby version 2.50 or higher. (Check your Ruby version) <code> ruby -v </code> 
   - RubyGems <code> gem -v </code>
   - GCC & Make <code>gcc -v </code> <code>make -v </code>
  
2. Setup Command line tools  
   - open a terminal run this command
   
        <pre><code>xcode-select --install </code></pre>

3. Install Ruby  
   
   You will need to install Homebrew to install Ruby on MacOs.  
   <pre><code> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"</code></pre>

   then, run this command to install Ruby  
   <pre><code> brew install ruby </code></pre>

   Restart the terminal and check the Ruby status

   <pre><code> which ruby </code></pre>
   <pre><code> ruby -v </code></pre>

4. Install Jekyll  
   
   Finally, we can install the Jekyll.  

   <pre><code> gem install --user-install bundler jekyll </code></pre>



### Setting up your GitHub page  

#### Requirements

1. Github account
2. your resume with Markdown format


#### Follow this step

1. Make a repository named [respoitory name].github.io
2. Under the repository, make a upload or write a resume.md file
3. 

