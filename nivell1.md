# Java (llenguatge de programació)
El **Java** és un [llenguatge de programació](https://ca.wikipedia.org/wiki/Llenguatge_de_programaci%C3%B) dissenyat el 1990 per _James Gosling amb_ altres companys de [_Sun Microsystems_](https://ca.wikipedia.org/wiki/Sun_Microsystems) a partir del [llenguatge C](https://ca.wikipedia.org/wiki/Llenguatge_C).
## Index 
* Característiques de Java
  * Tipus de Dades
  * Tipus de dada primitius o variables primitives
    * BOOLEÀ (boolean)
    * CARÀCTER (char)
    * NUMÈRICS ENTERS (byte, short, int, long) i NUMERICS REALS (fload, double)
  * Altres Característiques

## Característiques de Java
* **Senzill:** Java s'ha creat perquè sigui un llenguatge senzill amb una sintaxi elegant. Únicament consta de tres tipus de dades primàries, eliminant els punters i l'herència múltiple
* **Orientat a objectes:** Java segueix els paradigmes de la programació orientada a objectes, ja que la programació amb Java se centralitza en la manipulació, creació i construcció d'objectes.
* **Distribuït:** Java permet la construcció d'aplicacions distribuïdes per mitjà d'una col·lecció específica de classes.
* **Interpretat:** Es necessita un intèrpret per executar els programes de Java, això alenteix als programes però els hi dona flexibilitat.
* **Robust:** Java és un llenguatge robust i fiable, s'ha escrit pensant a poder verificar errors i està molt tipificat.
* **Segur:** Java té pocs problemes de seguretat, característica molt important en les aplicacions distribuïdes d'Internet.

### Altres Característiques

- Absència de punters
- Classes i objectes
- Herència
- Classes abstractes
- Interfícies
- Programació genèrica
- Encapsulació i polimorfisme
- Interfícies gràfiques d'usuari
- Gestió d'esdeveniments
- Programació concurrent
- Excepcions

> Els tipus de dades fan referència al tipus d'informació que es treballa, on la unitat mínima d'emmagatzematge és la dada, també es pot considerar com el rang de valors que pot prendre una variable durant l'execució del programa.

```// Hola.java
import java.io.IOException;
public class Hola {
    public static void main(String[] args)throws IOException {
        System.out.println("Hola, món!"); 
    }
}
```