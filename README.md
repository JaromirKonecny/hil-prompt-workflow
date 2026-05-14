> **English speakers:** This repository documents a Human-in-the-Loop 
> multi-model workflow for iteratively developing production-grade 
> prompts and workflows. Content is in German.

# HIL-PROMPT

**A Human-in-the-Loop Workflow for Developing Complex Prompts & Workflows**

Ein strukturierter Workflow, der rohe Ideen über mehrere 
Modell-Rollen (PromptPolierer → Hauptarchitekt → externer Auditor) 
in produktionsreife Artefakte überführt — mit menschlicher 
Kontrolle in jeder Phase.

![HIL-PROMPT Workflow](diagramme/hil_prompt_workflow.png)

## Was ist das?
Der Workflow ist auf Claude Code zugeschnitten, aber die Methode 
(Multi-Model-Iteration, Diff-only, Cross-Audit) ist auf jedes 
LLM-gestützte Coding-Tool übertragbar.

HIL-PROMPT formalisiert den Prozess, mit dem komplexe Prompts, 
CLAUDE.md-Dateien und Coding-Workflows iterativ entwickelt, 
auditiert und finalisiert werden. Der Workflow ist die 
Vorbereitungsphase für Agentic Coding mit Claude Code.

## Für wen?

- Studierende und Lehrende, die systematisch mit LLMs arbeiten wollen
- Entwickler, die Claude Code produktiv einsetzen
- Alle, die Prompts nicht „aus dem Bauch" schreiben wollen

## Schnellüberblick: 6 Phasen

| Phase | Was passiert |
|---|---|
| **P0** | Rohinput per Diktat oder Eintippen |
| **P1** | PromptPolierer strukturiert, HIL prüft |
| **P2** | Hauptarchitekt + HIL: Entwurf → Iteration |
| **P3** | Cross-Audit durch anderes Modell |
| **P4** | Finalisierung + Live-Test |
| **P5** | Übergabe in den Workspace |

## Von HIL-PROMPT zu Agentic Coding

> **Vibe Coding ohne HIL-PROMPT & Kontrolle = Glücksspiel.**  
> **Vibe Coding mit HIL-PROMPT & Kontrolle = Agentic Coding.**

![Agentic Coding Workflow](diagramme/agentic_coding_workflow.png)

## Inhalt

| Datei | Beschreibung |
|---|---|
| [HIL-PROMPT-Workflow.md](HIL-PROMPT-Workflow.md) | Vollständige Anleitung |
| [diagramme/](diagramme/) | Workflow-Diagramme |

## Autor

Prof. Dr. Jaromir Konecny & Claude Opus 4.6 — Mai 2026

## Lizenz

CC BY 4.0 — Namensnennung erforderlich.
