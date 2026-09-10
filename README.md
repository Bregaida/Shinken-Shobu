# 真剣勝負 — Shinken Shōbu

> **Se os maiores guerreiros do Japão lutassem, todos no auge e na mesma arena, quem venceria quem?**
> Um simulador de duelos históricos — realista, baseado em fatos, sem folclore nem poderes sobrenaturais.

[![Site](https://img.shields.io/badge/site-no_ar-2ea44f?style=flat-square)](https://bregaida.github.io/Shinken-Shobu/)
[![Licença: MIT](https://img.shields.io/badge/license-MIT-1f6feb?style=flat-square)](LICENSE)
![Guerreiros](https://img.shields.io/badge/guerreiros-~147-b8860b?style=flat-square)
![Idiomas](https://img.shields.io/badge/idiomas-5-orange?style=flat-square)

**🔗 Acesse o simulador:** **https://bregaida.github.io/Shinken-Shobu/**

---

## Sobre o projeto

*Shinken shōbu* (真剣勝負) quer dizer **"duelo com espada de verdade"** — o combate sério, decidido com aço afiado em vez das espadas de treino de madeira. É esse o espírito daqui: colocar frente a frente **cerca de 147 guerreiros japoneses reais**, de cinco eras diferentes, e responder à pergunta que todo apaixonado por história já se fez — *quem venceria?*

Nada de lendas nem habilidades mágicas. Cada guerreiro é avaliado pelas suas capacidades **documentadas**, medido no **auge da carreira** (sem doenças, ferimentos ou a idade pesando) e colocado num confronto **1 contra 1**.

## O que dá pra fazer

- 🥇 **Ranking geral e tier list** com todos os guerreiros
- 📊 **Gráficos de radar** mostrando os atributos de cada um
- 🏹 **Rankings por eixo** — melhor espadachim, melhor lanceiro e melhor arqueiro
- 🗺️ **Mapa mental** de todos os guerreiros organizados por era e clã, com busca por nome
- ⚔️ **Simulador 1×1** — escolha dois nomes e veja o resultado *com a justificativa*
- 🏆 **Chaves de torneio** — uma chave curada de 16 lutadores e a *Grande Chave* com todos os ~147
- 🛠️ **Monte sua própria chave** e simule o torneio do seu jeito
- 📜 **Ficha de cada guerreiro** — breve histórico, técnicas, armas usadas, retrato histórico e o emblema (*kamon*) do clã
- 🗡️ **Arsenal** — 12 armas com fotos reais, nomes corretos em japonês e ficha de atributos; a ficha de cada guerreiro leva direto à sua arma principal
- ☯️ **Modo Duelo ou Campo de batalha** — o mesmo confronto muda de resultado quando o que está em jogo é a honra individual ou a guerra
- 🌗 **Tema claro/escuro** e **5 idiomas**

## Como funciona a engine

O coração do projeto é um **motor de combate determinístico**: dados os mesmos dois guerreiros, o resultado é sempre o mesmo — não há sorte nem números aleatórios.

Cada guerreiro carrega um conjunto de atributos — perícia com a arma principal, alcance e controle da arma, força física, velocidade, defesa, experiência de combate e agressividade. O duelo é resolvido comparando esses atributos com **pesos calibrados**, e vantagens reais entram como bônus condicionais: o alcance de uma lança, por exemplo, conta mais contra quem tem pouco alcance, e a agressividade só decide encontros muito parelhos — sempre com peso moderado, para a comparação continuar realista.

O modo **Campo de batalha** reequilibra tudo: alcance, disciplina de formação e resistência ganham importância, enquanto o **Duelo** puro valoriza mais a técnica individual e a leitura do adversário.

## Idiomas

Interface e análises disponíveis em **Português · English · Español · 日本語 · Français**, selecionáveis no topo da página.

## Imagens e fontes

Todos os retratos e fotos de armas são de **domínio público**, embutidos no próprio arquivo (nada depende de links externos):

- **The Met Open Access** (CC0)
- **Wikimedia Commons**
- **Wikipédia**

As avaliações se apoiam em registros históricos, crônicas e na literatura consagrada sobre cada guerreiro e sua escola de combate.

## Tecnologia

Um **único arquivo HTML**, com CSS, JavaScript, dados e imagens todos embutidos. **Sem dependências, sem build, sem servidor** — abre em qualquer navegador moderno.

## Rodando localmente

```bash
git clone https://github.com/Bregaida/Shinken-Shobu.git
cd Shinken-Shobu
```

Depois é só abrir o `index.html` no navegador (duplo clique já resolve). Não precisa instalar nada.

## Estrutura

```
Shinken-Shobu/
├── index.html   → o aplicativo completo (tudo embutido)
└── LICENSE      → MIT
```

## Aviso

Este projeto é **entretenimento**. As avaliações são estimativas informadas, não medições exatas — ninguém cronometrou esses duelos. Se você discorda de algum resultado, ótimo: faz parte da diversão debater. Nenhuma comparação aqui pretende diminuir a memória ou o legado de qualquer guerreiro.

## Autor

Feito por **Eduardo Bregaida**.
Me acompanhe no Instagram: [@bregaida.aerobatics](https://instagram.com/bregaida.aerobatics)

## Licença

Distribuído sob a licença **MIT** — veja o arquivo [LICENSE](LICENSE).
© 2026 Eduardo Bregaida.


