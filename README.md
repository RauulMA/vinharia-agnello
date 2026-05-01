Projeto Vinharia Agnello
Este repositório contém a solução inicial para o portal de e-commerce da Vinharia Agnello, desenvolvida como parte das atividades do curso de Engenharia de Software. O projeto visa transpor a experiência de uma loja física tradicional para o ambiente digital, respeitando a história e o modelo de atendimento personalizado da empresa.

Contexto do Projeto
A Vinharia Agnello é uma empresa familiar de São Paulo com 15 anos de atuação. Conhecida pela consultoria especializada oferecida por seus vendedores, a empresa enfrentou a necessidade de digitalização devido às restrições de mobilidade urbana e à mudança no comportamento dos consumidores.

O desafio central deste projeto é mitigar a "frieza" comum ao e-commerce, entregando uma interface que auxilie o usuário — muitas vezes iniciante no mundo dos vinhos — na escolha do rótulo ideal, simulando o suporte técnico recebido presencialmente.

Objetivos da Solução
Preservação da Identidade: Criar uma interface que reflita o padrão de atendimento conservador e atencioso da loja física.

Auxílio na Tomada de Decisão: Facilitar a navegação para clientes que possuem pouco conhecimento técnico sobre variedades de uvas, safras e harmonizações.

Escalabilidade: Estruturar o código de forma que possa ser integrado futuramente ao ERP já utilizado pela empresa para gestão de estoque e vendas.

Estrutura do Repositório
O projeto foi dividido nas seguintes seções:

index.html: Página principal com destaques e introdução à marca.

src/pages/: Contém as páginas secundárias como Catálogo de Produtos, Nossa História, Quem Somos e Canais de Contato.

src/css/: Arquivo de estilo unificado que garante a identidade visual em todas as telas.

src/assets/: Repositório de imagens e recursos visuais utilizados.

Metodologia Aplicada
Seguindo as premissas de Engenharia de Software para cenários de alta incerteza, o desenvolvimento foi guiado por:

Foco na Experiência do Usuário (UX): Priorizando a facilidade de encontrar informações sobre harmonização e tipos de vinho.

Desenvolvimento Ágil: Atuando com a figura do Product Owner (representado pela personagem Bianca no estudo de caso) para definição de requisitos e validação de entregas.

Clean Code: Organização de código HTML e CSS focada na manutenibilidade por outros membros do squad.

Tecnologias Utilizadas
HTML5 (Estruturação semântica)

CSS3 (Layout responsivo com Flexbox e Grid)

Git (Controle de versão e resolução de conflitos de merge)

Links dos conteúdos externos:

Vídeo do index: https://www.youtube.com/embed/Ac559iPwbEs

Pisa da Uva: https://maps.app.goo.gl/i47RuAQrPaYnVxhr7

-------------------------------------------------------------------------------------------------------

Efeitos Visuais
Para garantir uma experiência de usuário premium e interativa, condizente com a sofisticação da Vinharia Agnello, foram aplicados recursos avançados de CSS3. Abaixo, detalhamos as implementações:

Pseudo-classes
As pseudo-classes foram utilizadas para fornecer feedback visual imediato às ações do usuário:

:hover: Aplicada aos links de navegação e cards de produtos. Nos links, altera a cor e adiciona um brilho suave (text-shadow); nos cards, ativa transformações de movimento.

:first-child: Utilizada no menu de navegação para destacar visualmente o primeiro item, ajudando na orientação do usuário.

:focus-within: Aplicada ao formulário de contato. Quando qualquer campo (input/textarea) é selecionado, o container pai recebe um destaque com borda dourada e uma leve escala, sinalizando a área ativa de interação.

Pseudo-elementos
Utilizados para adicionar elementos decorativos sem poluir a estrutura do HTML:

::after (Cabeçalho): Cria uma linha decorativa animada sob o título principal. A linha expande de 0 a 100% da largura quando o usuário passa o mouse.

::before (Seção Missão): Insere um ícone temático (🍷) antes do título da seção via CSS.

Animações e Transformações
A interface utiliza movimentos fluidos para guiar o olhar do consumidor:

@keyframes aparecerSuave: Uma animação de entrada que faz com que as seções da página surjam gradualmente (fade-in) enquanto se movem levemente para cima (translateY), eliminando o impacto visual de um carregamento estático.

Transformações (transform):

scale(1.02): Aumenta levemente o tamanho dos cards ao passar o mouse, simulando profundidade.

translateY(-10px): Eleva os produtos no eixo vertical durante o hover, criando um efeito de destaque (levitação).

transition: Todas as mudanças de estado possuem transições suaves (0.3s a 0.4s) para evitar saltos bruscos de imagem.

-------------------------------------------------------------------------------------------------------

Desenvolvido por:

Lucas Rodrigues dos santos - RM571778

Raul Moreira Andrade - RM571042

Guilherme Henrique Reis Gimenez - RM563389

Rafael de Souza - RM568777