🏎️ Projeto Expositor de Carros (Avançado) - VR
Este projeto consiste em uma experiência avançada de Realidade Virtual (VR) desenvolvida no Unity, focada em um ambiente de showroom automotivo de luxo. Criado com base nas aulas de Metaverso, o projeto utiliza o Meta SDK para fornecer interações imersivas, destacando a mecânica de agarrar objetos (Grab Interaction) e sistemas de interface de usuário (UI) por proximidade.

Autor: Luciano Damião de Brito

Trilha: 1

🛠️ Tecnologias e Versões
Engine: Unity 6000.3.13f1

SDK: Meta XR All-in-One SDK

Plataforma Alvo: Android (Oculus Quest 2 / 3)

🚀 Configuração do Ambiente
Para garantir que o projeto funcione corretamente na sua máquina, siga as etapas de configuração abaixo:

1. Alteração da Plataforma de Build
Como o foco do projeto são os dispositivos Meta Quest, é necessário alterar a plataforma de compilação:

Vá em File > Build Settings.

Selecione Android na lista de plataformas.

Clique em Switch Platform.

Certifique-se de que o Texture Compression está definido como ASTC.

2. Instalação do Meta SDK
O projeto utiliza as ferramentas oficiais da Meta para rastreio e interação. Para instalar:

Vá em Window > Package Manager.

Clique no ícone de + e selecione Add package from git URL ou procure por Meta XR All-in-One SDK na Unity Asset Store.

Garanta que o Oculus XR Plugin esteja habilitado em Edit > Project Settings > XR Plug-in Management.

🏢 Cenário e Elementos do Projeto
O ambiente virtual foi expandido para simular uma concessionária de alto padrão com maior complexidade. A cena é composta por:

🚗 5 Expositores contendo modelos de carros de luxo de alta fidelidade.

📋 Painéis Informativos Automáticos: Ao se aproximar de qualquer expositor, um quadro com as informações técnicas do automóvel surge automaticamente para o usuário.

🔑 5 Chaves posicionadas estrategicamente, configuradas com Grab Interaction para manipulação direta.

🪴 5 Plantas decorativas distribuídas pelo ambiente para detalhamento estético.

🖥️ 2 Mesas de escritório completas com suas respectivas cadeiras.

🛋️ 1 Conjunto de sofá compondo a área de recepção e descanso.

🧱 Estrutura Física: Paredes delimitadoras, Chão (Floor) e Céu (Skybox).

🎯 Objetivo do Projeto
O objetivo principal foi elevar o nível de interatividade em um expositor de carros usando Realidade Virtual. Além da implementação da interação de Grab (agarrar) nas chaves, o projeto focou na automação de eventos baseados na posição do usuário, permitindo que informações sobre os veículos sejam exibidas de forma fluida e intuitiva ao chegar perto dos expositores.

🚧 Desafios e Aprendizados
Durante o desenvolvimento, o maior desafio técnico permaneceu sendo a utilização do simulador nativo do Unity (XR Device Simulator). Devido a limitações de funcionamento e instabilidades do simulador, foi necessário buscar alternativas de testes para garantir a precisão das interações e dos gatilhos de proximidade.

📹 Demonstração em Vídeo
Confira o resultado desta versão avançada e o projeto em execução através do link abaixo:

🔗 Assistir demonstração no YouTube através do link: https://youtu.be/OoUyWKYUjfk
