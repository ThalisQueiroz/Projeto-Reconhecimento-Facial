# Sistema de Acesso Biométrico Utilizando Reconhecimento Facial

##Resumo

Este projeto apresenta um sistema inovador de controle de acesso baseado em reconhecimento facial, desenvolvido com o objetivo de oferecer uma solução segura e eficiente para ambientes residenciais e corporativos. A aplicação utiliza técnicas de inteligência artificial e visão computacional para identificar usuários autorizados, substituindo métodos tradicionais como chaves e senhas.

##Funcionamento

O sistema captura imagens da face do usuário através de uma webcam e, utilizando algoritmos de deep learning, realiza a comparação com um banco de dados de rostos previamente cadastrados. Ao identificar uma correspondência, o sistema aciona um relé, liberando o acesso.

##Tecnologias Utilizadas

-Hardware: Arduino Uno, display OLED, teclado matricial, relé, webcam.

-Software: Python, OpenCV, face_recognition.

-Bibliotecas: OpenCV (processamento de imagens), face_recognition (reconhecimento facial), os (manipulação de arquivos), serial (comunicação serial), time (controle de tempo), pickle (serialização).

##Arquitetura

-Captura de imagem: A webcam captura imagens em tempo real.

-Pré-processamento: As imagens são pré-processadas para otimizar o reconhecimento facial.

-Detecção de rosto: O algoritmo de detecção de rosto identifica a localização da face na imagem.

-Extração de características: São extraídas características faciais únicas para cada indivíduo.

-Comparação: As características extraídas são comparadas com as características armazenadas no banco de dados.

-Decisão: Se a similaridade entre as características for acima de um determinado limiar, o acesso é concedido.

##Funcionalidades

-Cadastro de usuários: Permite cadastrar novos usuários através da captura de imagens da face.
Reconhecimento facial em tempo real: Identifica usuários autorizados de forma rápida e precisa.

-Interface amigável: Dispõe de um display OLED para interação com o usuário.

-Alta segurança: Utiliza algoritmos de reconhecimento facial robustos para evitar fraudes.

##Possibilidades de Melhoria

-Escalabilidade: Integração com um banco de dados em nuvem para gerenciar um número maior de usuários.

-Precisão: Utilização de modelos de deep learning mais complexos para melhorar a taxa de acerto.

-Segurança: Implementação de mecanismos de autenticação multifator para aumentar a segurança.

##Conclusão

O sistema de acesso biométrico desenvolvido neste projeto demonstra o potencial da inteligência artificial aplicada à segurança. A utilização de reconhecimento facial oferece uma solução prática e eficiente para o controle de acesso, com diversas aplicações em ambientes residenciais e corporativos.
