# Hissa qo'shish qoidalari

Bu qoidalar `dtwinuz` org'idagi barcha repolarga tegishli. Repoda o'z `CONTRIBUTING.md` fayli bo'lsa, o'sha fayl ustun turadi.

## Ish tartibi

1. **Issue** — katta o'zgarishni boshlashdan oldin issue oching yoki mavjudini oling.
2. **Branch** — `main` dan oching: `feat/<qisqa-nom>`, `fix/<qisqa-nom>`, `docs/...`, `chore/...`.
3. **Commit** — [Conventional Commits](https://www.conventionalcommits.org/) uslubida:
   `feat: ...`, `fix: ...`, `docs: ...`, `refactor: ...`, `test: ...`, `chore: ...`, `ci: ...`
4. **PR** — `main` ga. Shablonni to'ldiring, issue'ni `Closes #N` bilan bog'lang.
5. **Review** — kamida bitta maintainer tasdig'i kerak. CI yashil bo'lishi shart.
6. **Merge** — squash merge. Merge'dan keyin branch avtomatik o'chiriladi.

## Kod sifati

- Yangi xatti-harakat uchun test yozing, xato tuzatilganda esa regressiya testi qo'shing.
- Secret, token, `.env` va shaxsiy ma'lumotlarni hech qachon commit qilmang. Push protection ularni bloklaydi.
- PR kichik va bitta maqsadga qaratilgan bo'lsin.

## Relizlar

Versiyalar [SemVer](https://semver.org/) bo'yicha: `git tag vX.Y.Z && git push origin vX.Y.Z`.
Teg qo'yilganda CI image'ni yig'adi va Release yaratadi.

## Muloqot

Savollar uchun [SUPPORT](SUPPORT.md) faylini ko'ring. Xulq-atvor qoidalari: [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md).
