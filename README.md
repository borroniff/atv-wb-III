# Sistema de Gerenciamento WB - ATVIII (Versão com React Hooks)

## 📋 Descrição
Sistema GUI moderno desenvolvido com **React Hooks** e TypeScript para o Grupo World Beauty, utilizando MaterializeCSS. Esta versão implementa todos os componentes como funções utilizando Hooks, seguindo as melhores práticas atuais do React.

## 🚀 Tecnologias
- **React**: 18.0.0 (com Hooks)
- **TypeScript**: 4.6.3  
- **MaterializeCSS**: 1.0.0
- **Node.js**: 16.x ou superior

## ✅ Funcionalidades
- **CRUD completo** para Clientes, Produtos e Serviços
- **Componentes funcionais** com useState, useEffect
- **Design responsivo** para desktop e mobile
- **Validação de formulários** integrada
- **Navegação** entre telas com estado gerenciado por hooks
- **Feedback visual** com toasts do Materialize

## 🛠️ Como executar

1. **Pré-requisitos**:
   ```bash
   node --version  # Verifique se é 16.x ou superior
   npm --version   # 6.x ou superior
   ```

2. **Instalação**:
   ```bash
   git clone https://github.com/borroniff/atv-wb-III
   cd atv-wb-III
   npm install
   ```

3. **Execução**:
   ```bash
   npm start
   ```

4. **Build para produção**:
   ```bash
   npm run build
   ```

## 📂 Estrutura do Projeto
```
src/
├── components/
│   ├── barraNavegacao.tsx        # Barra de navegação com useEffect
│   ├── formularioCadastro*.tsx   # Formulários com useState
│   ├── lista*.tsx                # Listagens com props
│   └── roteador.tsx              # Gerenciador de estado com useState
├── public/                      # Assets estáticos
└── types.ts                     # Tipos TypeScript
```

## 🔄 Hooks Utilizados
- `useState` para gerenciamento de estado local
- `useEffect` para side effects e inicialização

## 👨‍💻 Desenvolvido por
Angelina Borroni Ferreira
