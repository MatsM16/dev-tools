# DEV tools
A curated list of useful tools when working in [VSCode](https://code.visualstudio.com/).  
This page is intended to help quickly setup development environments for different toolchains.  
The page is currently heavily influenced by my work-habits and school.

## Add
Use this guide when adding new tools or extensions.
1. Find a `<section>` in `index.html` matching the tool.  
   If unable to find a appropriate section, create a new `<section>` in `<main>` using the template below.  
   **Section template:**  
   ```html
   <section>
       <h1>{section-name}</h1>

   </section>
   ```
2. Download an `png`-icon for the tool. Put the image in the `icons/`-folder.
3. Add the appropriate template to the `<section>` from `step 1`.  
   **Tool template:**  
   ```html
   <a target="_blank" class="tool" href="{download-page}">
       <img src="{icon}">
       <label>{name}</label>
   </a>
   ```
   **Extension template:**  
   ```html
   <a target="_blank" class="extension" href="{extension-page}">
       <img src="{icon}">
       <label>{name}</label>
       <cite>{extended-tool}</cite>
   </a>
   ```
4. Replace template text with useful text.  
   `{download-page}`: Download page for tool.  
   `{extension-page}`: Page for extension. *(Must be easy to install from here)*.  
   `{icon}`: Link to icon in `icons/`-folder. *(Must start with `icons/`)*.  
   `{name}`: Name of tool/extension. *(Short if possible)*  
   `{tool-name}`: Name of tool extended by extension.