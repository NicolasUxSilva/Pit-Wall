# Desafio Pit Wall · GP de São Paulo

Página visual inspirada no GP de São Paulo de Fórmula 1 (Interlagos), feita **somente com HTML5 e CSS3** para a disciplina de Linguagem de Marcação (LIMA).

> Projeto apenas visual: botões, filtros e formulário não executam nenhuma ação.

## Estrutura

```text
pit-wall/
├── index.html
├── styles.css
└── img/
    └── piloto.jpg
```

## Recursos utilizados

- Fonte **Titillium Web** (Google Fonts)
- Variáveis de cor com `:root` e `var()`
- `display: flex` no topo, hero e filtros
- `display: grid` com `repeat(auto-fit, minmax(...))` nos cards dos pilotos
- `form-grid` no formulário de ingressos
- `linear-gradient()` com corte seco (faixa vermelha) e `url()` (foto do carro)
- `repeating-linear-gradient()` na zebra da pista
- `opacity`, `:hover` e `transition`
- Tabela com `table`, `thead` e `tbody`
- Responsividade com `@media (max-width: 768px)`

## Como abrir

Basta abrir o arquivo `index.html` no navegador.

Foto: Jonathan Borba (Pexels).

---

Feito por **Nicolas Santos da Silva**.
