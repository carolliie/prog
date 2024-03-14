# simon-game
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=%20FINALIZADO&color=purple&style=for-the-badge"/>

## Descrição

Este repositório foi criado para servir como acervo aos códigos feitos a partir de estudos dentro da matéria de laboratório de programação.

O link disponível para a página web do repositório, direciona o usuário a um mini-jogo, chamado Simon Game.

O programa foi desenvolvido baseado no paradigma de programação orientado a eventos e no paradigma declarativo, onde o código funciona a partir da determinação de eventos com uma estrutura mais compreensível de programação.

Para ver mais projetos, entre nos repositórios do meu Github. 📺

                                            * Simon Game *

                                            -> How to Play:

- o mini-jogo é baseado em teste de memória, ou seja, o player deve memorizar as cores, sons e padrões dentro do jogo;

- ex.: level 1
obj.: acertar as cores que o sistema do jogo irá retornar.
assim que o botão com a cor acionada for clicado e a tentativa for correta, obtém-se sucesso e prossegue-se para um
outro nível.;

- a cada nível, a dificuldade inserida nos padrões de memorização, é aumentada;

- caso a tentativa de clique seja fora do padrão (incorreta), é acionado o som de "game over" e o jogo é reiniciado.

                                            Have a nice game!


                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡏⠒⠀⠀⠀⣀⡀⠀⣀⡀⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⠲⢤⡀⠀⠀⢀⠀⡇⠀⠁⠀⠀⢰⡏⢻⣿⣿
                ⣿⣿⣿⣿⣿⣿⠻⣿⣿⣿⣿⣿⣿⣿⣿⠹⠶⠊⠉⠀⠀⠀⠀⢸⢶⡢⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢁⣼⡴⢀⠇⠀⠀⠀⠀⠀⠀⠉⠿⢿
                ⣿⣿⣿⣿⣿⣿⣷⡙⢻⣿⣿⣿⣿⣿⣿⣶⣶⣬⣤⣄⣨⣄⣀⠈⠈⡍⠉⠁⡏⠀⠀⠀⠀⠀⡀⣅⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⠄⣤⠇⠧⣿⣄⣠⠚⢻⠀⠀⠀⠀⠀⠈
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣴⣄⡀⠀⠄⠀⠋⠈⣙⣤⣤⣤⣤⣶⣦⣤⣶⣶⣦⣶⣭⣴⠾⠀⢨⢲⡟⠋⠀⣴⣿⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⣁⣁⣈⣉⣙⣟⣻⣿⢻⣿⣿⣧⣤⣤⣬⣹⣾⣿⣿⣿⣾⣿⣟⡛⢛⠛⠉⢁⠁⢟⡿⢿⣶⣡⣿⠆⢀⡾⡟⣿⠀⠀⠀⠀⠀⢰
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⣿⣿⢛⠿⢿⠿⠋⠽⣿⣿⢿⣿⣿⠀⠀⠀⠙⣿⡿⢿⣿⣿⣋⣿⣿⣿⡟⠻⢿⣿⡥⠲⣋⢸⡄⢛⢀⡞⠀⡇⣼⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡷⢻⠀⠈⠻⢿⠏⠓⠤⣭⣩⣿⣦⣴⣿⣎⣿⣿⡏⠀⠀⠀⠀⢻⣿⡆⠁⢁⢴⡮⠯⢭⡤⢀⡽⠈⠽⡋⠉⢹⠃⣻⣿⠁⠀⢹⠋⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠘⣧⠀⠀⠈⢆⠀⠀⠀⠀⠨⠟⣻⢿⣿⢿⣿⣇⠀⠀⠀⠀⠈⢿⣆⠀⡀⢀⡈⢑⡖⠒⠏⠀⠀⠀⠀⠀⣼⠀⣼⠈⠀⠀⣸⠀⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⢿⣿⣿⣿⣿⣆⠙⠷⣄⣀⠀⠀⠀⠈⠀⠀⢐⣡⢾⠧⣸⣿⣧⠀⠀⠀⠀⠀⠈⢯⢧⡀⠀⠉⢖⡌⠁⠀⠀⠀⠀⢀⡼⠃⠀⣿⢀⠇⢠⠏⠀⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣀⡀⠀⢉⢉⢉⣒⠒⠊⠉⠉⠁⡀⣧⣶⣿⠇⠀⠀⠀⠀⠀⠀⠈⠳⣭⣓⠦⠤⠤⠤⠤⠴⠶⠚⠉⠀⠀⣰⣿⠋⢀⡏⠀⠀⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣧⣋⠐⡾⢷⠇⠀⠀⠀⠀⣹⡟⣿⣟⠂⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠱⠇⠰⢻⠀⠀⠀⠀⣰⣴⣤⣠⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠀⠀⠐⠀⠀⠀⠀⣸⣿⣤⣿⣍⠀⠀⠀⠀⠀⠀⣀⣤⢀⢬⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⠀⢀⠞⠀⠀⠀⠀⠘⠿⠿⠇⠁
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣮⡈⠈⠀⠁⢠⡜⢹⣿⣿⣿⣿⣿⣦⣤⣤⣴⣿⣿⣿⠃⠈⢖⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢼⠚⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⠴⠀⠀⢢⣎⣤⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣾⣿⣯⣿⣅⠠⢙⢤⡀⠀⠀⠀⠀⠀⠀⠀⠀⡿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠏⣿⣿⠖⠀⣠⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣥⠈⢅⠀⠀⠀⠀⠀⠀⢠⠇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠃⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡝⣧⡀⠀⠀⠀⠐⡾⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⣿⣿⣿⣏⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠆⠀⠀⠐⠁⣰⣧⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡉⣉⣩⣍⣙⣙⣉⢁⠉⠁⠋⠙⢻⣿⣿⣿⣿⠀⠄⠀⡤⣶⣿⣿⣿⣆⠀⠀⠀⠀⠀⠀⠀⡰⠆⢠⣮
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⡋⠙⡙⠟⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡄⢈⢠⠀⣿⣿⣿⣿⡽⠀⣾⣿⣿⣿⣿⣿⣿⣆⠀⠀⠀⠀⠀⠀⠀⠀⢜⣿
                ⣿⣿⣿⣿⣿⡿⢿⣿⣿⣿⣤⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣫⣷⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⡜⢵⣿⣿⣿⣿⣿⠣⣾⣿⣿⣿⣿⣿⣿⣿⡿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘
                ⣿⣿⣿⠉⣙⣥⣿⡟⣉⣭⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⣿⣿⣿⣿⣟⣽⣽⣎⢿⣿⣿⣿⣿⣇⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀
                ⣿⣿⣿⣿⣷⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⢾⣿⣏⡄⢻⣿⣿⣿⣿⣿⣿⣶⣦⣤⣀⡀⠀⠀⠀
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⢋⣾⢿⢷⣇⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢃⣶⢿⣏⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠯⡦⢫⣽⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
                ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢿⣟⠋⡠⣞⢓⣿⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿