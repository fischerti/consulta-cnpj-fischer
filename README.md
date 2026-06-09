# Central de Consulta CNPJ — Fischer®

Sistema web corporativo desenvolvido para consulta rápida, organizada e executiva de informações cadastrais de empresas por meio do CNPJ.

O projeto foi criado para apoiar os setores de **Compras, Fiscal, Contabilidade, Vendas e Cadastros**, centralizando em uma única tela dados cadastrais, fiscais, societários e operacionais retornados por uma base pública de consulta.

---

## Visão Geral

A **Central de Consulta CNPJ — Fischer®** permite consultar um CNPJ e visualizar as principais informações da empresa de forma clara, responsiva e pronta para uso corporativo.

O sistema foi desenvolvido em **HTML, CSS e JavaScript puro**, sem necessidade de instalação de dependências, banco de dados ou servidor próprio.

---

## Funcionalidades

- Consulta de CNPJ em base pública.
- Máscara automática no campo de CNPJ.
- Validação real dos dígitos verificadores do CNPJ.
- Exibição dos dados principais da empresa.
- Organização das informações em blocos visuais.
- Exibição de razão social, nome fantasia, situação cadastral, natureza jurídica, porte e capital social.
- Exibição de endereço, contato, CNAE principal e atividades secundárias.
- Exibição de inscrições estaduais, quando disponíveis.
- Exibição de quadro societário, quando retornado pela API.
- Botão para copiar CNPJ.
- Botão para copiar JSON completo.
- Visualização do JSON retornado pela API.
- Botão para geração de PDF/impressão.
- Relógio em tempo real no cabeçalho.
- Rodapé institucional com direitos reservados.
- Layout responsivo para computadores, notebooks, tablets e celulares.

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- GitHub Pages
- API pública CNPJ.ws

---

## Estrutura do Projeto

```text
consulta-cnpj-fischer/
│
├── index.html
└── README.md
```

### `index.html`

Arquivo principal do sistema. Contém toda a estrutura da página, estilos, scripts, validações e integração com a API.

### `README.md`

Arquivo de apresentação e documentação inicial do projeto.

---

## Como Acessar

O sistema pode ser acessado pelo GitHub Pages:

```text
https://fischertidev-afk.github.io/consulta-cnpj-fischer/
```

---

## Como Publicar no GitHub Pages

1. Criar um repositório no GitHub.
2. Adicionar o arquivo principal com o nome:

```text
index.html
```

3. Acessar:

```text
Configurações > Pages
```

4. Em **Build and deployment**, selecionar:

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

5. Salvar e aguardar a publicação.

---

## Como Atualizar o Sistema

Para atualizar a página publicada:

1. Acesse o repositório no GitHub.
2. Substitua o arquivo `index.html` pela nova versão.
3. Faça o commit da alteração.
4. Aguarde o GitHub Pages republicar o site automaticamente.

---

## Observação sobre os Dados

As informações exibidas são retornadas por uma base pública de consulta CNPJ.

Antes de qualquer decisão fiscal, cadastral, contábil, comercial ou administrativa, os dados devem ser conferidos conforme os procedimentos internos da empresa.

---

## Finalidade

Este sistema tem como objetivo facilitar a consulta e conferência de dados empresariais, tornando o processo mais rápido, padronizado e acessível para os setores internos da Fischer.

---

## Identidade Visual

O sistema utiliza a identidade visual da **Fischer®**, com layout corporativo, cores institucionais e apresentação profissional.

---

## Direitos Reservados

**Fischer® 2026 — Todos os direitos reservados.**
