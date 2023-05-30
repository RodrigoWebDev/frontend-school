# Aprenda Desenvolvimento Web Front end

## Antes de começar

Esse documento assume que você esta no Windows, caso uma das ferramentas não exista no seu sitema operacional basta procurar no google uma alternativa que funcione.\
Outro ponto importante é que se você realmente esta comprometido com o aprendizado, eu recomendo que se siga as seguintes regras:

- Não pule etapas
- Estude se possível de segunda a sexta por no mínimo 30 minutos, mais importante do que estudar muitas horas é estudar todos os dias, nem que seja um pouco. Estudar por várias horas nem sempre significa que você conseguiu absorver todas essas horas de estudo
- Tente fazer os desafios sem olhar as soluções deixadas no documento, caso você REALMENTE esteja travado em algum ponto, esta liberado olhar a solução APENAS para aquele ponto onde você travou. Isso vai estimular seu raciocínio lógico e solução de problemas
- Só passe para os póximo módulos caso se sinta confortável com os modulo atual. Uma regra que eu uso pra mim é: Se eu estou conseguindo fazer o desafio sem precisar ver a solução, significa que eu dominei o tópico e posso seguir para o próximo
- Após conseguir concluir o desafio, dê uma olhada na solução que eu deixei, isso é bom porque as vezes a sua forma de resolver foi diferente da minha, e tudo bem, o mais importante nesse momento é resolver o desafio
- Anote coisas como trechos de código, estilos, ou links que você perceber que esta usando com frequência e esquecendo. Você pode usar qualquer aplicativo de notas, mas recomendo um que você consiga salvar online, assim não tem a chance de você perder suas anotações
- Caso você termine os módulos desse documento não pare por ai, continue pesquisando e estudando, procure novos desafios, tente replicar sistemas, participar de projetos de código aberto e até procurar um trabalho, como programador você nunca deve parar de apreder

### Requisitos técnicos

Você só vai precisar de conhecimentos basicos em operar seu sistema operacional em geral. Exemplo: 

- Instalar e desinstalar softwares
- Gerenciar arquivos e pastas
- Navegar na internet

### Ferramentas e Softwares

- Um computador, apesar de ser possível programar pelo celular não é algo recomendado ja que não é um ambiente produtivo. Não precisa ser um computador top de linha, apenas um que não trave excessivamente
- [Navegador](https://www.google.com/intl/pt-BR/chrome/): auto explicativo
- [Editor de código](https://code.visualstudio.com/): vai servir para você criar arquivos de código, e tem algumas funcionalidades uteis como deixar o texto do código colorido, trabalhar com multiplos arquivos e etc

### Configuração do editor

Antes de começar a usar o VSCode, eu sugiro que você remova a funcionalidade de auto completar código porque isso pode atrapalhar seu progresso. Você precisa lembrar dos códigos e não depender dessa fucnionalidade. Ela pode ser muito útil quando você esta trabalhando e tem prazos, mas para estudo eu não recomendo. Para remover siga os passos a seguir

- Vá em `File > Preferences > Settings`, [Ver imagem](https://github.com/RodrigoWebDev/frontend-school/assets/30677819/6f24dfb5-6554-4b44-b799-049078444e11)
- No input de busca digite `acceptSuggestionOnCommitCharacter`
- Desmarque a opção que aparecer, [Ver imagem](https://github.com/RodrigoWebDev/frontend-school/assets/30677819/824e2aae-8f80-457f-8f19-48d28c1312bb)

Caso não esteja usando o Vscode recomendado nesse documento, não tem problema, só veja se seu editor tem essa funcionalidade ou qualquer outra que você identificar que pode atrapalhar seu aprendizado procure tutoriais de como desativa-las  temporariamente

## Modulo 1 - O Basico

Nesse módulo você vai aprender construindo um site o básico de HTML, CSS e Javascript que são as 3 pilares do desenvolvimento web front end

### Estudo

- [Iniciando no desenvolvimento web](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web/Installing_basic_software)
- [DevTools: A Ferramenta Secreta que todo Front-end deveria conhecer](https://www.youtube.com/watch?v=4TvNPKO0l-k)

### Desafio

Usando o que você aprendeu, crie o seu portfolio Front end. O Portfolio é um site onde você mostra os projetos que você ja desenvolveu e que comprova sua experiência.\
Provavelmente você não tem nenhum projeto para mostrar(vamos chegar la!), então nesse primeiro momento coloque informações sobre você, como contato, redes sociais, foto etc. Será um ótimo recurso a ser usado em uma entrevista por exemplo. Esse desafio não terá um link para você consultar a solução, mas segue um link para você se inspirar: https://www.w3schools.com/w3css/tryw3css_templates_parallax.htm

## Modulo 2 - Git

Nesse módulo você vai aprender a fazer o controle de versão do seu código com o GIT e hospeda-lo online no github. A partir de agora você deve usar o GIT e o GITHUB para todos os novos projetos que você fizer, isso vai servir para montar seu portfolio. O portfolio é essencila para você conseguir seu primeiro trabalho

### Estudo

- [Tutorial completo de GIt e Github](https://www.youtube.com/watch?v=kB5e-gTAl_s)
- [git - guia prático](https://rogerdudler.github.io/git-guide/index.pt_BR.html)(OPCIONAL)

### Desafio

Apesar do tutorial ja dar alguns desafios, eu gostaria de complementar com um novo desafio que é subir o site que você fez no módulo anterior no github

## Modulo 3 - CSS Layout com Flexbox

Nesse modulo você vai aprender recursos mais avançados do CSS como flexbox para criar estruturas de layout

### Estudo

- [Conceitos basicos de Flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- [Referência](https://origamid.com/projetos/flexbox-guia-completo/)(OPCIONAL)

### Desafio

Usando o GIT para fazer o controle de versão você vai replicar [ESSA PAGINA](https://codepen.io/RodrigoWebDev/full/wvmVxmZ) usando Flexbox e os outros conceitos de CSS que você ja aprendeu. Use as mesmas imagens da pagina

[Solução do desafio](https://codepen.io/RodrigoWebDev/pen/wvmVxmZ?editors=0100)

## Modulo 4 - Contador com Javascript

No módulo 1 você teve um breve contato com o Javascript, aqui você vai praticar um pouco mais

### Estudo

- [functions](https://www.w3schools.com/js/js_functions.asp)
- [querySelector](https://www.w3schools.com/jsref/met_document_queryselector.asp)
- [innerText](https://www.w3schools.com/jsref/prop_node_innertext.asp)
- [operadores](https://www.w3schools.com/js/js_operators.asp)

### Desafio

Usando os conecitos que estudou, crie um contador similar a [esse:](https://codepen.io/RodrigoWebDev/full/NWYggeG). Tente também replicar os estilos usando CSS

[Solução do desafio](https://codepen.io/RodrigoWebDev/pen/NWYggeG)

## Modulo 5 - Menu de navegação responsivo

Nesse módulo você vai aprender o que é responsividade e como fazer usando CSS, também vai aplicar um pouco de Javascript

### Estudo

- [O que é design responsivo](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [Manipulação de classes dos elementos HTML com JS](https://www.w3schools.com/jsref/prop_element_classlist.asp)

### Desafio

Desenvolver um menu de navegação responsivo similar a [esse](https://codepen.io/RodrigoWebDev/full/RwKBJyW). Tente redimensionar a janela do navegador e vai ver que o elemento tem um comportamento diferente para tamanhos maiores e menores de tela

[Solução do desafio](https://codepen.io/RodrigoWebDev/pen/RwKBJyW?editors=0010)

## Módulo 6 - Site responsivo

Nesse módulo você vai juntar quase tudo o que você aprendeu nos módulos anteriores: HTML, CSS e GIT para criar um site a partir de um desenho(Design). Uma parte do trabalho do desenvolvedor Front End é colocar em formato de código um site que um Designer de UX/UI desenhou e é isso que você vai praticar nesse módulo, segue o passo a passo para começar

Obs: Eu recomendo você repetir esse exercício até se sentir confortável em replicar websites com código. Não precisa ser o mesmo design, você pode usar qualquer outro que encontrar

- Criar uma conta no Figma
- Abrir [esse link](https://www.figma.com/file/5kvVZQrSXWO8SB4LPBakfr/homepage-(Community)?type=design&node-id=0-405&t=RJLoV2BBuC2XbRPH-0) contendo o design do site. Caso esse link eteja fora do ar, sinta-se livre para escolher um novo design [nesse link](https://www.uxcrush.com/figma-website-templates/). Você também pode procurar mais no google
- Se o design que você escolheu tiver mais de uma tela não precisa desenvolver todas, escolha uma e siga em frente. Depois você pode usar as outras telas para praticar mais
- Procure ser perfeccionista, prestando atenção em cada detalhe. Procure deixar o visual o mais próximo possível. Imagine que você esta recebendo dinheiro para fazer isso, e que seu cliente vai querer o site igual ao que esta no Design, nada mais, nada menos
- Dentro do Figma você consegue insepcionar os elementos, assim você consegue informações do tipo da fonte, tamanho, espaçamentos, cores e etc
- Links e botões não precisam ter ação ou redirecionamento
