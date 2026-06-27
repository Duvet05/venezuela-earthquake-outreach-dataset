# Dataset publico de contactos para ayuda humanitaria en Venezuela

Pagina estatica publica para descargar datasets de contactos y canales de
difusion relacionados con una app de ayuda tras el terremoto de Venezuela.

Referencia importante del ecosistema:
[AyudaVE / Ayuda Humanitaria Venezuela](https://ayudahumanitariavenezuela.com/).
Ese sitio ya concentra centros de acopio, donaciones, voluntariado, personas,
hospitales y recursos, por lo que debe tratarse como aliado o fuente central de
interoperabilidad antes de duplicar esfuerzos.

## Archivos

- `data/venezuela-earthquake-contact-dataset.csv`: dataset priorizado de
  contactos publicos, con fuentes cruzadas, canal publico, LinkedIn cuando
  aplica, puntaje de confianza, riesgos y siguiente accion recomendada.
- `data/venezuela-earthquake-influencer-dataset.csv`: lista complementaria para
  difusion, con medios, creadores, hubs de diaspora, organizaciones
  humanitarias y negocios comunitarios.

## Como leer las prioridades

- `P0`: contactar primero. Validadores, aliados tecnicos o plataformas ya
  directamente relacionadas con la respuesta.
- `P1`: segundo anillo. Organizaciones humanitarias, medios confiables o
  contactos con alto ajuste operativo.
- `P2`: usar cuando el mensaje y la validacion ya esten listos.
- `P3`: alta visibilidad pero menor ajuste operativo o mayor riesgo de ruido.

## Flujo recomendado

1. Coordinar primero con AyudaVE, verificadores y organizaciones humanitarias.
2. Preparar un paquete de confianza: URL, capturas, responsables, politica de
   privacidad, campos de datos, fuentes, mecanismo de correccion y opt-out.
3. Contactar medios de confianza con una historia de utilidad publica, no como
   promocion.
4. Activar creadores de alto alcance solo despues de contar con validacion
   publica de verificadores, medios u organizaciones.
5. Revalidar contactos durante una emergencia activa cada 7 a 14 dias.

## Nota de privacidad

Este repositorio no debe usarse como buscador de personas. Los datasets evitan
cedulas, RIF personales, direcciones privadas, centros de votacion, datos de
salud, telefonos privados y otros datos sensibles.

Cedula.com.ve aparece solo como posible contacto tecnico/API. No debe usarse
para enriquecer listas, perfilar ciudadanos, deduplicar personas o contactar a
gente por cedula. Cualquier integracion de identidad debe requerir consentimiento,
minimizacion de datos, auditoria, limites de uso y una finalidad humanitaria
explicita.
