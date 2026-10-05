# Entenda seu coração — Endocor

Material educativo visual para mostrar ao paciente durante a consulta.

## Estrutura

```
index.html                              página inicial com a lista de doenças
doencas/doenca-arterial-coronariana.html
assets/css/style.css                    identidade visual compartilhada (cores, fontes)
assets/js/dac.js                        animação do continuum da placa
```

## Como usar

Abra `index.html` no navegador. Na página da doença, avance as etapas com os botões ou com as setas ← → do teclado.

## Publicar no GitHub Pages

No repositório: Settings → Pages → Source: `Deploy from a branch` → Branch `main`, pasta `/ (root)`.

## Adicionar uma nova doença

1. Criar `doencas/nome-da-doenca.html` reaproveitando o cabeçalho e as classes de `style.css`.
2. Trocar o cartão "Em breve" correspondente em `index.html` por um link.
