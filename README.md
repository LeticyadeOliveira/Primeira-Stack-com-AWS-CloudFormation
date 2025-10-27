# Projeto | Primeira-Stack-com-AWS-CloudFormation
Este repositório tem como objetivo documentar o meu entendimento sobre o AWS CloudFormation e a implementação de stacks.

## O que é AWS CloudFormation? 
  - É um serviço da AWS que auxilia na automação de criação de recursos na AWS por meio de templates escritos em JSON ou YAML. É pago apenas pelas stacks criadas. Ao invés de criarmos manualmente cada recurso, é possível descrever toda a infraestrutura como código.
  
 > ***O que significa uma infraestrutura como código(IaC)?<br/>
     - Uma infraestrutura como código é a capacidade de simplificar uma infraestrutura de computação que seria feito atráves de documentações extensas ou processos manuais em **código**. Trazendo benéficios como: Duplicar facilmente um ambiente, reduzir erros de configuração e produzir diversas interações em ambientes.***<br/>
    
## Como funciona? 
 - Para que você possa utilizar esse recurso da AWS é necessário alguns pré-requisitos, como: <br/>
    > - **"Você deve ter acesso a uma Conta da AWS com um usuário ou perfil do IAM que tenha permissões para usar o Amazon EC2, o Amazon S3 e o CloudFormation ou ter acesso de usuário administrativo."** <br/>
   > - **"Você deve ter uma nuvem privada virtual (VPC) que tenha acesso à internet. Este modelo passo a passo requer uma VPC padrão, que vem automaticamente com as Contas da AWS mais recentes."**

Para criar sua primeira stack no cloudFormation você precisa:<br/>
    1.**Abrir o console do CloudFormation.** <br/>
    2.**Selecionar _Create Stack_** <br/>
    3. **Na página _Create Stack_, escolha “Build using the Infrastructure Composer” (Compilar com o Infrastructure Composer) e clique em Create (Criar).** <br/>
    4. **Nessa página , você poderá carregar, montar e validar o modelo que deseja usar como base para a criação da sua infraestrutura.** <br/>
    Para continuar o processo e entender o tutorial completo acesse: <br/>
  [Criar uma stack do cloudformation com o console](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/gettingstarted.walkthrough.html#getting-started-create-stack)

## 
