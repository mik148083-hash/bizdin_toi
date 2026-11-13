# Адилет & Акбермет — үйлөнүү тоюна чакыруу

Бул папка GitHub Pages аркылуу жарыялоого даярдалган сайтты жана жалпы каалоо-тилектер үчүн Supabase SQL схемасын камтыйт.

## Файлдар
- `index.html` — чакыруу сайты.
- `supabase-schema.sql` — бардык коноктор бирдей көрө турган каалоо-тилектер базасын түзүүчү SQL.
- `SETUP_KY.md` — кыргызча орнотуу кадамдары.
- `.nojekyll` — GitHub Pages Jekyll иштетүүсүн өткөрүп жиберет.
- `_config.yml` — GitHub Pages үчүн минималдуу конфигурация.

## Жарыялоо
Бардык алты файлды GitHub репозиторийинин `main` бутагынын root (`/`) бөлүгүнө жүктөңүз. GitHub → Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

**Эскертүү:** жалпы онлайн каалоолор иштеши үчүн Supabase долбоорун түзүп, `index.html` ичиндеги `SUPABASE_URL` жана `SUPABASE_ANON_KEY` бош маанилерине өзүңүздүн Project URL жана anon/public key коюңуз. `service_role` ачкычын эч качан сайтка салбаңыз.
