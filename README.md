
![localhost_3000_app](https://github.com/WesleyR10/Micro-Saas-Todo/assets/115756312/86f9bbaf-019b-4656-9925-5b6d907cf1a9)

# Micro-SaaS Todo App

## Descrição
O Micro-SaaS Todo App é uma aplicação Next.js projetada para gerenciamento de tarefas com recursos avançados como autenticação baseada em e-mail (Magic Link), integração com Stripe para pagamentos e uma interface responsiva. O objetivo é proporcionar uma experiência de usuário sem interrupções com capacidades eficientes de manipulação de tarefas.

## Tecnologias Utilizadas
- **Next.js**: Para renderização no lado do servidor e geração de sites estáticos.
- **NextAuth**: Para autenticação usando Magic Links.
- **Stripe**: Para manipulação de pagamentos.
- **Tailwind CSS**: Para estilização e design responsivo.
- **Prisma**: Como ORM para gerenciamento de banco de dados.
- **Nodemailer**: Para envio de e-mails.
- **React**: Para construção da interface do usuário.

## Principais Funcionalidades
- **Integração com E-mail**: Os usuários podem fazer login usando Magic Link enviado para o seu e-mail.
- **Integração com Stripe**: Facilita o processamento e gerenciamento de pagamentos.
- **Layout Responsivo**: Utiliza `shadcn/ui` para uma interface limpa e moderna.
- **Modo Alternável**: Permite que os usuários alternem entre o modo claro e escuro para melhor acessibilidade.

## Configuração e Instalação
1. Clone o repositório:
```
git clone https://github.com/WesleyR10/Micro-Saas-Todo.git
```
2. Instale as dependências:
```
cd micro-saas-todo-app
yarn
```
3. Configure as variáveis de ambiente:
   - Crie um arquivo `.env` e configure as chaves de API necessárias e URLs de banco de dados conforme o `.env.example`.

4. Execute o servidor de desenvolvimento:
```yarn dev```


## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para enviar um pull request ou abrir uma issue para qualquer bug ou melhoria.
