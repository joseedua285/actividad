using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Menusito
{
    class program
    {
        static void Main(string[] args)
        {
            bool continuar = true;
            while (continuar)
            {
                //Menu de opciones 
                Console.Clear();
                Console.WriteLine("----MENU de tienda de Anime----");
                Console.WriteLine("1-) OPCION de playera 1");
                Console.WriteLine("2-) OPCION de juguetes 2");
                Console.WriteLine("3-) OPCION llaveos 3");
                Console.WriteLine("4-) OPCION de salir 4");
                Console.WriteLine("INGRESA UNA OPCION PARA CONTINUAR");
                int opcion = Convert.ToInt32(Console.ReadLine());
                switch (opcion)
                {
                    case 1:
                        Console.WriteLine("Has entrado a la opcion playeras 1");
                        Console.WriteLine("presiona cualquier tecla para continuar");
                        Console.ReadKey();
                        break;
                    case 2:
                        Console.WriteLine("Has entrado a la opcion juguetes 2");
                        Console.WriteLine("presiona cualquier tecla para continuar");
                        Console.ReadKey();
                        break;
                    case 3:
                        Console.WriteLine("Has entrado a la opcion llaveros 3");
                        Console.WriteLine("presiona cualquier tecla para continuar");
                        Console.ReadKey();
                        break;
                    case 4:
                        Console.WriteLine("Esta seguro que desae salir?");
                        Console.WriteLine("si/no");
                        string deside = Console.ReadLine();
                        if (deside == "si")
                        {
                            continuar = false;
                        }
                        break;
                    default:
                        Console.WriteLine("Usted ha ingresado una opcion no valida initente de nuevo . :");
                        break;

                }

            }

        }
    }


}