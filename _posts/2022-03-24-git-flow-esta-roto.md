---
layout: post
title: Git Flow está roto
description: o de cómo tu estrategia de branching puede darle ventajas a tu competencia
tags: Blogging
---

# Git Flow está roto
##### *o de cómo tu estrategia de branching puede darle ventajas a tu competencia*.  


De un tiempo a esta fecha en las empresas, cualquiera sea su tamaño, se persigue la idea de hacer las cosas mas *ágiles* y mejor para no perder ese **time to market**.
Muchas veces esa urgencia lleva a tomar malas deciciones, algo que puede parecer trivial, como la manera en la que los equipos administran sus repositorios de código puede tener impactos significativos en el propio negocio de la empresa.  

¡Un momento! ¿Esto puede darle ventajas a la competencia?  

Bueno, no hay una respuesta sencilla, es un gran *depende* pero muchas personas podrían coincidir en que esa capacidad de entregar nuevas caracteristicas o arreglar errores lo más rápido posible hace que una empresa (o producto) se vea mejor ante los ojos de las personas usuarias y por consiguiente consiga mejor cuota de mercado.

Por el año 2010 [Vincent Driessen](https://nvie.com/posts/a-successful-git-branching-model/) proponía una manera de trabajo que fué adoptada por muchas organizaciones de diversos tamaños, como el propio Vincent menciona en su blog fué tan masivamente aceptado, adoptado y hasta venerado (?) que aún hoy en día se lo considera un estándar.  

Adoptar esta estrategia hoy en día podría ser uno de los mayores errores que una organización podría cometer. Veamos a qué me refiero.
Según lo que git-flow propone la rama *main* y *develop* son sagradas, incorporar nuevas caracteristicas o arreglar errores necesitan de sus propias ramas 

![git-flow](/img/git-model@2x.png)