# Treinamentos Sienge

Plataforma interna de treinamentos em vídeo e passo a passo, organizada por módulos do **Sienge**, destinada ao apoio operacional e padronização de processos.

Os vídeos são hospedados no YouTube como **não listados** e exibidos por meio de um site estático utilizando **GitHub Pages + Jekyll**.

---

## 🎯 Objetivo

- Centralizar treinamentos operacionais do Sienge
- Facilitar o aprendizado de novos usuários
- Padronizar processos internos
- Reduzir retrabalho e dúvidas recorrentes

---

## 🧩 Estrutura dos treinamentos

Os conteúdos são organizados por **módulo**:

- Compras
- Estoque
- Financeiro
- Contratos

Cada treinamento contém:
- 🎥 Vídeo demonstrativo
- 📝 Passo a passo textual
- 🔖 Identificação do módulo
- 🆕 Selo de **Novo** ou **Atualizado**

---

## 📂 Estrutura do projeto

```
/
├── _config.yml
├── index.html
├── README.md
├── assets/
│   └── style.css
├── _layouts/
│   ├── default.html
│   └── video.html
└── _videos/
    ├── compras-notas-fiscais.md
    ├── compras-solicitacoes.md
    ├── estoque-movimentos.md
    ├── estoque-posicoes.md
    ├── financeiro-titulos-a-pagar.md
    ├── contratos-cadastro-contratos.md
    ├── contratos-cadastro-medicoes.md
    └── contratos-liberacoes-medicoes.md
```

---

## ✏️ Como cadastrar ou editar um treinamento

Cada vídeo é um arquivo `.md` dentro da pasta `_videos`.

### Exemplo de configuração

```yaml
title: Cadastro de Solicitações de Compra
module: Compras
youtube_id: oTvLKLaE2CY
summary: Criar solicitação e encaminhar para o fluxo de compras.
order: 10
status: atualizado
tags: [compras, solicitação, fluxo]
```

---

## 🔃 Ordenação

A ordenação dentro de cada módulo é controlada pelo campo:

```
order: 10
```

Use valores espaçados (10, 20, 30…) para facilitar futuras inserções.

---

## 🆕 Selos de status

- `novo` → NOVO
- `atualizado` → ATUALIZADO

---

## 🔐 Aviso de confidencialidade

© 2026 **KLM Systems**. Todos os direitos reservados.  
Conteúdo interno e confidencial, destinado exclusivamente a pessoas autorizadas.  
É proibida a reprodução, redistribuição, gravação ou compartilhamento sem autorização prévia.

O acesso a este sistema implica ciência e concordância com as políticas internas de uso da informação.

---

## 🚀 Publicação

Publicado via **GitHub Pages** utilizando Jekyll.

---

**KLM Systems**  
Soluções em sistemas, automação e tecnologia.
