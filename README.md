# Fórmulas e Planilhas Auxiliares para o Power BI

Repositório centralizado com códigos DAX, fórmulas, scripts e planilhas auxiliares para dar suporte ao desenvolvimento e manutenção de relatórios e dashboards no **Power BI**.

---

## O que você encontra aqui?

* **Medidas DAX & HTML:** Snippets prontos para uso em cartões customizados e visuais HTML.
* **Bases Auxiliares:** Arquivos e datasets prontos para consultas e relacionamentos (ex: tabelas de apoio como CID-10).

---

## Destaques e Como Utilizar

### 1. Utilização de HTML no Power BI
Para renderizar os códigos HTML salvos neste repositório:
1. Certifique-se de estar utilizando um visual que suporte HTML (como o **HTML Content** do marketplace do Power BI).
2. Crie uma **Nova Medida** no seu modelo de dados colando o código DAX correspondente.
3. Arraste a medida para o visual escolhido.

> **Dica:** Evite o uso de gráficos de pizza ou rosca; prefira barras e cartões limpos seguindo os princípios de *Storytelling with Data*.

### 2. Planilhas e Bases Auxiliares
* **CID-10 (`/CID10CSV/`):** Arquivos em formato `.csv` contendo a Classificação Internacional de Doenças para cruzamentos e análises em dashboards de saúde ou RH.
