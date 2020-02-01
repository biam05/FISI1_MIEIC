##Como usar os batch files?
Simples, basta ir ao wxmaxima (se usarem esta versão) e fazer CTRL+B ou CMD+B para os macs.
Para quem não usa wxmaxima pode fazer batch("pathparaobatch");

De seguida a função do batch será carregada para o maxima, sendo que aparece o seu código que foi loaded pelo maxima.

Para correr a função em si basta fazer nome_da_função(); , sendo que podem ver qual o nome da função a chamar pelo início do output do comando batch que fizeram antes.

Depois deverá ser apenas seguir as instruções que o batch dá.

(Presumivelmente) Todos os batches que aqui estão têm comentários dentro do próprio ficheiro .mac (abrir com notepad ou equivalente) que explicam como o usar e também em grande parte destes está um enunciado exemplo com o resultado para testar o seu funcionamento.


##FAQ:
Q: Não consigo fazer gráficos porque o maxima diz que não sabe onde guardar os ficheiros ou algo assim!!111
R: Verifica o maxima_tempdir e o maxima_userdir para ver se estão em paths válidos. Estas variáveis podem ser mudadas como as outras variáveis do maxima, fazendo maxima_tempdir: "/home/userexemplo/pastamaximaexemplo".

Q: O meu maxima passa-se todo ao carregar o batch, parece que tem problemas de formatação!!
R: Tenta abrir o ficheiro do batch num editor de texto tipo notepad e guardar com o encoding UTF-8, costuma resolver.

Q: Carrego enter e nada acontece!
R: Se estás a usar wxMaxima, não te esqueças que é shift+enter, se estás a usar xmaxima ou maxima na consola genericamente, não te esqueças do ; no fim de cada comando.

Q: Outros problemas
R: Google is your friend, ou chateia alguém que perceba de maxima lol

Q: OMG salvaste-me a física!!11
R: Se estás assim tão contente então pensa na malta que vem aí e contribui também com batches extra que possam ter sido feitos entretanto.
