# 1. Titulo de la practica

Pon el enunciado de la practica aqui. 
- Esto es un ejemplo para separar por puntos.
- Esto es un ejemplo para separar por puntos.

# 2. Model conceptual
## 2.1. Enllaç públic a l'esquema
[Enlace hacia draw.io modelo conceptual](http://...)
- Recuerda que tiene que ser publico!

## 2.2. Esquema conceptual (EC ó ER)
  ![NOMBRE DE LA PRACTICA](./IMAGEN_MODELO_CONCEPTUAL.png)

# 3. Model lògic relacional
## 3.1. Esquema lògic
- Ejemplo modelo logico (Modifica por el tuyo)

Client (<ins>dni</ins>, nom, adreça, telefon)  
Assumpte (<ins>numExpedient</ins>, dataInici, dataArxiu, estat, dni)  
Procurador (<ins>dni</ins>, nom, adreça, telefon)  
AssumpteXProcurador (<ins>numExpedient, dni</ins>)  

## 3.2. Diagrama referencial
- Ejemplo Diagrama referencial (Modifica por el tuyo)

Relació referencial|Clau aliena|Relació referida
-|-|-
Asunto|Dni|Cliente
AsuntoXProcurador|Dni|Procurador
AsuntoXProcurador|NumExp|Asunto

# 4. Model físic
## 4.1 Enllaç a l'esquema físic
- Script en sql (Dejar ./ antes para que se pueda abrir siempre. No pongas la ruta de tu directorio solo ./nombre_practica.sql)
[script nombre_practica.sql](./nombre_practica.sql)