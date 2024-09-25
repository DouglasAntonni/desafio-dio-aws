# desafio-dio-aws
{
  "project": {
    "title": "Assistente de Delivery com AWS Step Functions e Bedrock XP",
    "welcome_message": "Bem Vindo ao Step Functions",
    "prerequisites": [
      "Conta AWS ativa",
      "Conhecimento básico em AWS",
      "Familiaridade com serviços como Step Functions e Bedrock XP"
    ],
    "problem_statement": "Necessidade de um assistente automatizado para gerenciar pedidos de delivery de forma eficiente.",
    "resources": {
      "step_functions_official_page": "https://aws.amazon.com/step-functions/",
      "official_documentation": "https://docs.aws.amazon.com/step-functions/latest/dg/welcome.html",
      "locating_service": "Acesse o console da AWS e busque por Step Functions."
    },
    "getting_started": {
      "project_template": "Utilize um projeto template disponível no repositório do AWS Step Functions para configurar rapidamente seu assistente de delivery.",
      "workflow_studio_and_asl": "Explore o Workflow Studio para visualizar e construir seus fluxos de trabalho usando ASL (Amazon States Language).",
      "hello_world": "Crie um exemplo básico 'Hello World' para entender a estrutura de um fluxo de trabalho e interações com serviços AWS.",
      "pricing_and_costs": "Verifique a página de preços do AWS Step Functions para entender os custos associados, como taxas por transição de estado e execução."
    },
    "configuration_levels": {
      "level_1_permissions": "Configure as permissões de perfil necessárias para acessar os serviços AWS como Lambda, DynamoDB e SNS.",
      "level_2_service_availability": "Certifique-se de que os serviços necessários estão disponíveis na região selecionada, especialmente Lambda e API Gateway."
    },
    "practical_example": {
      "creating_delivery_assistant": "Na prática, implemente um assistente de delivery utilizando exemplos do repositório aws-stepfunctions-examples. Um fluxo típico pode incluir receber pedidos, processá-los, e enviar notificações.",
      "repository_description": "AWS Step Functions é um serviço visual de workflow de baixo código. Este repositório inclui exemplos detalhados que ajudarão você a desbloquear o poder do workflow serverless."
    },
    "examples_and_supporting_blog_posts": [
      {
        "title": "Accelerating workloads using parallelism in AWS Step Functions",
        "description": "Construa um aplicativo que utiliza processamento paralelo para concluir tarefas rapidamente, ideal para gerenciamento de pedidos simultâneos.",
        "blog_post_link": "Link para o blog: Accelerating workloads using parallelism in AWS Step Functions"
      },
      {
        "title": "Controlling concurrency in distributed systems using AWS Step Functions",
        "description": "Controle a concorrência no seu sistema distribuído para evitar sobrecarga de recursos durante picos de pedidos.",
        "blog_post_link": "Link para o blog: Controlling concurrency in distributed systems using AWS Step Functions"
      },
      {
        "title": "Mocking service integrations with Step Functions Local",
        "description": "Teste uma máquina de estado simulando chamadas de serviço para desenvolver seu assistente de delivery localmente.",
        "blog_post_link": "Link para o blog: Mocking service integrations with AWS Step Functions Local"
      },
      {
        "title": "Orchestrating S3 Glacier Deep Archive object retrieval using Step Functions",
        "description": "Orquestre a restauração de objetos do S3 Glacier para recuperar dados históricos de pedidos se necessário.",
        "blog_post_link": "Blog Post: Orchestrating S3 Glacier Deep Archive object retrieval using Step Functions"
      },
      {
        "title": "Video Segment Detection and Edition with AWS Step Functions",
        "description": "Utilize AWS Step Functions para edição de vídeos promocionais de delivery.",
        "blog_post_link": "Blog Post: Low code workflows with AWS Elemental MediaConvert"
      }
    ],
    "demos": [
      {
        "title": "Step Functions Local testing with Mock service integrations",
        "description": "Use frameworks de teste Java (JUnit e Spock) para testar seu assistente de delivery localmente antes de implantá-lo na AWS."
      },
      {
        "title": "ASL Demo",
        "description": "Demonstra as capacidades do ASL e AWS Step Functions, incluindo funções intrínsecas e processamento de JSON Path."
      },
      {
        "title": "Video Transcription with AWS SDK Service Integrations",
        "description": "Construa um fluxo de trabalho de transcrição de vídeo utilizando integrações de serviço do AWS SDK, útil para criar conteúdos para marketing."
      }
    ],
    "security": "Consulte a seção de CONTRIBUTING para mais informações sobre segurança e boas práticas ao usar AWS Step Functions.",
    "license": "Esta biblioteca está licenciada sob a Licença MIT-0. Consulte o arquivo LICENSE."
  }
}
