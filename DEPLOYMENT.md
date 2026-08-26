# GitHub Pages Deployment Guide für MK Autoaufbereitung

## Schnelle Lösung - Website Live stellen

### Option 1: Mit Vercel (EMPFOHLEN - am einfachsten)

1. Gehe zu: https://vercel.com
2. Klicke "Sign Up" → "Continue with GitHub"
3. Melde dich mit deinem GitHub-Account an
4. Vercel fragt: "Which Git Repository would you like to import?"
5. Suche nach: `mk-autoaufbereitung`
6. Klicke "Import"
7. Vercel deployt automatisch
8. Du bekommst eine URL wie: `mk-autoaufbereitung.vercel.app`

**Fertig! Deine Website ist live!** 🎉

---

### Option 2: Mit Netlify

1. Gehe zu: https://app.netlify.com
2. Klicke "Sign up" → "Sign up with GitHub"
3. Autorisiere Netlify auf GitHub
4. Klicke "New site from Git"
5. Wähle: `mkautoaufbereitungsservice-dotcom/mk-autoaufbereitung`
6. Übernimm die Standard-Einstellungen
7. Klicke "Deploy site"

**Deine Website ist unter einer URL wie `mk-autoaufbereitung-XXX.netlify.app` erreichbar** 🚀

---

### Option 3: GitHub Pages (manuell)

1. Gehe zu: https://github.com/mkautoaufbereitungsservice-dotcom/mk-autoaufbereitung/settings
2. Klick auf "Pages" (links im Menü)
3. Unter "Source" wähle: **"Deploy from a branch"**
4. Wähle Branch: **main**
5. Wähle Folder: **/ (root)**
6. Klick "Save"
7. Warte 2-3 Minuten
8. Die Website ist erreichbar unter: `https://mkautoaufbereitungsservice-dotcom.github.io/mk-autoaufbereitung/`

---

## Welche Option ist am besten?

| Option | Vorteile | Nachteile |
|--------|----------|----------|
| **Vercel** | ✅ Superschnell, kostenlos, einfachste Setup | ❌ Neue Plattform |
| **Netlify** | ✅ Kostenlos, einfach, zuverlässig | ❌ Etwas langsamer |
| **GitHub Pages** | ✅ Kostenlos, alles auf GitHub | ❌ Manchmal Caching-Probleme |

**EMPFEHLUNG: Vercel verwenden!** Ist am schnellsten und einfachsten.

---

## Problembehebung

**Wenn die Website noch immer nicht sichtbar ist:**

1. Cache leeren: `Ctrl+Shift+Del` (oder `Cmd+Shift+Del` auf Mac)
2. Inkognito-Fenster öffnen und URL eingeben
3. Nach 5 Minuten nochmal versuchen (Deployment kann Zeit brauchen)
4. GitHub Pages Settings nochmal überprüfen

---

## Weitere Hilfe

- Website anpassen: Öffne `index.html` und bearbeite die Preise/Texte
- Neue Dateien hochladen: Push zu GitHub main branch
- Domain hinzufügen: In Vercel/Netlify Settings unter "Domains"

**Viel Erfolg! 🚀**
