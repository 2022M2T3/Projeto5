# Inteli - Instituto de Tecnologia e Liderança 

<p align="center">
<a href= "https://www.inteli.edu.br/"><img src="https://www.inteli.edu.br/wp-content/uploads/2021/08/20172028/marca_1-2.png" alt="Inteli - Instituto de Tecnologia e Liderança" border="0"></a>
</p>

# Yamaha Management System 

## Gakki 

## Integrantes: <a href="https://www.linkedin.com/in/victorbarq/">Beatriz Hirasaki</a>, <a href="https://www.linkedin.com/in/frederico-schur-6a3313237/">Frederico Schur</a>, <a href="https://www.linkedin.com/in/gutopompeo/">Luiz Augusto Ferreira</a>, <a href="https://www.linkedin.com/in/luiz-carlos-da-silva-j%C3%BAnior-82a0a5216/">Luiz Carlos da Silva</a>, <a href="https://www.linkedin.com/in/pedro-silva-14343022a/">Pedro Silva</a>, <a href="https://www.linkedin.com/in/sergiobalucas/">Sergio Lucas</a>, <a href="https://www.linkedin.com/in/thain%C3%A1-lima-169177232/">Thainá Lima</a>. 

## Descrição

  Para este módulo tivemos como parceiro de projeto a Yamaha, uma empresa que detém como principal foco a produção de motocicletas. Nosso parceiro vem buscando um método de gerenciar melhor sua equipe de TI, pois hoje não dispõem de um sistema que mostre com clareza a alocação e disponibilidade de seus funcionários nos seus projetos, sendo assim, foi proposto criar um sistema de capacity humano que demonstre em um dashboard as informações tanto do projeto quanto da equipe de TI. O Principal objetivo do projeto é mostrar através de um gráfico de saturação, as informações citadas anteriormente, alem das alocacoes de cada funcionario.
<br><br>
Meu projeto é um exemplo de como utilizar o github.
<br><br>
<p align="center">
<img src="https://pix4free.org/assets/library/2021-01-20/originals/game.jpg" alt="NOME DO JOGO" border="0">
  Game by <a href="http://www.nyphotographic.com/">Nick Youngson</a> <a rel="license" href="https://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a> <a href="http://pix4free.org/">Pix4free</a>
</p>


💡 De um a dois parágrafos sobre o que é seu projeto e o que ele faz.
<br><br>
Então para atingirmos o objetivo da Yamaha, começamos por introduzir uma tela de login para os administradores já cadastrados no sistema. A tela de login consiste em um design único autoral.


<br><br>
  A página inicial é o dashboard, área voltada completamente para a visualização dos gráficos de saturação e quantidade de projetos, além de oferecer uma visão de todos os projetos através do formato de lista. Já na próxima página de nossa aplicação foram criadas abas como: criar funcionário, criar novo projeto, criar governança e criar nova função. Tudo isso, gerando informações que irão para o bancos de dados para que possa ser usada na aplicação. Além das duas abas principais, que são o dashboard e a página de adicionar dados, também implementamos duas páginas suplementares, onde uma delas mostra de maneira mais detalhada o gráfico de saturação e as informações relacionadas a ele e a outra mostra detalhes dos projetos da Yamaha.
  O objetivo principal deste projeto é, alêm da administração de projetos e funcionarios, o gráfico de saturação, que caractetiza o workload dos funcionarios.  O gráfico mostra a capacidade total da empresa em horas, fazendo uma mêdia entre os funcionários CLTS e tercerizados, gerando uma linha da demanda ideal da empresa.
<br><br>

## 🛠 Estrutura de pastas

-Raiz<br>
|<br>
|-->documentos<br>
  &emsp;|-->antigos<br>
  &emsp;|GDD.docx ou Documentação.docx<br>
|-->executáveis<br>
  &emsp;|-->windows<br>
  &emsp;|-->android<br>
  &emsp;|-->HTML<br>
|-->imagens<br>
|-->src<br>
|readme.md<br>

A pasta raiz contem dois arquivos que devem ser alterados:

<b>README.MD</b>: Arquivo que serve como guia e explicação geral sobre seu projeto. O mesmo que você está lendo agora.

Há também 4 pastas que seguem da seguinte forma:

<b>documentos</b>: Aqui estarão todos os documentos do projeto, mas principalmente o <b>GDD (Game Design Document)/Documentação do Sistema</b>. Há uma pasta <b>antigos</b> onde estarão todas as versões antigas da documentação.

<b>executáveis</b>: Aqui estarão todos os executáveis do jogo, prontos para rodar. Há no mínimo 3 pastas, uma para binários <b>Windows</b>, uma para binários <b>android</b> e uma para a <b>Web/HTML</b>

<b>imagens</b>: Algumas imagens do jogo/sistema e logos prontos para serem utilizados e visualizados.

<b>src</b>: Nesta pasta irá todo o código fonte do jogo/sistema, pronto para para ser baixado e modificado.

## 🛠 Instalação

<b>Android:</b>

Faça o Download do JOGO.apk no seu celular.
Execute o APK e siga as instruções de seu telefone.

```sh
Coloque código do prompt de comnando se for necessário
```

<b>Windows:</b>

Não há instalação! Apenas executável!
Encontre o JOGO.exe na pasta executáveis e execute-o como qualquer outro programa.

```sh
Coloque código do prompt de comnando se for necessário
```

<b>HTML:</b>

Não há instalação!
Encontre o index.html na pasta executáveis e execute-o como uma página WEB (através de algum browser).

## 📈 Exemplo de uso

Alguns exemplos interessantes e úteis sobre como seu projeto pode ser utilizado.

Adicione blocos de códigos e, se necessário, screenshots.

Este modelo pode ser copiado e utilizado à vontade.

Através da cópia/clone/ download do repositório, altere os dados do readme.md e carregue os arquivos de seu projeto.

## 💻 Configuração para Desenvolvimento

Descreva como instalar todas as dependências para desenvolvimento e como rodar um test-suite automatizado de algum tipo. Se necessário, faça isso para múltiplas plataformas.

Para abrir este projeto você necessita das seguintes ferramentas:

-<a href="https://godotengine.org/download">GODOT</a>

```sh
make install
npm test
Coloque código do prompt de comnando se for necessário
```

## 🗃 Histórico de lançamentos

A cada atualização os detalhes devem ser lançados aqui.

* 0.2.1 - 25/01/2022
    * MUDANÇA: Atualização de docs (código do módulo permanece inalterado)
* 0.2.0 - 15/01/2022
    * MUDANÇA: Remove `setDefaultXYZ()`
    * ADD: Adiciona `init()`
* 0.1.1 - 11/01/2022
    * CONSERTADO: Crash quando chama `baz()` (Obrigado @NomeDoContribuidorGeneroso!)
* 0.1.0 - 10/01/2022
    * O primeiro lançamento adequado
    * MUDANÇA: Renomeia `foo()` para `bar()`
* 0.0.1 - 01/01/2022
    * Trabalho em andamento

## 📋 Licença/License

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/2022M2T3/Projeto5">Yamaha Project Management</a> by <span property="cc:attributionName">Grupo Gakki</span> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>

## 🎓 Referências

Aqui estão as referências usadas no projeto.

1. <https://github.com/iuricode/readme-template>
2. <https://github.com/gabrieldejesus/readme-model>
3. <https://creativecommons.org/share-your-work/>
4. https://chooser-beta.creativecommons.org/
5. <https://freesound.org/>
6. Músicas por: <a href="https://freesound.org/people/DaveJf/sounds/616544/"> DaveJf </a> e <a href="https://freesound.org/people/DRFX/sounds/338986/"> DRFX </a> ambas com Licença CC 0.
