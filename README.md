

# Dashboard de Gestão Audiovisual

## Sobre o Projeto

O projeto Dashboard de Gestão de Marketing Audiovisual propõe a criação de um painel interativo de visualização de dados, desenvolvido na plataforma Looker Studio. O principal objetivo do projeto é centralizar e estruturar os dados dispersos em uma base organizada, permitindo análises consistentes e apoiando a tomada de decisão estratégica da equipe.

Como o trabalho e conteúdo é feito semanalmente com diversos fabricantes e modelos diferentes de carro, a análise eficiente de como está o andamento se torna essencial para o funcionamento de todas as vertentes da produtora de conteúdo.

🔗 **[Acesse o Dashboard Interativo no Looker Studio](https://lookerstudio.google.com/reporting/1ff40bf8-f416-4863-b083-d60de7ac8776)** 

<img width="2091" height="1561" alt="image" src="https://github.com/user-attachments/assets/5c9734c5-f67f-4e85-a9cf-f4a874cc2cf7" />


## O Motivo

### Os dados sempre foram muito dispersos e isso sempre causou problemas organizacionais para toda a equipe.

* O armazenamento dessas informações era feito de forma rudimentar através de mensagens no WhatsApp e ClickUp.


* Os dados eram guardados de uma forma desorganizada, em uma lista de texto simples e sem especificar período, categoria, marca, etc.


* Sempre existia um debate na equipe sobre qual iria ser a próxima empresa que iremos contatar para pegar um carro de teste.



## A Solução

Para organizar o passivo de informações e preparar o terreno para o futuro, os dados foram transformados em um arquivo CSV a partir de um arquivo TXT.

* O arquivo CSV se transformou em uma planilha no Sheets.


* Essa planilha está ligada diretamente ao Looker Studio para que quando ocorra uma nova inserção de dados o dashboard se atualize automaticamente.



### Os dados foram padronizados nas seguintes dimensões principais:

**Modelo e Marca do carro:** Indica o modelo específico e a fabricante do veículo testado.

**Data Empréstimo:** Indica a data de empréstimo do carro (Essencial para organizar as avaliações e postagens).

**Links de Conteúdo:** Endereçamento direto para Reels, Carrosseis e demais conteúdos postados.


## Estrutura do Dashboard

O dashboard nasceu da ideia de que organização e eficiência geram mais produtividade e decisões mais fáceis. A interface foi dividida em duas frentes:

### 1. Visão Geral (Página 1)

A primeira página foca mais em uma visão geral das marcas e conteúdos gerados ao longo do tempo.
 
**KPIs Iniciais:** O primeiro contato do usuário é com os indicadores-chave (KPIs) mostrando a quantidade total de carros testados e a quantidade de marcas.

**Interatividade Dinâmica:** A interatividade entre os gráficos é essencial; caso o usuário clique em "FIAT" em uma tabela, logo à direita temos um gráfico em linhas do conteúdo gravado ao longo do tempo que se atualiza.

**Prevenção de Repetições:** Ao lado temos uma tabela importante que mostra os carros que já foram repetidos, ela serve de grande aviso para que esses carros sejam evitados por um período de tempo.



### 2. Conteúdos Específicos (Página 2)

A segunda página é focada nos conteúdos específicos.

**Controlador de Filtro:** Criei um controlador no topo da página que permite ao usuário escolher sobre qual conteúdo específico ele quer ver os dados.

**Proporção e Volume:** Conta com um gráfico em pizza mostrando a proporção de tal conteúdo por marca e KPIs mostrando o volume da produção de cada conteúdo.



## Ferramentas

**Looker Studio:** Data Storytelling e criação de painéis interativos.

**Google Sheets:** Estruturação, limpeza e espelhamento de dados.
 
**Business Intelligence:** Definição de KPIs, análise de gargalos operacionais e suporte à tomada de decisão.



---
