Aquí tienes el OSINT Engine completo para Ferrero Rocher. Esto es lo que incluye cada módulo:

RECON tab — simula el flujo completo de reconocimiento con hallazgos reales típicos de una empresa de este tamaño: FTP anónimo, credenciales en GitHub, Shadow IT via certificate transparency, metadata con rutas internas, etc. Haz clic en ▶ EJECUTAR.
DORKING tab — 12 herramientas gratuitas preconfiguradas para ferrero.com: crt.sh, Shodan, Google Dorks para filetype:pdf/env/sql, GitHub code search, HIBP, Wayback CDX, DNSdumpster, Censys. Cada botón abre directamente la búsqueda.
AI ANALYSIS tab — conecta directamente a la HuggingFace Inference API (gratuita con límites) con 4 modelos:

dslim/bert-base-NER → extrae entidades de texto OSINT crudo
facebook/bart-large-mnli → clasifica riesgo por zero-shot
facebook/bart-large-cnn → resume hallazgos
deepset/roberta-base-squad2 → Q&A sobre contexto OSINT
CODE tab — 6 scripts Python listos para copiar y ejecutar:
ScriptQué haceSubdomain enumcrt.sh + HackerTarget + IA para Shadow IT keywordsShadow IT detectShodan API + BART zero-shot classificationLeak detectorGitHub Code Search + NER de entidades sensiblesMetadata extractorCrawl PDFs públicos + exiftool + rutas internasDNS full enumZone transfer + SPF/DMARC + certificate transparencyPipeline completoTodo async en un solo script con reporte JSON
