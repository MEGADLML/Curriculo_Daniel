# Currículo — Daniel Leandro Ferreira da Silva

Site de divulgação do currículo profissional (Diretor Financeiro, Administrativo e Compras),
construído a partir do documento Word `Daniel_Ferreira_Currículo_2026.docx`.

- **Arquivo único:** `index.html` — sem dependências de build. Basta abrir no navegador.
- **Conteúdo:** perfil executivo, experiência profissional, competências, tecnologia e
  certificações, formação acadêmica e contato.
- **Design:** reaproveita a identidade do documento original — faixas pretas de seção com texto
  branco, barras cinza para as empresas e tipografia serifada (Spectral / IBM Plex).
- **Recursos:** índice lateral com seção ativa, tema claro e escuro automáticos, layout
  responsivo e folha de impressão (botão “Imprimir / PDF” gera o currículo em PDF).

## Publicar no GitHub Pages

1. Faça o merge deste branch em `main`.
2. Em **Settings → Pages**, selecione *Deploy from a branch* → branch `main` → pasta `/ (root)`.
3. O site fica disponível em `https://megadlml.github.io/curriculo_daniel/`.

## Como editar

Todo o conteúdo está em `index.html`, em seções comentadas (`<!-- 01 PERFIL -->`,
`<!-- 02 EXPERIÊNCIA -->` etc.). As cores ficam nas variáveis CSS no topo do arquivo,
no bloco `:root`.
