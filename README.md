# Comandos do Markdown no GitHub
 Explicações com comandos que exemplificam os usos das mecânicas do Markdown do GitHub

 ## Mecânicas da Linguagem
---
# Texto
***
1. ### Deixando em **Negrito**:
   * Usa-se duplo asterisco "**" ou duplo underline "__" entre a palavra desejada, tanto atrás como na frente.
1. ### Deixando em _Itálico_:
   * Usa-se apenas um asterisco "*" ou um underline "_" de modo similar ao do negrito.
1. ### ~~Riscando~~ a palavra:
   * Usa-se duplo til "~~" entre a palavra desejada, de modo similar aos anteriores.
1. ### Os efeitos anteriormente mostrados podem ser ~~_**combinados**_~~ entre si:
   * Para isso basta seguir o padrão, caso queira uma palavra em Itálico e em Negrito use "_**" ou "*__" de modo similar aos outros exemplo, entre a palavra desejada, segue a mesma lógica para as demais combinações.
1. ### Destacando uma linha de `Código`:
   * Usa-se apenas uma crase "`", novamente entre a palavra desejada, porém usado apenas para destacar uma linha, caso queira um trecho deve-se usar uma sequência de 3 crases "```" de modo que as 3 crases inicias formem um bloco com as 3 últimas crases e o código esteja no meio:

"```"

Exemplo

"```".

* Ex.: 
```
int Main() {

printf("Hello World!");

return 0;

}
```

6. ### Utilizando listas:
   * Para fazer uma lista não numerada, ou seja, apenas a marcação do ponto, usa-se um asterisco "*" ou um sinal de menos "-", dá-se um espaçamento e começa a escrever o que quer.
   * Já para listas numeradas usa-se "1." e espaçamento, para dar seguimento a numeração basta apenas utilizar de novo o "1." ou qualquer outro número que você queira, caso necessite especificar.
   1. Para listas encadeadas e necessário já ter um lista formada, após isso, quando for criar a outra numeração, dê 3 espaços e comece.
      1. Você pode encadear quantas vezes quiser, basta repetir o processo.
          a'. Funciona também para as listas não numeradas... lembrando que você também pode personalizar o índice que irá aparecer, basta apenas trocar o "1" pelo o que você quiser mostrar.

1. ### Lista de Afazeres:
   * Usa-se "- [ ]" com um espaçamento entre esse símbolo e o que quer escrever.

Ex.:
- [x] Escrever um guia.
- [x] Ajudar no entendimento e memorização dos comandos.
- [x] Marcar o que já foi feito da lista.
- [ ] Esse daqui não marcarei.

   * Para marcar um tópico como feito põe-se um "x" dentro do "[]", ficando dessa forma "- [x]".

8. ### Criando Tabelas:
   * Primeiramente usa-se a barra vertical "|" seguido, espaçadamente, dos títulos de cada coluna, (Ex.: Nome | Turma | Nota), depois na parte de baixo, dado enter, usa-se "|---|---|---" para montar o corpo da tabela e por último põe-se as informações desejadas, também criando outra linha com o enter (Ex.: Lucas | Ensino Médio | 9.5), a partir dessa parte pode-se adicionar quantas linhas de informação você quiser.

Ex.:
Nome | Signo | Cor Favorita
|---|---|---
Lucas | Sagitário do mês de **Novembro** | Castanho
Rodrigo | Leão do mês de **Julho** | Vermelho
Maria | Capricórnio de **Janeiro** | Roxo
Vanessa | Sagitário de **Dezembro** | Azul Bebê

9. ### Inserindo [Links](https://github.com/LucasHenrique-dev/ComandosMarkdownGitHub):
   * Usa-se "[]" seguido, sem espaço, de "()", onde dentro do parênteses vai a url, ou seja, o endereço da página que você quer mostrar e nos colchetes o tipo de mensagem que você quer que apareça, se nada for colocado aparecerá apenas o endereço. Ex.: O código "[GitHub]""(https://github.com/LucasHenrique-dev)", gera -> [GitHub](https://github.com/LucasHenrique-dev).
1. ### Fazendo Menções:
   * Usa-se "@" seguido pelo apelido da pessoa a quem se quer mencionar, serve como um link para a página inicial dessa pessoa no GitHub e para chamar a atenção de quem foi mencionado. Pondo-se "@" já aparecem algumas opções que são baseadas em atividades recentes daquele local em que se está, não sendo assim, restrito usar apenas os que aparecem, basta apenas digitar o nome desejado. Ex.: Venha conhecer o meu GitHub: @LucasHenrique-dev 
1. ### Fazendo "Citações":
   * Diferentemente do tradicional, tem-se uma forma específica e distinta da usual de se usar citação, nela usa-se ">" seguido de um espaçamento e logo após o que se quer mencionar.

> "Ou você morre como um herói, ou vive o suficiente para ver você se tornar o vilão".

* No caso de citações, o quanto você escrever fará parte da citação, para acabá-la basta dar um intervalo de uma linha.
12. ### Referenciando Issues, ~~!ERROR~~:
   * Estando-se em uma Issue de um trabalho qualquer você pode referenciar uma outra, estando ela fazendo parte do grupo de Issues do próprio repositório em que está interagindo, usando "#" e a numeração da Issue que se quer referenciar. Ex.: #2, gera um link que lhe leva para a Issue número 2 daquele repositório em questão, caso não exista o link não será ativado/referenciado.
13. ### Criando Linhas Divisórias:
   * Usa-se "---" ou "***" na linha seguinte a que se deseja utilizar. 
   
Ex.:
Texto

"---" (Ocorreu a separação)

Continuação do texto

# Elementos Visuais:
---
1. ### Inserindo Imagens:
   * Basta apenas tê-lo salvo no seu computador e jogar aqui na caixa de texto, é necessário esperar que o sistema carregue a informação para que possa ser mostrado corretamente, por padrão o seu formato é "![]""()", parecido com o de link, apenas contendo a interrogação "!" na frente dos colchetes.

![justicetocat](https://user-images.githubusercontent.com/62728919/78955921-1d748200-7ab7-11ea-8538-79efd1697d7a.jpg)

* Imagem pegue do site [Octodex](https://octodex.github.com/) e feita por @heyhayhay.

2. ### Inserindo Emojis 😎 :
  * Usa-se ":" seguido, sem espaço do nome do emoji e finalizado com ":". Ex.: Para fazer o Emoji de óculos escuros é necessário escrever ":"sunglasses"":"
   * Para saber mais sobre os atalhos de cada emoji veja o incrível trabalho que @ikatyang fez no seu repositório [emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet), vai lá dá uma acessada! 😉

-> Chegando aqui você já tem uma boa ideia de como trabalhar com os Markdown para o GitHub, querendo saber mais você pode visitar o site do GitHubGuides, [Clicando aqui](https://guides.github.com/features/mastering-markdown/).
