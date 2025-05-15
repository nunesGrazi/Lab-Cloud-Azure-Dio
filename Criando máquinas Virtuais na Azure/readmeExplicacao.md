# Criação de Máquina Virtual no Microsoft Azure  

Este repositório documenta o processo de criação de uma máquina virtual (Virtual Machine - VM) na plataforma Microsoft Azure, utilizando uma conta gratuita.  

## Passos Realizados  

### 1. **Criação de uma Conta Gratuita no Microsoft Azure**  
   - Acessei o [portal da Microsoft Azure](https://azure.microsoft.com/) e criei uma conta gratuita, aproveitando os créditos iniciais oferecidos para testes.  

### 2. **Início da Criação da Máquina Virtual**  
   - No painel do Azure, naveguei até a seção **"Virtual Machines"** e cliquei em **"Criar"** para iniciar o processo de configuração.  

### 3. **Configurações Básicas da VM**  
   - **Diretório e Assinatura**: Utilizei a assinatura gratuita padrão.  
   - **Grupo de Recursos**: Criei um novo grupo para organizar os recursos da VM.  
   - **Detalhes da Instância**:  
     - Nome da VM  
     - Região (selecionada com base na disponibilidade e latência)  
     - Imagem do sistema operacional (ex: Ubuntu Server, Windows Server, etc.)  
     - Tamanho da VM (selecionado dentro dos limites da conta gratuita)  
   - **Conta de Administrador**: Defini credenciais de acesso (usuário e senha/chave SSH).  
   - **Regras de Portas de Entrada**: Configurei as permissões de rede, liberando portas como SSH (22) ou RDP (3389), conforme necessário.  
   - **Armazenamento**: Utilizei disco gerenciado padrão (SSD ou HDD, dependendo do custo e desempenho).  

### 4. **Inicialização da Máquina Virtual**  
   - Após revisar todas as configurações, cliquei em **"Criar"** para implantar a VM.  
   - Acessei a VM via SSH (para Linux) ou RDP (para Windows) utilizando as credenciais definidas.  

## Imagens de Demonstração  
As imagens comprovando cada etapa do processo (criação da conta, configuração da VM e acesso remoto) estão disponíveis em anexo neste repositório.  

---  
**Observação**: A conta gratuita do Azure tem limitações de recursos e tempo de uso. Certifique-se de desligar ou excluir a VM quando não estiver em uso para evitar custos inesperados.  

🔹 **Tecnologias utilizadas**: Microsoft Azure, Virtual Machines, Cloud Computing.
