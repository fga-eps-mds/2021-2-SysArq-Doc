### Conheça nossa equipe

* falta linkar os perfis do github

| Membro | E-mail | Github | Papel |Matricula|
|-------------------------------|--------------------------|----------------------------------|----------------------|------------|
| Iago Oliveira Monteiro Ribeiro | iagorag363@gmail.com	| [iagoomr](https://github.com/) | EPS | 16/0124735 |
| João Luis Takur Baraky Dias | jlbaraky@gmail.com	| [baraky](https://github.com/) | EPS | 18/0033646 |
| Rafael Santos Teodosio | rafzteodosio@gmail.com	| [rafaelteodosio](https://github.com/) | EPS | 16/0142466 |
| Weiller Fernandes Pereira | weillerfernandes@gmail.com	| [WeillerFernandes](https://github.com/) | EPS | 13/0137995 |
| Alex Gabriel Alves Faustino | alexgabriel3357@gmail.com	| [Gabriel-Axl](https://github.com/) | MDS | 20/0056603 |
| André Corrêa da Silva | andre.correa.silva203@gmail.com	| [dartmol203](https://github.com/) | MDS | 20/0014447 |
| Arthur Henrique Amaral Santana | arthurhenrir4@gmail.com	| [black258br](https://github.com/) | MDS | 20/0035371 |
| Arthur Ferreira Rodrigues | fr.arthur.fr@gmail.com	| [ArthurFerreiraRodrigues](https://github.com/) | MDS | 20/0056981 |
| Cleber de Oliveira Brant | cleberobb@hotmail.com	| [Cleberbrant](https://github.com/) | MDS | 20/0061216 |
| Guilherme Puida Moreira | guilhermepmoreira00@gmail.com	| [guilherme-puida](https://github.com/) | MDS | 20/0019015 |
| Paulo Maciel Torres Filho | paulomacieltorresfilho@gmail.com	| [paulomacieltorresfilho](https://github.com/) | MDS | 20/0025937 |
| Wesley Carvalho Lira | wesleeylirac12@gmail.com	| [Weslin-0101](https://github.com/) | MDS | 20/0044559 |

### Conheça nossa documentação
* [SysArq Docs](https://fga-eps-mds.github.io/2021.1-PC-GO1/) //ainda falta linkar a nova wiki

## Organização SysArq
* [SysArq Profile](https://github.com/fga-eps-mds/2021.2-SysArq-Profile)
* [SysArq Archives](https://github.com/fga-eps-mds/2021.2-SysArq-Archives)
* [SysArq Front-End](https://github.com/fga-eps-mds/2021.2-SysArq-Frontend)

---

## Como Contribuir

### 1. Como começar
* Para contribuir no projeto é recomendado abrir as issues existentes e o backlog do produto em [SysArq Docs](https://github.com/fga-eps-mds/2021-2-SysArq-Doc/issues) para entender o que o projeto precisa atualmente.
* Se você perceber que o seu problema ainda não foi documentado crie uma issue, porém priorize as já existentes.

### 2. Orientações
* Se você for um colaborador externo, dê um fork no projeto.
* Issues só poderão ser criadas com os [templates de issue](.github/ISSUE_TEMPLATE) especificados no repositório.
* A criação de branches deve seguir a política de branches.
* No desenvolvimento, usar nossa política de commits, que pode ser encontrado no arquivo sobre [contribuição](CONTRIBUTING.md).
* Pull requests só serão aceitos se estiverem com o [template de pull request](.github/PULL_REQUEST_TEMPLATE.md) especificado no repositório.

### 3. Política de Branches
Nossa política segue algumas características do Gitflow. Então separamos nossas branches em:

### **main**
A master será nossa branch de produção, ou seja, nela estará a versão estável do projeto. E por questões de segurança ela será bloqueada para commits e push. A interação com a master vai se dá através da de Pull requests que virão da branch devel.

### **devel**
A devel será nossa branch de desenvolvimento, ou seja, vai agrupar o trabalho vindo das branches de features, o objetivo é criar uma release que será submetida para master.

### **branches de features**
As branches de features são criadas a partir da devel, e serve para o desenvolvimento de features presentes nas issues do repositório. No final do desenvolvimento a funcionalidade desenvolvida nessa branch deve ser enviada para a devel, através de um pull request e deve seguir a nomeclatura: número_da_issue_Nome_da_issue.

### **hotfix branches**
Hotfix branches são criadas a partir da master e servem para resolver de forma rápida os bugs em produção. Essa branch deve seguir a seguinte nomenclatura: hotfix_Nome_do_bug.
