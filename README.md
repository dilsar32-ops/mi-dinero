# Arca

Fondo compartido para la casa: uno manda dólares, la otra anota lo que
llega en quetzales, en qué lo gasta y la foto del recibo. Los dos ven el
mismo saldo.

**El app nunca inventa un tipo de cambio.** De cada envío se guardan dos
números reales — los dólares que salieron y los quetzales que llegaron —
y ninguno se calcula con el otro.

El esquema de la base está en `casa-schema.sql` (un nivel arriba en el repo
de trabajo). Las cuentas están probadas en `tests/dinero_test.js`.
