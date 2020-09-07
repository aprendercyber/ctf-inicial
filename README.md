# ctf-inicial
Primeiro CTF


Este repositório tem como finalidade compartilhar as experiências adquiridas ao montar uma competição do tipo CTF (Capture The Flag). As grandes premissas da competição eram gastar o mínimo possível e preparar desafios que levassem aos participantes a entender conceitos básicos de segurança da informação.

O texto será dividido nos seguintes tópicos: Planejamento, Montagem dos desafios, Montagem da Infra, Execução e uma breve Conclusão.

## 1. Planejamento
  Com base nas premissas de baixo custo e nível de dificuldade inicial, foi planejado um CTF que utilizasse uma plataforma já conhecida e testada, uma VPS de baixo custo e desafios que necessitassem do mínimo de infraestrutura possível.
  Com relação a plataforma, após a leitura de vários relatos na internet chegou-se a conclusão que a solução escolhida deveria ser de fácil configuração, permitisse a escolha de vários tipos de desafios, gerência de usuários facilitada e se possível permitisse a instalação em um container. A plataforma CTFd [1] foi a escolhida.
  A instalação da plataforma é bem simples, bastando instalar docker no VPS e executar o pull da versão oficial do CTFd disponível no DockerHub [2].
  No tocante a VPS, foram comparados os valores e serviços oferecidos na: AWS, DreamHost, AlibabaCloud, MercadoLivre.  Por conta da alta do dólar e pela falta de experiência do organizador, foi decidido que a plataforma deveria possuir ao menos 04 Gb de Ram, plataforma de gerência de fácil utilizadação e que pudesse ser paga em reais. No Mercadolivre foi possível encontrar uma VPS por 22,00 reais (somente no primeiro mês) com todas as características desejadas [3], principalemente no quesito preço, já que custava em média 3,7 Usd.
  Os desafios são a razão de ser de um CTF, logo a maior parte do tempo de planejamento se focou nesse tócpico. Com base em alguns CTFs conhecidos e com a visão de quem trabalha com segurança da informação foram planejados desafios que levassem ao participante pensar, pesquisar e resolver problemas sem necessáriamente utilizar plataformas ou tecnologias avançada, explorando o máximo possível dos conceitos basilares da computação. 
  

## 2. Elaboração dos desafios

## 3. Montagem da Infraestrutura

## 4. Execução

## 5. Conclusão



[1]:https://github.com/CTFd/CTFd
[2]:https://hub.docker.com/r/ctfd/ctfd
[3]:https://produto.mercadolivre.com.br/MLB-1073036594-servidor-vps-xeon-34ghz-4gb-ram-200gb-hdd-linux-_JM#position=1&type=item&tracking_id=9ce22eb8-45a6-43bb-85a3-6f2e5335f51c
