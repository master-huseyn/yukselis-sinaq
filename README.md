# Yukselis Deploy

Bu qovluq `GitHub Pages` ve `Netlify` ucun hazirlanmis statik sayt paketidir.

## Fayllar

- `index.html` - esas sayt
- `404.html` - GitHub Pages ucun yonlendirme fayli
- `netlify.toml` - Netlify konfiqurasiyasi
- `_redirects` - Netlify yonlendirmesi
- `.nojekyll` - GitHub Pages-in Jekyll emalinin sondurulmesi

## GitHub Pages

1. Bu qovluqdaki fayllari yeni GitHub reposuna yukleyin.
2. GitHub-da `Settings -> Pages` bolmesine daxil olun.
3. `Deploy from a branch` secin.
4. Branch olaraq `main`, qovluq olaraq `/ (root)` secin.
5. Bir nece deqiqeden sonra size link verecek.

## Netlify

1. Netlify-da `Add new site -> Import an existing project` secin.
2. GitHub reposunu baglayin.
3. `Base directory` bos qala biler.
4. `Publish directory` avtomatik olaraq `.` isleyir.
5. Deploy edin.

## Qeyd

- Sayt tek HTML faylidir ve server teleb etmir.
- `localStorage` istifade etdiyine gore her istifadecinin neticesi oz cihazinda ayrica saxlanacaq.
- Telefonda ve kompda brauzerle linkden acmaq daha rahat olacaq, fayl kimi gondermekden daha yaxsidir.
