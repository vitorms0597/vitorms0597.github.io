# Plano de execução - Site SBTECH

## Estrutura de páginas/seções (single page)
- **Hero**: proposta de valor + CTA "Fale com a gente"
- **Sobre**: história e missão da empresa
- **Serviços**: cards dos 4 serviços
- **Cases**: destaque para o Colégio Nova Prana
- **Projetos próprios**: projetos pessoais (pagos ou open source)
- **Fundadores**: Vitor e João Pedro com links para LinkedIn
- **Contato**: botão WhatsApp

## Pendências de conteúdo
- [ ] Projetos próprios: coletar nome, descrição, status e modelo (pago/open source) de cada projeto
- [ ] Fundadores: coletar de cada um — cargo/título, stack principal e bio curta (1-2 frases)
  - [ ] Vitor Mendes dos Santos
  - [ ] João Pedro Mendes dos Santos

## Tecnologia
- HTML / CSS / JavaScript puro (site estático)
- Sem build, sem dependências — abre direto no browser

## SEO (já implementado)
- `<title>` e `<meta description>` otimizados
- Open Graph tags (preview no WhatsApp/LinkedIn)
- Schema.org `Organization` (dados estruturados para o Google)
- HTML semântico com hierarquia h1→h2→h3 e atributos `aria-label`
- `robots.txt` e `sitemap.xml`
- `<link rel="canonical">`

## Hospedagem
- GitHub Pages (gratuito)
- Repositório: `<username>.github.io` → URL: `https://<username>.github.io`
- [ ] Definir username da organização no GitHub
- Domínio próprio: decidir depois

## Próximos passos
- [x] Definir objetivo e stack
- [x] Definir identidade visual (paleta extraída do logo)
- [x] Criar MVP da página com as seções principais
- [x] Aplicar SEO completo
- [ ] Coletar informações dos fundadores e preencher seção
- [ ] Coletar lista de projetos próprios e criar seção
- [ ] Definir username do GitHub e ajustar URLs do SEO
- [ ] Criar repositório e publicar no GitHub Pages
- [ ] Decidir sobre domínio próprio
