# Projeto Link-In-Bio

Este é um projeto front-end criado com Next.js e Tailwind CSS que exibe um cartão de perfil de rede social com links para plataformas como GitHub, Twitter, LinkedIn e Instagram. O código usa componentes reutilizáveis e estilizados, com um gradiente de fundo, ícones personalizados, e links estilizados para redes sociais.
## Tecnologias Utilizadas
- React
- Next.js
- Tailwind
- Shadcn
- Typescript

## Estrutura e Renderização
`socialLinks:` Array de objetos com detalhes de cada rede social:
- `name:` Nome da rede social.
- `icon:` Ícone correspondente.
- `url:` Link do perfil.
- `color:` Cor de fundo do botão associada à marca da rede.

## Exemplo de Uso
Este projeto pode ser utilizado em uma página de perfil ou landing page para promover conexão com o usuário nas redes sociais.

#### Observações Técnicas
- Compatibilidade com Next.js: Usa "use client" no topo para garantir a renderização no lado do cliente.
- Interatividade: Usa o onClick para abrir links externos e evitar problemas de navegação em Single Page Applications (SPA).

![banner](/public/banner.png)
