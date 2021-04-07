# Vefforritun 2, 2021, verkefni 5

[Kynning á verkefni](https://youtu.be/EyRD1dVVDiU).

## Routing

Setja skal upp og nota react router.

Yfirlit er á `/` og birtir alla flokka frá vefþjónustu.

Á `/:id` eru birtar fréttir fyrir þann flokk. Ef flokkur er ekki til er `404` síða sýnd (einfaldlega síða sem segir að síðan sé ekki til.) Setja skal `Til baka` link sem viðheldur stöðu, þ.e.a.s. notar `<Link>` úr react router.

Ef reynt er að skoða aðrar slóðir er `404` síða sýnd.

## Gögn

[RÚV RSS API proxy](https://github.com/vefforritun/vef2-2021-ruv-rss-json-proxy) veitir aðgang að nýjustu fréttum frá RÚV. Tólið er sett upp á `https://vef2-2021-ruv-rss-json-proxy.herokuapp.com/`.

Af handahófi er það lengi að skila niðurstöðum og/eða skilar villum. Gera skal ráð fyrir því með því að útfæra loading og error state fyrir componenta.

Nota skal `REACT_APP_API_URL` til að sækja slóð á vefþjónustu, sjá `.env.example`.

## Síður

Yfirlitssíða birtir flokka ásamt fimm nýjustu fréttum og link á fréttasíðu.

Fréttasíða birtir allar fréttir í flokk.

## Útlit

[Sjá útlit](./utlit).

Setja skal upp Sass og útfæra útlit per component í Sass skrá fyrir hann.

Ekki þarf að birta nákvæmlega eins útlit, en það skal í grunninn vera eins:

* Yfirlitssíða með fimm kassa með titli og fimm fréttum hver, linkur til að sjá allar
* Fréttasíða með titli, öllum fréttum og link til baka

## Tæki og tól

Gefinn er grunnur, með uppbyggingu á verkefni, byggt á `create-react-app`. Ekki ætti að þurfa að búa til fleiri componenta en það er leyfilegt. Ekki þarf að útbúa _container_ component, en það er leyfilegt.

## Mat

* 30% – Gögn sótt á vefþjónustu
* 20% – React router sett upp og routing skv. lýsingu
* 20% – Yfirlits- og fréttasíða uppsett
* 20% – Útlit og viðmót
* 10% – Verkefni sett upp á Heroku, engar linting villur og almennt snyrtilegur kóði

## Sett fyrir

Verkefni sett fyrir í fyrirlestri fimmtudaginn 11. mars 2021.

## Skil

Skila skal í Canvas í seinasta lagi fyrir lok dags laugardaginn 27. mars 2021.

Skilaboð skulu innihalda slóð á Heroku og slóð á GitHub repo fyrir verkefni, og dæmatímakennurum skal hafa verið boðið í repo ([sjá leiðbeiningar](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-user-account/inviting-collaborators-to-a-personal-repository)). Notendanöfn þeirra eru:

* `jonnigs`
* `mimiqkz`
* `Steinalicious`
* `zurgur`

Hver dagur eftir skil dregur verkefni niður um 10%, allt að 20% ef skilað mánudaginn 29. mars 2021 en þá lokar fyrir skil.

## Einkunn

Sett verða fyrir 6 minni verkefni þar sem 5 bestu gilda 8% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

---

> Útgáfa 0.1


| Útgáfa | Breyting |
|--------|----------|
| 0.1    | Fyrsta útgáfa |
