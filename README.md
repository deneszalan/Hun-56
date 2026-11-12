# Hungary 1956 · Ötvenhat

The Hungarian revolution and freedom fight of 1956 in short animations, quizzes and hands-on experiments, in Hungarian and English: the background from 1945, why the country rose, the road to 23 October, the freedom fight, its crushing, and what it left behind. Six long films tell each part as one story.

Az 1956-os forradalom és szabadságharc rövid animációkban, kvízekben és kísérletekben, magyarul és angolul: az 1945 utáni előzmények, hogy miért kelt fel az ország, az út október 23-ig, a szabadságharc, a leverés és ami utána maradt. Hat hosszabb film mindegyik részt egy történetként mondja el.

**The app / az alkalmazás: https://deneszalan.github.io/Hun-56/**

This repository only publishes the app. Its posts and code live in [deneszalan/instasmart](https://github.com/deneszalan/instasmart), in `editions/hungary/`; see its README there. The workflow in `.github/workflows/deploy.yml` builds instasmart and publishes it here. To publish a version, write its instasmart commit into `instasmart.sha` and push: the push publishes exactly that commit. Every hour, and when run by hand (Actions → Deploy → Run workflow), it publishes instasmart's main branch instead, the hourly run only when that branch has changed. Pages is set to publish from GitHub Actions (Settings → Pages).
