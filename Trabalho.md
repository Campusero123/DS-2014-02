# <h1 align="center">**Trabalho de Design de Software - Projeto Detalhado 2**</h1>

## <h2 align="center">**Escopo**</h2>
Esse trabalho será sobre um sistema de identificação de árvores, que possam gerar algum risco para a população, onde estas geralmente estão doentes ou mortas, e precisam ser cortadas pela cidade, a fim de evitar acidentes. 

## <h2 align="center">**Funcionamento**</h2>
O usuário, identificando uma árvore que ele acredita se enquadrar em um desses casos, cria uma denúncia no sistema, requisitando a retirada daquela árvore. O sistema avalia se aquela denúncia é válida, e solicita ou não a retirada daquela árvore à prefeitura.

## <h2 align="center">**Requisitos e Funcionalidades Principais**</h2>
+ Cadastrar e listar os tipos de árvores existentes na cidade
+ Cadastrar e listar fotos das árvores cadastradas em seu estado saudável
+ Cadastrar e listar os tipos de doenças possíveis para cada tipo de árvore cadastrada no sistema, com suas características de como diagnosticar
+ Cadastrar e listar fotos das árvores cadastradas em seus estados doentes ou mortas
+ Cadastrar usuário
+ Permitir que o usuário abra uma denúncia ou liste denúncias que ele já fez anteriormente
+ Prover um campo de descrição e botão para anexar fotos para enriquecer a denúncia
+ Comparar as informações das denúncias com o banco, julgando se as denúncias são pertinentes ou não
+ Caso a denúncia seja aprovada, o sistema envia um e-mail para a prefeitura, contendo as informações dessa denúncia

## <h2 align="center">**Diretrizes do Projeto**</h2>
O projeto será construído com as diretrizes **SOLID**, a fim de ter boas práticas de POO. 

## <h2 align="center">**Arquitetura do Projeto**</h2>
A arquitetura ainda não foi definida.

## <h2 align="center">**Banco de Dados**</h2>
Provavelmente, será utilizado um banco de dados não-relacional (possivelmente o MongoDB).
