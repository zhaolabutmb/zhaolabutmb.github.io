
# Brief introduction

This is the source code for Dr. [Haiqing Zhao](https://bmb.utmb.edu/people/faculty/bios/zhao)'s research group [website](https://zhaolabutmb.github.io) at the University of Texas Medical Branch. It is built using the customized Jekyll system for academics. Jekyll takes Markdown files and generates HTML styled with CSS. In building this website, we referenced templates and ideas from [Bedford lab](https://bedford.io/misc/about/) (the original author), [Nielson lab](https://nielsen-lab.github.io/), [Shen lab](https://www.columbia.edu/~ys2411/), and so on. Valuable discussions with [Guang Shi](https://www.shisguang.com/) on static HTML generators were also helpful in bringing this website to life.

A minimum manual for content updates: 
- Edit the `index.html` in root path to update the Homepage. 
- Edit the `index.html` in each Tab folder: `Research/`, `Papers/`, `News/`, and `Team/` to update each main page. 
- In each Tab folder, `_posts/` contains the markdown files for all the seperate posts.
- `_layout/` folder has all the layouts that each page imports.
- `css/custom.scss` has the pre-defined fontsize, colors, image sizes, and so on. Will be coded into css with html.
- `_site/` is the generated html folder after each jekyll code building (through command `bundle build`). 


#



