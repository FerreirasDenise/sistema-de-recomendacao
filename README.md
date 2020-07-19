Configuração inicial do Maven:
No diretório em que deseja criar o projeto, execute o seguinte comando (no terminal):

mvn archetype:generate -DgroupId=br.com.NomeOrganizacao -DartifactId=sistema-de-recomendacao -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
Onde:

mvn archetype: generate - cria projeto

GroupId - identificação do grupo do projeto, por convenção, inciamos com nomedopais.com.nomedaorganização

ArtifactId - nome do projeto

archetypeArtifactId - tipo de configuração inicial do projeto, no caso o quickstart usa configurações default.

Se o seu prompt não reconhecer o comando mvn, devemos adicioná-lo no PATH:

PATH=$PATH:onde_esta_o_bin_do_maven
E tente executar o comando para gerar o projeto novamente...

Java: O projeto não roda com Java 11

