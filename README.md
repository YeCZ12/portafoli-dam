# Portafoli DAM - Yeray Contreras

Benvingut al meu **portafoli personal de DAM (Desenvolupament d'Aplicacions Multiplataforma)**. En aquest repositori mostraré els projectes, exercicis i treballs que vaig realitzant durant els meus estudis.

## Sobre el projecte

Aquest portafoli serveix per recopilar i mostrar els meus coneixements i projectes relacionats amb la programació i el desenvolupament d'aplicacions.

A mesura que vagi avançant en els meus estudis, aniré **afegint nous projectes i actualitzant el repositori**.

## Funcionalitats

- 📂 Mostrar els **projectes i exercicis** realitzats durant el curs.
- 💻 Mostrar els coneixements adquirits en **programació amb Java**.
- 🛠️ Mostrar les eines que utilitzo, com **GitHub, ChatGPT, Notebook i Notion**.
- 📚 Recopilar diferents treballs i pràctiques en un mateix lloc.
- 🚀 Actualitzar el portfoli amb **nous projectes** a mesura que avanci en els meus estudis.

## Tasques

- [x] Crear el repositori del portfoli.
- [x] Crear el fitxer `README.md`.
- [x] Afegir un exemple de codi Java.
- [ ] Afegir nous projectes al portfoli.

## Instal·lació

Per tenir aquest projecte en local, cal seguir aquests tres passos:

1. Clonar el repositori de GitHub:

git clone https://github.com/YeCZ12/portafoli-dam.git


2. Entrar a la carpeta del projecte:

cd portafoli-dam


3. Obrir el projecte amb Visual Studio Code o un altre editor compatible.

## Exemple de codi

Aquest és un exemple d'un programa que he realitzat en **Java**. El programa simula un sistema d'aparcament amb diferents opcions: aparcament per hores, aparcament de dia complet, rentat de vehicle i recàrrega elèctrica.

import java.util.Scanner;

public class EjE {
    public static void main(String[] args) {
        Scanner e = new Scanner(System.in);
        int dec;

        System.out.println("===== APARCAMENT =====");
        System.out.println("1. Aparcament per hores");
        System.out.println("2. Aparcament de dia complet");
        System.out.println("3. Rentat de vehicle");
        System.out.println("4. Recàrrega electrica");
        System.out.println("=====================");
        System.out.println("Que opción escoges?");
        dec = e.nextInt();

        switch(dec){
            case 1:
                int horas;
                double descuento = 1, precio1;

                System.out.println("Cuantas horas te quieres estacionar?");
                horas = e.nextInt();

                if (horas > 5){
                    descuento = 0.9;
                }

                precio1 = (horas * 2) * descuento;

                System.out.println("El precio es: " + precio1 + " euros");
                break;

            case 2:
                int dias, ppdia = 15;
                double precio2;

                System.out.println("Cuantos dias te quieres quedar estacionado?");
                dias = e.nextInt();

                if (dias > 3){
                    ppdia = 12;
                }

                precio2 = dias * ppdia;

                System.out.println("El precio es: " + precio2 + " euros");
                break;

            case 3:
                int dec3;
                double precio3 = 0;

                System.out.println("Que tipo de rentado quieres? (1/2)");
                dec3 = e.nextInt();

                if (dec3 == 1){
                    precio3 = 8;
                }
                else if (dec3 == 2){
                    precio3 = 15;
                }
                else{
                    System.out.println("Tipo de rentado incorrecto");
                }

                System.out.println("El precio es: " + precio3 + " euros");
                break;

            case 4:
                double kWh, ppkWh = 0.3, precio4;

                System.out.println("Cuantos kWh has consumido?");
                kWh = e.nextDouble();

                precio4 = kWh * ppkWh;

                if (kWh > 40){
                    precio4 = precio4 - 2;
                }

                System.out.println("El precio es: " + precio4 + " euros");
                break;

            default:
                System.out.println("Opción no valida");
        }

        e.close();
    }
}

## Eines que utilitzo

Eina	Per a què serveix	Ús
ChatGPT	Ajuda a resoldre dubtes i entendre conceptes	Aprenentatge
Notebook	Prendre apunts i organitzar informació	Estudis
Notion	Organitzar tasques, apunts i projectes	Organització
GitHub
Utilitzo GitHub per guardar els meus projectes, controlar les diferents versions del codi i poder compartir els meus treballs.

Veure el meu perfil de GitHub

Tecnologies
Actualment estic treballant principalment amb:

Java
Git i GitHub
Markdown
Eines d'organització i aprenentatge com ChatGPT, Notebook i Notion
Objectiu
L'objectiu d'aquest portfoli és anar recopilant els meus treballs durant el cicle de DAM i poder veure la meva evolució com a desenvolupador.

