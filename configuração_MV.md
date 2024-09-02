# Configuração de Recursos e Dimensionamento de Máquinas Virtuais na Azure

## Passo 1: Acessar o Portal do Azure
1. Abra o navegador e acesse o [Portal do Azure](https://portal.azure.com).
2. Faça login com sua conta da Microsoft.

## Passo 2: Criar uma Nova Máquina Virtual
1. No painel do Azure, clique em **"Criar um recurso"**.
2. Selecione **"Máquina Virtual"** na lista de recursos disponíveis.
3. Escolha uma **assinatura** e **grupo de recursos** existentes ou crie um novo.
4. Insira um nome para a máquina virtual no campo **"Nome da VM"**.
5. Selecione a **região** onde a VM será implantada (por exemplo, "East US").

## Passo 3: Escolher o Sistema Operacional e Imagem
1. Na seção **"Imagem"**, selecione o sistema operacional desejado (por exemplo, "Windows Server 2022" ou "Ubuntu 20.04").
2. Escolha o **tamanho da VM** de acordo com suas necessidades de desempenho e custo (por exemplo, "Standard_D2s_v3").

## Passo 4: Configurar Opções de Redundância e Disponibilidade
1. Selecione uma **opção de alta disponibilidade** se necessário (por exemplo, conjuntos de disponibilidade ou zonas de disponibilidade).
2. Escolha um **modelo de disco de SO** (SSD, HDD, etc.) com base em suas preferências de desempenho e custo.

## Passo 5: Definir a Autenticação e Credenciais
1. Escolha o tipo de autenticação (senha ou chave SSH).
2. Insira o nome de usuário e senha para o acesso da VM.

## Passo 6: Configurar as Redes
1. Na aba **"Rede"**, configure a rede virtual e o sub-rede para sua máquina virtual.
2. Defina um **endereço IP público** se necessário.
3. Selecione as **regras de segurança** de entrada para controlar o tráfego.

## Passo 7: Configuração Avançada
1. Defina as opções de **monitoramento e diagnóstico**, como o Log Analytics.
2. Configure a **autoescala** se desejar ajustar automaticamente o tamanho da VM com base na demanda.

## Passo 8: Revisar e Criar
1. Revise todas as configurações definidas.
2. Clique em **"Revisar + Criar"**.
3. Após a validação, clique em **"Criar"** para iniciar a implantação da máquina virtual.

## Passo 9: Monitorar e Dimensionar a Máquina Virtual
1. Após a criação, vá para o recurso da VM no portal do Azure.
2. Use o painel de **"Monitoramento"** para visualizar o uso de CPU, memória e outros recursos.
3. Para redimensionar a máquina, clique em **"Tamanho"** na página de configurações da VM e escolha um novo tamanho conforme necessário.

## Passo 10: Ajustes Finais
1. Teste a conectividade da máquina virtual e o desempenho conforme necessário.
2. Faça ajustes adicionais, como balanceamento de carga, backup ou configuração de firewall, se necessário.

---

### Dicas Adicionais:
- Utilize **tags** para organizar e gerenciar seus recursos no Azure.
- Revise regularmente os custos associados à VM para garantir que você está operando de forma econômica.
- Configure **alertas de monitoramento** para ser notificado de qualquer uso excessivo ou problemas de desempenho.

Boa sorte com a configuração e dimensionamento das suas máquinas virtuais na Azure!
