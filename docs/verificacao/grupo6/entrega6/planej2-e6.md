# Planejamento da Verificação da Etapa 6 do Grupo

## Introdução

O artefato visa apresentar o planejamento para a verificação de cada artefato da etapa 6 do projeto do [grupo 6](https://github.com/Requisitos-de-Software/2024.2-MeuINSS).


## Objetivos

O objetivo deste documento é verificar se os artefatos produzidos para entrega 6 do [grupo 6](https://github.com/Requisitos-de-Software/2024.2-MeuINSS) possuem os itens e o padrão exigidos. É importante citar que essa verificação em momento nenhum busca diminuir os membros responsáveis seu trabalho, apenas aplicar os conceitos de verificação.

## Metodologia

A metodologia escolhida para esta verificação é uma adaptação da inspeção. Desenvolvida originalmente para códigos de software por Fagan na IBM em 1976, essa técnica consiste em uma revisão formal dos artefatos produzidos a fim de se encontrar defeitos, a figura 1 exemplifica as etapas que Fagan propôs para esse processo.

<center>

**Figura 1** - Etapas da Inspeção de acordo com Fagan.

<style>
img[alt="inspecaofagan"] {
    background-color: white;
    padding: 10px;
    border-radius: 5px;
}
</style>

![inspecaofagan](../../../assets/inspecao-fagan.png)

_Fonte: SOMMERVILLE (2007)._ <a id="anchor_5" href="#REF5"><sup>1</sup></a>

</center>

### Objetos da Verificação

Os artefatos alvos dessa verificação são:

- [Matriz de Rastreabilidade](https://requisitos-de-software.github.io/2024.2-MeuINSS/rastreabilidade/matriz/) na versão 1.6 de data 19/01/2025, produzido por [Todos integrantes](../../../../) com revisão de [Maurício Ferreira](https://github.com/mauricio-araujoo), [Ana Catarina Santos](https://github.com/an4catarina) e [Nicolas Bomfim](https://github.com/nickgehjk)
- [Foward-From](https://requisitos-de-software.github.io/2024.2-MeuINSS/rastreabilidade/foward/) na versão 1.0 de data 19/01/2025, produzido por [Júlia Fortunato](https://github.com/julia-fortunato), [Cristiano Morais](https://github.com/CristianoMoraiss) e [Maurício Ferreira](https://github.com/mauricio-araujoo), com revisão de [Ana Catarina Santos](https://github.com/an4catarina).
- [Backward-From](https://requisitos-de-software.github.io/2024.2-MeuINSS/rastreabilidade/backward-from/) na versão 1.0 de data 19/01/2025, produzido por [Ana Catarina Santos](https://github.com/an4catarina) e [Nicolas Bomfim](https://github.com/nickgehjk) com revisão de [Maurício Ferreira](https://github.com/mauricio-araujoo).

### Cronograma

A tabela 1 a seguir, apresenta o cronograma das atividades a serem realizadas.


<center>

**Tabela 1** - Cronograma das Atividades.

| Data       | Descrição                    | Responsável                                 |
| ---------- | ---------------------------- | ------------------------------------------- |
|  27/01/2024| Verificação Matriz de Rastreabilidade | [Victor Schmidt](https://github.com/moonshinerd) e [Thales Euflauzino](https://github.com/thaleseuflauzino) |
| 27/01/2024 | Verificação Foward-From |[Victor Schmidt](https://github.com/moonshinerd) e [Thales Euflauzino](https://github.com/thaleseuflauzino)  |
| 27/01/2024 | Verificação Backward-From |  [Victor Schmidt](https://github.com/moonshinerd) e [Thales Euflauzino](https://github.com/thaleseuflauzino)|
| 27/01/2024| Adição dos resultados.       |  [Victor Schmidt](https://github.com/moonshinerd) e [Thales Euflauzino](https://github.com/thaleseuflauzino)|

_Autor: [Thales Euflauzino](https://github.com/thaleseuflauzino), 2025_

</center>

### Geral

<center>

**Tabela 2** - Lista de Verificação dos Itens do Planejamento Geral do projeto .

|        ID        | Descrição                                                                                                           | Avaliação  |
| :--------------: | ------------------------------------------------------------------------------------------------------------------- | :--------: | 
| 1 | O histórico de versão padronizado? | - |
| 2 | O(s) autor(es) e o(s) revisor(es) para o artefato? | - |
| 3 | Referências bibliográficas e/ou bibliografia do artefato? | - |
| 4 | As tabelas e imagens possuem legenda e fonte e elas chamadas dentro dos texto? | - |
| 5 | Um texto fazendo uma introdução do artefatos? | - |

_Autores: Equipe do Projeto, 2025._

</center>


### Matriz de Rastreabilidade

<center>

**Tabela 3** - Lista de Verificação dos Itens do Matriz de Rastreabilidade.

|        ID        | Descrição                                                                                                           | Avaliação  |
| :--------------: | ------------------------------------------------------------------------------------------------------------------- | :--------: | 
| 6 | Os requisitos foram ligados aos artefatos correspondentes (na matriz geral)? | - |
| 7 | Os requisitos são rastreáveis ao longo de todo o ciclo de vida do sistema? | - |
| 8 | O artefato esta conectado entre si por meio de hyperlinks? | - |
| 9 | Na matriz de rastreamento, os artefatos iniciais estão representados nas linhas e os artefatos-alvo nas colunas? | - |


_Autores: Equipe do Projeto, 2025._

</center>


### Foward-From

<center>

**Tabela 4** - Lista de Verificação dos Itens do Foward-From.

|        ID        | Descrição                                                                                                           | Avaliação  |
| :--------------: | ------------------------------------------------------------------------------------------------------------------- | :--------: | 
| 6 | Existem elos do tipo: Satisfação, Recurso, Responsabilidade, Representação, Alocado e Agregação? | - |
| 7 | As informações rastreadas foram classificadas nos quatro níveis a seguir? Ambiental, Organizacional, Gerencial e Desenvolvimento? | - |
| 8 | O artefato esta conectado entre si por meio de hyperlinks? | - |
| 9 | Forward From: liga os requisitos a artefatos de desenho e implementação? | - |


_Autores: Equipe do Projeto, 2025._

</center>



### Backward-From

<center>

**Tabela 5** - Lista de Verificação dos Itens de Backward-From.

|        ID        | Descrição                                                                                                           | Avaliação  |
| :--------------: | ------------------------------------------------------------------------------------------------------------------- | :--------: | 
| 6 | Existem elos do tipo: Satisfação, Recurso, Responsabilidade, Representação, Alocado e Agregação? | - |
| 7 | As informações rastreadas foram classificadas nos quatro níveis a seguir? Ambiental, Organizacional, Gerencial e Desenvolvimento? | - |
| 8 | O artefato esta conectado entre si por meio de hyperlinks? | - |

_Autores: Equipe do Projeto, 2025._

</center>



## Bibliografia
> SOMMERVILLE, Ian. **Engenharia de software.** 08. ed. São Paulo: Pearson Addison Wesley, 2007
>
> SERRANO, MAURÍCIO; SERRANO, Milene. **Slides da aula Requisitos – Aula 04**. Acesso em: 02 de novembro de 2024.
>
> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. s.d. Acesso em: 17 jan. 2025
>
> SALES, André Barros. Plano de Ensino. Aprender 3. Distrito Federal, 2024. Acesso em 04 dez. 2024.
>

## Histórico de Versões

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| -------- | ------ | ------ | ---------- | ---------- |
| `1.0` | 17/01/2025 | Criação do documento  | [Thales Euflauzino](https://github.com/thaleseuflauzino) | [Víctor Schmidt](https://github.com/moonshinerd)  | [Victor Rodrigues](https://github.com/ViictorHugoo) |
