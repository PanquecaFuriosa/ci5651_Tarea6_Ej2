Implementación del condigo para el ejericio 2 de la tarea 6 de la materia CI5651 Diseño de Algoritmos I

Sea A = (N, C) un árbol (notemos que |C| = |N| − 1) y un predicado
p : C → {true, f alse}. Queremos responder consultas que pueden tener una de dos formas:
• forall(x, y), para x, y ∈ N, que diga si evaluar p para todas las conexiones entre entre
los nodos x e y resulta en true.
• exists(x, y), para x, y ∈ N, que diga si evaluar p para alguna de las conexiones entre
entre los nodos x e y resulta en true.
Diseñe un algoritmo que pueda responder Q consultas de cualquiera de estas formas en
tiempo O(|N| + Q log |N|), usando memoria adicional O(|N|)
