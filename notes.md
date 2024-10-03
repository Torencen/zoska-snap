Timotej Vanko, 4.C, 2. skupina

instalacia  next.js prikaz:

npx create-next-app@latest

nastavenia next.js:

What is your project named? my-app
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like your code inside a `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to use Turbopack for `next dev`?  No / Yes
Would you like to customize the import alias (`@/*` by default)? No / Yes
What import alias would you like configured? @/*

instalacia Material UI:

npm install @mui/material @emotion/react @emotion/styled

spustenie npm v developer mode:

npm run dev

prave tlacitko na src alebo app mozeme pridat folder alebo subor

app = router

rezervovane nazvy suborov:
page.tsx – hlavny subor programu
layout.tsx
not-found.tsx

vypisovanie textu na hlavnu stranku:
export default function TermsConditions() {  -   zadanie nazvu
return (
<Typography> Podmienky pouzivania tohto webu </Typography>     -    text co chceme vypisat
);
}
github – je to localhost ktory nam umozni hotovy projekt dat do sveta. Koncovku ma .git

prikazy k githubu :
get init – vytvori priecinok
get branch -m main
git config –global user.name „name“
git config –global user.email „email“
git remote add origin https://github.com/Torencen/zoska-snap.git
kontrola na predosly prikaz
git remote -v
git add .
Cez source control pridavanie commitu, nasledne sync changes.
Pridat extension ako gitlens, gitpull a prettier code
