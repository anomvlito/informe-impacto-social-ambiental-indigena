# Documento de Referencia: Informe de Impacto Social y Ambiental
## Pista de Atletismo — Isla de Pascua (Rapa Nui)

> **Actualizado:** 2026-03-11  
> **Investigadores:** Fabián Ortega & Lucas Nervi  
> Este archivo centraliza todas las rutas de fuentes, decisiones editoriales y estructura del informe LaTeX.

---

## Archivos del Informe (este directorio)

```
/home/fabian/src/investigacion rapa nui/informe-impacto-social-ambiental-indigena/
├── informe-impacto.tex          ← Documento LaTeX principal (CREADO)
├── referencias-y-rutas.md       ← Este archivo de referencia
├── borrador-informe.md          ← Borrador antiguo (referencia histórica)
├── estructura-informe.md        ← Estructura original preliminar
└── referencias.bib              ← Bibliografía LaTeX (por crear / adaptar)
```

---

## Fuentes Primarias: Investigación Cualitativa Propia

### Resumen Ejecutivo y Reflexiones (principal fuente de teoría)
| Archivo | Ruta | Uso en informe |
|---|---|---|
| Resumen ejecutivo completo | `/home/fabian/src/investigacion rapa nui/trabajo agente/RESUMEN_EJECUTIVO_Rapa_Nui_Deporte.md` | Teoría central, hallazgos, principios de diseño |
| Reflexiones finales | `/home/fabian/src/investigacion rapa nui/trabajo agente/REFLEXIONES_FINALES_resumen_ejecutivo.md` | Recomendaciones editoriales y metodológicas |
| Razonamiento | `/home/fabian/src/investigacion rapa nui/trabajo agente/RAZONAMIENTO_resumen_ejecutivo.md` | Decisiones de escritura |

### Monografía LaTeX (fuente de citas y texto estructurado)
```
/home/fabian/src/investigacion rapa nui/trabajo agente/monografia/
├── MONOGRAFIA_Rapa_Nui_Deporte.tex       ← Documento maestro
├── monografia_referencias.bib            ← BIBLIOGRAFÍA COMPLETA (usar esta)
└── sections/
    ├── 01_introduccion/
    │   ├── marco_historico.tex           ← Historia colonización, Compañía Explotadora
    │   ├── deporte_contexto.tex          ← Contexto deportivo en Rapa Nui
    │   ├── pregunta_objetivos.tex        ← Preguntas y objetivos de investigación
    │   └── enfoque.tex                   ← Enfoque metodológico
    ├── 02_marco_teorico/                 ← Marco teórico (Bourdieu, Freire, Hau'ofa)
    ├── 03_metodologia/                   ← Metodología TF constructivista + Talanoa/Vā
    ├── 04_hallazgos/
    │   ├── a_sujeto_nucleo.tex           ← Juventud, Marco interno, Motivación (CITAS DIRECTAS)
    │   ├── b_cimientos_relacionales.tex  ← Familia, Capital social
    │   ├── c_ecosistema_deportivo.tex    ← Entrenadores, Organizaciones, Recursos
    │   ├── d_matriz_cultural.tex         ← Cultura, Identidad, Género
    │   ├── e_barreras_estructurales.tex  ← Migración, Adversidad, Salud (CITAS DIRECTAS)
    │   └── f_contexto_practica.tex       ← Contexto de práctica deportiva
    ├── 05_teoria_central/
    │   ├── formulacion.tex               ← Teoría "Del potencial al proyecto"
    │   ├── modelo_dinamico.tex           ← Modelo condiciones-mecanismos-resultados
    │   ├── proposiciones.tex             ← P1-P5 proposiciones teóricas
    │   └── aporte_teorico.tex            ← Aporte original de la investigación
    ├── 06_principios_diseno/
    │   └── principios_completo.tex       ← 7 principios operativos con indicadores
    └── 07_conclusiones/
```

### Entrevistas Codificadas (citas directas de actores)
```
/home/fabian/src/investigacion rapa nui/Entrevistas_carpeta_oficial/
├── CODIFICADAS/
│   ├── 12_Pua/                          ← Entrevista Pua (docx + comentado + códigos xlsx)
│   ├── 22_Felipe_Custer_2/              ← Entrevista Felipe Custer
│   ├── 27_yasmani_acosta/               ← Entrevista Yasmani Acosta
│   ├── 31 LISTO Kiu Kiva/               ← Entrevista Kiu Kiva
│   ├── 4_entrevista_tito/               ← Entrevista Tito
│   └── 7_LISTO_entrevista_hopu_manu/    ← Entrevista Hopu Manu
├── PRE-CODIFICADAS/
├── 1 charla harold_/
├── 19_juan_pakomio_3/
├── 25 panel deportistas 1/
├── 26 panel deportistas 2/
├── 33_32_matarena_tea/
└── 34_Nehe_Pakomio/
```

### Categorías de análisis (mapas conceptuales SVG)
```
/home/fabian/src/investigacion rapa nui/compilado_categorias/
├── Cultura.svg                           ← Identidad cultural, prácticas
├── Familia.svg                          ← Hanai, crianza comunitaria
├── Juventud.svg                         ← Potencial, barreras
├── Salud.svg                            ← Salud pública, bienestar
├── Motivación Deportiva.svg             ← Motivación intrínseca/extrínseca
├── Capital Social y Estructuras de Apoyo.svg
├── Identidad y Resiliencia en un Contexto de Cambio.svg
├── Dimensiones de la Adversidad.svg     ← Riesgo, violencia colonial
├── Género y deporte.svg                 ← Participación femenina
├── Recursos.svg                         ← Infraestructura, financiamiento
├── Sostenibilidad.svg                   ← Continuidad de proyectos
├── Formación deportiva.svg              ← Trayectorias, etapas
├── Pilares del Desarrollo Deportivo.svg
├── Estructura y Gobernanza Organizacional.svg
├── Marco Interno del Individuo.svg
├── Entrenador.svg
├── migración.svg
├── potencial.svg
├── referentes.svg
├── consumo.svg
├── aplicación de la ley.svg
├── Normalización y prácticas culturales de consumo.svg
└── deporte.svg                          ← Categoría principal
```

---

## Fuentes Secundarias: Papers y Documentos del Repositorio

### Documentos institucionales y contextuales
| Archivo | Ruta | Relevancia |
|---|---|---|
| Informe Consejo Rapa Nui | `/home/fabian/src/investigacion rapa nui/info rapa nui/32.-Informe_consejo_rapa_nui.pdf` | Gobernanza indígena, derechos |
| Sectorial Ministerio del Deporte 2020 | `/home/fabian/src/investigacion rapa nui/info rapa nui/23-2020-SECTORIAL-MINISTERIO-DEL-DEPORTE.pdf` | Marco nacional deporte |
| IDH PNUD Informe Rural | `/home/fabian/src/investigacion rapa nui/info rapa nui/undp_cl_idh_informe_rural_es.pdf` | Desarrollo humano, brechas territoriales |
| La Compañía Explotadora | `/home/fabian/src/investigacion rapa nui/info rapa nui/la compañia explotadora.pdf` | Historia colonial, contexto territorial |

### Papers de salud y sociedad
| Archivo | Ruta | Relevancia |
|---|---|---|
| Obesidad y globalización Rapa Nui | `/home/fabian/src/investigacion rapa nui/info rapa nui/Obesidad-y-globalizacion-rapa-nui.pdf` | Salud pública, efectos globalización |
| Interculturalidad en salud mental | `/home/fabian/src/investigacion rapa nui/info rapa nui/Interculturalidad-en-salud-mental.pdf` | Salud mental, pertinencia cultural |
| Ta-aku-poki | `/home/fabian/src/investigacion rapa nui/info rapa nui/Ta-aku-poki.pdf` | Crianza, infancia Rapa Nui |
| Whanau violence prevention | `/home/fabian/src/investigacion rapa nui/info rapa nui/The basis for whānau violence prevention and intervention.pdf` | Marco intervención comunitaria Pacífico |

### Papers de deporte y metodología
| Archivo | Ruta | Relevancia |
|---|---|---|
| Sport in NZ Pasifika communities | `/home/fabian/src/investigacion rapa nui/info rapa nui/SPORTANDRECREATIONINNEWZEALANDpasifikacommunities.pdf` | Deporte comunidades indígenas Pacífico |
| Modern sports in Rapa Nui | `/home/fabian/src/investigacion rapa nui/info rapa nui/modern sports in Rapa Nui and Polynesia, focusing on their development and presence in contemporary culture - SciSpace Literature Review.pdf` | Desarrollo deporte moderno Rapa Nui |
| Deporte Bendrups | `/home/fabian/src/investigacion rapa nui/info rapa nui/d.-Bendrups-Shima-v2n1.pdf` | Cultura y deporte insular |
| Cannabis en NZ (Marco Māori) | `/home/fabian/src/investigacion rapa nui/info rapa nui/cannabis-and-methamphetamine-in-new-zealand-a-kaupapa-maori-literature-review.pdf` | Consumo sustancias, marco indígena |

### Herramientas metodológicas (Papers de investigación)
```
/home/fabian/src/investigacion rapa nui/Papers/
├── AntroDno_Paper3-Interview-Boeije-presenting the self.pdf    ← Entrevistas
├── AntroDno_Paper4-Fieldnotes-Emerson-Participating Observing Jotting.pdf
├── AntroDno_Paper5-Interview-Weiss-Making the best of.pdf
├── AntroDno_Paper6-Observation-Bernard-Direct Observation.pdf
└── AntroDno_Paper9-Fernandez-Analisis de texto.pdf            ← Análisis textual
```

---

## Bibliografía clave del proyecto (extraída de monografia_referencias.bib)

La bibliografía completa está en:
`/home/fabian/src/investigacion rapa nui/trabajo agente/monografia/monografia_referencias.bib`

**Autores clave para el informe:**
- `\cite{charmaz2014}` — Teoría Fundamentada Constructivista
- `\cite{bourdieu1977}`, `\cite{bourdieu1990}` — Capital, habitus, campo
- `\cite{freire1970}` — Pedagogía crítica, concientización
- `\cite{hauofa1994}` — "Mar de islas", identidad polinésica
- `\cite{smith1999}` — Metodologías descoloniales
- `\cite{escobar2007}` — Asimetría epistémica, desarrollo
- `\cite{foucault1980}` — Discurso, poder/saber
- `\cite{chilisa2012}` — Metodologías indígenas
- `\cite{pakomio2021}` — Salud mental Rapa Nui (aparece en e_barreras_estructurales.tex)
- `\cite{dobbs2014}` — Violencia colonial, contexto Pacífico

---

## Estructura del informe LaTeX (`informe-impacto.tex`)

```
1. Introducción
   - Contexto geográfico e histórico
   - Objetivo del informe
   - Metodología del estudio de impacto

2. Descripción del proyecto
   - Componentes de la pista
   - Objetivos del proyecto

3. Diagnóstico territorial
   - Marco histórico (colonización, desposesión)
   - Demografía y aislamiento
   - Brechas de infraestructura deportiva
   - Fragmentación institucional actual

4. Impacto social
   - Salud pública ← Categoría Salud + hallazgos e_barreras
   - Formación deportiva y trayectorias ← a_sujeto_nucleo + principios_completo
   - Cohesión comunitaria ← b_cimientos_relacionales
   - Juventud y oportunidades ← a_sujeto_nucleo (Juventud)
   - Motivación y adherencia deportiva ← a_sujeto_nucleo (Motivación)

5. Impacto en identidad y cultura rapanui [SECCIÓN NUEVA]
   - Hanai y deporte como práctica comunitaria
   - Koros como transmisores de saberes
   - Tapati Rapa Nui y deporte tradicional
   - El espacio relacional (Vā) en la infraestructura
   - Mar de islas: identidad y proyección

6. Impacto ambiental
   - Fragilidad ecosistémica insular
   - Impactos en fase de construcción
   - Impactos en fase de operación
   - Huella logística (materiales via marítima/aérea)
   - Medidas de mitigación

7. Participación comunitaria y gobernanza [SECCIÓN NUEVA]
   - Actores clave del territorio
   - Proceso participativo propuesto (Principio Legitimidad Primero)
   - Mesa interactor (municipio-organizaciones-escuela-salud)
   - Mecanismo de devolución y corrección comunitaria

8. Barreras y mecanismos de traducción [SECCIÓN NUEVA]
   - El régimen colonial-burocrático aplicado a infraestructura
   - 5 mecanismos de traducción (teoría "Del potencial al proyecto")
   - Cómo la pista habilita los mecanismos

9. Conclusión y justificación de inversión
   - Síntesis del impacto
   - Recomendación al SNI
   - Próximos pasos

Glosario de términos rapanui
Referencias bibliográficas
```

---

## Citas directas para usar en el informe

Extraídas de `a_sujeto_nucleo.tex`:

**Sobre educación vs. deporte (tensión intergeneracional):**
> "Eso es pa' nosotros, ya pasó, pa' ustedes ya tiene todo esto, tiene beca tiene todo."
— *Madre participante, entrevista en profundidad*

**Sobre falta de incentivos y participación:**
> "Éramos 4 competidores, yo tuve que invitar a mi hermano que ya no competía, a mi otra hermana que no competía, yo y había otros chicos más y los chicos los que estaban."
— *Atleta participante, entrevista en profundidad*

**Sobre salud mental y sistema sanitario (e_barreras_estructurales.tex):**
> Análisis de diagnósticos estandarizados (CIE-10, DSM-5) aplicados con "patrones ajenos" — falta de pertinencia cultural documentada.

---

## Decisiones editoriales

| Elemento | Decisión |
|---|---|
| Formato | LaTeX con clase `article` (o `report`), compilable con pdflatex |
| Bibliografía | Archivo `.bib` copiado/adaptado de `monografia_referencias.bib` |
| Idioma | Español (paquetes: `babel`, `inputenc UTF-8`) |
| Citas | Sistema autor-año (natbib o biblatex) |
| Términos rapanui | En cursiva la primera vez, luego normal |
| Citas directas de entrevistas | Entorno `quote` o `quoting`, en cursiva |
| Longitud objetivo | ~20-25 páginas |
| Investigación propia | Citada como: Ortega \& Nervi (2026) |

---

## Estado de avance

- [x] Plan de mejora creado
- [x] Mapa de rutas de archivos completo (este documento)
- [x] Documento LaTeX creado (`informe-impacto.tex`)
- [ ] Sección 3 enriquecida con marco histórico (leer `marco_historico.tex`)
- [ ] Sección 4 con citas de entrevistas codificadas
- [ ] Sección 5 (identidad y cultura) desarrollada
- [ ] Sección 7 (participación) desarrollada
- [ ] Sección 8 (barreras y mecanismos) desarrollada
- [ ] Bibliografía `.bib` adaptada
- [ ] Primera compilación exitosa

---

## Comandos de compilación

```bash
cd "/home/fabian/src/investigacion rapa nui/informe-impacto-social-ambiental-indigena"
pdflatex informe-impacto.tex
bibtex informe-impacto
pdflatex informe-impacto.tex
pdflatex informe-impacto.tex
```
