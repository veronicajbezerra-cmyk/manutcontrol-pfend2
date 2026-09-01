# ManutControl

Sistema de controle de manutenção da Indústria Atlas, feito para a atividade da disciplina PFEND2.

## Aluno

Veronica de Jesus Bezerra

## Sobre o projeto

O ManutControl foi feito para facilitar o acompanhamento das manutenções da empresa.

Na tela principal, é possível visualizar as ordens de serviço, os equipamentos e algumas informações importantes sobre as manutenções.

Os dados do projeto foram fornecidos pelo professor e estão em um arquivo JSON.

## Tecnologias usadas

* Next.js
* React
* JavaScript
* Tailwind CSS
* JSON

## Funcionalidades

### Indicadores

Na parte superior da tela são mostrados:

* Ordens abertas
* Ordens vencidas
* Equipamentos parados

### Busca e filtros

É possível pesquisar as ordens de serviço e também filtrar os resultados por:

* Status
* Prioridade

Também existe a opção de limpar os filtros.

### Ordens de serviço

A tabela mostra informações como:

* Código da ordem
* Descrição
* Equipamento
* Prioridade
* Técnico
* Vencimento
* Status

As ordens vencidas ficam destacadas para facilitar a visualização.

### Agenda do dia

Mostra as atividades que possuem horário agendado, junto com o equipamento e o técnico responsável.

### Equipamentos críticos

Mostra os equipamentos que precisam de mais atenção, indicando o status e o nível de criticidade.

## Funcionalidade adicionada

Foi usado um indicador de criticidade para facilitar a identificação dos equipamentos que precisam de maior atenção.

A criticidade pode ser:

* Alta
* Média
* Baixa

## Estrutura do projeto

```text
projeto01/
├── public/
├── src/
│   └── app/
│       ├── components/
│       ├── data/
│       │   └── manutcontrol_dados.json
│       ├── globals.css
│       ├── layout.jsx
│       └── page.jsx
├── .gitignore
├── eslint.config.mjs
├── jsconfig.json
├── next.config.mjs
├── package.json
├── package-lock.json
├── postcss.config.mjs
└── README.md
```
