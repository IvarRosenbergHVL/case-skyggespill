# Skyggespill

**Status:** Arkitektur / pre-produksjon  
**Case engine:** CER 2.0 (`cer_v2_core`)  
**Arbeidsform:** truth-first, graph-first, document-later

`Skyggespill` er en moderne Etterforskerne-case med to koblede dødsfall, to gjerningspersoner og to spillfaser. Første drap kan løses korrekt i fase 1, mens fase 2 re-kontekstualiserer deler av fase-1-materialet uten å gjøre den første løsningen feil.

Repoet skal bygges CER v2-native. Spillerdokumenter skal **ikke** produseres før sannhets-, kunnskaps-, motiv-, objective-, evidence- og discovery-grafene er stabile nok til å bestå intern fair-play-gjennomgang.

## Designprinsipper

- Objective truth skilles fra actor knowledge/belief og player-provable knowledge.
- To incidents modelleres separat, men med eksplisitte causal/knowledge bridges.
- Fase 1 skal gi en reell og tilfredsstillende løsning på drap 1.
- Fase 2 skal ikke være en retcon; eldre artifacts får ny betydning uten å endres.
- Minst flere sentrale deductions skal kreve visuell observasjon, fysisk sammenligning eller spatial/timeline-rekonstruksjon, ikke bare lesing.
- Visuelle spor er evidens, ikke dekorasjon.
- Ingen enkelt fil skal løse identity + method + motive + concealment alene.
- Realistisk provenance og knowledge access skal modelleres før dokumentproduksjon.
- Russland/etterretning er en reell del av sannheten, men skal ikke bli en altforklarende konspirasjon.
- Murder mystery-kjernen skal være sterkere enn spionthriller-laget.

## Foreløpig struktur

```text
architecture/
  case-intent.yaml
  case-design-plan.yaml
  open-decisions.yaml

graphs/
  truth-graph.yaml
  actor-knowledge-graph.yaml
  motive-graph.yaml
  objective-graph.yaml
  hypothesis-graph.yaml
  discovery-graph.yaml
  recontextualization-graph.yaml

incidents/
  incident-01-ingrid.yaml
  incident-02-martin.yaml

characters/
  characters.yaml

evidence/
  evidence-strategy.yaml
  visual-evidence-plan.yaml

documents/
  README.md
```

## Produksjonsgate

Før første player-facing dokument produseres skal minst følgende være avklart:

1. begge incident-sannheter og causal order
2. begge gjerningspersoners fullstendige motive chains
3. hvordan Martin vet at Hovdens motivforklaring er falsk/ufullstendig
4. hva Ingrid konkret oppdaget om Morozov-relasjonen
5. hva Martin faktisk finner som utløser drap 2
6. hvem som vet hva, og når
7. minst én komplett fair inference path per required solution claim
8. planlagte recontextualizations mellom fase 1 og fase 2
9. visuelle discovery moments og nødvendig redundans
10. provenance for alt sentralt bevismateriale

## Viktig

Navn, partinavn, enkelte motiver og metoder er foreløpige arkitektbeslutninger og er ikke låst før de er eksplisitt markert som `locked` i Case Design Plan.
