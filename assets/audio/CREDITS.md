# Звуки

Все записи — Creative Commons 0 (общественное достояние): можно использовать в коммерческой игре без указания авторства. Авторы указаны из уважения.

| Файл | Источник | Автор | Обработка |
|---|---|---|---|
| alt/rain_archway.ogg | [Rain at night under house archway](https://freesound.org/people/felix.blume/sounds/709870/) | felix.blume | петля 120 с, crossfade 5 с, −24 LUFS |
| alt/rain_window.ogg | [ambience, light rain, from the window, town](https://freesound.org/people/AlexanderChe/sounds/706604/) | AlexanderChe | петля 120 с |
| alt/rain_puddles.ogg | [Rain in puddle mud on ground](https://freesound.org/people/felix.blume/sounds/673946/) | felix.blume | петля 100 с |
| (не используется) rain_porch.ogg | [rain med porch 2nd floor](https://freesound.org/people/kyles/sounds/51812/) | kyles | петля 120 с |
| alt/rain_courtyard_old.ogg | [AMB_M_City_Rain_Courtyard](https://freesound.org/people/conleec/sounds/171982/) | conleec | петля 58 с |
| yard_autumn.ogg | [russia autumn residential yard traffic](https://freesound.org/people/KEDR_SFX/sounds/326652/) | KEDR_SFX | петля 140 с, crossfade 5 с, −24 LUFS |

Петли собираются скриптом `tools/make_loop.py` из превью Freesound (`tools/freesound_fetch.py`).
Для релиза лучше скачать оригиналы WAV (нужен аккаунт Freesound) и пересобрать петли из них.

Сравнить варианты на слух: `npm run dev` → http://localhost:5199/tools/sounds.html

| steps_wet.ogg (+ .json) | [walking small street wet asphalt](https://freesound.org/people/Rico_Casazza/sounds/539556/) | Rico_Casazza (CC0) | 7 отдельных шагов (4, 5, 8 убраны автором; полный набор — art-inbox/music/steps_wet_10), `tools/slice_steps.py` |
| alt/steps_wet_alt.ogg | [Walking on wet asphalt](https://freesound.org/people/SpinOpel/sounds/835102/) | SpinOpel (CC0) | 9 шагов |

## Музыка
| music_main.ogg | «loop fon» — автор игры | основной слой, 256 с, петля |
| music_layer2.ogg | «loop fon 2» — автор игры | второй слой, 64 с, вступает на втором объекте, тише |
| music_menu.ogg | «menu» — автор игры | музыка меню, 112 с, петля (громкость выровнена под игровую) |

| rain_main.ogg | «copyright free rain sounds» — Dragon Studio (Pixabay, 331497) | петля 240 с, crossfade 6 с, −24,6 LUFS (как прежний дождь) |
| music_tree.ogg | «567567» — автор игры | 32 с, петля; звучит у дерева за гаражом, громкость от расстояния, в такт с основной |
