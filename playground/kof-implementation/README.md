# doom-fire-algorithm - KOF

[English](#english) | [Português](#português)

## English

Fire effect from DOOM in [Kof](https://github.com/KofLang/Kof4j), a new statically-typed language that targets JVM, native and web from the same source.

Same propagation logic as the original: bottom row seeded at max intensity, each pixel copies the one below it with random decay and a slight horizontal drift, mapped through a 36-step palette. Rendered as 24-bit ANSI background colors, two spaces per cell.

### Requirements

- [Kof](https://github.com/KofLang/Kof4j/releases) (0.3.x-beta or later)

### Running

```
git clone https://github.com/filipedeschamps/doom-fire-algorithm.git
cd doom-fire-algorithm/playground/kof-implementation
kof run Main.kf --target jvm
```

Ctrl+C to stop, it loops forever.

### More

A bilingual (PT/EN) browser build with a live fire-intensity slider, served by Kof's own `kof.web`, plus the terminal build above: [obrenoalvim/doom-fire-kof](https://github.com/obrenoalvim/doom-fire-kof).

---

## Português

Efeito de fogo do DOOM em [Kof](https://github.com/KofLang/Kof4j), uma linguagem nova, estaticamente tipada, que compila para JVM, nativo e web a partir do mesmo código-fonte.

Mesma lógica de propagação do original: a linha de baixo nasce com intensidade máxima, cada pixel copia o de baixo com decaimento aleatório e leve deriva horizontal, mapeado numa paleta de 36 passos. Renderizado como cor de fundo ANSI 24 bits, dois espaços por célula.

### Requisitos

- [Kof](https://github.com/KofLang/Kof4j/releases) (0.3.x-beta ou mais recente)

### Rodando

```
git clone https://github.com/filipedeschamps/doom-fire-algorithm.git
cd doom-fire-algorithm/playground/kof-implementation
kof run Main.kf --target jvm
```

Ctrl+C para parar, roda para sempre.

### Mais

Uma versão bilíngue (PT/EN) no browser, com slider de intensidade do fogo ao vivo, servida pelo próprio `kof.web`, além da versão de terminal acima: [obrenoalvim/doom-fire-kof](https://github.com/obrenoalvim/doom-fire-kof).
