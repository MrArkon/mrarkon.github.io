# mrarkon.github.io
[![](https://img.shields.io/github/actions/workflow/status/MrArkon/mrarkon.github.io/gh-pages.yml?logo=github&style=for-the-badge)](https://github.com/MrArkon/mrarkon.github.io/actions/workflows/gh-pages.yml)
[![](https://img.shields.io/github/license/MrArkon/mrarkon.github.io?style=for-the-badge)](https://github.com/MrArkon/mrarkon.github.io/blob/rewrite/LICENSE)
[![](https://img.shields.io/github/issues/MrArkon/mrarkon.github.io?label=ISSUES&logo=github&style=for-the-badge)](https://github.com/MrArkon/mrarkon.github.io/issues)


This repository hosts the source code for my personal portfolio website. Powered by [Hugo](https://gohugo.io/) and [PaperMod](https://git.io/hugopapermod)

## Running
Before proceeding please ensure you have installed [Hugo](https://gohugo.io/)

1. Update the PaperMod theme with the following command after cloning the repository:

   ```bash
   git submodule update --init --recursive
   ```
2. To run a development server use the following command:
  
   ```bash
   hugo server -D
   ```
   
   To build a static website run the following command:
   
   ```bash
   hugo build --minify
   ```


## License
This project is licensed under the GPL-3.0 license. See the file [`LICENSE`](https://github.com/MrArkon/mrarkon.github.io/blob/master/LICENSE) for more information. 
If you plan to use any part of this source code in your website/portfolio, I would be really grateful if you include some form of credit somewhere. 
