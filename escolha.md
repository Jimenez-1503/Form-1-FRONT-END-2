**O QUE MUDOU:**

* **Instalação:** Bootstrap usa CDN direto; Tailwind exige Node.js, CLI e compilação via terminal.
* **Grid:** Bootstrap exige `row` + `col-*` (Flexbox 12 colunas); Tailwind aplica CSS Grid direto no elemento pai (`grid grid-cols-*`).
* **Nomenclatura:** Bootstrap usa classes semânticas (`bg-danger`); Tailwind usa classes descritivas e atômicas (`bg-red-600`).

**O QUE FICOU IGUAL:**

* **Estilização no HTML:** Ambos permitem criar telas completas usando utilitários direto nas tags, sem CSS próprio.
* **Classes Utilitárias:** Vários nomes de classes são idênticos (`p-4`, `text-white`, `shadow-sm`).
* **Responsividade:** Ambos adotam Mobile-First com prefixos para telas maiores (`md:`, `lg:`).