# 📋 PLANO DE TESTE - [SM Style]

---

## 1. 🎯 Objetivo dos Testes

Garantir a perfeita funcionalidade do site com os pré requisitos ja estabelecidos.

---

## 2. 📦 Escopo dos Testes

### ✔️ O que será testado

Liste aqui todas as funcionalidades que serão testadas:

| Funcionalidade               | Descrição                                        |
|-----------------------------|--------------------------------------------------|
| Carrinho                    | Usuário poderá criar carrinho com roupas selecionadas|
| Pagamento                   | Usuário poderá pagar pelas roupas no carrinho        |
| Interface de usuário        | Verificar a usabilidade e responsividade da UI       |
| Cadastro                    | Verificar se usuario é cadastrado corretamente       |

### ❌ O que **não** será testado

Liste funcionalidades que estão fora do escopo deste plano de teste:

| Funcionalidade fora do escopo  | Justificativa                            |
|-------------------------------|-------------------------------------------|
| Segurança                      | Será avaliada em uma fase futura         |
| Moedas diferentes              | Falta de acesso as diferentes moedas     |

---

## 3. ✅ Critérios de Sucesso

Especifique os critérios para considerar o teste como **bem-sucedido**:

| Funcionalidade           | Critério de sucesso                                 |
|--------------------------|-----------------------------------------------------|
| Adicionar no carrinho    | Roupa aparece corretamente na lista após salvar     |
| Editar compra            | Opções diferentes de pagamento devem funcionar corretamente|
| Excluir roupa do carrinho| Roupa removida sem erros                           |
| Registrar usuario novo   | Registro correto e Login funcional                 |

---

## 4. 🧪 Estratégia de Teste

Descreva a abordagem dos testes que serão realizados:

### Tipos de Testes Utilizados:

- [x] Testes Funcionais
- [x] Testes de Interface (UI)
- [x] Testes de Usabilidade

### Método de Execução:

- [ ] Manual
- [ ] Automatizado
- [x] Híbrido

---

## 5. 🧰 Recursos Necessários

### Equipamentos:

| Equipamento        | Especificações mínimas                     |
|--------------------|--------------------------------------------|
|  Celular Android   | Versão 10 ou superior                      |
|  Computador        | Navegador Chrome/Firefox/Opera atualizado  |

### Ferramentas:

| Ferramenta             | Finalidade                             |
|------------------------|----------------------------------------|
|     JUnit              | Testes automatizados                   |

### Equipe Envolvida:

| Função                 | Quantidade | Nome(s) (opcional)       |
|------------------------|------------|--------------------------|
| Testador               |      2      |  Heloisa/Nathalia       |
| Desenvolvedor          |      0      |                         |


---

## 6. 🛠️ Plano de Execução

Descreva como os testes serão realizados na prática.

### Etapas de Execução:

1. Preparação dos ambientes de teste.
2. Instalação da versão de teste do sistema.
3. Execução dos casos de teste manuais.
4. Registro de defeitos encontrados.
5. Análise de resultados.

### Ambiente de Teste:

| Ambiente               | Descrição                                     |
|------------------------|-----------------------------------------------|
| Desenvolvimento        | Versão com novas funcionalidades              |

---

## 7. 📆 Cronograma

Organize o tempo das etapas do teste.

| Atividade                  | Data de Início | Data de Término |
|---------------------------|----------------|-----------------|
| Planejamento do Teste     |   04/06/2025   |04/06/2025 +20 min|
| Preparação do Ambiente    |04/06/2025 +20 min| 05/06/2025    |
| Execução dos Testes       |    05/06/2025  | 9/06/2025       |
| Documentação dos Resultados|   10/06/2025  |    10/07/2025   |

---

## 8. ⚠️ Riscos e Mitigações

Liste possíveis problemas que podem afetar os testes, com planos de ação.

| Risco Identificado                      | Possível Impacto                   | Estratégia de Mitigação                     |
|----------------------------------------|-----------------------------------|---------------------------------------------|
| Incompatibilidade com iOS antigo   | Site não aparece corretamente em alguns aparelhos | Testar em diferentes versões do iOS|
| Falta de dispositivos de teste     | Atraso nos testes manuais         | Uso de emuladores                               |
| Incompatibilidade com Linux        | Site pode não ser acessivel para usuarios de Linux | Testar as diferentes versões do Linux|

---
