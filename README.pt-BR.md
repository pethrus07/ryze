# RYZE

[English](README.md) · Português

Identidade visual da RYZE, a marca de desenvolvimento freelancer de Pedro Oliveira (João Pessoa), e as fontes
usadas nos documentos gerados com a marca.

## Status

Ativo (novembro de 2026). Não há sistema aqui: só arquivos de marca. Sem diagrama.

## A marca em uma tela

- **Cores:** preto `#0D0D0D` (base), dourado `#FFB700` (destaque e logo; `#CC9200` para texto sobre fundo
  claro), roxo `#6A28C9` (tecnologia). Proporção: 55% preto, 20% dourado, 10% roxo, 15% neutros.
- **Tipografia:** Space Grotesk nos títulos, Plus Jakarta Sans no corpo, JetBrains Mono em dados e rótulos.
- **Logo:** seta que sobe. Uso principal dourado sobre preto; em documento, a versão monocromática.
- **Direção:** limpo, muito respiro, números em destaque.

O detalhe está no guia: abra `identidade/Identidade completa.html` no navegador.

## Fontes

Os arquivos em `documentos/fontes/` são instâncias estáticas (um peso por arquivo) das fontes variáveis do
Google Fonts. O Chrome headless embute TTF estático de forma previsível no PDF, o que a fonte variável não
garante. As três famílias são distribuídas sob a SIL Open Font License 1.1.

## Pastas

```
identidade/
  Identidade completa.html            guia de marca autocontido (cores, tipografia, logo, uso)
  logo-montanha.svg                   logo
  logo-montanha-preto.svg             logo monocromático preto
  logo-montanha-branco.svg            logo monocromático branco
  ryze-symbol-gold-transparent.svg    símbolo dourado, fundo transparente
documentos/
  fontes/                             TTF estáticos para gerar PDF (Chrome headless)
```

## Decisões e limites conhecidos

Documentos feitos para clientes (resumos, propostas, contratos, conversas transcritas, áudios) **não ficam no
git**. Eles vivem em `documentos/<cliente-AAAA-MM>/` só no disco, e o `.gitignore` ignora toda subpasta de
`documentos/` exceto `fontes/`, além de qualquer áudio ou vídeo.

## Licença

- Código (o guia em HTML em `identidade/`): MIT. Veja [LICENSE](LICENSE).
- Fontes em `documentos/fontes/`: SIL Open Font License 1.1, de seus autores. Veja [OFL.txt](documentos/fontes/OFL.txt).
- O nome, o logo e o símbolo RYZE são marca registrada do autor, não licenciada para reuso.
