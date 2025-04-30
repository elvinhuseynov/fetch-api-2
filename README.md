Layihə strukturu

- index.html – <div id="app"> 

- styles.css – əsas layout və kart üslubları

- main.ts – bütün loqikanın TypeScript giriş faylı

Tapşırıq

Səhifə yüklənən kimi https://pokeapi.co/api/v2/pokemon?limit=50 ünvanına GET sorğusu göndərin

Ad siyahısını göstərin

#app içində bir <ul> yaradın

Hər Pokémon üçün <li> elementində adını göstərən mətni və “Details” düyməsini əlavə edin

Ətraflı məlumatları göstərin

“Details” düyməsi klikləndikdə, həmin Pokémon-un url-indən tam məlumatları gətirin

Siyahının altında göstəriləcək:

Sprite (sprites.front_default)

Tiplər (types.map(t => t.type.name))

Boy və çəki

Yalnız document.createElement və appendChild metodlarından istifadə edin

- Canlı axtarış əlavə edin

Siyahının üstündə bir <input> yaradın

Hər input hadisəsində siyahıdakı <li> elementlərini axtarış sorğusuna uyğun filtrələyin

- Yüklənmə və xəta mesajları

Hər sorğu zamanı “Loading…” bildirimi göstərin

Əgər sorğu uğursuz olarsa, səhifədə oxunaqlı bir xəta mesajı yerləşdirin

