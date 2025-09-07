# 📦 NPM Cheat Sheet for Web Developers

## 🔹 Project Setup
- `npm init` → Δημιουργεί αρχείο `package.json` για νέο project.

## 🔹 Install / Uninstall
- `npm install <package>` → Εγκατάσταση πακέτου (dependency).
- `npm install <package> --save-dev` → Εγκατάσταση πακέτου μόνο για ανάπτυξη (devDependency).
- `npm uninstall <package>` → Απεγκατάσταση πακέτου.
- `npm update` → Ενημέρωση όλων των εξαρτήσεων.

## 🔹 Scripts (package.json → "scripts")
- `npm run start` → Εκκίνηση development server.
- `npm run build` → Δημιουργία production build.
- `npm run lint` → Έλεγχος ποιότητας κώδικα (linting).
- `npm run <script>` → Εκτέλεση οποιουδήποτε custom script.

## 🔹 Useful Commands
- `npm install` → Εγκατάσταση όλων των εξαρτήσεων από το `package.json`.
- `npm outdated` → Έλεγχος για πακέτα που έχουν νεότερες εκδόσεις.
- `npm audit` → Έλεγχος για ευπάθειες ασφαλείας.
- `npm audit fix` → Αυτόματη διόρθωση ευπαθειών (όπου είναι δυνατό).

---

💡 **Tip:** To αρχείο `package-lock.json` κρατάει σταθερές τις εκδόσεις για να δουλεύει το ίδιο σε όλους τους developers.
