# 🌌 Animated Wallpapers

> Wallpapers animados feitos com HTML e JavaScript puro, leves, personalizáveis e compatíveis com Wallpaper Engine.



## ✨ Wallpapers disponíveis

### 🌠 Starfield
Um céu noturno animado com classificação estelar realista, galáxias, estrelas cadentes, satélites e muito mais, tudo renderizado em Canvas a 30fps. O fundo é preto puro (`#000000`), ideal para telas OLED.

<img src="Imagens/Starfield.gif" width="500">

**Efeitos:**
- Estrelas com brilho pulsante e **classificação espectral realista** (classes M, K, G, F, A, B e O), cada tipo com cor, tamanho e frequência de ocorrência próprios
- **Spikes de difração** em estrelas mais brilhantes (tipos A, B e O), em cruz ou diagonal
- **Aglomerados estelares** (star clusters) com distribuição gaussiana
- **Galáxias** em 4 paletas de cor (azuladas, quentes/neutras, avermelhadas com redshift e exóticas/roxas) com núcleo pulsante e ângulo de visão variável, de frente a quase de lado
- **Estrelas cadentes** cruzando a tela com rastro de luz que desvanece
- **Satélites** se movendo lentamente com leve cintilação de painel solar
- **Trens Starlink** em fileira com deploy progressivo simulado, satélites mais juntos no início e separando ao longo do tempo
- **OVNIs** raríssimos, com movimento errático, mudança brusca de direção e ciclo de cores piscando (verde, azul, roxo, vermelho, âmbar e branco)
- **Vinheta** escurecendo as bordas para dar profundidade

**Frequência dos eventos:**
| Evento | Intervalo aproximado |
|---|---|
| Estrela cadente | ~35s |
| Satélite | ~50s |
| Trem Starlink | ~4 minutos |
| OVNI | ~5 minutos |



### ❄️ The North Remembers
é um wallpaper animado criado para desktop, focado em criar uma ambientação cinematográfica através de efeitos visuais sutis e elementos vivos em tempo real.
A proposta foi construir uma cena minimalista, porém imersiva, utilizando animações suaves, partículas dinâmicas e composição visual inspirada em ambientes frios e atmosféricos.
Este foi meu **primeiro projeto de wallpaper animado**, marcando o início da minha exploração em experiências visuais interativas para desktop.

<img src="Imagens/TheNorthRemembers.gif" width="500">

**Efeitos:**
- **Personagem central em alta definição** com leve animação de respiração (*breathing effect*), criando sensação de presença viva e movimento sutil contínuo  
- **Aura luminosa azulada dinâmica** posicionada atrás do personagem, utilizando *radial gradient* com pulso suave de intensidade para destacar a silhueta e gerar profundidade cinematográfica  
- **Sistema de neve procedural em múltiplas camadas**, com partículas caindo em velocidades variadas, simulando ambiente congelado e tempestade leve em tempo real  
- **Camada frontal de neve volumétrica** passando à frente do personagem, reforçando imersão tridimensional e sensação de profundidade espacial  
- **Névoa densa atmosférica** posicionada na base da cena, com movimento lateral contínuo (*fog drift animation*) e aplicação de *blur* para criar ambientação fria e misteriosa  
- **Efeito de iluminação dramática indireta** combinando contraste entre fundo claro e sombras suaves, valorizando o personagem e aumentando impacto visual  
- **Sistema de relógio integrado em tempo real**, exibindo horas, minutos, segundos e data completa atualizada dinamicamente dentro da composição visual  
- **Animação de pulso energético no fundo**, expandindo e contraindo suavemente para evitar cena estática e transmitir sensação orgânica constante  
- **Vinheta cinematográfica sutil nas extremidades da tela**, escurecendo bordas gradualmente para direcionar o foco visual ao centro da composição  
- **Composição visual inspirada em atmosfera invernal épica**, recriando cenário frio, silencioso e intenso com estética baseada em fantasia medieval e ambientação dramática


## 🚀 Como usar

### No Wallpaper Engine
1. Abra o **Wallpaper Engine**
2. Clique em **"Criar wallpaper"** e selecione **"Web"**
3. Selecione o arquivo `starfield-wallpaper-static.html`
4. Aplique e aproveite

### No navegador
Basta abrir o arquivo `.html` diretamente no navegador, sem servidor, sem dependências externas.

### Como página web / fundo de site
Os wallpapers podem ser embutidos como `<iframe>` em qualquer projeto web:

```html
<iframe src="starfield-wallpaper-static.html" style="position:fixed;top:0;left:0;width:100%;height:100%;border:none;z-index:-1;"></iframe>
```

### Com [Lively Wallpaper](https://github.com/rocksdanister/lively) *(alternativa open source ao Wallpaper Engine)*
1. Abra o Lively
2. Arraste o arquivo `.html` para a janela
3. Defina como wallpaper ativo



## 🛠 Tecnologias utilizadas

```bash
HTML5
CSS3
JavaScript Vanilla
Canvas API
Wallpaper Engine Web Project
```

## 📁 Estrutura do repositório

```
animated-html-wallpapers/
├── LICENSE
├── starfield-wallpaper-static.html
├── preview.gif
└── README.md
```

> Novos wallpapers serão adicionados seguindo esse padrão.



## 🤝 Contribuindo

Tem uma ideia de wallpaper? Abre uma issue ou manda um pull request, quanto mais efeitos, melhor.


 
## 🙏 Créditos
 
O wallpaper Starfield foi desenvolvido em colaboração com o [Claude](https://claude.ai) (Anthropic), que auxiliou na arquitetura dos efeitos e na implementação do código.



## 📄 Licença
 
[MIT](LICENSE), use, modifique e distribua à vontade.
 

