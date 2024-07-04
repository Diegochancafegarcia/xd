// Paquete Controlador
package controlador;

import modelo.Autor;
import modelo.Publicacion;

public class ControladorAutor {

    public void agregarPublicacion(Publicacion publicacionNueva, Autor autor) {
        autor.agregarPublicacion(publicacionNueva);
    }

    public Autor crearAutor(String filiacion, String linealnvestigacion, String nacionalidad, String nombre) {
        return new Autor(filiacion, linealnvestigacion, nacionalidad, nombre, 10);
    }

    public Publicacion crearPublicacion(int año, String nombreRevista, String titulo) {
        return new Publicacion(año, nombreRevista, titulo);
    }

    public String imprimirAutor(Autor autor) {
        return autor.toString();
    }
}
