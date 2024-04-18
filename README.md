# Guia  de consulta de Bases de Datos  NO SE COPIEN VAGOS

### **Alumnos:** Juan Baader, Sofia Arisi y Julieta Kogan

### **Año:** 2024

### **Curso:** 4B TIC

### **Profesor/a** Ignacio Vigilante

[Link a Github](https://github.com/juanpanpanyz/Base-de-datos-consultas)


<br>

## **Primer Ejercicio**
Una búsqueda que devuelva todos los registros ordenados por una columna
```sql
SELECT *
FROM `Desarolladores`
ORDER BY `DNI_D`;
```
```sql
SELECT *
FROM `Estudio`
ORDER BY `ID_estudio`;
```
```sql
SELECT *
FROM `Oficina`
ORDER BY `ID_Oficina`;
```
```sql
SELECT *
FROM `Tiendas`
ORDER BY `ID_Tienda`;
```

## **Segundo Ejercicio**
Una búsqueda que devuelva algunos registros (+ de 1) pero no todos

```sql
SELECT `DNI_D`, `Nombre`
FROM `Desarolladores`
ORDER BY `Nombre`;
```

```sql
SELECT `ID_estudio`, `nombre_estudio`
FROM `Estudio`
ORDER BY `nombre_estudio`;
```

```sql
SELECT `ID_Oficina`, `Oficina`
FROM `Oficina`
ORDER BY `Oficina`;
```

```sql
SELECT `ID_Tienda`, `Nombre`
FROM `Tiendas`
ORDER BY `Nombre`;
```

## **Tercer Ejercicio**
Una consulta que agregue un nuevo registro

```sql
INSERT INTO `Desarolladores` (`DNI_D`, `Nombre`) VALUES (`200631`, `Roberto`);
```

```sql
INSERT INTO `Estudio` (`ID_estudio`, `nombre_estudio`) VALUES (`28`, `Robertogaming`);
```

```sql
INSERT INTO `Oficina` (`ID_Oficina`, `Oficina`) VALUES (`69`, `RobertoOficina`);
```

```sql
INSERT INTO `Tienda` (`ID_Tienda`, `Nombre`) VALUES (`19`, `tiendaRoberto`);
```
