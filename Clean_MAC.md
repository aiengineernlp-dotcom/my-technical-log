228Go de disque, 99% utilisé. Il te reste **109Mo seulement**.

Next.js seul pèse ~300Mo. C'est impossible d'installer quoi que ce soit.

**Avant tout code, tu dois libérer de l'espace.** C'est ta mission maintenant — pas moi qui peux faire ça à ta place (Règle 9).

Pistes à explorer sur ton Mac :
- La Corbeille (vider)
- `~/Downloads/` (souvent énorme)
- Applications inutilisées
- `~/Library/Caches/` (cache système)

Lance ça pour voir les plus gros dossiers :

```bash
du -sh ~/* 2>/dev/null | sort -rh | head -20
```

Objectif : libérer au moins **5Go** avant de revenir.

Dis-moi quand c'est fait.


Lance ça pour voir les plus gros dossiers :

Montre-moi l'espace disponible maintenant.

```bash
df -h /
```