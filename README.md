# Sereia's • H8O

Site estático em HTML e CSS apresentando o projeto Sereia's (H8O), sua proposta, valores e equipe.

## Visão Geral
A proposta é comunicar de forma leve e elegante a iniciativa Sereia's, com estética marítima suave, tipografia artesanal e foco em clareza. O layout foca em:
- Hero inicial com identidade (logo, ondas decorativas e "H8O").
- Seção introdutória com cards temáticos.
- Página Sobre: Introdução, Objetivos, Missão, Visão, Valores e galeria.
- Página Equipe: nomes intercalados com ícones marinhos.
- Animações suaves de entrada e flutuação respeitando prefers-reduced-motion.

## Tecnologias
- HTML5 sem frameworks.
- CSS3 (Flexbox, Grid, animações, responsividade).
- Tipografias Google Fonts: Yeseva One, Alice, Sacramento, Amatic SC.

## Estrutura
```
index.html
pages/
  about.html
  team.html
styles/
  globals.css
  about.css
  team.css
  animation.css
assets/
  Logo.png, ondas.png, ícones e ilustrações
```

## Paleta de Cores
- Azul claro header: `#caecf1`
- Fundo seções claras: `#ddfaff`
- Seção inferior home: `#e9decf`
- Títulos marrons: `#886956`
- Subtítulos / destaques: `#42638f` / `#23476a`

## Animações
Definidas em `animation.css`:
- fadeIn, fadeUp, gentleScale para entrada.
- float / bob para elementos decorativos.
- Delays escalonados em listas e seções.
- Suporte a prefers-reduced-motion.

## Responsividade
Breakpoints utilizados (~560px, 600px, 700px, 900px, 981px) ajustam tamanhos tipográficos, espaçamentos e reorganização de elementos para leitura fluida em mobile.

## Acessibilidade
- Uso de alt em imagens relevantes.
- Elementos puramente decorativos marcados semanticamente ou sem texto redundante.
- Animações desativadas para usuários com redução de movimento.

## Como Executar
Não há dependências. Basta abrir `index.html` em um navegador moderno.

## Melhorias Futuras (Sugestões)
- Adicionar página de contato ou formulário.
- Otimização das imagens (webp já utilizado, considerar tamanhos responsivos). 
- Dark mode opcional.
- Testes de contraste adicionais.

## Contribuição
Sugestão: criar branches por feature e abrir Pull Request descrevendo mudanças visuais.

## Licença
Definir (MIT / Creative Commons ou outra). Adicionar arquivo LICENSE se necessário.

---
Projeto educacional / demonstrativo. Ajuste livre conforme evolução do design.
