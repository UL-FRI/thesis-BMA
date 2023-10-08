## How to compile the project in Overleaf

1. Open `thesis_template.tex`
2. Open "Menu" on the top left
3. Set "TeX Live version" to "2020 (Legacy)"
4. Recompile
5. (Optional) If the whole text is marked red (Overleaf can't find \begin{document}):
     - Copy the contents from `style/thesis_front_pages.tex` into `thesis_template.tex` on line "\input{style/thesis_front_pages}"
     - Delete "\input{style/thesis_front_pages}"
