# Beamer Theme TU Ilmenau
This is a latex presentation (beamer) theme for the technical university in ilmenau.
The background image from TUIlmenau template is from Institut für Werkstofftechnik. 

## Usage
<code>
\input{style/template.tex}
\usepackage{style/tuilmenau} % for TUIlmenau coperate design
%\usepackage{style/clear} % for a clear design
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

