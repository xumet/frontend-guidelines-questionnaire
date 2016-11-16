# Cuestionario de Directrices de Maquetación
Un cuestionario rápido para ayudar a tu equipo a establecer unas pautas eficaces, de manera que podáis escribir un código consistente y cohesionado juntos.

## HTML
### Principios HTML
- **¿Cuáles son los principios generales que tu equipo debe seguir al escribir HTML?** *(por ejemplo, marcado semántico HTML5, accesibilidad, etc. Mira [estos](http://www.yellowshoe.com.au/standards/#html) [recursos](http://codeguide.co/#html) para [inspirarte](http://manuals.gravitydept.com/code/html))*

### Herramientas HTML
- **¿Utilizáis un preprocesador HTML** *(como [HAML](http://haml.info/), [Jade](http://jade-lang.com/), etc)*?
- **¿Utilizáis un sistema de plantillas** *(como [Mustache](https://mustache.github.io/), [Handlebars](http://handlebarsjs.com/), etc)*?
- **¿La arquitectura del backend influye en la maquetación del frontend de alguna manera** (por ejemplo, WordPress agregará `wp-paginate` a una clase en tu maquetación)? Si es así, ¿puedes destacar estas convenciones?

### Estilo HTML
- **¿Espacios o Tabuladores?**
- **¿Qué apariencia tienen los comentarios HTML?** 

---------------

## CSS 

### Principios CSS
- **¿Cuáles son algunos de los principios generales que debe seguir tu equipo al escribir las CSS?** *(Por ejemplo, modularidad, evitar nombres largos para selectores, etc. Mira [estos](http://cssguidelin.es/) [recursos](http://www.yellowshoe.com.au/standards/#css) [para](http://manuals.gravitydept.com/code/css) [inspirarte](http://codeguide.co/#css))*

### Metodología CSS
- **¿Usa tu equipo una metodología CSS** *(como [SMACSS](https://smacss.com/), [BEM](https://en.bem.info/method/), u [OOCSS](http://oocss.org/))*? En caso afirmativo, ¿dónde está la documentación para esa metodología?
- **¿Os desviáis de esa metodología de alguna manera?** Si es así, ¿puedes destacar estas convenciones?

### Herramientas CSS
- **¿Usa tu equipo un preprocesador** *(como [Sass](http://sass-lang.com/) o [Less](http://lesscss.org/))*?
- **¿Cuáles son las directrices para usar ese preprocesador** *(echa un vistazo a [Sass Guidelines](https://sass-guidelin.es/) para inspirarte)*?
- **¿Usáis una base CSS** *(como [Normalize](https://necolas.github.io/normalize.css/) o un [reset](http://meyerweb.com/eric/tools/css/reset/))*?
- **¿Usáis algún postprocesador CSS** *(como [Prefixfree](https://leaverou.github.io/prefixfree/) o [Autoprefixer](https://github.com/postcss/autoprefixer))*?
- **¿Utilizáis alguna técnica específica para las CSS** *(como [critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/))*?

### Frameworks CSS
- **¿Está el equipo usando un framework** *(como [Bootstrap](https://getbootstrap.com/) o [Foundation](http://foundation.zurb.com/))*? En caso afirmativo, ¿dónde está la documentación de ese framework?
- **¿Os desviáis del framework de alguna forma?** Si es así, ¿podéis destacar estas convenciones?

### Estilo CSS
- **¿Espacios o Tabuladores?**
- **¿Espaciando alrededor de reglas?**
- **¿Propiedades de [Agrupación](https://smacss.com/book/formatting#grouping)?**
- **¿Qué apariencia tienen los comentarios CSS?** 

---------------

## JavaScript

### Principios JavaScript
- **¿Cuáles son algunos de los principios generales que debe seguir tu equipo al escribir JavaScript?** *(Mira [estos](https://github.com/airbnb/javascript) [recursos](https://github.com/rwaldron/idiomatic.js) para [inspirarte](https://github.com/styleguide/javascript))*


### Herramientas JavaScript
- **¿Usáis algún framework JavaScript** *(como [jQuery](https://jquery.com/), [Ember](http://emberjs.com/), [Angular](https://angularjs.org/), etc)*?
- **¿Dónde está la documentación para esos frameworks?**
- **¿Usáis algún tipo de polyfills o shims** *(como [cualquiera de estos](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills))*?
- **¿De qué código de terceros depende el proyecto** *(como scripts para validar formularios, gráficos, animaciones, etc)*?
- **¿Testeáis vuestro JavaScript?** Si es así, ¿qué herramientas usáis *(como [Jasmine](https://jasmine.github.io/), [Karma](https://github.com/karma-runner/karma), [Selenium](http://docs.seleniumhq.org/), etc)*?

### Estilo JavaScript
*(Mira [estos](https://github.com/airbnb/javascript) [recursos](https://github.com/rwaldron/idiomatic.js) para [inspirarte](https://github.com/styleguide/javascript))*
- **Espacios o Tabuladores?**
- **¿Qué apariencia tienen los comentarios JS?** 
- **¿Qué patrones seguís?** *(Mira [estos](https://addyosmani.com/resources/essentialjsdesignpatterns/book/) [recursos](https://shichuan.github.io/javascript-patterns/))*

---------------

## Media
- **¿Cómo tratáis los iconos** *(tal como usando SVG, fuentes de iconos, etc)*?
- **¿Cómo tratáis las imágenes responsivas** *(tal como usando `srcset` y `<picture />`)*?
- **¿Usáis alguna [herramienta](https://addyosmani.com/blog/image-optimization-tools/) para optimizar y servir las imágenes**?

---------------

## Fuentes
- **¿Cómo cargáis las fuentes personalizadas?**
- **¿Utilizáis alguna herramienta para ayudar a implementar las web fonts** *(como [Font Squirrel](https://www.fontsquirrel.com/), etc)*?
- **¿Utilizáis algun servicio para gestionar y servir las fuentes personalizadas** *(como [Fonts.com](https://www.fonts.com/), [Typekit](https://typekit.com/), etc)*?


---------------

## Rendimiento
- **¿Usáis estimaciones de rendimiento?** Si es así, qué [métricas](https://timkadlec.com/2014/11/performance-budget-metrics/) estáis usando para determinar las estimaciones? ¿Dónde estáis haciendo el seguimiento de las estimaciones de rendimiento?
- **¿Cómo medís la velocidad de vuestro proyecto** *(como [Pingdom Speed Test](http://tools.pingdom.com/) o [Google PageSpeed](https://developers.google.com/speed/pagespeed/))*?
- **¿Qué técnicas usáis para reducir el tamaño de los archivos** *(como [Gzip](https://css-tricks.com/snippets/htaccess/active-gzip-compression/), [Image Optimization](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization))*?
- **¿Qué herramientas relacionadas con el rendimiento estáis usando en vuestro proceso de trabajo?** *(como [WebPagetest](http://www.webpagetest.org/), [BigRig](https://aerotwist.com/blog/bigrig/) [Speedcurve](https://speedcurve.com/))*?


---------------

## Accesibilidad
- **¿Seguís las recomendaciones de accesibilidad establecidas en [esta lista](http://a11yproject.com/checklist.html)?**
- **¿Qué [herramientas](http://a11yproject.com/resources.html) relacionadas con la accesibilidad usáis en vuestro proceso de trabajo??**

---------------

## Herramientas
- **¿Usáis algún automatizador de tareas** *(como [Grunt](http://gruntjs.com/) o [Gulp](http://gulpjs.com/))*?
- **¿Usáis algún gestor de dependencias** *(como [Bower](http://bower.io/) o [Composer](https://getcomposer.org/))*?
- **¿Usáis alguna herramienta de scaffolding** *(como [Yeoman](http://yeoman.io/))*?
- **¿Usáis alguna herramienta para reforzar el estilo de la maquetación** *(como [Editor Config](http://editorconfig.org/) o [linters](https://github.com/CSSLint/csslint))*?
- **¿Hay algún otro programa que sea necesario para trabajar en este proyecto?**

---------------

## Control de Versiones
- **¿Qué sistema de control de versiones usáis para vuestro código frontend** *(como [Git](https://git-scm.com/) o [Subversion](https://subversion.apache.org/))*?
- **¿Dónde está alojado vuestro código versionado** *(como [Github](https://github.com/) o [Bitbucket](https://bitbucket.org/))*?
- **¿Usáis algún gestor de ramas y flujos de trabajo** *(como [gitflow](http://nvie.com/posts/a-successful-git-branching-model/), [centralized](https://www.atlassian.com/git/tutorials/comparing-workflows/centralized-workflow), [feature-branch](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow), etc)*?
- **¿Quién es el responsable de administrar el repositorio de código?**?
- **¿Dónde se hace el seguimiento de los problemas?**

-----------

## Soportar y Optimizar
Es importante identificar la diferencia entre ["soportar" y "optimizar"](http://bradfrost.com/blog/mobile/support-vs-optimization/). Hay que hacer todo lo posible para soportar tantos entornos como sea posible mientras simultáneamente se optimizan los entornos que tienen más sentido para la empresa y los usuarios.

- **¿Para qué navegadores se *optimiza*?**
- **¿Para qué dispositivos se *optimiza*?** 
- **¿Estáis usando algún sistema de [soporte de navegador graduado](https://github.com/yui/yui3/wiki/Graded-Browser-Support)?**
- **¿Existen componentes específicos que requieran un [grado más específico](https://www.filamentgroup.com/lab/grade-the-components.html)?** 

-----------

## Localización
- **¿Se muestra vuestro sitio web en diferentes idiomas?** Si es así, ¿qué consideraciones necesitáis tener en cuenta cuando localizáis para otros idiomas?

-----------

## Despliegue/Integración
- **¿Cómo se integra la maquetación dentro del entorno de producción?**

-----------

## Documentación
- **¿Estáis utilizando alguna [herramienta de biblioteca de patrones](http://styleguides.io/tools.html) para documentar vuestra arquitectura de maquetación?**
- **¿Dónde reside vuestra documentación?** ¿Cuáles son los enlaces hacia la documentación?
- **¿Quién es el responsable de mantener y administrar la documentación?**
- **¿Qué pasa cuando las directrices se actualizan?**

-----------

*Puedes modificar o extender libremente este documento (tal como añadir secciones específicas sobre rendimiento, accesibilidad, etc) según las necesidades de tu organización. Para preguntas, comentarios, adiciones, y correcciones, por favor abrir una incidencia en Github y/o contacta con [@brad_frost](https://twitter.com/brad_frost) en Twitter.*
*Igualmente, en lo referente a esta traducción podéis contactar con [@xumet](https://twitter.com/xumet) en Twitter.*
