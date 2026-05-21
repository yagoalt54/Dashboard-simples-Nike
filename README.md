# Dashboard Nike (Excel) 

Este projeto contém um **dashboard simples em Excel** inspirado no estilo visual da Nike, criado para responder a perguntas de negocios simples, usando uma base de vendas simulada de tênis.

---

## 🎯 Objetivo do Dashboard
O dashboard foi desenhado para responder **somente** as perguntas abaixo:

1. **Como está o faturamento e sua evolução mensal?**
2. **Quais modelos geram mais receita?** 
3. **Como o mix de receita varia por gênero?** 
---

## 🗂️ Arquivos

- **`Dashboard_Nike_Excel_CORRIGIDO.xlsx`** — arquivo final do dashboard.  
---
## 🧱 Estrutura do Workbook (abas)

O arquivo **`Dashboard_Nike_Excel.xlsx`** possui as seguintes abas:

1. **`Dashboard`** *(única worksheet do dashboard)*  
   - KPIs (“big numbers”) e 3 gráficos principais.
   - Filtros no topo (drop-down): **Loja, Cidade, Gênero, Modelo, Ano-Mês**. 

2. **`Base_Dados`** 
   - Base consolidada em formato de **Tabela do Excel** para facilitar fórmulas e expansão.
   - Inclui colunas derivadas para análise (ex.: **Ano-Mês** e **Faturamento**).

3. **`Assets`**  
   - Paleta de cores em estilo “Nike-inspired” e áreas reservadas para imagens/logos.  

---

## 📊 Dados Utilizados

A base de dados usada contém vendas simuladas com as principais colunas abaixo:

- **Data da Venda**
- **Loja de Venda**
- **Modelo do Tênis / Modelo de Tênis**
- **Preço de Venda (R$)**
- **Quantidade Vendida**
- **Cidade**
- **Idade do Comprador**
- **Gênero do Comprador** 

No dashboard, foi criado o campo:

- **Faturamento (R$) = Preço × Quantidade**

E também:

- **Ano-Mês** (derivado da data) — para agregações mensais. citeturn2search7turn2file8

---

## 🎨 Estilo visual (Nike-inspired)

O projeto inclui uma paleta “Nike-inspired”, disponível na aba **`Assets`**:

- **Preto (base):** `#111111`
- **Branco:** `#FFFFFF`
- **Cinza claro:** `#F5F5F5`
- **Cinza escuro:** `#2B2B2B`
- **Laranja (alerta):** `#FF5A00`

> Nota: é um estilo visual **inspirado** na estética Nike (não é um padrão oficial da marca). 

---

## ▶️ Instruções de uso (usuário final)

1. Abra **`Dashboard_Nike_Excel.xlsx`**. 
2. Vá na aba **`Dashboard`**.
3. Use os filtros no topo:
   - **Loja** (célula `B4`)
   - **Cidade** (célula `D4`)
   - **Gênero** (célula `F4`)
   - **Modelo** (célula `B5`)
   - **Ano-Mês** (célula `D5`)
4. Os KPIs e gráficos devem recalcular automaticamente.

Se algo aparecer em branco/zero, force:
- **Dados → Atualizar Tudo**
- **Fórmulas → Calcular Agora**

---

## 🧩 Notas técnicas de compatibilidade

- O arquivo final está configurado para **recalcular tudo ao abrir** (importante para KPIs e gráficos).

---

Desenvolvido por: Yago Alves Toledo (https://github.com/yagoalt54)
