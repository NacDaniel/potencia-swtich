# potencia-swtich
Pegar a potência Rx e Tx de switches. 

Sim, eu poderia utilizar SNMP para isso, mas escolhi o pior caminho, que é SSH.

A conexão é feita via SSH com o equipamento escolhido e a aplicação apenas realiza a filtragem de dados. 

Em sua maioria, equipamentos da Huawei possuem o mesmo procedimento para obter a potência de determinadas portas. Por outro lado, a Datacom tem um processo diferente para cada DmOS. 

Farei uma espécie de regex para Huawei e para alguns modelos da Datacom. Caso deseje usar esse sistema pouco intuitivo, deverá se virar com o filtro de outros modelos ou marcas.


