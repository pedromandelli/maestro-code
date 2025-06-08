# Pedrom.pro - Site Pessoal

## Visão Geral
Site pessoal profissional para Pedro Mandelli, inspirado no design minimalista e focado do https://ian.is. O objetivo é criar uma presença online clean, profissional e que destaque experiências, projetos e conhecimentos.

## Objetivos do Projeto

### Principal
- Criar um site pessoal profissional e minimalista
- Estabelecer presença online para networking e oportunidades
- Showcase de projetos e habilidades técnicas

### Secundários  
- Implementar blog para compartilhar conhecimentos
- Criar seções para portfólio de projetos
- Integrar com redes sociais e GitHub

## Arquitetura Técnica

### Stack Proposta
- **Frontend**: HTML5, CSS3, JavaScript vanilla (minimalista)
- **Hospedagem**: VPS atual com Docker
- **Domínio**: Pedrom.pro (já adquirido)
- **SSL**: Let's Encrypt via Nginx
- **CMS**: Opcional - considerar headless CMS para blog

### Estrutura de Deployment
- Container Docker isolado seguindo o padrão do VPS_MULTI_PROJECT_GUIDE
- Nginx como proxy reverso
- Backup automatizado
- Monitoramento via Portainer

## Funcionalidades Principais

### V1.0 (MVP)
- [ ] Página inicial com bio profissional
- [ ] Seção "Sobre"
- [ ] Lista de projetos/experiências
- [ ] Contato e links sociais
- [ ] Design responsivo

### V2.0 (Futuro)
- [ ] Blog integrado
- [ ] Sistema de comentários
- [ ] Newsletter
- [ ] Analytics

## Inspirações de Design
- **ian.is**: Minimalismo, tipografia clean, foco no conteúdo
- **Design Philosophy**: "Less is more" - conteúdo > decoração

## Próximos Passos
1. ✅ Criar feature plan detalhado para o MVP → [website-mvp-plan.md](features/website-mvp-plan.md)
2. Configurar estrutura Docker no VPS
3. Implementar design base
4. Deploy e configuração de domínio

## Feature Plans Ativos
- **[Website MVP](features/website-mvp-plan.md)** - Landing page minimalista inspirada no ian.is - *ATIVO*

---

*Este plano será refinado conforme o desenvolvimento avança. Consulte `.ai/plans/features/` para planos específicos de cada feature.* 