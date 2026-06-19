![Imagem](Cabecalho.png)

<div align="center">
  
# Visualizador de Gradiente 3D
</div>

## Introdução 
Projeto desenvolvido para a matéria de Prática em Ciência de Dados, ministrada pelos professores Dr. Daniel Roberto Cassar, Dr. James Moraes de Almeida e Dr. Leandro Nascimento Lemos. O trabalho consistiu em desenvolver um programa em Python que demonstrasse o domínio e consolidação dos conceitos abordados no primeiro semestre do curso de Ciência e Tecnologia. Dessa forma, optei por desenvolver um visualizador de gradiente, dada algumas das principais funções utilizadas na disciplina de Cálculo 3. 

## Objetivos 
Este código tem por objetivo criar uma ferramenta que, a partir de uma função real de duas variáveis $f(x,y)$ e de um ponto $(x, y)$ do domínio, calcula as derivadas parciais, monta o vetor gradiente, determina seu módulo no ponto escolhido e produz uma vizualisação tridimensional da superfície junto com o ponto analisado e a projeção do vetor gradiente sobre ela. 

## Fundamentação teórica do projeto
Na matemática, dada uma função diferenciável $f(x,y)$, o gradiente é o vetor formado pelas suas derivadas parciais: 

$$\nabla f(x, y) = \left( \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y} \right)$$

Geometricamente, esse vetor aponta na direção em que $f$ cresce mais rapidamente a partir do ponto considerado, e seu módulo $|\nabla f| = \sqrt{f_x^2 + f_y^2}$, mede a taxa de crescimento nessa direção. Em qualquer ponto, o gradiente é ortogonal à curva de nível que passa por esse ponto, por isso, ao projetá-lo sobre a superfície tridimensional, ele indica visualmente o caminho de subida mais inclinado.

## Resultados 
Os resultados obtidos pelo projeto foram favoráveis às expectativas, uma vez que após testes realizados foi possivel calcular assim como visualizar o gradiente e seu módulo em um gráfico 3D. 
