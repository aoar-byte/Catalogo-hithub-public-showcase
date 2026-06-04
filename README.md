# 🎵 HHB Catálogo Musical - Showcase Técnico

![Next.js](https://img.shields.io/badge/Next.js-16.2-black?logo=next.js)
![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ecf8e?logo=supabase)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)

## 🚀 Destaques Técnicos

### 🔐 Segurança com Signed URLs
- **Arquivo**: `app/api/audio/route.ts`
- **Técnica**: Geração de URLs assinadas via Supabase Storage (expiração de 60s)
- **Proteção**: Frontend NUNCA vê a URL original do arquivo

### 🎧 Player de Áudio Protegido
- **Arquivo**: `app/audition/[token]/page.tsx`
- **Features**: Playlist dinâmica, busca textual, filtro por gênero
- **Segurança**: Bloqueio de botão direito, `draggable={false}`, `select-none`

### 🔑 Fluxo de Autenticação Customizado
- **Arquivo**: `app/invite/[token]/page.tsx`
- **Métodos**: Google OAuth + EmailJS (código de 6 dígitos)
- **Pattern**: Convite por link → Login → Redirecionamento com token

### 🗄️ Modelagem de Banco Relacional
- **Arquivo**: `sql/schema.sql`
- **Tabelas**: tracks, users, audition_playlists, user_playlists, play_logs
- **Destaque**: Array columns (`track_ids`, `shared_with`, `compradores`)
- **Índices**: Otimização para buscas por gênero, token e email

## 🛠️ Stack Tecnológica

| Tecnologia | Uso |
|-----------|-----|
| Next.js 16 (App Router) | Framework React com SSR |
| Supabase | PostgreSQL + Storage + Auth |
| TypeScript | Tipagem estática |
| Tailwind CSS | Estilização utility-first |
| Lucide Icons | Biblioteca de ícones |
| EmailJS | Envio de emails transacionais |

## 📂 Estrutura do Projeto
