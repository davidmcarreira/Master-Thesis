# LaTeSe - A template for a master's thesis at the University of Coimbra

<p align="center">
    <a href="https://www.uc.pt/">
        <img src="images/MarcaUC_v.png" width="300">
    </a>
</p>

</br>

---
A template that has the advantage, over others, of:
- Compiling the cover in LaTeX rather that importing an external PDF. This guarantees the proper formatting, fonts, color palette and logo size/resolution.

- Using the \standalone package allows a smoother and faster compilation, since the whole document doesn't need to be compiled, which is a big problem when a lot of graphics are present. The package allows each `.tex` file to be compiled individually while being written and then group compiled when the `main.tex` file is ran. 

</br>

## Requirements for VS Code:
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- Zotero
    - Zotero browser extension
    - [Zotero LaTeX (VS Code extension)](https://marketplace.visualstudio.com/items?itemName=bnavetta.zoterolatex)
- [Optional: LTeX - LanguageTool (VS Code extension)](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex)

## Requirements for Overleaf:
- Untested for now

</br>

## Special macros
- `\red{}` easily colors the text red (useful to indicate placeholders or temporary content).
- `\reffig{}` automatically references mid-text the figure with the correct number and creates a hyperlink to it. Takes as an argument the label of the figure, i.e. `\reffig{fig:label name}`, and outputs (Figure #).
---

# Notes:

- You must compile using XeLatex (or LuaLatex), otherwise the process to change to the required fonts is very cumbursome
- Just install the fonts in your system using the usual `.ttf` format ([Arrus BT](https://www.fonts100.com/font+5384_Arrus+BT.html), [Arrus BT Small Caps](https://freefontsdownload.net/free-arrus_smcap_bt-font-66394.htm) and [Arrus BT Small Caps Bold](http://fonts3.com/fonts/a/Arrus-SmCap-BT-Bold-Small-Cap.html)) 