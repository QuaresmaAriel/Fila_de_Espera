# 📋 Sistema de Fila de Espera - Lazzarella

Este software foi projetado para resolver de forma simples e direta o fluxo de recepção do restaurante Lazzarella. 
Diferente de sistemas complexos, ele foca na agilidade da operação manual, utilizando a lógica de **Pagers Físicos** para organizar a espera de mesas sem distrações tecnológicas para o cliente.

## 🚀 O que torna o sistema eficiente?

* **Operação em Cliques:** O fluxo foi desenhado para que o recepcionista gaste o mínimo de tempo possível no cadastro, focando apenas no essencial: Telefone, Nome e Pager.
* **Reconhecimento de Clientes:** Ao digitar o telefone, o sistema identifica automaticamente se o cliente já é da casa, exibindo o histórico de visitas e facilitando um atendimento personalizado.
* **Sincronização Simples:** Todos os dados são salvos diretamente no navegador (LocalStorage), garantindo que a fila não se perca mesmo se a página for fechada acidentalmente.
* **Fila Visual e Limpa:** A tela de espera mostra apenas o primeiro nome, a quantidade de pessoas e o número do pager, permitindo uma batida de olho rápida para a tomada de decisão.
* **Controle Administrativo:** Uma área restrita por senha permite gerenciar o banco de dados de clientes, editar informações ou remover registros antigos com total facilidade.

## 🛠️ Tecnologias de Base

* **Lógica de Front-end:** JavaScript puro (ES6+) para manipulação dinâmica da fila e validações de segurança.
* **Persistência de Dados:** Web Storage API para armazenamento local rápido e sem custo de servidor.
* **Interface:** CSS estruturado para leitura clara em tablets ou desktops na recepção.

## 📂 Organização dos Arquivos

* `index.html`: Porta de entrada com login administrativo.
* `cadastro.html`: Onde a mágica acontece (Verificação e Inclusão na Fila).
* `fila.html`: Painel operacional para chamar ou remover clientes.
* `clientes.html`: Gestão completa (CRUD) dos dados de fidelidade.

## ⚙️ Como Utilizar

O sistema é extremamente leve e não exige instalação:
1. Baixe os arquivos do repositório.
2. Abra o `index.html` em seu navegador de preferência.
3. Para acessar a base de dados, utilize a senha de administrador configurada no script inicial.

---
**Desenvolvido por Ariel Quaresma** *Foco em UX para hospitalidade e automação de processos físicos.*
