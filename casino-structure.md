```
casino-royal/
├── src/
│   ├── app/                         # Páginas e rotas Next.js
│   │   ├── admin/                   # Área administrativa
│   │   ├── api/                     # Endpoints da API
│   │   ├── auth/                    # Páginas de autenticação
│   │   ├── dashboard/               # Dashboard do usuário
│   │   ├── games/                   # Jogos de cassino
│   │   ├── affiliate/               # Sistema de afiliados
│   │   └── payments/                # Sistema de pagamentos
│   ├── components/                  # Componentes React reutilizáveis
│   │   ├── common/                  # Componentes globais
│   │   ├── admin/                   # Componentes da área admin
│   │   ├── games/                   # Componentes dos jogos
│   │   ├── dashboard/               # Componentes do dashboard
│   │   └── layout/                  # Componentes de layout
│   ├── hooks/                       # Hooks personalizados
│   ├── lib/                         # Bibliotecas e utilitários
│   │   ├── auth/                    # Lógica de autenticação
│   │   ├── db/                      # Configuração do banco de dados
│   │   ├── api/                     # Funções de API 
│   │   └── games/                   # Lógica dos jogos
│   ├── models/                      # Modelos de dados e types
│   ├── utils/                       # Funções utilitárias
│   └── styles/                      # Estilos globais
├── public/                          # Arquivos estáticos
│   ├── assets/                      # Imagens e ícones
│   ├── sounds/                      # Sons dos jogos
│   └── animations/                  # Animações
├── prisma/                          # Configuração do Prisma ORM
│   └── schema.prisma                # Schema do banco de dados
├── .env.example                     # Template de variáveis de ambiente
├── .gitignore                       # Arquivos ignorados pelo Git
├── package.json                     # Dependências do projeto
├── next.config.js                   # Configuração do Next.js
├── tsconfig.json                    # Configuração TypeScript
└── README.md                        # Documentação do projeto
```