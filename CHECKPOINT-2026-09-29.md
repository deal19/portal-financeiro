# CHECKPOINT — Portal Financeiro — 2026-09-29

Este arquivo marca o estado estável do Portal Financeiro solicitado pelo usuário antes das próximas alterações.

## Estado do código
- Repositório: deal19/portal-financeiro
- Branch principal no momento do checkpoint: main
- Commit exato do código estável: ef3194d68dc5c772090f7cc36692b2f2cf078ce1
- Mensagem do commit: Ajustar mensagem após criação da conta
- Branch de preservação: checkpoint-estavel-2026-09-29

## O que estava funcionando
- Cadastro de usuário
- Login
- Mensagem pós-cadastro: "Conta criada com sucesso. Faça login para entrar."
- Confirmação de e-mail desativada no Supabase
- Cadastro sem envio de e-mail de confirmação
- Sem redirecionamento para localhost
- Onboarding de primeiro login
- Dashboard financeiro
- Lançamentos
- Despesas fixas
- Categorias
- Metas
- Reserva
- Relatórios
- Conta/perfil
- Interface responsiva para iPhone/Android
- Supabase conectado
- Vercel conectado ao GitHub

## Supabase
- Projeto: portal-financeiro
- Project ref: jfomzksnsjytqhsuaqto
- Região: sa-east-1
- URL: https://jfomzksnsjytqhsuaqto.supabase.co
- Confirm Email: OFF no momento do checkpoint

## Banco criado
- public.perfis
- public.categorias
- public.lancamentos
- public.metas
- public.reservas
- public.configuracoes
- public.despesas_fixas
- Trigger public.handle_new_user para perfil, reserva e categorias padrão
- RLS configurado por usuário
- Security Advisor estava sem lints após a criação do schema

## Regra de trabalho a partir deste checkpoint
Preservar este estado. Para novas mudanças: uma função por vez; testar; se funcionar, criar novo ponto de backup antes da próxima alteração.

## Regra de restauração
Se o usuário disser "volte para aquele último projeto salvo", "volte para o checkpoint" ou equivalente, usar este checkpoint como referência principal e não misturar com DEXL Finance, Materiais Aldeia ou projetos antigos/deletados.
