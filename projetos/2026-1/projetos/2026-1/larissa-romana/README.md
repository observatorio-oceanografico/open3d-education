# Balança Algébrica 3D: Matemática Manipulável

## Integrantes

-Larissa Romana dos Santos 

## Resumo

Este projeto consiste no desenvolvimento de um kit modular de uma Balança Algébrica tátil e funcional, fabricada por meio de impressão 3D. O recurso foi idealizado para mitigar a extrema abstração no ensino de equações de 1º grau no Ensino Fundamental, materializando o conceito de igualdade matemática através do equilíbrio físico de massas. Com este material, o símbolo de igual (=) deixa de ser apenas um comando de ação e passa a ser compreendido visual e taticamente como uma relação de equivalência.

## Objetivo

O objetivo principal é fornecer uma ferramenta pedagógica de código aberto (open-source) para escolas e professores, capaz de demonstrar fisicamente a lógica das operações inversas e a propriedade simétrica das equações, estimulando o aprendizado multissensorial e a inclusão de alunos com diferentes necessidades de aprendizado.

## Descrição do modelo 3D

O modelo foi desenvolvido de forma customizada e modular utilizando a plataforma Tinkercad, sendo otimizado para fabricação sem a necessidade de suportes complexos. O conjunto é composto por quatro partes lógicas:
1. Base Quadrada Estrutural: Projetada com um rebaixo/compartimento oco para inserção de lastro físico (como moedas ou parafusos), garantindo estabilidade e impedindo o tombamento do conjunto.
2. Coluna Central: Torre vertical com encaixe por pressão na base e topo em formato de "U" para o apoio do eixo.
3. Braço Transversal (Alavanca): Haste reta contendo entalhes de posição posicionados simetricamente em relação ao centro para evitar erros de torque.
4. Pratos Suspensos e Pesos: Duas caçambas com alças rígidas integradas e um kit de blocos de peso (Cubos Unidade "1" e Prismas Incógnita "X"). A lógica do modelo prevê cavidades internas nos blocos para abrigar porcas metálicas de forma padronizada, garantindo que o volume geométrico do bloco x corresponda exatamente à proporção de massa de 5 cubos unidade (razão 1:5).

## Arquivos do projeto

- `modelos/base-quadrada.stl`: Base com compartimento de lastro.
- `modelos/coluna-central.stl`: Torre vertical de sustentação.
- `modelos/braço-transversal.stl`: Haste oscilante com ranhuras de posição.
- `modelos/balanca.stl`: balança para equilibrar os blocos.
- `modelos/cubo.stl`: Peso tátil.  
- `imagens/kit-completo.png`: Renderização/fotografia do conjunto montado.
- `documentos/manual-explicativo-uso.pdf`: Roteiro pedagógico com sugestões de dinâmicas para a sala de aula.

## Como visualizar ou imprimir

Os arquivos `.stl` podem ser visualizados diretamente na interface do GitHub ou importados para softwares de modelagem e fatiamento como **OrcaSlicer, Cura, PrusaSlicer, Tinkercad, Blender ou FreeCAD**.

## Imagens

Inclua imagens do modelo, renderizações ou fotos do protótipo.

Exemplo:

![Visualização do Kit no Tinkercad](imagens/kit-completo.png)

## Observações

Limitação de Material: O plástico PLA puro é muito leve, o que reduzia a sensibilidade física da balança. A decisão de projeto de criar cavidades internas para porcas metálicas resolveu o problema da falta de massa inercial.

## Licença e uso

Este material foi produzido para fins educacionais no contexto do repositório `open3d-education`.
