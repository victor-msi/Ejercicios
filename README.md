# Ejercicios
<?php
class Arbol
{
    public $CantidadHojas;
    public $Tipo;
    public $Antiguedad;
    public $Altura;

    public function Crecer()
    {
        echo "Esta es mi altura: $this->Altura <br>";
    }

    public function CrearHojas()
    {
        echo "He creado $this->CantidadHojas hojas <br>";
    }
    public function Fotosintesis()
    {
        echo "Soy un arbol de $this->Antiguedad, y de tipo $this->Tipo <br>";
    }
}

$Arbol1 = new Arbol();
$Arbol1 -> CantidadHojas = "50";
$Arbol1 -> Tipo = "Secolla";
$Arbol1 -> Antiguedad = "15";
$Arbol1 -> Altura = "10";
$Arbol1 ->Crecer();
$Arbol1 ->CrearHojas();
$Arbol1 ->Fotosintesis();
?>


<?php
class Humano
{
    public $altura;
    public $genero;
    public $edad;
    public $caracter;

    public function Hablar()
    {
        echo "Hola Como Estas!! <br>";
    }

    public function Correr()
    {
        echo "Estoy Corriendo <br>";
    }

    public function Comer()
    {
        echo "Estoy Comiendo una Pizza <br>";
    }
}

$Persona1 = new Humano();
$Persona1 -> altura = "1.6";
$Persona1 -> genero = "Masculino";
$Persona1 -> edad = "21";
$Persona1 -> caracter = "Soy un Humano";
$Persona1 -> Hablar();
$Persona1 -> Correr();
$Persona1 -> Comer();
?>
