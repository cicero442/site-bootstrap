# ✈️ ViajaMais Turismo

## 📌 Nome do Projeto
**ViajaMais Turismo** — Site Institucional e Catálogo de Pacotes de Viagem.

## 👤 Nome do Aluno
Cícero caetano e shopia varcalho

## 📝 Descrição do Projeto
O **ViajaMais Turismo** é uma plataforma web responsiva voltada para a divulgação de destinos e pacotes turísticos nacionais e internacionais. O projeto foi desenvolvido com foco na usabilidade, navegação intuitiva e design moderno adaptável a diferentes dispositivos (smartphones, tablets e computadores).

O site é composto por 3 páginas HTML interconectadas:
1. **Página Principal (`index.html`)**: Apresenta a marca, banner principal de destaque (Hero), atrativos da agência e principais destinos em alta.
2. **Conteúdo do Tema (`destinos.html`)**: Catálogo completo de pacotes de viagem com informações de preços, modal de solicitação de reserva e seção de dúvidas frequentes (FAQ).
3. **Conhecendo o Bootstrap (`bootstrap.html`)**: Página dedicada a explicar os conceitos fundamentais do framework Bootstrap 5, incluindo definição, utilidade, sistema de grid, responsividade e os componentes utilizados no projeto.

---

## 🎯 Tema Escolhido
**Turismo e Agência de Viagens**

---

## 🚀 Tecnologias Utilizadas
- **HTML5**: Estruturação semântica de todo o conteúdo.
- **CSS3**: Estilizações personalizadas e ajustes visuais.
- **Bootstrap 5.3**: Framework CSS para layout responsivo, sistema de grid e componentes.
- **Bootstrap Icons**: Biblioteca de ícones vetoriais.
- **Vercel**: Plataforma para hospedagem e deploy contínuo do site.

---

## 🔗 Link do Site Publicado no Vercel
👉 [Acessar Projeto no Vercel](https://viajamais-turismo.vercel.app) site-bootstrap-lilac.vercel.app

---

## 🛠️ Breve Explicação sobre o Desenvolvimento

O desenvolvimento do site foi estruturado com base nas boas práticas do **Bootstrap 5**, priorizando a utilização dos recursos nativos do framework em vez de estilos CSS customizados redundantes.

### Principais Destaques do Desenvolvimento:
1. **Padronização de Navegação e Rodapé**:
   - Todas as 3 páginas compartilham a mesma **Navbar** responsiva com menu colapsável (hambúrguer) para telas menores e links funcionais de navegação.
   - O **Footer** padronizado inclui as informações exigidas: nome do projeto, nome do aluno, ano e informações sobre a agência.

2. **Grid System e Responsividade**:
   - O layout foi construído com a estrutura `.container -> .row -> .col-*`.
   - A distribuição dos cards de destinos utiliza breakpoints responsivos:
     - **Celulares (`col-12`)**: 1 card por linha.
     - **Tablets (`col-md-6`)**: 2 cards por linha.
     - **Desktops (`col-lg-4`)**: 3 cards por linha.

3. **Componentes Bootstrap Utilizados**:
   - **Navbar**: Navegação superior fixa e expansível.
   - **Cards**: Exibição dos pacotes de viagem e caixas informativas.
   - **Buttons & Badges**: Identificação de promoções e botões de ação interativos.
   - **Alerts**: Mensagens promocionais e avisos com opção de fechar (`alert-dismissible`).
   - **Modal**: Formulário flutuante de reserva ativado pelos botões de pacote.
   - **Accordion**: Painel sanfonado para a seção de perguntas frequentes.

4. **Identidade Visual**:
   - Paleta de cores consistente baseada nas classes nativas do Bootstrap (`primary`, `warning`, `dark`, `light`).
   - Espaçamentos uniformes ajustados com as utilidades de margem e preenchimento (`mb-*`, `py-*`, `g-*`).
