# Chaac Memory Helper

Ferramenta visual para registrar manualmente a sequência do desafio de memória do **Templo de Chaac** em Sunflower Land.

## Objetivo

A interface imita a lógica espacial da roda do minigame:

- 1 posição central
- 4 posições no círculo menor
- 4 posições no círculo maior

Enquanto a sequência aparece no jogo, basta clicar na mesma posição no helper. Cada movimento é salvo imediatamente na lista abaixo.

## Recursos

- Roda clicável com 9 posições
- Feedback visual instantâneo
- Sequência numerada
- Mini-mapa de cada movimento
- Destaque do último clique
- Desfazer último movimento
- Limpar sequência com confirmação
- Persistência em `localStorage`
- Responsivo para desktop e celular
- Atalhos de teclado
- Zero dependências externas

## Atalhos

```text
Q   ↑   E
← Espaço →
Z   ↓   C
```

`Backspace` desfaz o último movimento.

## GitHub Pages

O projeto é totalmente estático. Para publicar:

1. Abra **Settings** no repositório.
2. Acesse **Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione `main` e `/ (root)`.
5. Salve.

O endereço ficará normalmente em:

`https://generosorafa.github.io/chaac-helper/`

## Observação

Esta é uma ferramenta independente de auxílio visual. Ela não lê, modifica ou automatiza ações dentro do Sunflower Land.
