# Atividade WAI-ARIA
### Feito por: [Nathan](https://GitHub.com/Nathan-Luiz) e [Paulo](https://github.com/PauloC-09)

#

## Questão 1 – Conceito
* a) O que é o WAI-ARIA e qual é sua principal finalidade?
* O WAI-ARIA (Web Accessibility Initiative – Accessible Rich Internet Applications) é um conjunto de atributos que melhora a acessibilidade de páginas e aplicações web. Sua principal finalidade é fornecer informações adicionais para tecnologias assistivas, como leitores de tela, permitindo que usuários compreendam e utilizem corretamente os elementos da interface. Os principais beneficiados são pessoas com deficiência visual, mas o WAI-ARIA também pode auxiliar usuários com outras deficiências, como limitações motoras e cognitivas, tornando a navegação mais acessível.

#

## Questão 2 – Análise de Código
* a) Qual é a função do atributo aria-controls?
* O atributo aria-controls informa qual elemento da página é controlado pelo botão. Nesse exemplo, ele indica que o botão controla o elemento com o identificador "menuPrincipal".
* b) O que informa o atributo aria-expanded?
* O atributo aria-expanded informa se o elemento controlado está expandido ou recolhido. No exemplo, o valor false indica que o menu está fechado.
* c) Qual é a importância do atributo aria-label para usuários que utilizam leitores de tela?
* O atributo aria-label fornece uma descrição clara da função do botão para leitores de tela. Assim, o usuário escuta "Abrir menu", entendendo a finalidade do botão mesmo que o texto visível não seja suficiente.

#

## Questão 3 – Reflexão
* a) O WAI-ARIA não substitui o HTML semântico porque os elementos semânticos, como <button>, <nav> e <main>, já possuem significado e acessibilidade nativos. Sempre que possível, eles devem ser utilizados, pois oferecem melhor compatibilidade com navegadores e tecnologias assistivas.
* O WAI-ARIA deve ser usado apenas quando o HTML semântico não é suficiente. Um exemplo é um menu expansível criado com JavaScript. Nesse caso, atributos como aria-expanded e aria-controls informam aos leitores de tela se o menu está aberto ou fechado e qual conteúdo está sendo controlado, tornando a interface mais acessível para todos os usuários.
