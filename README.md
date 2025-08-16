# Hora do Sistema em Java

Este projeto é um programa simples desenvolvido como parte do aprendizado em **Java** no **NetBeans IDE**. O objetivo é exibir a hora atual do sistema no console.

## Sobre o projeto

- Linguagem: Java  
- IDE utilizada: NetBeans  
- Tipo de projeto: Console application  
- Autor: Luan Fernandes  

## Funcionalidade

O programa cria um objeto `Date` para capturar a data e hora atual do sistema e exibe no console.

```java
import java.util.Date;

public class HoraDoSistema {
    public static void main(String[] args) {
        Date relogio = new Date();
        System.out.println("A hora do sistema é");
        System.out.println(relogio.toString());
    }
}
```
Exemplo de saída

A hora do sistema é
Sat Aug 16 03:37:30 GMT-03:00 2025
