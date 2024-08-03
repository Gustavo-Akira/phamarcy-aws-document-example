# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 02/08/2024
Empresa: Abstergo Industries 
Responsável: Gustavo Akira Uekita

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Gustavo Akira Uekita. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- AWS Elastic Beanstalk
- Deploy e gerenciamento de aplicações
- Primeiramente iriamos elencar as aplicações tanto internas e externas para as configurar dentro do elastic beanstalk, configurando a escalabilidade daquelas que nescessitarem de uma robustes maior em periodos sazonais como por exemplo um e-commerce, e assim conseguindo um serviço pago de acordo com o uso.Com isso se ganha tempo, pois não se teria a parte de preocupação e nem investimento com segurança de rede, infraestrutura e escalabilidade.

Etapa 2: 
- AWS RDS
- Armazenar dados que ficam no banco das aplicações
- Avaliar os bancos de dados e depois configuralos dentro do RDS de tal forma que as aplicações que foram implatados na Etapa1 ou outras que consumam eles consigam acessá-los de forma consistente e ainda garantindo perfomance, segurança e economia.

Etapa 3: 
- AWS VPC
- Criar redes para comunicação com as aplicações
- Análise de caso a caso para criar redes privadas para a aplicação e seus bancos depois analizar quais aplicações devem estar exposta a internet e criar um gateway com o amazon transit gateway para que se tenha uma url e não expor nada diretamente a internet.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries espera um aumento significativo na segurança, já que a infraestrutura estará na nuvem, sem acesso físico, e as aplicações e bancos de dados não estarão expostos à internet, pois estarão dentro de VPCs com um gateway de proteção. Além disso, a escalabilidade e a disponibilidade serão aprimoradas com os recursos elásticos oferecidos pelo Elastic Beanstalk e pelo RDS, com suas configurações flexíveis. Por fim, haverá economia, pagando apenas pelo que for utilizado e eliminando custos com energia, manutenção, internet e refrigeração de servidores físicos*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
### Links
#### Elastic Beanstalk
https://aws.amazon.com/pt/elasticbeanstalk/?gclid=Cj0KCQjwh7K1BhCZARIsAKOrVqF8k0NrentIS0SkfbzzoUmxIhzK3dtaHPChxENcbvoV9tILs0ar_ZQaAq3fEALw_wcB&trk=e9c37b8b-37f2-4eb2-b96a-039537bda446&sc_channel=ps&ef_id=Cj0KCQjwh7K1BhCZARIsAKOrVqF8k0NrentIS0SkfbzzoUmxIhzK3dtaHPChxENcbvoV9tILs0ar_ZQaAq3fEALw_wcB:G:s&s_kwcid=AL!4422!3!651510165333!e!!g!!elastic%20beanstalk%20pricing!19836375517!149589157600
#### RDS

#### VPC


### Tabela comparativa
### Comparação de Gastos: Infraestrutura Física vs. Infraestrutura na AWS

| **Item**                    | **Infraestrutura Física**                             | **Infraestrutura na AWS (Elastic Beanstalk, VPC, RDS)** |
|-----------------------------|------------------------------------------------------|-------------------------------------------------------|
| **Custo Inicial**           | Alto (compra de servidores, rede, espaço físico)     | Baixo (sem compra de hardware, apenas configuração)   |
| **Manutenção de Hardware**  | Alta (reparos, substituições, técnicos)              | Zero (AWS gerencia o hardware)                        |
| **Energia Elétrica**        | Alta (consumo constante de servidores e refrigeração)| Zero (incluso no custo do serviço)                    |
| **Refrigeração**            | Alta (ar condicionado e sistemas de refrigeração)    | Zero (incluso no custo do serviço)                    |
| **Conectividade de Internet**| Média (links de internet de alta velocidade)        | Média (tráfego de dados pode gerar custos)            |
| **Segurança Física**        | Alta (controle de acesso, segurança)                 | Zero (segurança gerenciada pela AWS)                  |
| **Segurança Digital**       | Média (firewalls, antivírus, monitoramento)          | Alta (incluído nas VPCs, gateways de segurança)       |
| **Escalabilidade**          | Baixa (compra de novos servidores conforme a demanda)| Alta (elasticidade automática com Elastic Beanstalk)  |
| **Disponibilidade**         | Média (dependente de manutenção física e redundância)| Alta (AWS oferece alta disponibilidade e redundância) |
| **Tempo de Configuração**   | Alto (semanas a meses para instalação e configuração)| Baixo (minutos a horas para configuração inicial)     |
| **Custos de Licenciamento** | Variável (software, sistemas operacionais)           | Variável (alguns softwares têm custo adicional)       |
| **Custo Mensal Estimado**   | Alto (considerando todos os itens acima)             | Variável (baseado no uso; pode ser mais baixo em muitos casos)|

### Estimativa de Custos Mensais

**Infraestrutura Física:**
- Compra de Hardware: $50,000
- Manutenção: $1,000/mês
- Energia Elétrica: $500/mês
- Refrigeração: $300/mês
- Conectividade de Internet: $200/mês
- Segurança Física: $100/mês
- Total: ≈ $3,490/mês

**Infraestrutura na AWS:**
- Elastic Beanstalk: $100 - $500/mês (dependendo da carga e configuração)
- RDS: $100 - $1,000/mês (dependendo da configuração)
- VPC: $0 (incluso em outros custos)
- Tráfego de Dados: $50 - $200/mês (dependendo do uso)
- Total: ≈ $250 - $1,700/mês (média $975/mês)


Assinatura do Responsável pelo Projeto:

Gustavo Akira Uekita