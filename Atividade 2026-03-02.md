# Atividade 2026-03-02

## Stephanie de Brito Leal

***Um resumo do Git***
- O Git é um software livre que permite que programadores tenham controle das versões do código e alterem simultaneamente o código.
- Foi projetado e desenvolvido por Linus Torvalds para o desenvolvimento do kernel Linux.
- O Git não precisa necessariamente ser usado apenas para programação: ebooks também podem ser editados simultaneamente por ele, por exemplo. Ele também facilita a reprodutibilidade científica de várias disciplinas.
- Cada diretório de trabalho do Git é um repositório com um histórico completo e habilidade total de acompanhamento das revisões, não dependente de acesso a uma rede ou a um servidor central.

***Comandos do Git no CLI***
1. Para logar no Git:
> git config --global user.name "Your Name Comes Here"
>
> git config --global user.email you@yourdomain.example.com
2. Para saber se já estou logada:
> git confing --list
3. Para inicializar um repositório:
> git init
>
>*Lembre-se: este comando deve ser dado dentro da pasta que ficará ligada ao repositório* 
4. Adicionando coisas ao seu repositório:
> git add **adiciona tudo**
>
> git add \* **só adiciona o que foi alterado**
>
> git add NOME DO ARQUIVO
5. Fazer um commit (**Lembre-se: ao commitar, você estará alterando a versão do repositório!**)
> git commit -m "MENSAGEM"
>
>-m "MENSAGEM" é o comentário que você quer deixar atrelado ao seu commit
6. Verificar registro de commits:
> git log
>
>git log --oneline (versão resumida)
7. Linkar diretório da sua máquina com repositório  (seguir a ordem):
>Primeiro: git branch -M main
> 
>Segundo: git remote add origin (OU NOME SUGERIDO PELO GITHUB) LINK DO REPOSITÓRIO REMOTO
>
>Terceiro: git push origin (OU NOME SUGERIDO PELO GITHUB) main (branch escolhida)
>
    - Detalhe: branch é uma linha de desenvolvimento independente que permite mudanças sem alterar o código-base central. Main é considerada a branch primária que contém o código-base, convencionalmente.7