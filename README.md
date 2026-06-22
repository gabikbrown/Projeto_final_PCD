![Imagem](Cabecalho.png)

<div align="center">
  
# Visualizador de Gradiente 3D
</div>
 
Projeto desenvolvido para a matéria de Prática em Ciência de Dados, ministrada pelos professores Dr. Daniel Roberto Cassar, Dr. James Moraes de Almeida e Dr. Leandro Nascimento Lemos. O trabalho consistiu em desenvolver um programa em Python que demonstrasse o domínio e consolidação dos conceitos abordados no primeiro semestre do curso de Ciência e Tecnologia. Dessa forma, optei por desenvolver um visualizador de gradiente, dada algumas das principais funções utilizadas na disciplina de Cálculo 3. 

## Bibliotecas utilizadas
- `Numpy` foi importado para realizar operações matemáticas 
- `Sympy` foi importado para transformar strings, como "x" e "y", em símbolos para serem manipulados matematicamente
- `Matplotlib` foi importado para criar gráficos
- `Axes3D` foi importado para desenhar gráficos em 3D, especificamente 

**Descrição do projeto
Este código tem por objetivo construir uma ferramenta que, a partir de uma função real de duas variáveis $f(x,y)$ e de um ponto $(x, y)$ do domínio, seja capaz de:
- Calcular simbolicamente as derivadas parciais de $x$ e $y$ por meio da biblioteca `Sympy`
- Exibir o vetor gradiente em dois pontos escolhidos pelo usuário
- Determinar o módulo do gradiente no ponto analisado
- Produzir uma visualização tridimensional da superfície $z = f(x,y)$, com o ponto analisado destacado e o vetor gradiente projetado sobre ela.

Para isso, necessita-se das bibliotecas `Numpy` para operações numéricas e para geração da malha, `Sympy` para diferenciação simbólica e conversão numérica por meio do módulo `lambdify`. Além disso, para parte gráfica, é empregado o `Matplotlib` para a renderização da superfície bem como do vetor com os módulos `plot_surface` e `quiver`

## Acesso ao projeto 
Você pode [acessar o código fonte do projeto](http://localhost:8888/lab/tree/James/ProjetoFinalPCD.ipynb) ou [baixá-lo](http://localhost:8888/files/James/ProjetoFinalPCD.ipynb?_xsrf=2%7Cbb372380%7Ca712f182f1fce7c9e326f06dde87e171%7C1781466553) 
## Abrir e rodar o projeto 
Para rodar o projeto, basta entrar no código fonte e rodá-lo.
Ou ainda, baixar o projeto e rodá-lo em ambiente Jupyter.
## Bibliotecas utilizadas
- numpy
- sympy
- matplotlib
## Professores
<table>
  <tr>
    <td align="center">
      <a href="#" title="Prof. Daniel R. Cassar">
        <img src="https://avatars.githubusercontent.com/u/9871905?v=4" width="100px;" alt="Foto do Daniel do Github"/><br>
          <a href="https://github.com/drcassar"><b>Prof. Dr. Daniel R. Cassar<b></a>
      </a>
    </td>
    <td align="center">
      <a href="#" title="Prof. James M. de Almeida">
        <img src="https://avatars.githubusercontent.com/u/108157661?v=4" width="100px;" alt="Foto do James do Github"/><br>
          <a href="https://github.com/jamesmalmeida"><b>Prof. Dr. James M. de Almeida<b></a>
      </a>
    </td>
    <td align="center">
      <a href="#" title="Prof. Leandro N. Lemos">
        <img src="https://avatars.githubusercontent.com/u/1894434?v=4" width="100px;" alt="Foto do Leandro do Github"/><br>
          <a href="https://github.com/llemos"><b>Prof. Dr. Leandro N. Lemos<b></a>
      </a>
    </td>
  </tr>
</table>

## Autores 
[Gabriela Cabral ](https://github.com/gabikbrown)
