// Paquete Modelo
package modelo;

public class Publicacion {
    private int año;
    private String nombreRevista;
    private String titulo;

    public Publicacion(int año, String nombreRevista, String titulo) {
        this.año = año;
        this.nombreRevista = nombreRevista;
        this.titulo = titulo;
    }

    public int getAño() {
        return año;
    }

    public String getNombreRevista() {
        return nombreRevista;
    }

    public String getTitulo() {
        return titulo;
    }

    @Override
    public String toString() {
        return "Publicacion{" +
               "año=" + año +
               ", nombreRevista='" + nombreRevista + '\'' +
               ", titulo='" + titulo + '\'' +
               '}';
    }
}
