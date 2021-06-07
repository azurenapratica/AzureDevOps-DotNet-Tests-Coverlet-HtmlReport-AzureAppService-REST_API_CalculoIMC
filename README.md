# AzureDevOps-DotNet-Tests-Coverlet-HtmlReport-AzureAppService-REST_API_CalculoIMC
Pipeline do Azure DevOps para automação de testes, build e deployment de uma API REST (cálculo do Índice de Massa Corpórea - IMC) no Azure App Service em Linux. Inclui geração de relatório de cobertura de código com Coverlet + ReportGenerator e publicação dos logs de testes em HTML.

Projeto que serviu de base para a implementação deste Pipeline:

https://github.com/renatogroffe/ASPNETCore5-REST_API-xUnit-Coverlet_CalculoIMC

Extensão do Azure DevOps a ser instalada para publicação de HTMLs como reports ao executar
pipelines:

https://marketplace.visualstudio.com/items?itemName=JakubRumpca.azure-pipelines-html-report