# AtividadePratica5
*Atividade pratica* de **Modelagem e Implementação de Software**

```
for i in range(1,tamSeq1):
    for j in range(1,tamSeq2):
        if(seq1[i-1]==seq2[j-1]):
            result = acerto
        else:
            result = erro
        A = M[i-1][j-1] + result
        B = M[i][j-1]+gap
        C = M[i-1][j]+gap 
        M[i][j] = max(A,B,C)
```

**Requisitos da atividade**
1.  O repositório deve conter um arquivo README com título, texto formatado (itálico e negrito), trecho de código em qualquer linguagem de programação, listagem de tópicos (numerada ou não),  hyperlinks e imagem.
2.  O repositório deve conter, pelo menos, 3 commits.
3.  Enviar o link do Repositório pelo *campus virtual*

[Entender sobre *Markdown*](https://guides.github.com/features/mastering-markdown/)

![Use linux](https://github.com/RenatoPereira2600/AtividadePratica5/blob/main/6b05859c-6659-4ac2-8a59-9fd5a107d8f8.jpg)
