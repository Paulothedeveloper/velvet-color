<div align="center">

<img src="assets/velvet-logo.png" alt="VELVET" width="120" />

# VELVET

**Esteira de looks pro seu vídeo — do app direto pro DaVinci Resolve, sem retrabalho.**

[![status](https://img.shields.io/badge/status-BETA-d9a63e?style=for-the-badge)](https://paulocodex.com/p/velvet)
&nbsp;
[![plataforma](https://img.shields.io/badge/Windows%20%7C%20macOS-1f1f1f?style=for-the-badge&logo=davinciresolve&logoColor=white)](https://paulocodex.com/p/velvet)

[![Página do projeto](https://img.shields.io/badge/P%C3%A1gina%20do%20projeto-abrir-5e5ce6?style=for-the-badge)](https://paulocodex.com/p/velvet)

<img src="assets/velvet-pro.png" alt="VELVET — câmera de origem, antes/depois e galeria de looks" width="880" />

</div>

---

Color grading é onde o vídeo ganha (ou perde) a cara de cinema — e é onde amador e profissional mais perdem tempo. O **VELVET** é uma sala de cor num app só: escolhe a câmera, aplica um look, dosa a força e joga o grade pronto **direto na timeline do DaVinci Resolve**. Nada de arrastar LUT, empilhar nó atrás de nó e refazer tudo no próximo clipe.

Uma esteira: **do app → pro Resolve**, com o processo de colorista já embutido — não a imagem crua com uma cor chapada por cima.

## ✨ O que faz

- **Biblioteca de looks prontos** — 22 looks curados (Neutro, Institucional, Cinematic, Teal & Orange, Quente Premium, Frio Clean, High-Key, Golden Hour, Preto e Branco, Cold Thriller, Bleach Bypass, Cross Process, Retro 70s/80s, Pastel e mais), organizados entre *Base* e *Criativo*. Um clique parte de uma base já tratada, não da imagem crua.
- **Câmera de origem em um toque** — normaliza o material LOG/HDR pro Rec.709 (gamma **e** gamut, como um CST de verdade): Rec.709, Sony S-Log2/S-Log3, Panasonic V-Log, DJI D-Log, ARRI LogC3/LogC4, Canon C-Log/C-Log2/C-Log3, Fuji F-Log/F-Log2, Apple Log, **Samsung Log** (raro — quase nenhuma ferramenta tem), Nikon N-Log, RED Log3G10, GoPro, HLG, PQ HDR, ACES e DaVinci Intermediate. 24 perfis.
- **Integração direta com o DaVinci Resolve** — o app conversa com o Resolve e monta o grade nos nós por você. Você continua editando; a cor chega pronta.
- **Do app pro timeline, sem retrabalho** — configurou uma vez, o look viaja pro projeto. Sem exportar `.cube` na mão, sem reconstruir o mesmo tratamento clipe a clipe.
- **Modo Amador e Modo Pro no mesmo app** — simples por padrão (câmera → look → intensidade); e quando quiser, o Pro abre rodas de cor (Lift/Gamma/Gain/Offset), curvas, HSL por faixa e acabamento de filme (halação, grão, bloom, vinheta).
- **Antes / Depois de verdade** — comparador com slider na imagem inteira, pra julgar o grade na hora.
- **Escopos com leitura real** — waveform, parade, vetorscópio e histograma medidos do clipe, não de enfeite.
- **VELVET AI (exclusivo)** — digita a **intenção** em português ("quente nostálgico anos 80", "clean corporativo", "teal cinema"); a IA lê os escopos e decide o grade — e explica o que mudou, pra você aprender em vez de seguir às cegas.

## 🎨 Por que VELVET

A maioria das ferramentas "one click" do mercado (tipo OneClick Grade, US$ 37–89) é, no fundo, **uma LUT + um slider de intensidade**. Ficam bonitas num clipe e quebram no próximo, porque não tem processo de cor por baixo — é cor chapada sobre imagem crua.

O VELVET foi construído ao contrário:

| | Ferramentas "one click" | **VELVET** |
|---|---|---|
| Base do look | LUT fixa | Motor de cor procedural (ombro fílmico, contraste com pivô na pele, 3-way, densidade, proteção de pele) |
| Conversão de câmera | Lista de LUTs | Conversão real de gamma **+ gamut**, 20+ perfis |
| Controle | 1 slider | Amador simples **ou** Pro completo, no mesmo app |
| Inteligência | Nenhuma | IA lê os escopos + a sua intenção e explica o grade |
| Entrega | Você arrasta a LUT | Vai **direto pra timeline** do Resolve |

Resultado: sai de material cru pra um grade profissional em segundos — com processo de colorista, não um filtro por cima.

## 🖥️ Modo Pro

<div align="center">

<img src="assets/velvet-pro.png" alt="VELVET — Modo Pro: rodas de cor, acabamento de filme e escopos" width="880" />

</div>

Rodas de cor, curvas e HSL por faixa, acabamento de filme (halação · grão · bloom · vinheta) e escopos — a profundidade de uma sala de cor, sem sair do fluxo.

## 🧩 A suíte VELVET — não é só cor

VELVET virou uma **suíte de edição pro DaVinci Resolve**. Além do app de cor, três plugins nativos que instalam num pack só e aparecem **separados** no menu de Integrações — cada um com seu ícone, cada um uma função (nada de canivete suíço que faz tudo mal).

<div align="center">
<img src="assets/plugin-autocut.png" alt="VELVET AutoCut" width="270" />
<img src="assets/plugin-legenda.png" alt="VELVET Legenda" width="270" />
<img src="assets/plugin-transcricao.png" alt="VELVET Transcrição" width="270" />
</div>

- <img src="assets/icon-autocut.png" width="18" align="absmiddle" /> **VELVET AutoCut** — corta silêncio, gaguejo e take repetido em segundos, sem sair do DaVinci. Presets Pouco / Normal / Muito. A timeline original fica intacta.
- <img src="assets/icon-transcricao.png" width="18" align="absmiddle" /> **VELVET Transcrição** — edite pelo **texto** como no Premiere, com transcrição por IA rodando **na sua GPU** (Whisper local): sem nuvem, sem limite de horas, sem custo por minuto. Excluir texto corta o vídeo (ripple), localizar/substituir, exportar SRT.
- <img src="assets/icon-legenda.png" width="18" align="absmiddle" /> **VELVET Legenda** — legenda viral com **karaokê**, biblioteca de SFX e **34 letterings próprios**, nativa no Resolve. O que o CaptionFlow faz no Premiere, aqui com transcrição embutida.

### Por que VELVET (e não os outros)

Nenhum concorrente junta as quatro coisas: **DaVinci-nativo + em português + compra única + IA 100% local**. Os pagos de legenda BR (CaptionFlow, Legendas Master) só rodam no Premiere; os de DaVinci (AutoCut.com, FireCut) são **assinatura mensal**. VELVET é compra única e a IA roda no seu PC.

| | Concorrentes | **VELVET** |
|---|---|---|
| Onde roda | Premiere (os BR) ou assinatura | **DaVinci nativo, compra única** |
| Transcrição | nuvem, por minuto/limite de horas | **sua GPU (Whisper local), ilimitada** |
| Idioma | inglês | **português** |
| Preço | US$10-20/mês recorrente | **paga uma vez, é seu** |

### Preços (lançamento)

| Produto | Lançamento |
|---|---|
| VELVET AutoCut | R$67 |
| VELVET Transcrição | R$97 |
| VELVET Legenda | R$137 |
| **VELVET Suíte** (os 3) | **R$197** — ~33% off |
| VELVET Complete (+ Color) | R$297 |

Compra única, 2 PCs por licença, atualizações inclusas. **Teste 3 dias grátis** em cada um.

➡️ **[paulocodex.com/p/velvet](https://paulocodex.com/p/velvet)** — lançamento em breve, entre na lista.

## 🚧 Status

**Beta — motor provado, lançamento em breve.** O núcleo de cor passa em **52/52 provas numéricas** contra referências publicadas (WB Bradford vs Lindbloom, PQ/ST.2084, LUT oficial de Samsung Log) e já foi **validado rodando no DaVinci Resolve Studio 21** (aplica o grade no nó e renderiza na GPU de verdade — não "compila", *funciona*). Compra única, 100% offline, em português. Este repositório é a **apresentação pública**; o código-fonte é fechado.

Quer ser avisado quando abrir?

➡️ **[paulocodex.com/p/velvet](https://paulocodex.com/p/velvet)**

## ⚙️ Feito pra rodar em

- **DaVinci Resolve 18.6–21** (Free e Studio)
- **Windows** e **macOS**
- Interface **em português**, do amador ao profissional

## 🥷 Mascote

<img src="https://paulocodex.com/brand/ninjas/velvet.png" alt="Velvet — ninja" width="200" align="right" />

Todo projeto do estúdio tem o **ninja Codex** na cor da sua identidade — o mesmo mascote da casa, recolorido pro tema do **Velvet**.

<br clear="right" />

## 👤 Sobre o desenvolvedor

<img src="https://paulocodex.com/products/paulo.jpg" alt="Paulo Adriel" width="130" align="left" style="margin-right:18px;border-radius:12px" />

**Paulo Adriel** é produtor de vídeo e desenvolvedor indie brasileiro. Construo o produto **e** a apresentação dele — código + identidade visual, motion e material de lançamento — do zero ao ar em 30 dias. Trabalho de forma aberta e escuto quem usa. Estúdio [**Paulocodex**](https://paulocodex.com).

<br clear="left" />

---

<div align="center">

📧 [contato@paulocodex.com](mailto:contato@paulocodex.com) &nbsp;·&nbsp; 🌐 [paulocodex.com](https://paulocodex.com) &nbsp;·&nbsp; 📸 [Instagram](https://instagram.com/paulodev.codex) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/paulo-adriel/) &nbsp;·&nbsp; 🐙 [github.com/Paulothedeveloper](https://github.com/Paulothedeveloper)

_Repositório de **apresentação pública** — o código-fonte é fechado. Nada de dado ou segredo aqui._

</div>
