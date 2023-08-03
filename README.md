# projeto-phising-linux
Este é um repositório para o projeto de formação em Cybersecurity Specialist da DIO, ministrado por Cassiano Ricardo de Oliveira Peres ([@cassiano-dio](https://github.com/cassiano-dio). O curso aborda tópicos importantes em segurança cibernética, incluindo phishing, engenharia social e o uso do setoolkit.

O objetivo deste repositório é relatar o uso do SEToolkit para clonar o layout de um site e colher informações credenciais de um formulário de login, contendo endereço de e-mail e senha. Na primeira tentativa, foi utilizado o Facebook como site alvo. No entanto, por algum motivo, no site clone, o botão para concluir o formulário de login deixou de funcionar. Portanto, não foi possível receber nenhuma informação no SEToolkit. 

Após várias tentativas, foi decidido trocar o site alvo para o GitHub. O processo de construção do site clone foi reiniciado e as informações de e-mail e senha foram inseridas no formulário de login do GitHub:

![Captura de tela 2023-08-03 003935](https://github.com/OlStudios/projeto-phising-linux/assets/95282667/f288a71e-759f-4da3-a26b-29fd9e7f42bd)

As informações credenciais foram recebidas no terminal:

![Captura de tela 2023-08-03 004019](https://github.com/OlStudios/projeto-phising-linux/assets/95282667/6ce2af57-391b-41d9-81ac-dcc9094acba5)

Apesar de ter sido necessário mudar o site alvo, foi possível compreender o funcionamento da ferramenta SEToolkit e simular uma tentativa de phishing bem sucedida.
