# cloud_dio

Passo a passo para criação de uma VM

1. **Acesso ao Portal Azure**: Acessar o portal: portal.azure.com

2. **Início do Processo de Criação**: Clicar no botão "Criar" e selecionar "Máquina Virtual do Azure".

3. **Configurações Básicas**:
     Grupo de Recursos: Você deve selecionar um grupo de recursos existente ou criar um novo. Os grupos de recursos são utilizados para organizar e gerenciar recursos no Azure de forma coesa. É uma boa prática agrupar recursos que têm um ciclo de vida similar.
   - **Nome**: Escolher um nome único para sua VM.
   - **Grupo de Recursos**: Você deve selecionar um grupo de recursos existente ou criar um novo. Os grupos de recursos são utilizados para organizar e gerenciar recursos no Azure de forma coesa
   - **Região**: Selecionar a região onde a VM será hospedada. Isso pode afetar a latência e a conformidade.
   - **Imagem do Sistema Operacional**: Selecionar a imagem do SO. A Azure oferece várias opções de sistemas operacionais, como Windows Server, Ubuntu e outras distribuições Linux.
   - **Tamanho da Máquina**: O Azure oferece diferentes tamanhos de VM, que variam em termos de CPU, memória e armazenamento. O tamanho deve ser escolhido com base nas necessidades de desempenho do aplicativo que será executado.

4. **Configurações de Segurança**:
   - Definir um método de autenticação, como uma senha ou uma chave SSH.
   - Configurar as regras de firewall (Grupo de Segurança de Rede) para controlar o tráfego de entrada e saída da VM.

5. **Discos e Armazenamento**: Escolher entre diferentes tipos de discos (HDD ou SSD) e definir se a VM terá discos adicionais. Isso afetará o custo da VM. HDD são mais baratos que SSD, por exemplo.

6. **Revisão e Criação**: Revisar as configurações, permitindo verificar se todas as opções estão corretas antes de criar a VM.

7. **Gerenciamento Pós-Criação**: Uma vez que a VM é criada, o portal fornece opções para gerenciamento, como acesso remoto, redimensionamento, configuração de backups e monitoramento de desempenho.

8. **Custos**: É fundamental considerar os custos associados à criação e operação de uma VM no Azure. O portal oferece uma calculadora de preços para ajudar na estimativa dos custos.
