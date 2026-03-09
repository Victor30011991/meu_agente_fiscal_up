# 🧾 Meu Agente Fiscal — Controle Financeiro Pessoal

Sistema de controle financeiro completo em **HTML + CSS + JavaScript puro**, sem backend, sem banco de dados, sem dependências de servidor. Tudo roda **100% no navegador**.

---

## 📦 Estrutura do Projeto

```
meu_agente_fiscal_up/
├── index.html        ← Dashboard + Lançamentos (arquivo principal)
├── export.html       ← Relatórios (Excel + PDF)
├── import.html       ← Importação (Excel / PDF)
└── themes/
    ├── dark.css
    ├── emerald.css
    ├── gold.css
    ├── indigo.css
    └── rose.css
```

---

## 🚀 Como publicar no GitHub Pages

### 1. Crie um repositório no GitHub
- Acesse [github.com](https://github.com) → **New repository**
- Nome do repositório: `meu_agente_fiscal_up`
- Deixe como **público**
- Clique em **Create repository**

### 2. Faça upload dos arquivos
Opção A — Interface web:
1. No repositório criado, clique em **Add file → Upload files**
2. Arraste **todos os arquivos e a pasta `themes/`**
3. Clique em **Commit changes**

Opção B — Git no terminal:
```bash
git clone https://github.com/SEU_USUARIO/meu_agente_fiscal_up.git
cd meu_agente_fiscal_up
# cole os arquivos aqui
git add .
git commit -m "feat: Meu Agente Fiscal v14"
git push origin main
```

### 3. Ative o GitHub Pages
1. No repositório → **Settings → Pages**
2. Em **Source**, selecione: `Deploy from a branch`
3. Branch: `main` / Pasta: `/ (root)`
4. Clique em **Save**
5. Aguarde ~2 minutos

### 4. Acesse o sistema
```
https://SEU_USUARIO.github.io/meu_agente_fiscal_up/
```

---

## 🔒 Sobre os dados

- ✅ Todos os dados ficam **no seu navegador** (localStorage)
- ✅ Nenhum dado é enviado para servidores
- ✅ Funciona offline após o primeiro carregamento
- ✅ Chave: `meu_agente_fiscal_v14`

---

## 📊 Funcionalidades

- Lançamentos com Entrada/Saída, Categoria, Valor, CPF/CNPJ, Investimento e Observação
- Múltiplos perfis de usuário
- Lançamentos recorrentes (semanal, quinzenal, mensal, anual)
- 8 gráficos interativos e configuráveis
- Exportação para **PDF** (4 estilos de capa) e **Excel** (múltiplas abas)
- Importação de Excel e PDF
- Backup/restauração em JSON
- Temas de cor personalizáveis
- Meta mensal de economia

---

## 🛠️ Dependências (CDN — sem instalação)

| Biblioteca | Versão | Uso |
|---|---|---|
| Chart.js | 4.4.0 | Gráficos |
| SheetJS | 0.18.5 | Excel |
| jsPDF | 2.5.1 | PDF |
| PDF.js | 3.11.174 | Leitura de PDF |
| Google Fonts | — | Tipografia |

---

**Meu Agente Fiscal** — versão 14 com patches de segurança e estabilidade aplicados
