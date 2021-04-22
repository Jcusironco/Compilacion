using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace CapaNegocio
{
    public class Alumno
    {
        // atributos
        private string apellidos;
        private string nombres;
        private int edad;
        private string lugaNacimiento;

        //propiedades
        public string Apellidos
        {
            get { return apellidos; } // lectura de atributos
            set { apellidos = value;  }// escritura del atributo
        }
        public string Nombres
        {
            get { return nombres; } // lectura de atributos
            set { nombres = value; }// escritura del atributo
        }
        public int Edad
        {
            get { return edad; } // lectura de atributos
            set { edad = value; }// escritura del atributo
        }
        public string LugaNacimiento
        {
            get { return this.lugaNacimiento; } // lectura de atributos
            set { this.lugaNacimiento = value; }// escritura del atributo
        }

        // Metodos u operaciones
        public string Estudiar()
        {
            return " no se ha implementado el metodo estudiar";
        }
        public string Trabajar()
        {
            return " no se ha implementado el metodo trabajar";
        }
        public string AprobarExamen()
        {
            return " no se ha implementado el metodo aprobar examen";
        }

        public string Enseñar()
        {
            return " no se ha implementado el metodo aprobar examen";
        }
    }
}
