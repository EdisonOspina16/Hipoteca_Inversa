# Reverse Mortgage Calculator

## Who Made This?
**Author:** Yonatan Calimeño and Juan Diego

## What Is It and What Is It For?
This project is an application to calculate the monthly payments of a reverse mortgage, considering factors such as the property's value, the property's condition, marital status, the ages of the owner and spouse, and the interest rate.

## How Do I Run It?

### Prerequisites
Make sure you have Python and kivy  installed on your system. 

**Kivy Installation:** Provided instructions to install Kivy using `pip`
Sometimes it doesn't let you download Kivy with the basic command "pip install Kivy", so my recommendation is that you use the Anaconda Python interpreter, and from the Anaconda console execute the command: "pip install Kivy", I also leave you the Kivy documentation here:https://kivy.org/doc/stable/gettingstarted/installation.html

### Running the Program
To run the program outside of the development environment:

1. Navigate to the folder:
   Once you have cloned the file, open the command prompt (cmd) or Anaconda Prompt, and navigate to the folder where you saved the file, for example:

    ```bash
    cd C:\Users\yonatan\Desktop\language_two\PRACTICE_CLEANCODE-main
    ```

2. Run the main script:
    ```bash
    python src/console/main.py
    ```

## How Is It Made?

### Project Architecture
The project is organized into two main folders:

- **src**: Contains the application's source code.
  - **console**: Contains the main script `main.py` for user interaction.
  - **logic**: Contains the logic for reverse mortgage calculation (`reverse_mortgage.py`).
- **test**: Contains unit tests to validate the functionality of the code.

### Module Organization
- `src/console/main.py`: Main file for user interaction. Collects user inputs and displays the results.
- `src/logic/reverse_mortgage.py`: Contains the logic functions for reverse mortgage calculation, including input validation and payment calculation.

### Dependencies
 -`kivy` and `unittest` as dependencies

## Usage
To run the unit tests from the `tests` folder, use the following command:

```bash
python test/unit_tests.py

To run the main file:
python src/console/main.py
python src/console/main_console.py"
```

# ACTUALIZACIONES 

### Dependencias 
```
- python 3
- psycopg2 --> PIP INSTALL PSYCOPG2
```

### Estructa del proyecto:
se creo tres nuevas carpetas con los nombres de : 

- CONTROLLER: Contiene el codigo fuente con la conexion a la base de datos y los querys que se pueden ejecutar

- MODEL: Contiene el codigo fuente para modelar los usuarios que se van a ingresar a la base de datos.

- VIEW_CONSOLE: Contiene el codigo fuente de la interfaz por consola.

y un archivo de test que esta dentro de la carpeta test.
Esta carpeta contiene las pruebas unitarias para validar el correcto funcionamiento del código.

### Para acceder a los test:
 ```
test\TestMVC.py
 ```

### Acceder a la consola : 

```
src\VIEW_CONSOLE\Crear_Usuario.py
```


# MODIFICACIONES

- Creacion de consola.
- Organización estructuras de carpetas.

### Nombre Colaboradores:
- Edison Ospina.
- Juan Manuel Garcia.
