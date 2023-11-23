Indicación: Definicion y ejemplo de las nuevas etiquetas HTML5


### USO DE HEADER Y FOOTER

    Estas divisiones sirven para dejar claro el nombre de las divisiones o secciones, estableciendo asi el orden
    <header></header>
    <footer></footer>

    Ejemplo

    <header>
    <h1>OTROS ELEMENTOS DE HTML</h1>
    </header>

    <footer>
        <h2>Derechos Reservados</h2>
    </footer>

### NAV

    Esta etiqueta se utiliza para especificar donde iran los enlacen o menus en la pagina, ya que estos se vincularan como hipervinculo a otras secciones es buena practica especificar su espacio

    Ejemplo
        <nav>
        <ul>
            <li><a href="#">HEADER Y FOOTER</a></li>
            <li><a href="#">NAV</a></li>
            <li><a href="#">MAIN</a></li>
            <li><a href="#">SECTION</a></li>
            <li><a href="#">ARTICLE</a></li>

        </ul>
    </nav>

## SECTION
    Las secciones se utilizan para delimitar más la pagina, si esta se presta a tener varias secciones que necesitan esto

        <section>
        <header>
            <h3>Header y Footer</h3>
            
        </header>
        <p>Estas divisiones sirven para dejar claro el nombre de las divisiones o secciones, estableciendo asi el orden</p>
    </section>
    <section>
        <header>
        <h3>NAV</h3>
        </header>
        <p>
            Esta etiqueta se utiliza para especificar donde iran los enlacen o menus en la pagina, ya que estos se vincularan como hipervinculo a otras secciones es buena practica especificar su espacio 
        </p>
    </section>

## ARTICLE

    Contenido independiente, pero completo
    Se puede colocar dentro de una seccion
    "An article should make sense on its own and it should be possible to distribute it independently from the rest of the site."

    Se puede utilizar para

    - Forum post
    - Blog post
    - News story
