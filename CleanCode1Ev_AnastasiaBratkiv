/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package cleancode1ev_anastasiabratkiv;

/**
 *
 * @author aanas
 */
public class CleanCode1Ev_AnastasiaBratkiv {

    final static int Marca2000 = 1;
    final static int Marca2001 = 2;
    final static int Marca2002 = 3;
    final static int numMaxParticipantes = 10;

    // Variable para asignar dorsales
    static int numDorsal = 0;

    public static void main(String[] args) {
        registrarParticipante("Juan", Marca2001);
        registrarParticipante("María", Marca2000);
        registrarParticipante("Pedro", Marca2002);
        mostrarInformacionParticipantes();
    }

    static void registrarParticipante(String nombre, int marca) {
        if (numDorsal < numMaxParticipantes) {
            numDorsal++;
            System.out.println("Registrando a " + nombre + " con dorsal " + 
                    numDorsal + " y marca " + obtenerNombreMarca(marca));
        } else {
            System.out.println("No hay cupo para más participantes.");
        }
    }

    // Función para obtener el nombre de la marca según el código    
    static String obtenerNombreMarca(int codigoMarca) {
        if (codigoMarca == Marca2000) {
            return "Marca 2000";
        } else if (codigoMarca == Marca2001) {
            return "Marca 2001";
        } else if (codigoMarca == Marca2002) {
            return "Marca 2002";
        } else {
            return "Marca Desconocida";
        }
    }

    static void mostrarInformacionParticipantes() {
        System.out.println("\nInformación de Participantes:");
        for (int i = 1; i <= numDorsal; i++) {
            System.out.println("Dorsal " + i + ": " + 
                    obtenerNombreMarca(Marca2000) + " - Nombre: " + "Participante " + i);
        }
    }

    }

                
