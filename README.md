# Gentium Incantation

The Gentium font extended with cantillation marks for the
[Community Chanting Book][chanting-book] (Buddhist Pali Chanting).

This font adds arrow-shaped cantillation marks:

![cantillation marks][marks]

[marks]: http://profound-labs.github.io/gentium-incantation-font/img/yo-so-bhagava.png

Without the font (but typing the correct Unicode letters) the marks simply show up as the default bar shapes:

    [Yo so] bha꜕gavā a꜕rahaṃ sammāsambuddho
    Svākkhā꜓to yena bha꜕gava꜓tā dhammo

- **Portability between people.** Copying or editing marks is not
  dependent on whether this font is installed.
- **Readability.** The marks are not interfering with the Pali accents.
- **Portability between software.** Using Unicode codepoints avoids corruption of the text
  when passed around between different software.

Copy list:

    up: ꜓ down: ꜕ up long: ꜒ down long: ꜖
    
    ā ī ū ṃ ṅ ñ ṭ ḍ ṇ ḷ
    Ā Ī Ū Ṃ Ṅ Ñ Ṭ Ḍ Ṇ Ḷ

Copy-paste the letters or use keyboard mappings. When using the
Gentium Incantation font, you will see the marks as arrow
shapes. Without the font (in email, text editors, or here on Github)
the marks will simply display as the default bar shapes.

Using the above letters and marks chanting texts can be opened, copied and edited
even when this font is missing, or can't be applied (copying in email,
or missing fonts on other people's computers).

## Unicode codepoints

The marks are implemented in the Unicode range for
[Modifier Tone Letters][tone-letters], using the codepoints for 'Left-stem tone
letters'.

- `U+A712`, `꜒` Long High Tone
- `U+A713`, `꜓` High Tone
- `U+A714`, `꜔` Mid Tone (not used here)
- `U+A715`, `꜕` Low Tone
- `U+A716`, `꜖` Long Low Tone

We are using arrow shapes that are above or below the letters, instead
of the default vertical bar shapes.

We don't use the mid-tone mark (`U+A714`, `꜔`) and so this shape is
left unchanged.

## Sylistic Set 02

Decorative forms

- `bracketleft.ss02`
- `bracketright.ss02`

[chanting-book]: https://github.com/profound-labs/community-chanting-book

[tone-letters]: https://en.wikipedia.org/wiki/Modifier_Tone_Letters_(Unicode_block)

