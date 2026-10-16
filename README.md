# ops-control

Interruptor del sistema `ops`. Un único fichero, `modo`:

- `normal`: los agentes trabajan según su nivel de autonomía.
- `reducido`: solo vigilan, informan y dejan borradores.
- `parado`: nada se ejecuta.

Para cambiarlo desde el móvil: github.com → este repo → `modo` → editar (lápiz) → commit.
Lo leen los hooks de las routines y los scripts de Hermes; ninguna routine puede escribirlo.
