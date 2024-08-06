# Memoria-TFG

Configuración de settings.json extraída del chatgpt para que funcione bien:

"latex-workshop.latex.outDir": "%DIR%/out",
"latex-workshop.latex.tools": [
    {
        "name": "pdflatex",
        "command": "pdflatex",
        "args": [
            "-synctex=1",
            "-interaction=nonstopmode",
            "-file-line-error",
            "-output-directory=%OUTDIR%",
            "%DOC%"
        ]
    }
],
"latex-workshop.latex.recipes": [
    {
        "name": "pdflatex",
        "tools": [
            "pdflatex"
        ]
    }
],
"latex-workshop.view.pdf.viewer": "tab"