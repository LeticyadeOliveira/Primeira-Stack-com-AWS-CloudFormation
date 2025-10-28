# Projeto: Primeira Stack com AWS CloudFormation | Automação e gerenciamento
Este repositório tem como objetivo documentar o meu entendimento sobre o AWS CloudFormation e a implementação de stacks.

## O que é AWS CloudFormation? 
  - É um serviço da AWS que auxilia na automação de criação de recursos na AWS por meio de templates escritos em JSON ou YAML. Podemos usar quantas vezes precisarmos e é pago apenas pelas stacks criadas. Ao invés de criarmos manualmente cada recurso, é possível descrever toda a infraestrutura como código(IaC).
  
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
    
  - Para continuar o processo e entender o tutorial completo acesse: <br/>
  [Criar uma stack do cloudformation com o console](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/gettingstarted.walkthrough.html#getting-started-create-stack)

## Principais componentes 

 Em um template(modelo) há alguns componentes chave como:<br/>
 
       * Resources: define os recursos a serem criados (como um: EC2, S3, RDS etc.)
       * Parameters: permite entrada de valores personalizados.
       * Outputs: retorna informações úteis após a criação.
       * Mappings e Conditions: ajudam a adaptar o template a diferentes regiões ou configurações.

## Casos de uso
   Como citado anteriormente o CloudFormation é uma ferramenta que pode ser muito utilizada para diversos casos, alguns deles são:<br/>
    1.**Criar uma instância EC2.<br/>
    2.Um bucket S3 para hospedar o site estático (HTML, CSS, JS)** <br/>
    3.**Dentro de um site de e-commerce, por exemplo, um API Gateway + Lambda para processar as requisições como “adicionar ao carrinho” ou “finalizar compra”.** <br/>
- Dessa forma. o CloudFormation auxilia e facilita o gerenciamento da infraestrutura em nuvem tronando-o mais eficaz, seguro e escalável.

   
## Referências
[Documentação oficial da AWS](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/gettingstarted.walkthrough.html)<br/>
[O que é infraestrutura como código](https://aws.amazon.com/pt/what-is/iac/#:~:text=Infraestrutura%20como%20c%C3%B3digo%20(IaC)%20%C3%A9,a%20novas%20oportunidades%20de%20neg%C3%B3cios.)<br/>
[Vídeo explicativo](https://youtu.be/jxNpRLLrDFg?si=TaEFfH_SpZb_N9p1)
