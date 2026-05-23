# Sobre
Site feito em html e css para o projeto final da disciplina de HTML/CSS da Pós-Graduação em Desenvolvimento Web usando IA, na UTFPR.

É uma _Landing Page_ para a banda de _hardcore punk_ TAG29. Apresenta os membros, próximos shows e singles já produzidos pela banda, além de uma pequena bio de introdução.

# Competências do trabalho:

1. Estrutura Semântica Rigorosa: Construir o layout completo utilizando apenas tags semânticas (Módulo 01), garantindo que a estrutura seja compreensível para motores de busca e leitores de tela.

Primeiro fiz um esboço para determinar quais seriam as tags necessárias, depois carreguei um projeto já feito durante os módulos da disciplina que coíncidia com as exigências do projeto e alterei o que era necessário.
TODO: colocar o esboço aqui.

2. Sistema de Design com Variáveis: Implementar um esquema de cores e tipografia centralizado em variáveis CSS, permitindo a troca de identidade visual do seu tema de forma global e organizada (Módulo 02).

Criei variáveis para os elementos visuais que são alterados com o uso do Dark Mode; vide: TODO: colocar todas as variáveis porque não lembro de cabeça.

3. Layout Híbrido (Flex & Grid): Criar seções que combinem o alinhamento do Flexbox (menus/botões) com a robustez do CSS Grid para o posicionamento da grade principal de conteúdo (Módulo 03).

Foi usado flex para fazer o header e os posteres dos shows. GRID foi usado para apresentar os cards dos membros e dos cards dos singles.

4. Interface Responsiva: Garantir que o projeto seja adequado para telas pequenas (mobile) e escale com fluidez até resoluções desktop, sem quebras visuais (Módulo 04).

Algumas coisas do corpo do site mudam de tamanho quando chegam a um determinado tamanho para poder aproveitar o espaço melhor. O Header muda para um hamburg em dispositivos móveis. Cards diminuem de tamanho para evitar de apresentar elementos ímpares em grids, e também os posteres ajustam de tamanho em relação ao tamanho horizontal da tela para ser sempre visível em qualquer dispositivo.

5. Microinterações de Feedback: Desenvolver animações de entrada e estados de hover que deem vida à interface e melhorem a experiência do usuário (Módulo 05).

Ao entrar no site há uma animação do banner flutuando para baixo até a posição final. Os posteres quando clicados mostram a imagme inteira com animações de entrada e saída. Os cards de single são "_flippable cards_", ao passar o mouse por cima o card vira para mostrar a parte traseira com o link da música. Os cards dos membros respondem com o passar do mouse como se fossem "pressionadas." 

6. Curadoria de Código com IA: Utilizar IA para gerar e refatorar um componente específico da sua página, documentando como você validou e ajustou o código gerado para o seu projeto (Módulo 06).

Enviei o código para o DEEPSEEK (provavelmente, ainda n fiz isso) para criar variáveis que não identifiquei a repetição originalmente. Usei para conferir se a estrutura está rigorosa e arrumar a animação travada de quando os posteres são clicados.

7. Implementação de Dark Mode Nativo (Pesquisa): Pesquisar e aplicar a media query prefers-color-scheme para que o seu site se adapte automaticamente às preferências de tema do sistema do usuário.

Foi aplicado o uso de Dark Mode Nativo, onde certos elementos se alteram conforme o tema do dispositivo.

8. Sticky Headers e Scroll Snap (Pesquisa): Pesquisar propriedades de scroll do CSS para criar um cabeçalho fixo e seções que se ajustam suavemente à tela durante a navegação.

Foi utilizado Sticky Headers e Scroll Snap.

9. Otimização de Performance e Assets (Pesquisa): Pesquisar sobre formatos de imagem modernos (como WebP) e carregamento de fontes para garantir que sua landing page abra instantaneamente. Tente atingir uma pontuação de performance próxima de 100 no Google PageSpeed.

Foi convertido todos os assets para WEBP e usado fontes do Google Fonts.

10. Acessibilidade Avançada com Teclado (Pesquisa): Pesquisar e implementar o gerenciamento de foco visual (:focus-visible) e atributos ARIA básicos para garantir que qualquer pessoa consiga navegar no seu projeto sem usar o mouse.

A tag <a></a> naturalmente implementa isso devidamente, porém foi necessário fazer certas alterações. Nos posteres foram necessários alteração de estilo para ficarem destacados com :focus-visible. Os cards de singles foram necesários alterar para realizar a animação do card "flippando" quando :focus-visible.
