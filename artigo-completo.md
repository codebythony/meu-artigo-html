# Do <div> ao <article>: Escolhendo o Elemento HTML Correto para Cada Situação

Introdução: Para Além da "Div" Universal

Se você já se pegou envelopando tudo com <div> na esperança de que funcione, relaxa – todo mundo já passou por isso! A <div> é como uma caixa de mudanças genérica: útil, mas que não diz nada sobre o que tem dentro.

O HTML5 trouxe uma revolução silenciosa com elementos semânticos que dão significado à estrutura. Eles não são só nomes bonitos – são superpoderosos para organização, acessibilidade e SEO.

Vamos decifrar juntos essa evolução e aprender a escolher a tag certa na hora certa. Prometo que seu código vai agradecer!

O Que Muda da <div> para um Elemento Semântico?

Imagine que você está organizando sua cozinha. Usar só <div> seria como ter vários potes idênticos sem etiqueta – farinha, café e açúcar todos iguais. Funciona, mas dá trabalho para achar cada coisa.

Já os elementos semânticos são como potes transparentes com etiquetas: <article> para o pote de biscoitos, <nav> para o organizador de talheres. Sua vida (e a do navegador) fica muito mais fácil!

A mudança principal é significado: você comunica claramente qual é a função de cada pedaço do seu site.

O <section>: Agrupando Conteúdo Temático

Pense no <section> como um capítulo de livro. Ele agrupa conteúdos que têm um tema em comum, criando blocos lógicos dentro da sua página.

Por exemplo: uma seção "Sobre Nossa Empresa", outra com "Depoimentos de Clientes" e uma terceira com "Nossos Serviços". Cada uma vira uma <section>.

É importante que cada seção tenha seu próprio título (h1-h6). Se o conteúdo faz sentido sozinho, talvez seja um <article>. Se é só um agrupamento visual, provavelmente uma <div>.

O <article>: Conteúdo Auto-suficiente e Independente

O <article> é a estrela do conteúdo que faz sentido sozinho. Pense em um post de blog, uma notícia, um produto em um e-commerce ou um comentário.

A grande sacada: se você pegar aquele conteúdo e colocar em outro site, ele ainda deve fazer sentido completo. É independente como um sanduíche embalado!

Dica prática: se o conteúdo pode ser compartilhado via RSS ou lido isoladamente, provavelmente é um <article>. Dentro dele, você pode ter <section>s para organizar partes do conteúdo.

O <aside>: Conteúdo Complementar e Laterais

O <aside> é aquele amigo que comenta "por sinal..." numa conversa. Ele contém informações relacionadas ao conteúdo principal, mas não essenciais.

Pense em barras laterais com biografia do autor, links relacionados, glossários ou anúncios contextuais. É conteúdo complementar, não obrigatório.

Pode estar dentro de um <article> (complementando aquele conteúdo específico) ou fora (relacionado ao site todo). Só não o use como desculpa para enfiar qualquer coisa na lateral!

O <nav>: Definindo os Blocos de Navegação

O <nav> é bem direto ao ponto: ele envolve os principais blocos de navegação do seu site. É a tag para menus principais, menus de rodapé ou qualquer conjunto importante de links.

Mas calma! Não precisa colocar <nav> em cada grupo de links. Aquele monte de links de redes sociais no rodapé? Provavelmente não é um <nav>.

Reserve para as navegações principais mesmo. E pode ter mais de um por página – menu principal, menu secundário, etc.

O <header> e <footer>: Cabeçalho e Rodapé em Qualquer Contexto

Aqui tem um segredo: <header> e <footer> não são só para o topo e base da página! Eles podem ser usados em qualquer seção ou artigo.

O <header> é como a capa de um livro (ou capítulo): pode ter título, logo, menu. O <footer> é o rodapé: informações de contato, links secundários, copyright.

Podem existir dentro de um <article> (cabeçalho e rodapé do artigo) ou dentro de uma <section>. São super flexíveis!

O <main>: O Conteúdo Principal da Página

O <main> é o herói não reconhecido do HTML semântico. Ele envolve – adivinhe – o conteúdo principal da sua página. Aquele que é único e não se repete.

A grande vantagem? Leitores de tela podem pular direto para o conteúdo principal. É como um atalho mágico para acessibilidade!

Importante: use apenas um <main> por página, e não coloque dentro de <article>, <aside>, <footer>, <header> ou <nav>. Ele é o conteúdo "rei".

Comparação Rápida: Um Resumo Visual para Não se Perder

Vamos simplificar:

<div>: "Não sei qual tag usar" ou "É só para estilização"

<section>: "Este é um capítulo/categoria do conteúdo"

<article>: "Este conteúdo vive sozinho, como uma notícia"

<aside>: "Isto é relacionado, mas não essencial"

<nav>: "Estes são links importantes para navegar"

<header>/<footer>: "Isto é introdução/encerramento"

<main>: "Isto é o conteúdo principal da página"

Não fique neurótico! O importante é tentar acertar mais do que errar.

Conclusão: Próximos Passos na Jornada do HTML Semântico

Parabéns! Você deu o primeiro passo para sair do mundo das <div> sem rumo. Lembre-se: HTML semântico não é sobre perfeição, é sobre comunicação clara.

Cada tag certa ajuda usuários com deficiência, motores de busca e até você mesmo no futuro, quando for manter o código.

Continue praticando e prestando atenção na semântica. Logo vai vir naturalmente, como andar de bicicleta (mas com menos chances de cair)!

Gostou do conteúdo? 🚀

Se este artigo te ajudou a descomplicar o HTML semântico, que tal continuar essa conversa?

Instagram: @thony_alyson.exe	GitHub: codebythony

	Ilustrações de capa: gerada pela lexica.art
	Conteúdo gerao por: DeepSek e revisões humanas
