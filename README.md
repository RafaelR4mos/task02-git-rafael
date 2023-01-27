# Aprendizados sobre Git

<div align="center"> 
<p>Confira meu mapa mental dos conteúdos <a href="https://www.figma.com/file/zSjDSl2ZmnaCM8xOEEKwQR/Untitled?node-id=0%3A1&t=i8Cp9XkNEHt5aYfV-1" target="_blank">Clique Aqui!</a></p>
<img src='https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white' alt="Badge laranja com a logo do git" />
<img src='https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white' alt="Badge laranja com a logo do git" />
</div>

## Sumário

-   [🤔 O que é git?](#oque-e-git)
-   [🛠️ Principais ferramentas](#principais-ferramentas)
    -   [Ferramentas](#ferramentas)
        -   [Github](#github)
        -   [GitKraken](#gikraken)
        -   [BitBucket](#bitbucket)
        -   [GitLab](#gitlab)
        -   [SmartGit](#smartgit)
    -   [Terminais](#terminais)
        -   [Git Bash](#git-bash)
        -   [Power Shell](#power-shell)
-   [⚙️ Funcionamento](#funcionamento)

    -   [Estados](#estados)
    -   [Git Flow](#git-flow)
    -   [PR e Code Review](#git-flow)
    -   [Git Ignore](#git-ignore)
    -   [Branches](#branches)
        -   [Nomenclatura](#nomenclatura)
        -   [Hierarquia](#hierarquia)
        -   [Convenções](#convencoes)
        -   [Conflitos](#conflitos)

-   [Principais Comandos](#principais-comandos)

</br>

## O que é git?

---

Git é uma ferramenta de controle de versão facilitadora, que permite com que desenvolvedores tenham um controle das versões de seus projetos, além de poderem salvar alterações, reverter seus códigos ou até mesmo publicarem as suas soluções com seus squads ou comunidade trabalhando de forma tanto assíncrona quanto síncrona.

 </br>

## Principais ferramentas

---

### Github

O [Github](https://github.com/) é uma das principais ferramentas utilizadoras do Git sendo popular no mercado de TI pelo seu open source, facilitações no controle de git-flows e por ser propriedade de uma empresa renomada como a Microsoft

### GitCracken

O [GitKraken](https://www.gitkraken.com/) possui uma interface mais intuitiva e embelezada, que pode facilitar na hora de controlar as versões de um projeto, entretanto, por conta dessas funcionalidades acaba sendo um recurso pago

### BitBucket

Possuindo um recurso de integração com o Jira (controle de tarefas no modelo Kanban) o [BitBucket](https://bitbucket.org/product/) é uma solução Open DevOps daAtlassian.

### GitLab

Desde o planejamento para produção o [GitLab](https://about.gitlab.com/) une os times , reduzindo custos, aumentando a segurança e a produtividade dos desenvolvedores que optam por utilizar a ferramenta.

### Smart Git

O [Smart Git](https://www.syntevo.com/smartgit/) não só auxilia usuários novatos em git, mas também, faz com que desenvolvedores mais experientes trabalhem de forma mais produtiva.

 </br>

## Terminais

---

### Git Bash

![Git bash terminal](./assets/git-bash.png)

### Power Shell

![Powershell terminal](./assets/powershell.png)

> É importante destacar que existem outros terminais disponíveis para digitar comando git comoi o: ZSH

</br>

## Funcionamento

| Estados  | Descrição                                             |
| -------- | ----------------------------------------------------- |
| Commited | Dados armazenados no banco local                      |
| Modified | Arquivo alterado, porém ainda sem commit registrado   |
| Staged   | Arquivos marcados e adicionados para serem commitados |
