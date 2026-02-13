# Pokédex Kanto

Uma Pokédex interativa e completa dos 151 Pokémon originais da região de Kanto, construída com HTML, CSS e JavaScript puro.

---

## Funcionalidades

### Pokédex

- **151 Pokémon de Kanto** carregados da PokéAPI com artwork oficial
- **Busca** por nome ou número
- **Filtro por tipo** (Fogo, Água, Planta, etc.)
- **Ordenação** por número (#) ou nome (A-Z)
- **Favoritos** com persistência via localStorage
- **Dark Mode** com persistência
- **Skeleton loading** durante carregamento
- **Cards animados** com hover effects e badges de Starter/Lendário
- **Design responsivo** para mobile, tablet e desktop

### Modal de Detalhes

- **4 abas**: Sobre, Stats, Tipos e Evolução
- **Gráfico Radar SVG** para visualização dos stats
- **Barras animadas** com total de base stats
- **Efetividade de tipos** — fraquezas, resistências e imunidades
- **Cadeia evolutiva** clicável com nível de evolução
- **Grito do Pokémon** (Cry) via áudio
- **Toggle Sprite** — clique na imagem para alternar entre artwork e pixel sprite
- **Navegação** entre Pokémon com setas ou teclas `←` `→`

### Mini-Game

- **"Quem é esse Pokémon?"** — quiz com silhueta escura e 4 opções
- Sistema de pontuação com sequência (streak) e recorde salvo

---

## Tecnologias

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura |
| **CSS3** | Estilos, animações, variáveis, radar SVG |
| **JavaScript** | Lógica, fetch API, localStorage |
| **[Squeleton](https://squeleton.dev)** | Grid responsivo, utilitários CSS, modais |
| **[PokéAPI](https://pokeapi.co)** | Dados dos Pokémon |

---

## Estrutura

```
pokedex-kanto/
├── index.html    # Aplicação completa (HTML + CSS + JS)
└── README.md
```

Projeto single-file por design — todo o código está em um único arquivo HTML para máxima portabilidade.

---

## Créditos

- Dados: [PokéAPI](https://pokeapi.co/)
- Pokémon é propriedade da Nintendo / Game Freak / Creatures Inc.

---

## Licença
Este é um projeto de fã, criado para fins de entretenimento e sem fins lucrativos. Dúvidas, sugestões ou quer contribuir? Entre em contato!
