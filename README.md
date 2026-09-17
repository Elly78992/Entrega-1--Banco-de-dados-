# Entrega-1--Banco-de-dados-
## Metadados

- **Nomes dos alunos e RGM**

## 1. Caracterização da Organização
- **Nome e natureza da organização:** 
- **Contexto e porte:** 
- **Problemas e necessidades identificados:**
- **Justificativa da escolha:**
- **Evidências da organização:**

## 2. Processos de Negócio

## 3. Requisitos do Sistema
### 3.1 Requisitos Funcionais
- **RF01(Aceitabilidade de cadastro):** O sistema deve cadastrar celulares e computadores, destacando o modelo, fabricante, endereço IP, numero de serie e data de aquisiçao.
- **RFO2(Registro de garantia):** O sistema deve registrar o período de garantia do equipamento e data de fabricaçao.
- **RF03(Observação dos usuários):** O sistema deve permitir o acesso aos dados dos stakeholders nos equipamentos para observaçoes de uso.
- **RF04(Situação dos equipamentos):** O sistema deve registrar a situação predominante no equipamento, destacando as manutenções realizadas; estoque disponível; descartes e defeitos.
- **RF05(Registro de histórico):** O sistema deve disponibilizar um histórico detalhado de alterações e cadastros dos equipamentos registrados.
- **RF06(Consulta de equipamentos):** O sistema deve permitir a busca e leitura dos equipamentos registrados, alteraçoes manuais dos dados e solicitaçao de estoque.
- **RF07(Registro de suporte Tecnews):** O sistema deve registrar as  solicitações de suporte (N1,N2, Help Desk) para a verificação dos equipamentos.

### 3.2 Requisitos Não Funcionais
- **RN01:** O sistema deve restringir o acesso aos dados e alterações apenas para operadores e administradores autorizados pela empresa.
- **RN02:** O sistema deve garantir que o historico de registro e validaçoes nao haja alteraçoes e exclusao.
- **RN03:** O sistema deve ter um limite de 1.000 linhas de cadastro, garantindo otimizaçao em volumes baixos de leitura e escrita.

## 4. Regras de Negócio
- **Regras operacionais:**
- **RN01:** O acesso dos equipamentos deve ser vinculado a um usuario por vez, contendo seus registros. Em casos de alteraçoes, o sistema deve encerrar o processo anterior antes de registrar um novo dado.
- 
