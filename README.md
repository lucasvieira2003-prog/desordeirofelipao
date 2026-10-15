# Desordeiro — Website

Site estático da Desordeiro, preparado para **GitHub + Cloudflare Pages**. A base visual e o conteúdo comercial foram preservados do projeto `desordeirov1`.

## V2: refinamentos visuais

- Hero com cinco peças de xadrez em **contorno SVG animado**, com animação leve e sem dependências externas.
- Alternância editorial: **hero escuro → Soluções claro → Manifesto escuro → Processo claro → Equipe escuro → final escuro**.
- Transição entre hero e Soluções mais curta e discreta.
- Soluções com grid revisado, painel de Performance mais à direita, legenda alinhada e entrada progressiva nas abas.
- Contraste e leitura revisados para seções escuras.
- Responsividade específica para desktop, tablet e celular.
- Animação compatível com a opção de **pausar movimento** já existente e com `prefers-reduced-motion`.

## Publicação

- Plataforma: **Cloudflare Pages**
- Framework preset: **None** (HTML estático)
- Build command: **em branco**
- Build output directory: **.** (raiz do repositório)
- Branch de publicação: **main**
- Arquivo inicial: `index.html`
- Cabeçalhos: `_headers`

> **Importante:** alterações neste repositório só atualizam um domínio Cloudflare Pages conectado a **este** repositório. Se `desordeirov1.pages.dev` estiver conectado ao projeto antigo, publique esta versão na configuração correta ou conecte o repositório à sua implantação.

## Estrutura

```text
index.html       Site inteiro (CSS, JS, imagens e peças de xadrez incorporados)
_headers         Cabeçalhos HTTP para Cloudflare Pages
README.md        Guia de manutenção e publicação
```

## Revisões antes da produção

Verificar a experiência em 320, 375, 390, 768, 1024 e 1440px; confirmar o menu, tabs de soluções, formulário/WhatsApp, equipe, FAQ e botão de pausar movimento. A validação visual em navegador é necessária antes da publicação final.

**Muraka Dev Kit:** referência de diretrizes e QA, sem modificar o repositório do kit.
