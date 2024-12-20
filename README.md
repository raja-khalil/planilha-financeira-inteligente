# Projeto de Planilha Inteligente em VBA

Este projeto foi desenvolvido como parte de um exercício para um bootcamp. O objetivo era criar uma planilha inteligente utilizando VBA, mesmo sem conhecimento prévio da linguagem.

## Objetivo

O objetivo principal deste projeto foi construir uma planilha em Excel com várias funcionalidades automatizadas através de macros VBA, incluindo:

- Criação de 10 abas com diferentes propósitos
- Tabelas dinâmicas
- Uma aba de dashboard com gráficos
- Automação de tarefas repetitivas

## Processo de Desenvolvimento

### 1. Criação das Abas
- Abas criadas: `Transações`, `Contas`, `MembrosFamilia`, `TiposRenda`, `ListaSuspensa`, `Dashboard`, entre outras.
- Cada aba possui uma função específica, facilitando a organização e análise dos dados.

### 2. Configuração de Listas Suspensas
- Utilização de listas suspensas para facilitar a entrada de dados, especialmente nas colunas `Categoria`, `ID Membro Família` e `ID Tipo Renda`.
- Validação de dados para garantir a consistência das entradas.

### 3. Automação com VBA
- Implementação de macros para automatizar a criação de listas suspensas, formatação de colunas, e inserção de dados.
- Sub-rotinas principais:
    - `CriarAbaFormTransacoes`: Cria a aba do formulário para entrada de dados.
    - `EnviarTransacao`: Transfere os dados do formulário para a aba `Transações`.
    - `LimparCamposTransacao`: Limpa os campos do formulário após a inserção.

### 4. Dashboard
- Criação de uma aba de dashboard com gráficos dinâmicos para visualização e análise dos dados.
- Utilização de tabelas dinâmicas para facilitar a manipulação e visualização das informações.

## Funcionalidades Implementadas

- **Formulário de Entrada de Dados**: Facilita a inserção de novas transações com validação de dados e listas suspensas.
- **Automação de Tarefas**: Macros automatizadas para formatação de colunas, inserção de dados e geração de gráficos.
- **Dashboard**: Visualização gráfica dos dados inseridos, permitindo uma análise rápida e eficaz.

## Próximos Passos

Apesar de a planilha estar funcional, ainda são necessários alguns ajustes para aprimorar a experiência do usuário e garantir a precisão dos dados. As próximas etapas incluem:

- Refinamento das tabelas dinâmicas
- Melhoria dos gráficos no dashboard
- Testes adicionais para garantir a robustez das macros
- Implementação de novas funcionalidades conforme necessário

## Conclusão

Mesmo sem conhecimento prévio de VBA, foi possível, com o auxílio do Microsoft Copilot, criar uma planilha inteligente e funcional, demonstrando que a tecnologia pode ser uma poderosa aliada no aprendizado e desenvolvimento de novas habilidades.


