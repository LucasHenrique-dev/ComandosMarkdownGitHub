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
   * Usa-se "[]()", onde dentro do parênteses vai a url, ou seja, o endereço da página que você quer mostrar e nos colchetes o tipo de mensagem que você quer que apareça, se nada for colocado aparecerá apenas o endereço.
   