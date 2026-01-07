# Návod na spuštění

1. V Supabase vytvoř tabulku `gifts` s těmito sloupci:
   - `id` (integer, auto increment, primary key)
   - `nazev` (text)
   - `rezervovano` (boolean, default false)
   - `rezervoval_jmeno` (text, může být prázdné)

2. Získej URL a public API key svého Supabase projektu.

3. Otevři soubor `index.html` ve složce `dary` a nahraď hodnoty `SUPABASE_URL` a `SUPABASE_KEY` svými údaji.

4. Přidej do tabulky pár dárků (ručně přes Supabase webové rozhraní).

5. Otevři `index.html` v prohlížeči. Web funguje bez backendu, vše běží v prohlížeči.

6. Pro nasazení nahraj soubory na GitHub Pages nebo jinam.

Hotovo!