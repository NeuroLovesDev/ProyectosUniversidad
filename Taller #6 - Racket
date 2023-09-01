#lang racket

;proposito: Verificar si una persona es apta para el ingreso al ejercito
;ejemplo: edad 19, genero f, estado fisico regular, estado psicologico bueno = no apto
;parametros de entrada: edad,genero,estado fisico, estado psicologico
;definicion:

(define(aptitud edad genero efisico epsicologico)
  (if(and(> edad 18)(< edad 24)
         (genero "m")
         (efisico "si")
         (epsicologico "bueno")
     )
     (display "Eres apto para el ingreso al ejercito")
     (display "No eres apto para el ingreso al ejercito")
  )
)

;introduccion de los datos

(display "Ingrese su edad: ")
(define edad (read))

(display "Ingrese su genero (m/f): ")
(define genero (read))

(display "Tiene buen estado fisico? (si/no): ")
(define efisico (read))

(display "Ingrese resultado de estado psicologico (bueno/regular/malo): ")
(define epsicologico (read))

(newline)

((aptitud edad genero efisico epsicologico))
