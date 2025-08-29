<h1>Resolução do desafio proposto no Bootcamp de nuvem AWS da DIO</h1>
<h3> - Esse relatório apresenta o processo de implementação de ferramentas na empresa
Abstergo Industries. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade
de realizar diminuição de custos elevados.</h3>

     Etapa 1:
        Nome da ferramenta: Amazon Aurora

        Foco da ferramenta: 
        - É um banco de dados ralacional da AWS que oferece baixo custo e atende bem a empresa

        Descrição de caso de uso:
        Usaremos esse banco de dados para construção do banco que armazenará os dados,
        centralizando as informações do produto e pedido com as farmácias parceira. Além de ter
        escalabilidade e ofecer baixo custo, eleminamos a necessidade de manutenção e preocupação
        com os servidores. Também é compatível com PostreSQL e MySQL, então se já estiver uma
        aplicação existente, facilita a integração.
    
    Etapa 2:
        Nome da ferramenta: Amazon S3 (Intelligent-Tiering)

        Foco da ferramenta:Gerenciar o armazenamento do objeto

        Descrição de caso de uso: usamos essa ferramenta porque a frequência de acesso aos dados
        pode ser variável, tem grande redução de custos porque os dados são armazenados na camada
        mais econômica. Além dos produtos, também podemos armazenar imagens, notas fiscais digitalizadas,
        relatórios e históricos de transações no S3.

    Etapa 3:
        Nome da ferramenta: AWS Direct Connect

        Foco da ferramenta: fazer a conexão segura entre a empresa e a AWS

        Descrição de caso de uso: utilizaremos essa ferramenta para fazer a conexão segura
        entre o data center da empresa e a nuvem, para garantir a segurança do tráfego de
        informações sensíveis. Essa ferramenta funciona em uma rede privada.