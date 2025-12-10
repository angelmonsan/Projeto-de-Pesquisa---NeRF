# Anotações do Grupo de Pesquisa NeRF

Estas são as anotações referentes ao grupo de pesquisa NeRF (Neural Radiance Fields), que ocorre aos sábados.  

O principal objetivo do grupo é o desenvolvimento de uma inteligência artificial capaz de gerar modelos tridimensionais (3D) a partir de imagens, permitindo posteriormente a exploração desses modelos em ambientes de realidade virtual. Em outras palavras, a ideia é criar uma ferramenta que una aprendizado de máquina, visão computacional e imersão digital, abrindo caminho para novas aplicações tanto na área de tecnologia quanto nas artes visuais e interativas. O grupo ainda está em sua fase inicial, mas decidi participar porque achei o projeto extremamente interessante e promissor. Além disso, essa oportunidade me permitirá aprofundar meu entendimento sobre a criação e manipulação de modelos 3D, algo que pode contribuir significativamente para melhorar a qualidade dos meus próprios projetos pessoais e acadêmicos.  

Os responsáveis pela orientação do grupo são os professores Gustavo e Eron, que enfatizaram desde o início a importância do comprometimento. Segundo o professor Gustavo, os participantes que não comparecessem com frequência ou não demonstrassem envolvimento ativo poderiam ser convidados a se retirar do grupo, já que o projeto requer dedicação continua, curiosidade e colaboração efetiva. Estou bastante animado com a experiência e mal posso esperar para contribuir com o desenvolvimento das pesquisas, aprendendo mais sobre o funcionamento dos NeRFs e aplicando esse conhecimento de maneira prática nos projetos futuros.  

---

*Link das anotações que eu faço:*

https://sites.google.com/edu.unifil.br/aluno-angelo-dos-santos-montei?usp=sharing

---

# Sites e Vídeos Recomendados (para consulta futura)

Para aprimorar o aprendizado sobre NeRFs, modelagem 3D e realidade aumentada, seria interessante consultar materiais como:  

- Tutoriais sobre Neural Radiance Fields e implementação de modelos 3D a partir de imagens.
  
- Conteúdos introdutórios e avançados de aprendizado profundo*aplicado à visão computacional.
  
- Recursos sobre realidade aumentada (AR) e realidade virtual (VR), incluindo princípios básicos de renderização 3D.
  
- Artigos e estudos de caso sobre a integração de IA e ambientes digitais imersivos.  

---

*Links de alguns tutoriais e alguns artigos:*

https://unity.com/pt/solutions/xr/ar

https://theaisummer.com/nerf/

https://medialab.dei.unipd.it/research-areas/nerf/

https://deeprender.ai/blog/plenoxels-radiance-fields-without-neural-networ

https://arxiv.org/html/2501.13104v1

---

# Códigos e Implementações

Os códigos produzidos durante o grupo de pesquisa ficarão organizados nesta seção, conforme forem sendo programados, testados e corrigidos. Cada bloco de código será documentado e comentado, permitindo acompanhar o desenvolvimento e entender os experimentos realizados passo a passo. No momento, ainda estou estudando e revisando melhor a matéria, pois alguns dos códigos que desenvolvi apresentaram erros e outros problemas. Assim que tudo estiver ajustado, funcionando corretamente e organizado, irei disponibilizar aqui o conjunto completo dos códigos.

---

*Link de algumas programações feitas (Pode usar para se inspirar ou desenvolver outras coisas):*

https://messenger.abeto.co/

https://abeto.co/

https://www.igloo.inc/

https://qodeinteractive.com/magazine/playable-interactive-websites

https://webflow.com/blog/interactive-website?

https://www.mockplus.com/blog/post/interactive-website-example/

https://medialab.dei.unipd.it/research-areas/nerf/

---

# Origem e Evolução da Realidade Aumentada, Modelos 3D e Aplicações em Jogos

A Realidade Aumentada (RA) é uma tecnologia que combina o mundo físico com elementos digitais, como imagens, sons, textos e objetos virtuais, utilizando dispositivos como smartphones, tablets ou óculos especiais. Ao contrário da Realidade Virtual (RV), que transporta o usuário para um ambiente totalmente digital, a RA mantém a percepção do mundo real e adiciona camadas de informação virtual sobre ele, criando experiências interativas e dinâmicas. A história da RA remonta à década de 1960, quando o pesquisador Ivan Sutherland desenvolveu o primeiro protótipo de sistema de realidade virtual, conhecido como "The Sword of Damocles". Esse sistema permitia a visualização de objetos tridimensionais (3D) sobre o ambiente real, por meio de um capacete conectado a computadores, sendo considerado o primeiro passo na integração entre mundo físico e objetos virtuais. O nome curioso se deve à estrutura suspensa sobre a cabeça do usuário, lembrando a espada de Dâmocles da mitologia. Na década de 1990, o termo "Realidade Aumentada" foi cunhado pelo cientista Thomas Caudell, enquanto trabalhava na Boeing. Ele desenvolveu um sistema para auxiliar trabalhadores na montagem de aeronaves, sobrepondo instruções visuais aos objetos reais. Esse uso prático marcou o início da aplicação industrial da RA, demonstrando que a tecnologia podia reduzir erros, agilizar processos e melhorar a produtividade.


Paralelamente, a criação de modelos tridimensionais (3D) tem raízes ainda mais antigas, iniciando na década de 1960 e 1970, com pesquisadores em computação gráfica desenvolvendo técnicas para representar objetos e cenas em três dimensões em computadores. Esses modelos permitiam simular formas, volumes e iluminação, sendo inicialmente usados em design industrial e cinema. O desenvolvimento dos modelos 3D digitais evoluiu ao longo das décadas, com técnicas de renderização mais avançadas, softwares especializados e a introdução de métodos de captura de objetos reais, como fotogrametria e, mais recentemente, redes neurais como os NeRFs (Neural Radiance Fields). Com o avanço da tecnologia de RA e modelos 3D, surgiram aplicações inovadoras no entretenimento e nos jogos. Jogos como Pokémon GO demonstraram o potencial da RA para criar experiências interativas, onde elementos virtuais se integram ao mundo real, incentivando o movimento e a exploração física do ambiente pelo jogador. Além disso, motores de jogos modernos, como Unity e Unreal Engine, passaram a permitir o uso de modelos 3D detalhados em RA, possibilitando desde jogos educativos até simulações complexas em realidade aumentada.

---

## A evolução da RA e dos modelos 3D levou a aplicações em diversas áreas:

- *Educação:* visualização de modelos científicos e históricos em 3D sobre o ambiente real.

- *Saúde:* simulação de procedimentos cirúrgicos e treinamentos médicos.

- *Indústria e Manufatura:* manutenção assistida, treinamentos de operadores e inspeção de equipamentos.

- *ntretenimento e Jogos:* experiências interativas que misturam objetos digitais ao mundo real, aumentando a imersão e a ludicidade.

Hoje, a combinação de RA e modelos 3D está se tornando cada vez mais acessível, com dispositivos portáteis capazes de processar gráficos complexos em tempo real. A integração dessas tecnologias permite experiências ricas, imersivas e altamente interativas, transformando a forma como aprendemos, jogamos, trabalhamos e interagimos com o mundo ao nosso redor.

---

*Assista os vídeos logo abaixo caso queira aprender mais:* 

https://youtu.be/ZC1rIIu9ni4?si=sOww8zF3plR9CZZb

https://youtu.be/FuuirfHFG2M?si=KiojYbhWr3lMLYl5

https://youtu.be/DjkIhyrSzvw?si=B6QfU-zUG37lfrdZ

https://youtu.be/OZMi5WmvgME?si=iLH1XMrRXC72k68a

---
