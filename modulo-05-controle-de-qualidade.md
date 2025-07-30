# Módulo 5: Controle de Qualidade

**Instrutor:** 3º Sgt Gustavo Pereira

## Objetivos de Aprendizagem
- [ ] Compreender o Workflow Toolbox
- [ ] Construir modelos usando o model helper
- [ ] Compreender especificidades dos modelos
- [ ] Montar workflows completos
- [ ] Executar workflows existentes
- [ ] Trabalhar com modalidades de tratamento

## Pré-requisitos
> **📋 Pré-requisito:** Todos os módulos anteriores concluídos

## 1. Workflow Toolbox
 **Introdução**
Neste módulo, será apresentado o uso da ferramenta **Workflow Toolbox** do DSGTools, responsável pela automação e padronização de processos de controle de qualidade de dados geoespaciais. A ferramenta permite o encadeamento de algoritmos (Modelos) e o monitoramento de execuções, otimizando o tempo e reduzindo erros.

### 1.1 Conceitos Fundamentais
O Workflow Toolbox é a ferramenta de validação de dados geoespaciais do plugin DSGTools. Sua principal finalidade é garantir que os dados obedeçam a uma padronização previamente definida, por meio da execução de fluxos compostos pelo próprio usuário, a partir da combinação de Modelos (ou models), que representam processos ou algoritmos específicos. Cada modelo executa uma tarefa pontual, como verificar topologias, validar atributos ou checar relações espaciais. A junção desses modelos em uma sequência controlada constitui o workflow.
A utilização do Workflow Toolbox possibilita:
- Automatizar rotinas de validação que, manualmente, seriam longas e sujeitas a erros;
- Aplicar regras padronizadas a diferentes conjuntos de dados;
- Registrar exceções e idenficar inconsistências;
- Facilitar o controle de qualidade

A construção dos modelos será abordada detalhadamente na Unidade 2 deste módulo..

### 1.2 Arquitetura do Sistema
A arquitetura do Workflow Toolbox foi desenvolvida para oferecer flexibilidade, modularidade e controle durante os processos de validação de dados geoespaciais. A ferramenta está estruturada em três componentes principais:

- **Modelos (Models)**: São unidades funcionais que executam tarefas específicas, como checagens topológicas, análise de atributos, validações geométricas ou relacionais. Cada modelo pode ser reutilizado em diferentes workflows.

- **Workflows**: Representam a sequência lógica de execução dos modelos. São compostos por etapas interligadas, nas quais a saída de um modelo pode servir como entrada para o próximo. A ordem de execução, as dependências e as configurações são definidas pelo usuário.

- **Gerenciador de Execução (ferramenta do DSG tools)** : Responsável por controlar o andamento do workflow. Monitora o status de cada etapa (pendente, em execução, concluída ou com erro), permite pausas, retomadas, reexecuções e registro das exceções.
  
### 1.3 Interface do Usuário
A interface do Workflow Toolbox foi projetada para oferecer uma experiência visual clara e funcional durante a configuração e execução dos workflows. A ferramenta é acessada por meio do menu do DSGTools, dentro do ambiente do QGIS.

A interface principal é composta pelos seguintes elementos:

- 1- Painel de Workflows: localizado no topo da tela, exibe os workflows disponíveis no projeto, permitindo selecionar, abrir e criar novos fluxos de validação.

- 2- Visualizador de Etapas: ao selecionar um workflow, é apresentada uma visualização sequencial das etapas (modelos) que o compõem, com indicadores de status (✔️ concluído, ⏳ em execução, ❌ com erro, etc.).

- 3- Permite ao usuário adicionar ou remover workflows, além de visualizar e editar os parâmetros e modelos utilizados na execução. Entre as opções disponíveis, é possível configurar ações como: interromper após a execução, permitir falsos positivos, definir o comportamento da camada de saída, entre outras.

- 4- Barra de Ações (parte inferior): disponibiliza botões para iniciar, pausar e retomar a execução a partir do último modelo processado.

<img src="assets/modulo-05/img-interface-workflow.png" alt="Interface do Workflow Toolbox no QGIS" width="500"/>
      
  *Figura 1.0: Interface Workflow Toolbox no QGIS*

### 1.4 Integração com QGIS Processing

## 2. Como Montar os Models

### 2.1 Model Helper
#### 2.1.1 Funcionalidades do Model Helper
#### 2.1.2 Assistente de Criação
#### 2.1.3 Templates e Configurações

### 2.2 Especificidades dos Modelos

## 3. Como Montar o Workflow

## 4. Executar um Workflow Existente

## 5. Modalidades de Tratamento

### 5.1 Falso Positivo

### 5.2 Voltar Etapa

### 5.3 Salvar no Projeto

### 5.4 Outras Modalidades

## Resumo
- O Workflow Toolbox automatiza processos de controle de qualidade
- A construção de modelos permite customização para necessidades específicas
- O monitoramento garante execução confiável
- As modalidades de tratamento oferecem flexibilidade no processo



## Material Complementar
- [Guia do Workflow Toolbox](https://exemplo.com)
- [Biblioteca de Modelos](https://exemplo.com)
