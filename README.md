# Скоростноты (SpeedSheets RU)

Русскоязычная адаптация веб-приложения **SpeedSheets** для обучения чтению нот с листа.

👉 **[Открыть тренажёр в браузере](https://dragonfuckingborn.github.io/SpeedSheets_RussianLanguage/)**

## О проекте
Этот проект представляет собой интерактивный тренажер для развития навыков чтения нот с листа. Оригинальный проект был создан автором [bohemian-miser](https://github.com/bohemian-miser/SpeedSheets).

В данном форке был полностью переведен пользовательский интерфейс на русский язык, адаптированы музыкальные термины (гаммы, октавы, режимы), а также исправлена логика работы некоторых элементов для корректного отображения кириллицы.

## Особенности
- Полностью русскоязычный интерфейс.
- Режимы тренировки: слова, случайные ноты, гаммы, прогон A-G и другие.
- Встроенный метроном и звуковое сопровождение.
- Статистика ошибок и интервальное повторение (SRS).
- Генерация ссылок для обмена результатами.

## Благодарности
Огромная благодарность автору оригинального проекта за создание такого полезного инструмента.

---

# SpeedSheets

SpeedSheets is a highly interactive, feature-rich web application to teach sheet music reading. It supports a Grand Staff, virtual keyboard, multiple game modes, spaced repetition (SRS), audio feedback, and cryptographically shareable scores and recordings!

Play it live here: **[https://bohemian-miser.github.io/SpeedSheets/](https://bohemian-miser.github.io/SpeedSheets/)**

## Features

- **Endless Scrolling Grand Staff:** Read continuous notes on the treble and bass clefs.
- **Focus Range Brackets:** Visually constrain notes to a specific set of lines and spaces using draggable bracket handles on the left.
- **Violin Stats Heatmap:** Easily spot your visual weak points with a smooth red/green visualizer highlighting the exact staff lines you miss most often.
- **Spaced Repetition (Training Mode):** A smart algorithm feeds you your weakest notes.
- **Time Trials & Speed Runs:** Compete against the clock or race to 100 notes as fast as possible.
- **Audio Feedback & Keyboard Shortcuts:** Realistic audio context playback, plus rebindable keyboard modifiers for octave shifts and accidentals.
- **Cryptographic Share Links:** Share your scores securely. A SHA-256 validation prevents URL tampering and slaps a "FAKED" stamp on manipulated results!

## Practice Mode (Shareable Recordings)

You can share tiny URLs containing encoded melodies that your friends can play through in "Practice Mode"! To do this, simply use the `?practice=` URL parameter.

The encoding format is incredibly simple:
- **`a-g`** : Play a standard note.
- **`j`** : Shift down one octave.
- **`k`** : Shift up one octave.
- **`;`** : Make the *next* note a sharp (♯).
- **`l`** : Make the *next* note a flat (♭).
- **`+`** : Stack notes into a chord (e.g. `c+e+g`).

### Example Songs

Click any of these links to instantly load the song into Practice Mode! We've categorized them so you can practice your sight-reading with melodies you already know.

#### Pop & Rock
**Seven Nation Army - The White Stripes** (Features Octave Drops)
[https://bohemian-miser.github.io/SpeedSheets/?practice=eegedcjbkeegecdcjba](https://bohemian-miser.github.io/SpeedSheets/?practice=eegedcjbkeegecdcjba)

**Never Gonna Give You Up - Rick Astley** (Chorus)
[https://bohemian-miser.github.io/SpeedSheets/?practice=cdfddggfcdfdfefcdfdkcjbf](https://bohemian-miser.github.io/SpeedSheets/?practice=cdfddggfcdfdfefcdfdkcjbf)

**All Star - Smash Mouth** (Chorus - Features Sharps)
[https://bohemian-miser.github.io/SpeedSheets/?practice=gkdjbbaaggkcjbaaggg;f;fedde](https://bohemian-miser.github.io/SpeedSheets/?practice=gkdjbbaaggkcjbaaggg;f;fedde)

**Take On Me - A-ha** (Chorus - Features Sharps)
[https://bohemian-miser.github.io/SpeedSheets/?practice=;fga;fga;fedde;fga](https://bohemian-miser.github.io/SpeedSheets/?practice=;fga;fga;fedde;fga)

#### Movies & Games
**Star Wars (Main Theme) - John Williams** (Features Octave Jumps)
[https://bohemian-miser.github.io/SpeedSheets/?practice=gggkcgfedkcjgfedkcjgfefd](https://bohemian-miser.github.io/SpeedSheets/?practice=gggkcgfedkcjgfedkcjgfefd)

**Super Mario Bros. (Overworld Theme) - Koji Kondo**
[https://bohemian-miser.github.io/SpeedSheets/?practice=keeecegjgkcjgeablbag](https://bohemian-miser.github.io/SpeedSheets/?practice=keeecegjgkcjgeablbag)

**Tetris Theme (Korobeiniki)**
[https://bohemian-miser.github.io/SpeedSheets/?practice=kejbkcdcgbaakcedcjbbkcdecjaa](https://bohemian-miser.github.io/SpeedSheets/?practice=kejbkcdcgbaakcedcjbbkcdecjaa)

**Megalovania (Undertale) - Toby Fox** (Features Flats)
[https://bohemian-miser.github.io/SpeedSheets/?practice=ddkdjlagfdfgcckdjlagfdfg](https://bohemian-miser.github.io/SpeedSheets/?practice=ddkdjlagfdfgcckdjlagfdfg)

**Hedwig's Theme (Harry Potter) - John Williams** (Features Sharps)
[https://bohemian-miser.github.io/SpeedSheets/?practice=bkeg;febak;f](https://bohemian-miser.github.io/SpeedSheets/?practice=bkeg;febak;f)

**He's a Pirate (Pirates of the Caribbean)**
[https://bohemian-miser.github.io/SpeedSheets/?practice=gkcccdeeeefgggagffeddc](https://bohemian-miser.github.io/SpeedSheets/?practice=gkcccdeeeefgggagffeddc)

#### Classical & Traditional
**Für Elise - Beethoven** (Features Sharps)
[https://bohemian-miser.github.io/SpeedSheets/?practice=ke;de;dejbkdcja](https://bohemian-miser.github.io/SpeedSheets/?practice=ke;de;dejbkdcja)

**Ode to Joy - Beethoven**
[https://bohemian-miser.github.io/SpeedSheets/?practice=eefggfedccdeeddeefggfedccdedcc](https://bohemian-miser.github.io/SpeedSheets/?practice=eefggfedccdeeddeefggfedccdedcc)

**Happy Birthday** (G Major - Includes Octave Shifts and Sharps!)
*Notice the `k` to jump up to the high D, the `j` to come back down, and the `;f` to play an F#.*
[https://bohemian-miser.github.io/SpeedSheets/?practice=ddedg;fddedagddkdjbg;fekccjbgag](https://bohemian-miser.github.io/SpeedSheets/?practice=ddedg;fddedagddkdjbg;fekccjbgag)

**Joy to the World** (D Major - Descending Scale with Sharps)
[https://bohemian-miser.github.io/SpeedSheets/?practice=kd;cjbbag;fed](https://bohemian-miser.github.io/SpeedSheets/?practice=kd;cjbbag;fed)

**Mary Had a Little Lamb** (Simple C Major)
[https://bohemian-miser.github.io/SpeedSheets/?practice=edcdeeedddeggedcdeeeeddedc](https://bohemian-miser.github.io/SpeedSheets/?practice=edcdeeedddeggedcdeeeeddedc)

**Twinkle Twinkle Little Star**
[https://bohemian-miser.github.io/SpeedSheets/?practice=ccggaagffeeddcggffeedggffeedccggaagffeeddc](https://bohemian-miser.github.io/SpeedSheets/?practice=ccggaagffeeddcggffeedggffeedccggaagffeeddc)

---

## Local Development

SpeedSheets is a monolithic `index.html` application. There is no build step required! Simply open `index.html` in any modern web browser to start playing. Tailwind CSS is loaded via CDN, and all logic is self-contained. 

To clear your local save data, click the "Clear Stats" button below the virtual keyboard.
