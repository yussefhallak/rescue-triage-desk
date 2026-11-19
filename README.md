# Arca · Rescue Triage Desk

**AI-assisted flood rescue triage. Second place in the Reasoning Architecture category at the Open Agent Hackathon 2026.**

Arca was created by Yussef Omar Hallak, a Control and Automation Engineering student at UFSM. The project grew out of a problem exposed by the May 2024 floods in Rio Grande do Sul: rescue teams had to piece together calls for help from many channels while deciding which cases needed attention first.

**Watch Arca at work:** [Português](https://github.com/yussefhallak/arca/releases/download/v2.0/Arca_pt_16x9.mp4) · [English](https://github.com/yussefhallak/arca/releases/download/v2.0/Arca_en_16x9.mp4) · [Project overview and screenshots](https://github.com/yussefhallak/arca)

*Em português:* O Arca ajuda equipes de resgate a organizar pedidos de socorro, identificar quais casos precisam de atenção primeiro e pedir mais informações quando faltam dados. A decisão de enviar uma equipe é sempre humana.

## What Arca does

Arca helps dispatchers find locations in Portuguese-language rescue requests, assess urgency, and identify duplicate reports. It asks for missing information rather than guessing and can suggest ways to group and respond to cases. A person makes the final dispatch decision.

## Evaluation

In a 30-case evaluation with live model calls, Arca made 29 correct triage decisions in about 11 seconds per case on average. In a separate test on 100 previously unseen requests, 94 recommendations were rated safe. These were test scenarios, not operational rescues. Performance on real rescue traffic was not measured.

## What is public

This repository contains selected core triage agents, evaluation scripts and results, and synthetic examples. Some scripts depend on private modules and cannot run from this repository alone. The full pipeline, dispatch interface, fleet tools, integrations, map data, and development history remain private.
