# Pipeline_databricks_azure

🔍 Este projeto tem como objetivo automatizar a ingestão e transformação de dados utilizando Azure Data Factory e Databricks. Com a configuração de um gatilho de execução por hora, o pipeline garante o processamento contínuo e eficiente de novos dados, promovendo maior agilidade e escalabilidade no fluxo de trabalho.

🚀 Tecnologias Utilizadas

Azure Data Factory

Azure Databricks

GitHub

⚙️ Instalação e Configuração

Siga os passos abaixo para configurar e executar o pipeline:

1- Crie um Grupo de Recursos no portal Azure para organizar todos os recursos relacionados ao projeto.

2- Crie uma Storage Account e, dentro dela, configure um Data Lake Gen2 para armazenar os dados de entrada, processamento e saída.

3- Registre uma aplicação (App Registration) no Azure Active Directory para o Databricks, vinculando-a ao Grupo de Recursos criado. Essa etapa permite o controle de permissões e autenticação segura.

4- Crie um workspace no Azure Databricks dentro do mesmo Grupo de Recursos. Configure os notebooks responsáveis pelo tratamento e transformação dos dados.

5- Configure o Azure Data Factory dentro do mesmo Grupo de Recursos e crie um pipeline de orquestração de dados.

6- Crie um gatilho (trigger) no Data Factory para executar o pipeline automaticamente a cada hora.

7- Estabeleça a conexão entre o Data Factory, o Data Lake e o Databricks, garantindo que os dados fluam corretamente entre os serviços.

▶️ Como Usar

Após configurado, o pipeline será executado automaticamente a cada hora ou quando novos dados forem disponibilizados na camada de entrada. O monitoramento das execuções pode ser feito diretamente pelo portal do Azure, tanto no Data Factory quanto no Databricks.

🤝 Contribuições Contribuições são sempre bem-vindas! Se você tiver sugestões, melhorias ou correções, abra uma issue ou envie um pull request.

📄 Licença Este projeto está licenciado sob a Licença MIT.
