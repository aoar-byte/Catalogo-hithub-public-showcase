# 🎵 HHB Catálogo Musical

[![Next.js](https://img.shields.io/badge/Next.js-16.2-black)](https://nextjs.org/)
[![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ecf8e)](https://supabase.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)](https://www.typescriptlang.org/)

## 🚀 Sobre o Projeto

Plataforma full-stack de gerenciamento de catálogo musical com:

- 🔐 **Autenticação customizada** (Google OAuth + EmailJS)
- 🎧 **Player de áudio com Signed URLs** (Supabase Storage)
- 📋 **Sistema de playlists** para audição de clientes
- 👥 **Controle de acesso** (Admin, Sócio, Ouvinte)
- 📊 **Classificação de músicas** (Inédita, Gravada, Buyout, Sync, Exclusiva)
- 🔗 **Convites por link** com landing page personalizada

## 🔒 Aviso de Segurança
> - O código-fonte completo está em repositório privado para proteger lógica proprietária.
> - Estrutura de banco de dados
> - Chaves de API e tokens de acesso
> - Para avaliadores técnicos: Solicite acesso via Issue ou LinkedIn. Enviarei o convite de colaborador imediatamente. 

## 🛠️ Stack Tecnológica

| Camada | Tecnologia |
|--------|-----------|
| Frontend | Next.js 16 (App Router) + React 18 |
| Estilização | Tailwind CSS + Lucide Icons |
| Backend | Supabase (PostgreSQL + Storage) |
| Autenticação | Google OAuth + EmailJS |
| Deploy | Vercel (CI/CD automático) |
| Linguagem | TypeScript (tipagem estrita) |

## 📊 Métricas do Projeto

- **100+ deploys** em produção
- **5 tipos de usuários** com permissões distintas
- **40+ músicas** no catálogo
- **Sistema de logs** com rastreamento de plays

## 🎯 Funcionalidades Implementadas

### Para Sócios/Admin:
- CRUD completo de músicas
- Criação de playlists de audição
- Compartilhamento entre sócios
- Geração de links de convite
- Painel administrativo com logs

### Para Clientes:
- Login simplificado via convite
- Player de música com busca e filtros
- Layout limpo (sem dados internos)
- Experiência mobile-first

### Segurança:
- URLs de áudio assinadas (expiração em segundos)
- Proteção contra download (bloqueio de contexto)
- Sanitização de inputs
- Row Level Security (RLS) no banco

## 📞 Contato

**Desenvolvedor:** Leandro Aô  
**GitHub:** [@aoar-byte](https://github.com/aoar-byte)  
**Disponível para:** Projetos e oportunidades

---

*"Transformando ideias em ativos musicais através da tecnologia."*
