# Gerenciando de Instancias EC2 na AWS

## Criação e Configuração das Instâncias EC2
Nessa etapa, o administrador escolhe a AMI (Amazon Machine Image), que define o sistema operacional e softwares básicos. Também são definidos o tipo de instância (CPU, memória e desempenho), chaves de acesso (Key Pair), grupos de segurança (firewall) e rede (VPC e sub-rede). Uma configuração adequada garante segurança, desempenho e custo eficiente desde o início.

## Monitoramento e Manutenção
Após a instância estar em execução, é essencial monitorar seu funcionamento. A AWS oferece o Amazon CloudWatch, que acompanha métricas como uso de CPU, memória (com agente), disco e tráfego de rede. O gerenciamento inclui atualizações do sistema, aplicação de patches de segurança, backup com snapshots do EBS e reinicializações quando necessárias. Isso ajuda a manter a instância estável, segura e disponível.

## Escalabilidade, Custos e Encerramento
O EC2 permite escalabilidade vertical (alterar o tipo da instância) e horizontal (usar Auto Scaling para adicionar ou remover instâncias automaticamente). O gerenciamento também envolve controle de custos, escolhendo opções como On-Demand, Reserved Instances ou Spot Instances. Quando uma instância não é mais necessária, ela deve ser encerrada corretamente, evitando cobranças desnecessárias e liberando recursos.

![aws_imagem](https://github.com/user-attachments/assets/9120be48-ed8b-46f9-af06-ee256e2642e8)
