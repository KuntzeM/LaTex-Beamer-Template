# Beamer Theme TU Ilmenau
This is a latex presentation (beamer) theme for the technical university in ilmenau.
The background image from TUIlmenau template is from Institut für Werkstofftechnik. 

## Usage
<code>
\input{style/template.tex}

\usepackage{style/tuilmenau} % for TUIlmenau coperate design

%\usepackage{style/clear} % for a clear design
</code>

## Styles
In the folder style are different files. In "template.text" are implemented generally settings.

You can use "\usepackage{style/tuilmenau}" to use the TU Ilmenau corporate design. The "\usepackage{style/clear}" - package include my simply clear design.

You can copy one of these files to create your own theme!

**important:** you have to change the package name on the top of the file: "\ProvidesPackage{tuilmenau}"

## additional commands

* add reference to the left lower corner

<code latex>
\addcite{reference_name, reference_name2, ...}
</code>

* enable dualview mode
* the generated pdf has the double width, the right one is for notes
* to display this on linux, I'm using "dspdfviewer".
 * for windows is it possible, too.

<code latex>
\setDualView
</code>

