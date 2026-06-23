<h1 align="center">
<img src="https://raw.githubusercontent.com/termucoin/termucoin/master/share/pixmaps/termucoin256.svg" alt="Termucoin" width="256"/>
<br/><br/>
Termucoin Core [TERM, ]  
</h1>

Termucoin é uma criptomoeda voltada para a comunidade inspirada num   . O software Termucoin Core permite que qualquer pessoa opere um nó nas redes blockchain Termucoin e usa o método de hash Scrypt para Prova de Trabalho. É adaptado do Bitcoin Core e outras criptomoedas.

Para mais informações acerca das taxas de transação utilizadas na rede Termucoin, por favor clica aqui:
[taxas recomendadas](doc/fee-recommendation.md).

## Utilização 💻

Para começares a tua jornada com o Termucoin Core, ve o [manual de instalação](INSTALL.md) e o [guia para iniciantes](doc/getting-started.md).

A API JSON-RPC incluida no Termucoin Core é auto documentada e pode ser vista com o comando `termucoin-cli help`, mais informações detalhadas sobre cada comando podem ser encontradas utilizando `termucoin-cli help <command>`.

### Quais as portas

O Termucoin Core utiliza por padrão a porta `8599` para comunicação em rede
ponto-a-ponto que é necessária para sincronizar a blockchain da "rede principal",
(mainnet), e se manter atualizadas de novas transações e blocos. Adicionalmente a
porta JSONRPC pode ser aberta que por defeito é `8598` para a rede principal.
É fortemente recomendado a não expor as portas RPC publicamente na internet.

|  Função  | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   8599 |   12253 |   8433 |
| RPC      |   8598 |   12252 |   8432 |

## Desenvolvimento continuo - Plano Lua 🌒

O Termucoin Core é um programa de código aberto gerido pela comunidade. O processo de desenvolvimento é aberto e visivel publicamente; qualquer um pode ver, discutir e trabalhar no programa.

Recursos principais de Desenvolvimento:

* [Projetos do Github](https://github.com/termucoin/termucoin/projects) é utilizado para conduzir trabalhos planeados ou que estejam em desenvolvimento para as próximas atualizações.
* [Discussão do Github](https://github.com/termucoin/termucoin/discussions) é usado para discutir sobre as funcionalidades, planeadas ou não, relacionadas ao desenvolvimento do programa Termucoin Core, os protocolos adjacentes e o criptoativo TERM.

### Estratégia das Versões
Os numeros de compilação seguem a seguinte semantica:  ```major.minor.patch```

### Ramificações
Este repositório possui 3 principais ramificações (branchs), são estas:

- **master:** Estável, contém a ultima versão da ultima atualização principal *major.minor*.
- **maintenance:** Estável, contém a ultima versão de atualizações anteriores, que ainda estão em manutenção. Formato: ```<version>-maint```
- **development:** Instável, contém código novo para atualizações planeadas. Formato: ```<version>-dev```

*As ramificações Master e Maintenance, são exclusivamente mutáveis por lançamento. Atualizações*
*planeadas terão sempre uma ramificação de desenvolvimento e as solicitações de inclusão deverão ser*
*encaminhadas por meio destas. Ramificações de manutenção existem apenas para **correção de bugs,***
*por favor, encaminhem novos recursos na ramificação de desenvolvimento com a versão mais alta.*

## Contribuindo 🤝

Se encontrastes um bug ou tivestes alguma situação incomum com este programa, por favor informa-nos do ocorrido utilizando o [sistema de problemas (issues)](https://github.com/termucoin/termucoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Por favor, acede ao [guia de contribuições](CONTRIBUTING.md) para ver como podes participar
no desenvolvimento do Termucoin Core. Existem alguns [pedidos de ajuda](https://github.com/termucoin/termucoin/labels/help%20wanted)
onde os contribuintes terão uma grande importância e apreço. wow.

## Perguntas frequentes ❓

Tens alguma questão relacionada com o Termucoin? Talvez já haja uma resposta, disponivel no
[FAQ](doc/FAQ.md) ou na
[seção Q&A](https://github.com/termucoin/termucoin/discussions/categories/q-a)
do nosso quadro de discussão!

## Licenças ⚖️
Termucoin Core é disponibilizada sob os termos de uso da licença MIT. Vê,
[COPYING](COPYING) para mais informações.
