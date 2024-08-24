---
data: 2024-08-23
related:
  - banco de dados
source: 
tags:
---

```mermaid
graph LR
Mini-Mundo --> Conceitual --> Lógico --> Físico
```
## mini-mundo
Levantamento de requisitos
![[Pasted image 20240823221138.png]]
## modelos conceituais (auto nível)
Descrevem a estrutura de um banco de dados de acordo com a percepção dos usuários independentes de aspectos de implementação.
Ex: modelo entidade - relacionamento
![[Pasted image 20240823221147.png]]

## modelo representativo (lógico)
Descrevem a estrutura de banco de dados da forma como será manipulado pelo SGBDs mais dependentes de aspectos de implementação
ex: modelo relacional, modelo OO

![[Pasted image 20240823221104.png]]
## modelo físico (baixo nível)
Descrevem a estrutura de banco de dados da forma como os dados são fisicamente armazenados totalmente dependestes de aspectos de implementação (registros, blocos, índices, etc.)
ex: implementação específica para um SGBD


