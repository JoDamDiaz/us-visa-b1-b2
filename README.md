# 🛂 Skill: Preparación de visa americana B1/B2 (turismo/negocios)

Una guía conversacional, en español, para acompañar paso a paso a quien solicita una visa estadounidense de turismo o negocios (B1/B2). Está escrita en Markdown plano para que pueda usarse con **cualquier asistente de IA**.

1. **Llenar el DS-160**: explica cada sección, qué datos tener a la mano y los errores comunes.
2. **Pagar y agendar**: pago de derechos consulares y citas (CAS y Embajada).
3. **Documentos**: checklist personalizado para la entrevista.
4. **Simulacro de entrevista**: práctica con retroalimentación, una pregunta a la vez.

> ⚠️ **Proyecto comunitario y no oficial.** No está afiliado, avalado ni patrocinado por el Gobierno de EE. UU., el Departamento de Estado ni la Embajada. Lee el [aviso legal](AVISO_LEGAL.md).

## Cómo usarla

Dale a tu asistente de IA el contenido de `us-visa-b1-b2/SKILL.md` como instrucciones y, según lo necesite, los archivos de `references/` y `assets/` como contexto. El punto de entrada es `SKILL.md`.

## Qué NO hace (a propósito)

- No llena el DS-160 por ti ni responde por ti las preguntas de antecedentes y seguridad.
- No pide ni guarda contraseñas, números de tarjeta ni respuestas de seguridad.
- No garantiza ni predice la aprobación de la visa: eso depende de tu caso y del criterio del oficial consular.
- No afirma de memoria cuánto cuesta la visa; te remite a la fuente oficial.

## Alcance y vigencia

- Pensada para la **Embajada/Consulado de EE. UU. en Bogotá, Colombia**. En otros países el formulario es el mismo, pero cambian el CAS, los bancos y las plataformas.
- Contenido contrastado contra las transcripciones de los videos el **29-sep-2026**. Los videos son de finales de 2019 e inicios de 2020. Bancos, plataformas, plazos y enlaces cambian; verifica siempre en <https://co.usembassy.gov/es/visas-es/>.
- Si encuentras algo desactualizado, abre un *issue* o un *pull request*.

## Estructura

```
us-visa-b1-b2/
├── SKILL.md                      # Instrucciones y flujo principal
├── references/
│   ├── llenar-ds160.md
│   ├── pago-y-cita.md
│   ├── documentos-entrevista.md
│   ├── simulacro-entrevista.md
│   ├── enlaces-oficiales.md
│   └── fuentes-videos.md         # Videos, enlaces al minuto y correcciones
└── assets/
    └── checklist-template.md     # Plantilla del checklist
```

## Fuentes y verificación

La skill se basa en tres videos oficiales de la Embajada/Consulado de EE. UU. en Bogotá. Cada dato de `references/` incluye un enlace que abre el video en el minuto correspondiente, para que cualquiera pueda comprobarlo. Consulta [`us-visa-b1-b2/references/fuentes-videos.md`](us-visa-b1-b2/references/fuentes-videos.md): allí están los videos, la tabla completa de tiempos, las contradicciones entre videos, los datos ya desactualizados y las correcciones hechas al validar.

## Contribuir

Se agradecen correcciones, actualizaciones de datos operativos y adaptaciones para otras embajadas. Por favor:
- Cita la fuente oficial y **escribe con tus propias palabras**; no copies transcripciones ni textos literales.
- No incluyas datos personales de nadie.
- Indica la fecha en que verificaste la información.

## Licencia

[MIT](LICENSE) © JoDamDiaz. El contenido oficial que inspira esta guía pertenece a sus respectivos autores; aquí solo se incluyen resúmenes propios y enlaces.
