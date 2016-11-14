# Beamer Theme TU Ilmenau
This is a latex presentation (beamer) theme for the technical university in ilmenau.
The images and theme is generally from Institut für Werkstofftechnik. I modified it. 

## Usage
<code>
\input{style/tuilmenau.tex}
</code>

## additional commands

* add reference to the left lower corner

<code latex>
\addcite{reference_name, reference_name2, ...}
</code>

* enable dualview mode
* the generated pdf has the double width, the right one is for notes
* to display this on linux, I'm using "dspdfviewer".

<code latex>
\setDualView
</code>

