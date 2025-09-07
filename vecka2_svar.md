# Vecka 2 – Svar
## 1. Vattenfall vs Agilt

**Vattenfall:** Linjär process (krav → design → kod → test → drift). Bra när kraven är fasta.  
**Agilt:** Iterativt i sprintar, feedback tidigt. Bra när kraven kan ändras.  

## 2. Git-commit och scenario

Ett **commit** är som en sparpunkt i projektets historia.  
Det visar vad som ändrats, av vem och varför.  

**Varför viktigt:**  
- Man kan backa om något går fel.  
- Man kan se historiken och förstå varför ändringar gjordes.  
- Lättare att hitta var en bugg kom in.

**Scenario:**  
Jag råkar ta bort en regel i en .NET-modell. Några dagar senare upptäcks en bugg.  
Med commit-historiken ser jag exakt vilken commit som orsakade felet och kan fixa det snabbt.

## 3. Samarbete i GitHub

- **Branch:** En egen arbetsgren där jag kan jobba utan att påverka `main`.  
- **Pull Request (PR):** Ett förslag att föra in min branch i `main`. Här kan man granska kod och köra tester.  
- **Merge:** När PR:en godkänns slås ändringarna ihop med `main`.

Det gör samarbetet säkert, eftersom flera utvecklare kan jobba parallellt utan att skriva över varandras kod.
