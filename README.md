# gaitatab

**Gaita Bounce** - visualizador MIDI com gaita de boca (harmônica diatônica de 10 furos, afinação Richter em Dó), no estilo do saxtab/flutetab.

- **Player**: abra um MIDI e veja a gaita tocando. O furo da nota acende, com seta ↑ (soprar) ou ↓ (aspirar) e, quando preciso, "bend ½ tom / 1 tom / 1½ tom" ou "overblow/overdraw". A nota aparece na pauta com o nome em solfejo. Quando a nota tem outra posição (ex.: Sol4 = furo 2 aspirar ou furo 3 soprar), ela aparece menor no canto; toque nela para trocar.
- **Partitura**: editor em piano roll (vozes, acordes, articulações, ligaduras), com a posição da nota selecionada.
- **Extensão**: C4 a C7, todas as notas cromáticas (com bends e overblows). Notas de MIDI fora dela são dobradas por oitava.
- **Som**: gravações de gaita de boca do soundfont FluidR3_GM (Creative Commons Attribution 3.0), embutidas no `index.html`; funciona offline.

Tabela usada (Dó, Richter): soprar 1–10 = C4 E4 G4 C5 E5 G5 C6 E6 G6 C7; aspirar 1–10 = D4 G4 B4 D5 F5 A5 B5 D6 F6 A6.
Bends: aspirar nos furos 1, 2 (½ e 1 tom), 3 (½, 1 e 1½), 4 e 6; soprar nos furos 8, 9 e 10 (½ e 1 tom).
Overblow (furos 1–6) = nota de aspirar + ½ tom; overdraw (7–9) = nota de soprar + ½ tom.

Publique todos os arquivos na raiz do repositório (GitHub Pages). A cada atualização, mude o número em `CACHE_NAME` do `sw.js` (e o `?v=` dos ícones, se trocá-los).

Créditos do som: FluidR3_GM por Frank Wen (CC BY 3.0), via github.com/gleitz/midi-js-soundfonts.
