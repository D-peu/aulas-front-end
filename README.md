# aulas-front-end

## HTML

Linguangem para estruturação de cpnteúdo em páginas web.

## CSS 

Linguangem para estilização de páginas web.

CSS é uma sigla que significa "Folhas de EStilo em Cascata", e possui 3 formas de implementação.

### Inline

O CSS é aplicado diretamente em cada tag HTML.

### Interna ou OnPage (na página)

O CSS é criado usando regras (com seletores, propriedades e valores) dentro da pópria página que queremos formatar.

As regras vão valer para todas as tags/elementos desta página.

### Externa 

Arquivo CSS dedicado a elaboração de regras CSS.

Este arquivo será "conectado" a cada página HTML do seu site, permitindo assim centralizar toda a estilização de um projeto.

---

### Sobre seletores 

#### Tag

Regras criadas com seletor do tipo tag, são mais generalistas, ou seja, a formatação será aplicadas à todas as tags que "casem" com o seletor.

#### Classes

Regras criadas com seletor do tipo classe, são mais versáteis, ou seja, você desenvolvedor determina onde aplicar a classe e sua formatação.

Classes podem ser reutilizadas na mesma página e combinadas com outras classes.

### ID (identificador)

Regras criadas com seletor do tipo id, são mais versáteis, ou seja, você desenvolvedor determina onde aplicar o id e sua formatação. **ATENÇÂO** você não pode reaproveitar IDs, ou seja, seletor ID deve ser usado SOMENTE PARA UM ELEMENTO por página.

### Grupo de Seletores

Regra composta por outros seletores, útil quando objetivo é aplicar uma mesma formatação em diversos elementos diferentes.

### Descendente 

Regra para formatação de elementos que estão dentro de outros elementos, permitindo assim um grau maior de precisão ou especificidade.