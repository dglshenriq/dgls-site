# Dgls

Site-portfólio de um desenvolvedor web especializado em **sites e landing pages para pequenos negócios**. O objetivo da página é apresentar os serviços, explicar o processo de trabalho e converter visitantes em clientes.

## Seções

- **Header fixo** com logo e menu de navegação
- **Hero** com chamada principal e CTA
- **Por que ter um site ou uma landing page?**
- **Benefícios** (design responsivo, carregamento rápido, foco em conversão, suporte)
- **Serviços** (landing pages, páginas de captura, sites institucionais, integrações)
- **Processo** (briefing, desenvolvimento, revisão, entrega)
- **Portfólio**
- **Sobre**
- **CTA final** e **Footer** com redes sociais, navegação e contato

## Tecnologias

- HTML5 semântico
- CSS3 (variáveis, Grid, Flexbox, media queries)
- JavaScript puro (menu mobile)
- Sem frameworks e sem dependências, só as fontes do Google Fonts

## Estrutura do projeto

```
├── index.html
├── img/
├── js/
│   └── main.js
└── css/
    ├── base.css
    ├── header.css
    ├── hero.css
    ├── o-que-e.css
    ├── beneficios.css
    ├── servicos.css
    ├── processo.css
    ├── portfolio.css
    ├── sobre.css
    ├── cta.css
    └── footer.css
```

Cada componente tem o seu próprio arquivo CSS, o que facilita a manutenção. As cores e fontes ficam centralizadas como variáveis em `base.css`.

## Como rodar

Não precisa instalar nada. Clone o repositório e abra o `index.html` no navegador:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

Se preferir, use a extensão **Live Server** do VS Code.

## Personalização

- **Cores:** altere `--primary`, `--secondary` e `--accent` em `css/base.css`
- **Textos e contatos:** edite diretamente o `index.html`
- **Foto de perfil:** coloque a imagem em `img/` e ajuste o `src` na seção Sobre

## Contato

- E-mail: seu-email@exemplo.com
- LinkedIn: [seu perfil](https://linkedin.com/in/seu-perfil)

## Licença

Defina a licença que preferir (por exemplo, MIT) ou mantenha o projeto como "todos os direitos reservados".
