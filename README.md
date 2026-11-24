# TP Linux - Trabajo Práctico

## Integrantes
- Brian Paul Salinas

Repositorio con los entregables del Trabajo Práctico de Linux (Universidad de Palermo).

## Cómo reconstruir /var

El directorio /var se subió spliteado en partes (var_part_aa, var_part_ab, ...)
porque el .tar.gz original pesa más de lo recomendado para un solo archivo en GitHub.

Para reconstruirlo:
    cat var_part_* > var.tar.gz
    tar -xzf var.tar.gz
