# Funções Lambda

AWS Lambda é um serviço de computação serverless que permite executar código sem provisionar ou gerenciar servidores. Você paga apenas pelo tempo de computação consumido, não há cobrança quando seu código não está em execução.

## Como funciona?
- Execução Orientada a Eventos: Funções Lambda são acionadas por eventos de outros serviços AWS (ex: uploads no S3, requisições do API Gateway, atualizações no DynamoDB).
- Suporte a Múltiplas Linguagens: Python, Node.js, Java, Go, .NET e outras.
- Segurança Integrada: Funções usam roles IAM para permissões e executam em ambientes isolados.
Tarefas Automatizadas: Executar tarefas agendadas

# Lambda Functions
AWS Lambda is a serverless compute service that lets you run code without provisioning or managing servers. You pay only for the compute time you consume—there is no charge when your code is not running.

## How does it work?
- Event-Driven Execution: Lambda functions are triggered by events from other AWS services (e.g., S3 uploads, API Gateway requests, DynamoDB updates).
- Multiple Language Support: Python, Node.js, Java, Go, .NET, and others.
- Integrated Security: Functions use IAM roles for permissions and run in isolated environments.
- Automated Tasks: Execute scheduled tasks using EventBridge.
