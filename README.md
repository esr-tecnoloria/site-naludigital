# Nalu Digital - Site Institucional

Site institucional moderno e responsivo para a Nalu Digital, empresa especializada em criação de apps, bots, IA e sites.

## 🚀 Características

- **Design Moderno**: Interface limpa e profissional inspirada nos melhores sites do mercado
- **Totalmente Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Performance Otimizada**: Carregamento rápido e otimizado
- **Animações Suaves**: Transições e efeitos visuais elegantes
- **SEO Friendly**: Estrutura otimizada para mecanismos de busca

## 📁 Estrutura do Projeto

```
site-naludigital/
├── index.html      # Página principal
├── styles.css      # Estilos e design
├── main.js         # JavaScript e interatividade
└── README.md       # Documentação
```

## 🎨 Seções do Site

1. **Home**: Hero section com apresentação da empresa e estatísticas
2. **Serviços**: Cards destacando os 4 principais serviços:
   - Aplicativos
   - Bots Inteligentes
   - Inteligência Artificial
   - Sites Modernos
3. **Sobre**: Informações sobre a empresa e valores
4. **Contato**: Formulário de contato e informações de contato

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (com variáveis CSS e Grid/Flexbox)
- JavaScript (Vanilla JS)
- Google Fonts (Inter)

## 📱 Como Usar

1. Abra o arquivo `index.html` em um navegador moderno
2. Ou use um servidor local:
   ```bash
   # Com Python
   python -m http.server 8000
   
   # Com Node.js (http-server)
   npx http-server
   
   # Com PHP
   php -S localhost:8000
   ```

## 🎯 Personalização

### Cores

As cores podem ser alteradas nas variáveis CSS no arquivo `styles.css`:

```css
:root {
    --first-color: #4A90E2;      /* Cor principal */
    --first-color-alt: #357ABD;  /* Cor principal alternativa */
    --second-color: #7B68EE;     /* Cor secundária */
    --title-color: #1A1A1A;      /* Cor dos títulos */
    --text-color: #4A4A4A;       /* Cor do texto */
}
```

### Conteúdo

Edite o arquivo `index.html` para alterar textos, informações de contato e conteúdo das seções.

### Formulário de Contato

O formulário de contato atualmente mostra uma mensagem de sucesso simulada. Para integrar com um backend real, edite a função de submit no arquivo `main.js`.

## 📧 Informações de Contato

Atualize as informações de contato na seção de contato do `index.html`:

- E-mail: contato@naludigital.com.br
- Telefone: +55 (85) 99999-9999
- Localização: Fortaleza - CE, Brasil

## 🌐 Compatibilidade

- Chrome (últimas versões)
- Firefox (últimas versões)
- Safari (últimas versões)
- Edge (últimas versões)

## 📝 Licença

Este projeto foi criado para a Nalu Digital.

## 👨‍💻 Desenvolvimento

Para desenvolvimento futuro, considere:

- Integração com backend para formulário de contato
- Adição de blog/notícias
- Seção de portfólio com projetos realizados
- Integração com Google Analytics
- Otimizações adicionais de performance
- Testes automatizados
