# Tailwind CSS Cheat Sheet (Bahasa Indonesia)

Panduan referensi cepat untuk utilitas Tailwind CSS yang paling sering digunakan.

---

## 1. Tata Letak (Layout)

| Fitur | Class | Deskripsi |
|------|-------|-----------|
| Container | `container` | Mengatur lebar maksimal sesuai breakpoint. |
| Display | `block`, `inline-block`, `flex`, `grid`, `hidden` | Mengatur tipe tampilan elemen. |
| Position | `static`, `fixed`, `absolute`, `relative`, `sticky` | Mengatur posisi elemen. |
| Z-Index | `z-0`, `z-10`, `z-50`, `z-auto` | Mengatur tumpukan elemen (layering). |
| Overflow | `overflow-auto`, `overflow-hidden`, `overflow-scroll` | Mengatur konten yang meluap dari wadah. |

---

## 2. Flexbox & Grid

### Flexbox
- `flex` — Mengaktifkan container flex
- `flex-row`, `flex-col` — Arah flex
- `justify-start`, `justify-center`, `justify-between` — Perataan sumbu utama
- `items-start`, `items-center`, `items-end` — Perataan sumbu silang
- `flex-wrap`, `flex-nowrap` — Membungkus elemen flex
- `grow`, `grow-0` — Kontrol pertumbuhan elemen

### Grid
- `grid` — Mengaktifkan container grid
- `grid-cols-1` sampai `grid-cols-12` — Jumlah kolom
- `col-span-1` sampai `col-span-full` — Rentang kolom elemen
- `gap-1`, `gap-4`, `gap-8` — Jarak antar baris/kolom

---

## 3. Spasi (Spacing)

> Gunakan angka: 1 unit = 0.25rem (4px)

| Tipe | Prefix | Contoh |
|------|--------|--------|
| Padding | `p-` | `p-4`, `px-2` |
| Margin | `m-` | `m-auto`, `-mt-4` |
| Space Between | `space-x-` | `space-x-4` |

---

## 4. Tipografi (Typography)

- **Font Size**: `text-xs`, `text-base`, `text-xl` sampai `text-9xl`
- **Font Weight**: `font-light`, `font-normal`, `font-medium`, `font-bold`
- **Alignment**: `text-left`, `text-center`, `text-right`, `text-justify`
- **Color**: `text-blue-500`, `text-gray-900`, `text-opacity-50`
- **Decoration**: `underline`, `italic`, `uppercase`, `capitalize`

---

## 5. Latar Belakang & Border

- **Background**: `bg-white`, `bg-blue-500`, `bg-gradient-to-r`, `from-indigo-500`, `to-purple-500`
- **Radius**: `rounded-none`, `rounded-md`, `rounded-lg`, `rounded-full`
- **Border**: `border`, `border-2`, `border-gray-300`, `border-dashed`
- **Shadow**: `shadow-sm`, `shadow-md`, `shadow-xl`, `shadow-inner`

---

## 6. Efek & Interaktivitas

- **Opacity**: `opacity-0` sampai `opacity-100`
- **Cursor**: `cursor-pointer`, `cursor-not-allowed`
- **Transition**: `transition-all`, `duration-300`, `ease-in-out`
- **Transform**: `scale-110`, `rotate-45`, `translate-x-2`

---

## 7. Filter

- `blur-none`, `blur-sm`, `blur-md`, `blur-lg`
- `brightness-50`, `brightness-100`, `brightness-150`
- `contrast-50`, `contrast-125`
- `grayscale`, `grayscale-0`

---

## 8. Animasi

- `animate-none`
- `animate-spin`
- `animate-ping`
- `animate-pulse`
- `animate-bounce`

---

## 9. SVG Styling

- `fill-current`
- `stroke-current`
- `stroke-1`, `stroke-2`

---

## 10. Directives & Functions

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
