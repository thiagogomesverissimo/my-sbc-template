## my-sbc-template

Template da Sociedade Brasileira de Computação disponível em:

https://www.sbc.org.br/documentos-da-sbc/summary/169-templates-para-artigos-e-capitulos-de-livros/878-modelosparapublicaodeartigos

Porém organizado de uma forma mais desacoplada.

## Exemplos

Exemplo de como converter um notebook em python para um arquivo .tex:

    jupyter nbconvert --to markdown meu_lindo_notebook.ipynb
	pandoc --listings -f markdown -t meu_lindo_notebook.md -o meu_lindo_notebook.tex
