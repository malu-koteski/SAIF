# SAIF – Sistema de Fiscalização de Animais Intrusos e Fugitivos

## Descrição

O SAIF (Sistema de Fiscalização de Animais Intrusos e Fugitivos) é um projeto desenvolvido na Universidade Federal de São Paulo para monitoramento de galinheiros de pequeno porte. O sistema tem como objetivo identificar possíveis invasões de predadores e fugas de galinhas por meio da análise de dados provenientes de sensores de movimentação, peso e ruído.

Este repositório contém os arquivos de simulação do sistema em formato `.panda`, utilizados para representar e validar os circuitos digitais desenvolvidos para o projeto.

## Requisitos

Para abrir e executar os arquivos do projeto, é necessário:

* Possuir o simulador compatível com arquivos `.panda` instalado em seu computador;
* Caso não possua o Wired Panda, faça a instalação do software via https://gibis-unifesp.github.io/wiRedPanda/pt-br/download/;
* Sistema operacional Windows, Linux ou macOS;
* Permissão de leitura e escrita na pasta do projeto.

## Como Executar os Arquivos `.panda`

1. Faça o download ou clone este repositório:

```bash
git clone https://github.com/seu-usuario/SAIF.git
```

2. Abra o simulador compatível com arquivos `.panda`.

3. No simulador, selecione:

```text
Arquivo → Abrir
```

4. Navegue até os arquivos.

5. Selecione o arquivo `.panda` desejado e clique em **Abrir**.

## Arquivos de Simulação

* Arquivos: implementam módulos utilizados pelo SAIF.

## Funcionamento Geral do Sistema

1. Os sensores monitoram continuamente o ambiente.
2. Os sinais são processados pelos circuitos digitais.
3. O sistema determina se há:

   * presença de intrusos;
   * fuga de galinhas;
   * condições normais de operação.
4. As saídas são acionadas conforme a lógica definida:

   * atualização da contagem de galinhas;
   * acionamento dos alarmes sonoros;
   * ativação do dispositivo sonoro de alta frequência.

## Autores

Projeto desenvolvido por:

* André Miléo Mendonça
* Maria Luisa Koteski Bustamante de Melo
* Vitoria Elena de Melo Cenatti
* Victor Eduardo da Silva
* Equipe do projeto SAIF

## Licença

Este projeto possui finalidade acadêmica e educacional. Sua utilização, modificação e distribuição são permitidas mediante a devida atribuição aos autores.
