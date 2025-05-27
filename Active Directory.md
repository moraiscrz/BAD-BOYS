# 🪟 Active Directory – Instalação e Configuração

## Pré-requisitos

- Windows Server já instalado
- IP fixo configurado

## Instalação

1. Abra o **Gerenciador de Servidores**.
2. Clique em **Adicionar funções e recursos**.
3. Avance até chegar em **Funções do Servidor**.
4. Marque a opção **Serviços de Domínio do Active Directory**.
5. Instale e aguarde a finalização.

## Configuração (Promover a Controlador de Domínio)

1. Após a instalação, clique na notificação no topo: **"Promover este servidor a controlador de domínio"**.
2. Selecione **Adicionar uma nova floresta** e defina um nome de domínio (ex: `empresa.local`).
3. Defina senha do modo de restauração do diretório (DSRM).
4. Avance com as opções padrão e conclua.
5. O servidor será reiniciado automaticamente.

## Verificação

- Use a ferramenta **"Usuários e Computadores do Active Directory"** para criar usuários e grupos.
- Verifique se o DNS foi configurado automaticamente.
