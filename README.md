### Aluno:
- **Nome**: André Luiz Bento da Silva
- **Curso**: Desenvolvimento Mobile
- **Matéria**: Desenvolvimento Nativo para iOS
- **Atividade**: Atividade 3 


Agora que já aprendemos o básico sobre como desenvolver apps para iOS, vamos colocar esse conhecimento em prática criando um app que vai nos ajudar a cuidar do nosso bairro!

A proposta é que você crie um aplicativo onde o usuário possa registrar qualquer problema que veja em seu bairro ou em sua cidade. Encontrou um semáforo com defeito? Um sinal de estrada quebrado? Buraco na rua ou na calçada? Lixeira danificada? Abra o aplicativo e registre esse problema (com foto, localização e outras informações) para que você possa entrar em contato com o órgão responsável posteriormente.


## O aplicativo deve funcionar da seguinte forma:

1) O aplicativo terá 3 telas: Listagem, Exibição e Edição/Criação;

2) A tela inicial será a tela de Listagem, uma TableViewController onde serão listados todos os problemas registrados pelo usuário. Nesta lista deverá aparecer o nome e a data do problema registrado;

3) A navegação entre as telas será feita via NavigationController;

4) A partir da tela inicial o usuário poderá criar um novo registro (clicando em algum botão presente) ou selecionar um dos registros listados;

5) Ele também poderá excluir um registro utilizando o gesto de Swipe;

6) Ao selecionar um registro, ele será levado para a tela de Exibição, onde serão apresentados todos os dados do mesmo, que são:

    * Nome
    * Localização (endereço)
    * Fotografia
    * Descrição

    Abaixo está um exemplo:

    - **Nome**: buraco na calçada
    - **Endereço**: Av. Lins de Vasconcelos 3100, Aclimação, São Paulo – SP
    - **Descrição**: Este buraco de aproximadamente 80 cm de diâmetro, localizado na calçada direita (sentido centro) em frente ao Lins' Pet Shop, está dificultando a circulação de pedestres que muitas vezes acabam tendo que invadir a via na risco de ser atropelado.

7) A partir dessa tela, ele poderá voltar para a tela de Listagem ou ir para a tela de Edição/Criação;

8) A tela de Edição/Criação servirá tanto para a edição de um novo registro (alteração dos seus dados) quanto para a criação de um novo. Se ela for acessada a partir do botão de criação na tela Listagem, ela entrará no modo "Criação". Caso seja acessada pela tela de Exibição, entrará no modo "Edição";

9) Os dados deverão ser armazenados utilizando Core Data;

10) Toda a definição de interface (UI) do aplicativo ficará por conta do aluno.