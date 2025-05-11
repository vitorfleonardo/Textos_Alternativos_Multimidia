# 🎧 Fone Bluetooth - Acessibilidade na Web com WCAG 2.2

## 👥 Grupo e Integrantes

<table>
  <tr>
    <td align="center"><a href="https://github.com/vitorfleonardo"><img style="border-radius: 50%;" src="https://github.com/vitorfleonardo.png" width="100px;" alt=""/><br /><sub><b>Vitor Feijó</b></sub></a><br />
  </tr>
</table>

---

## 📝 Critérios WCAG 2.2 Implementados

| Critério WCAG 2.2                                   | Descrição                                                                                                                                                                       |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1.1.1 Conteúdo Não Textual**                      | Fornece alternativas textuais para imagens e ícones. [[WCAG 2.2 - 1.1.1](https://www.w3c.br/traducoes/wcag/wcag22-pt-BR/#conteudo-nao-textual)]                                 |
| **1.2.1 Apenas Áudio e Apenas Vídeo (Pré-gravado)** | Oferece descrição em texto para mídias somente de áudio ou vídeo. [[WCAG 2.2 - 1.2.1](https://www.w3c.br/traducoes/wcag/wcag22-pt-BR/#apenas-audio-e-apenas-video-pre-gravado)] |
| **1.2.2 Legendas (Pré-gravadas)**                   | Fornece legendas sincronizadas em vídeos pré-gravados. [[WCAG 2.2 - 1.2.2](https://www.w3c.br/traducoes/wcag/wcag22-pt-BR/#legendas-pre-gravadas)]                              |

---

## 🎯 Importância e Público-Alvo

Esses critérios garantem que **informações visuais e auditivas estejam disponíveis em formato textual ou legendado**, possibilitando o acesso de:

- 🧑‍🦯 **Pessoas com deficiência visual total ou parcial** (descrições textuais em imagens e vídeos).
- 🧑‍🦻 **Pessoas com deficiência auditiva** (legendas em vídeos e descrições em áudio).
- 🧑‍🦼 **Usuários com restrições tecnológicas** (que não conseguem carregar mídias).
- 📱 **Usuários em ambientes sem áudio** (como transporte público).

Esses recursos tornam o conteúdo **perceptível a um público mais amplo**, conforme o primeiro princípio **Perceptível (P)** da WCAG 2.2.

---

## 💻 Técnicas de Programação Utilizadas

- ✅ **`<img>` com atributo `alt`**: fornece texto alternativo para imagens.
- ✅ **`<figcaption>`**: apresenta uma legenda visível para a imagem.
- ✅ **`<audio>` com descrição em texto**: oferece alternativas para conteúdos apenas em áudio.
- ✅ **`<iframe>` do YouTube com descrição textual**: permite incorporar vídeos com legendas nativas do YouTube.
- ✅ **Descrições alternativas em `<p>`**: garantem que o conteúdo seja acessível mesmo sem áudio ou vídeo.

---

## 🚀 Como Rodar o Código

### ✅ Requisitos

- Navegador moderno (Google Chrome, Firefox, Edge, etc.).
- Estrutura de arquivos:
