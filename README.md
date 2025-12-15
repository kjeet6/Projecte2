
Aquest README està pensat perquè **vosaltres dos sapigueu sempre què fer i què NO fer**.

Pots **copiar-enganxar tal qual** a un fitxer `README.md` a l’arrel del projecte.

---

````md
# Projecte2 – Unity (Treball en equip)

Projecte Unity desenvolupat en equip utilitzant **Git i GitHub** per treballar de forma sincronitzada sense passar fitxers.

Aquest README està pensat perquè qualsevol dels membres sàpiga:
- com començar
- com treballar cada dia
- què NO s’ha de fer per no trencar el projecte

---

## 👥 Membres de l’equip
- Karan Jeet Singh
- Marc Fàbregas

---

## 🛠️ Requisits
- Unity Hub instal·lat
- La mateixa versió de Unity (important)
- Git instal·lat
- Accés al repositori de GitHub

---

## 🚀 Com començar (primer cop)

### 1️⃣ Clonar el repositori
NO crear un projecte Unity nou.

```bash
git clone git@github.com:kjeet6/Projecte2.git
````

### 2️⃣ Obrir el projecte a Unity

* Obrir **Unity Hub**
* Clicar **Add**
* Seleccionar la carpeta clonada
* Unity generarà automàticament les carpetes que falten (`Library`, etc.)

---

## 🔁 Flux de treball diari (molt important)

### Abans de començar a treballar

Sempre fer:

```bash
git pull
```

Això evita conflictes.

---

### Després de fer canvis

```bash
git add .
git commit -m "Descripció clara del que s’ha fet"
git push
```

Exemples de bons missatges:

* `Add player movement`
* `Fix collision with obstacles`
* `Add main menu UI`

---

## ⚠️ Normes importants (llegir sí o sí)

### ❌ NO fer

* ❌ No tocar la mateixa escena (`.unity`) alhora
* ❌ No esborrar fitxers si no n’estàs segur
* ❌ No treballar sense fer `git pull` abans
* ❌ No pujar carpetes com `Library/`, `Logs/`, `UserSettings/`

### ✅ Sí fer

* ✅ Repartir escenes (ex: menú / joc / UI)
* ✅ Commits petits i freqüents
* ✅ Avisar l’altre abans de tocar una escena important

---

## 🧠 Recomanacions per Unity + Git

* Asset Serialization: **Force Text**
* Version Control: **Visible Meta Files**

(Unity → Edit → Project Settings → Editor)

Això redueix molt els conflictes.

---

## 🆘 Si hi ha problemes

1. Para
2. No facis més commits
3. Parla amb l’altre membre
4. Si cal, revisa l’historial amb:

```bash
git log --oneline
```






