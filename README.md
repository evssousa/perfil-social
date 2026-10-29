# Perfil Social

Cartão de perfil pessoal em página única, no estilo "link na bio": reúne foto, nome, área de atuação e links para as principais redes sociais, com alternância entre modo claro e escuro.

🔗 **Demo:** [evssousa.github.io/perfil-social](https://evssousa.github.io/perfil-social)

<p align="center">
  <img src="img/preview-claro.png" alt="Preview do Perfil Social no modo claro" width="48%">
  <img src="img/preview-escuro.png" alt="Preview do Perfil Social no modo escuro" width="48%">
</p>

## Funcionalidades

- Cartão de perfil centralizado, com foto circular, nome e cargo
- Ícones de redes sociais (Facebook, Instagram, GitHub e LinkedIn) com efeito de hover
- Botão para alternar entre **modo claro e escuro**, com transição suave de cores
- Layout simples e responsivo, sem dependência de frameworks

## Tecnologias

- **HTML5**: estrutura da página
- **CSS3**: layout com Flexbox, transições e temas claro/escuro
- **JavaScript (puro)**: alternância do tema
- **[Font Awesome 4.7](https://fontawesome.com/v4/)**: ícones das redes sociais
- **[Google Fonts (Poppins)](https://fonts.google.com/specimen/Poppins)**: tipografia
- **GitHub Pages**: hospedagem

## Estrutura do projeto

```
perfil-social/
├── img/
│   ├── perfil.png          # foto de perfil
│   ├── preview-claro.png   # print do modo claro
│   └── preview-escuro.png  # print do modo escuro
├── index.html              # estrutura da página
├── style.css               # estilos e temas
├── script.js               # alternância claro/escuro
└── README.md
```

## Como rodar localmente

Não precisa instalar nada. Basta clonar o repositório e abrir o arquivo no navegador:

```bash
git clone https://github.com/evssousa/perfil-social.git
cd perfil-social
```

Depois, abra o `index.html` no navegador (duplo clique no arquivo ou, no VS Code, use a extensão Live Server).

## Como funciona o modo escuro

O botão no canto superior do cartão adiciona ou remove a classe `dark` na seção principal (`script.js`). O CSS (`style.css`) usa essa classe para trocar as cores de fundo, do cartão, dos textos e dos ícones, com `transition` para suavizar a mudança.

## Ideias de melhorias futuras

- Lembrar a escolha de tema do visitante com `localStorage`
- Respeitar o tema do sistema com `prefers-color-scheme`
- Adicionar `aria-label` nos links de redes sociais para melhorar a acessibilidade
- Incluir mais redes ou links (portfólio, e-mail)

## Autor

**Everson Sousa**, Análise e Desenvolvimento de Sistemas

[![GitHub](https://img.shields.io/badge/GitHub-evssousa-181717?logo=github&logoColor=white)](https://github.com/evssousa)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-evssousa-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/evssousa)
[![Instagram](https://img.shields.io/badge/Instagram-evs.py-E4405F?logo=instagram&logoColor=white)](https://instagram.com/evs.py)
