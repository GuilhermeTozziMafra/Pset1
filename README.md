# Pset1: Processamento de imagens
## Aluno: Guilherme Tozzi Mafra
### Turma: cc3m
### Professor: Abrantes Araújo Silva Filho
#### Esse PSET é uma tradução da primeira tarefa de programação que os alunos da disciplina “MIT 6.009: Fundamentals of Programming” recebem logo no primeiro dia de aula, feita para os alunos da disciplina “Linguagens de Programação” na Universidade Vila Velha (UVV). Neste PSET você ajudará nosso próprio laboratório “CSI: Computer Science Investigation” a construir suas ferramentas para manipulação de imagens. Ao final do PSET você terá escrito o código para inverter, desfocar, aumentar a nitidez e encontrar as bordas em imagens em tons de cinza. Também fornecemos sugestões de outras manipulações de imagens que se baseiam neste PSET (incluindo como trabalhar com imagens coloridas na subseção 9.3), se você quiser expandir ainda maisseu conjunto de ferramentas. Muitos filtros de imagem do mundo real são implementados usando as mesmas ideias que desenvolveremos ao longo deste trabalho.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Questão 1:
       im = pset1.Imagem(4, 1, [29, 89, 136, 200])
            resultado = im.invertida()
            esperado = pset1.Imagem(4, 1, [226, 166, 119, 55])
            self.assertEqual(resultado, esperado)
            
 O output esperado é 226, 166, 119, 55. Pois, será 255 (valor do pixel máximo) - o valor das Arrays.        
            

#### Questão 2:
![nova_bluegill.png](https://github.com/GuilhermeTozziMafra/Pset1/blob/main/imagens_pset1/nova_bluegill.png)
### Questão 3: 
    0.00    -0.07    0.00
    -0.45    1.20    -0.25
    0.00    -0.12    0.00

             X

    80      53       99
    129    127      148
    175    174      193

    = 80 x 0.00 +    53 x (-0.07) +    99 x 0.00 +
    129 x (-0.45) +    127 x 1.20 +    148 x (-0.25) +
    175 x 0.00 +    174 x (-0.12) +    193 x 0.00
    =  32,76


#### Questão 4:
![nova_pigbird.png](https://github.com/GuilhermeTozziMafra/Pset1/blob/main/imagens_pset1/nova_pigbird.png)

#### Questão 5:

#### Questão 6:

#### Questão Extra:
![nova_cat.png](https://github.com/GuilhermeTozziMafra/Pset1/blob/main/imagens_pset1/nova_cat.png)
