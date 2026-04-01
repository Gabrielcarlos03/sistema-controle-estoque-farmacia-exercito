# 🏥 Sistema de Controle de Estoque Farmacêutico — Exército Brasileiro

Sistema completo de gestão de medicamentos desenvolvido e aplicado em ambiente real na farmácia do Exército Brasileiro. O projeto automatiza o controle de atendimentos, estoque, validade e consumo de mais de 50 medicamentos, eliminando registros manuais e garantindo rastreabilidade completa.

---

## 📋 Sobre o Projeto

O sistema nasceu de uma necessidade real: organizar e automatizar o controle de medicamentos de uma farmácia militar com múltiplas subnidades atendidas diariamente.

A solução foi desenvolvida do zero — da ideia à aplicação — integrando um formulário de atendimento com uma planilha automatizada por fórmulas, sem necessidade de intervenção manual após cada registro.

Todo o design e identidade visual também foram criados pelo desenvolvedor.

---

## ⚙️ Como Funciona

1. O atendente preenche o **Google Forms** com os dados do atendimento
2. As respostas alimentam a planilha **automaticamente em tempo real**
3. A planilha calcula estoque bruto, líquido e consumo total
4. Os status de validade mudam sozinhos conforme a data **(VÁLIDO / ALERTA)**
5. O sistema gera relatórios de consumo por medicamento e subnidade

---

## 📁 Estrutura do Sistema

### 📊 Planilha — Google Sheets
| Aba | Função |
|---|---|
| Estoque | Controle de estoque bruto, líquido, consumo e validade |
| Respostas ao Formulário | Dados brutos integrados via Google Forms |
| Relatório de Consumo | Consumo consolidado por medicamento |
| Material Farmácia | Controle de materiais gerais |

### 📝 Formulário — Google Forms
| Seção | Campos |
|---|---|
| Seção 1 | Nome completo e nome de guerra do militar |
| Seção 2 | Posto/graduação e subnidade |
| Seção 3 | Medicamento entregue (catálogo com 50+ itens e validade) |
| Seção 4 | Quantidade entregue e data do atendimento |

---

## 🖼️ Imagens do Sistema

### Planilha

**Aba Estoque**
![Planilha Aba Estoque](PLANILHA%20ABA%20ESTOQUE%20.jpg)

**Aba Relatório de Consumo**
![Planilha Aba Relatório de Consumo](PLANILHA%20ABA%20RELATORIO%20DE%20CONSUMO.jpg)

**Aba Material**
![Planilha Aba Material](PLANILHA%20ABA%20MATERIAL.jpg)

**Aba Respostas**
![Planilha Aba Resposta](PLANILHA%20ABA%20RESPOSTA.jpg)

### Formulário de Atendimento

**Seção 1 — Identificação do Militar**
![Forms Seção 1](FORMS%20-%20SE%C3%87%C3%83O%201%20NOME%20DE%20GUERRA%20DO%20MILITAR.jpg)

**Seção 2 — Posto e Subnidade**
![Forms Seção 2](FORMS%20-%20SE%C3%87%C3%83O%202%20POSTO%20E%20SUBNIDADE.jpg)

**Seção 3 — Medicamento Entregue**
![Forms Seção 3](FORMS%20-%20SE%C3%87%C3%83O%203%20REMEDIO%20ENTREGUE.jpg)
![Forms Seção 3 Parte 2](FORMS%20SE%C3%87%C3%83O%203%20REMEDIO%20ENTREGUE%20PARTE%202.jpg)
![Forms Seção 3 Parte 3](FORMS%20SE%C3%87%C3%83O%203%20REMEDIO%20ENTREGUE%20PARTE%203.jpg)

**Seção 4 — Quantidade e Data**
![Forms Seção 4](FORMS%20SE%C3%87%C3%83O%204%20QUANTIDADE%20E%20DATA%20ENTREGUE.jpg)

---

## 🛠️ Ferramentas Utilizadas

- **Google Sheets** — Planilha com automação por fórmulas avançadas
- **Google Forms** — Formulário de registro de atendimentos
- **Fórmulas condicionais** — Alertas automáticos de validade e cálculo de estoque
- **Design visual** — Identidade visual criada pelo desenvolvedor

---

## 👨‍💻 Desenvolvedor

**Gabriel Carlos**
[LinkedIn](https://www.linkedin.com/in/itsgabrielcarlos) • [GitHub](https://github.com/Gabrielcarlos03)
