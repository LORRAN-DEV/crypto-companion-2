# Crypto Companion

![React](https://img.shields.io/badge/React-18-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue?logo=typescript)
![Vite](https://img.shields.io/badge/Vite-5.4-purple?logo=vite)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4-blue?logo=tailwindcss)
![Supabase](https://img.shields.io/badge/Supabase-Backend-green?logo=supabase)

---

## Introducao

**Crypto Companion** e uma aplicacao web para **acompanhamento e gestao de criptomoedas**, construida com **React + TypeScript** e backend **Supabase**.

O projeto permite visualizar dados de mercado, acompanhar portfolio de criptoativos e gerenciar investimentos com uma interface moderna e responsiva.

---

## Como Executar

### Pre-requisitos
- Node.js 18+
- npm ou bun

### Instalacao
```bash
# Clone o repositorio
git clone https://github.com/LORRAN-DEV/crypto-companion-2.git
cd crypto-companion-2

# Instale as dependencias
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

### Acesso
| Servico     | URL                    |
|-------------|------------------------|
| Frontend    | http://localhost:8080   |

---

## Arquitetura e Tecnologias

### Stack Principal
| Tecnologia        | Funcao                          |
|-------------------|---------------------------------|
| **React 18**      | Biblioteca de UI                |
| **TypeScript**    | Tipagem estatica                |
| **Vite**          | Build tool e dev server         |
| **Tailwind CSS**  | Estilizacao utility-first       |
| **shadcn/ui**     | Componentes de interface        |
| **Supabase**      | Backend, auth e banco de dados  |

### Bibliotecas de Suporte
| Biblioteca              | Funcao                          |
|-------------------------|---------------------------------|
| **React Router DOM**    | Roteamento SPA                  |
| **TanStack React Query**| Gerenciamento de estado server  |
| **React Hook Form**     | Gerenciamento de formularios    |
| **Zod**                 | Validacao de schemas            |
| **Recharts**            | Graficos e visualizacao de dados|
| **Lucide React**        | Icones                          |
| **Sonner**              | Notificacoes toast              |
| **next-themes**         | Suporte a dark mode             |
| **date-fns**            | Manipulacao de datas            |

### Componentes UI (Radix UI)
O projeto utiliza **shadcn/ui** com diversos componentes Radix:
- Dialog, Dropdown, Accordion, Tabs
- Tooltip, Popover, Toast
- Carousel (Embla), Resizable Panels
- Command Palette (cmdk)

---

## Features

- Dashboard com graficos de mercado cripto (Recharts)
- Dark Mode com alternancia de tema
- Autenticacao via Supabase Auth
- Design Responsivo com Tailwind CSS
- Command Palette para navegacao rapida
- Formularios com validacao em tempo real (Zod + React Hook Form)
- Notificacoes toast para feedback do usuario
- HMR com Vite para desenvolvimento rapido

---

## Scripts Disponiveis

```bash
npm run dev       # Servidor de desenvolvimento
npm run build     # Build para producao
npm run preview   # Preview do build
npm run lint      # Linting com ESLint
npm run test      # Testes com Vitest
```

---

## Configuracao

### Variaveis de Ambiente (`.env`)
```bash
VITE_SUPABASE_URL=<sua-url-supabase>
VITE_SUPABASE_ANON_KEY=<sua-chave-publica>
```

### Estrutura de Configuracao
| Arquivo               | Funcao                     |
|-----------------------|----------------------------|
| `vite.config.ts`      | Configuracao do Vite       |
| `tailwind.config.ts`  | Tema e design system       |
| `tsconfig.json`       | Configuracao TypeScript    |
| `components.json`     | Configuracao shadcn/ui     |
| `eslint.config.js`    | Regras de linting          |

---

## Resumo

- Stack moderna com React 18 + TypeScript + Vite
- UI profissional com shadcn/ui + Tailwind CSS
- Backend serverless com Supabase
- Graficos interativos para dados de mercado
- Autenticacao e gerenciamento de sessao
- Dark mode e design responsivo
- Testes configurados com Vitest
