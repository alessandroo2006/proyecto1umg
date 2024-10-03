#include <iostream>
#include <vector>
#include <string>
#include <iomanip>
#include <ctime>

using namespace std;

struct Estudiante {
    int codigo;
    string nombres;
    string apellidos;
    string carrera;
    string direccion;
    string departamento;
    string municipio;
    string aldea;
    string telefonoPersonal;
    string telefonoCasa;
    string telefonoEmergencia;
    string fechaNacimiento;
    int edad;
    int anioIngreso;   
    string correo;
};

struct Curso {
    string codigoCurso;
    string nombreCurso;
    int semestre;
    int creditos;
    vector<double> notasParciales;
    double notaFinal;
    string estado;
};
