# Planejador de Rotas da PUCC - Android App

Este projeto consiste em um aplicativo Android desenvolvido em Kotlin utilizando o Android Studio. O objetivo do aplicativo é auxiliar os usuários a planejarem os caminhos mais rápidos e eficientes entre os prédios da Pontifícia Universidade Católica de Campinas (PUCC).

## Funcionalidades

- O usuário pode selecionar o prédio de origem e o prédio de destino desejados.
- Ao clicar no botão "Calcular", o aplicativo utiliza o algoritmo de Dijkstra para encontrar o menor caminho entre os prédios selecionados.
- O algoritmo de Dijkstra é aplicado a um mapa de conexões entre os prédios, que é previamente cadastrado no aplicativo.
- O resultado exibido ao usuário é o tempo estimado para percorrer o caminho mais rápido entre os prédios selecionados.

## Tecnologias Utilizadas

- Kotlin: Linguagem de programação utilizada para desenvolver o aplicativo Android.
- Android Studio: Ambiente de desenvolvimento integrado (IDE) utilizado para criar o aplicativo.
- Algoritmo de Dijkstra: Algoritmo utilizado para encontrar o caminho mais curto em um grafo ponderado.

## Como Executar o Projeto

1. Certifique-se de ter o Android Studio instalado em sua máquina.
2. Clone ou faça o download deste repositório.
3. Abra o Android Studio e importe o projeto.
4. Aguarde até que o Android Studio configure e sincronize o projeto.
5. Conecte um dispositivo Android ou inicie um emulador.
6. Execute o aplicativo no dispositivo/emulador clicando no botão "Run" no Android Studio.

## Limitações e Possíveis Melhorias

- O aplicativo atualmente suporta apenas os prédios cadastrados na PUCC. Para utilizá-lo em outro campus ou ambiente, seria necessário modificar o mapa de conexões entre os prédios.
- A precisão das estimativas de tempo pode variar dependendo das condições reais do ambiente (tráfego, condições climáticas, etc.).
- O aplicativo não leva em consideração as preferências pessoais do usuário, como evitar escadas, preferir elevadores, etc. Essa funcionalidade poderia ser implementada para oferecer rotas personalizadas.
- Atualmente, o aplicativo não possui uma interface gráfica sofisticada. A melhoria da interface do usuário e a adição de recursos visuais podem tornar a experiência do usuário mais agradável e intuitiva.

## Contribuição

Contribuições para a melhoria deste projeto são sempre bem-vindas! Se você deseja contribuir, sinta-se à vontade para enviar pull requests com suas alterações ou abrir problemas para relatar problemas ou sugerir novos recursos.

Espero que este projeto seja útil para ajudar os usuários a encontrar os caminhos mais rápidos e melhores entre os prédios da PUCC. Divirta-se explorando o aplicativo e tenha uma ótima experiência de navegação na universidade!
