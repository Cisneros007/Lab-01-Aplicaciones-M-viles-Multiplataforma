//Problema 04 

void main() {
  // Declarar un mapa llamado "persona" para almacenar información
  
  Map<String, dynamic> persona = {
    'nombre': 'Juan',
    'edad': 30,
    'ciudad': 'Madrid'
  };

  // Acceder al valor correspondiente a la clave 'nombre' y 'edad' en el mapa "persona" 
  print("Nombre: ${persona['nombre']}");
  print("Edad: ${persona['edad']}");

  // Modificar el valor de 'edad' en el mapa "persona" y que sea 35
  persona['edad'] = 35;

  // Agregar una nueva clave 'profesion' con el valor 'Ingeniero' al mapa
  
  persona['profesion'] = 'Ingeniero';

  // Iterar sobre el mapa "persona"
  print("Información de la persona:");
  persona.forEach((key, value) {
    print("$key: $value");
  });
}