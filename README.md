# Clean Architecture

Exemplo: https://github.com/nglauber/books_jetpack

Resume-se em 3 camadas:<br>
### Data
Onde ficam as informações da aplicação (remote config, redes, database, etc).<br>

### Domain
Regra de negócio. Onde ocorre a lógica. Não trabalhamos com elementos de tela. Ela permite o plug-desplug de interfaces sem prejudicar a aplicação.<br>

### Presenter
Onde fica a UI. Se usarmos MVVM + Clean Architecture, a camada presenter seria a View + Viewmodel da MVVM.<br>
<br>
<br>
Juntando as camadas de MVVM com a Clean, temos: {View + Viewmodel}(presenter) + (domain) + (data)<br>
