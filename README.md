# Consórcio Familiar Inteligente — Smart Contract

Um contrato inteligente (smart contract) desenvolvido para facilitar a criação e gestão de grupos de consórcio familiar voltados para a compra colaborativa de bens e imóveis, eliminando intermediários, reduzindo custos e garantindo transparência e automação no processo.

# 📌 Sobre o Projeto

Este projeto implementa um sistema de consórcio descentralizado, no qual os participantes contribuem com valores mensais para formar uma poupança coletiva. O contrato inteligente automatiza:

A criação de grupos de consórcio

O gerenciamento das contribuições

A seleção automática ou manual do contemplado

A verificação de saldo e elegibilidade

A emissão de comprovantes de participação

A transparência de todas as operações na blockchain

**O objetivo é permitir que familiares ou grupos pequenos possam se organizar de forma segura, auditável e sem intermediação financeira.**

# 🚀 Funcionalidades

🔐 Cadastro de participantes

💰 Registro e controle de contribuições

🎯 Sorteio ou contemplação por lance (se implementado)

🏆 Seleção e liberação de crédito para o contemplado

📄 Histórico transparente das transações

⛓️ Imutabilidade e automação garantidas pela blockchain

# 🛠️ Tecnologias Utilizadas

Solidity (desenvolvimento do contrato)

Ethereum / EVM (compatível)

Hardhat ou Foundry (dependendo do seu setup)

Node.js (scripts e automações)

OpenZeppelin (segurança e padrões)

# 📁 Estrutura do Projeto

     /contracts
         ConsorcioFamiliar.sol
    /scripts
    /test
    hardhat.config.js
    package.json
    README.md

    
**⚙️ Como Executar o Projeto**

1. Instale as dependências

     bash
   
         npm install

2. Compile o contrato

      bash

         npx hardhat compile
 3. Execute os testes

     bash


           npx hadrhat test
 
 4. faça o deploy em uma rede local


      bash


           npx hardhat run scripts/deploy.js --network localhost

# 🔒 Segurança

Funções críticas protegidas por modificadores de acesso

Validações de integridade financeira

Utilização de padrões recomendados pela OpenZeppelin

Lógica auditável e transparente

Se quiser, posso adicionar uma seção de auditoria, riscos e mitigação.

# 📌 Status do Projeto

🟩 Em desenvolvimento

Funcionalidades principais implementadas / sendo aprimoradas:

Cadastro de participantes

Registro de contribuições

Seleção de contemplado

Retirada de crédito

Em breve:

Gestão de múltiplos grupos

Lances e sorteios

Interface Web3 (dApp)

# 🤝 Contribuição

Pull requests são bem-vindos!
Siga as boas práticas de commit e utilize branches organizadas:

main – versão estável

dev – desenvolvimento

feature/* – novas funcionalidades

# 📄 Licença

Este projeto é distribuído sob a licença MIT.
Sinta-se livre para usar, modificar e contribuir.

# ✉️ Contato

Caso queira trocar ideias, sugerir melhorias ou colaborar:

Felipe Ziul

📧 felipe.kobe@hotmail.com

🌐 GitHub: felipe1fluiz-byte

   
    


