# Gentium Incantation

The Gentium font extended with cantillation marks for the
[Community Chanting Book][1] (Buddhist Pali Chanting).

- *Portability between people.* Copying or editing marks is not
  dependent on whether this font is installed.
- *Readability.* The marks are not interfering with the Pali accents.
- *Portability between software.* Using Unicode codepoints avoids corruption of the text
  when passed around between different software.

Copy list:

    ꜒ ꜓ ꜕ ꜖
    ā ī ū ṃ ṅ ñ ṭ ḍ ṇ ḷ
    Ā Ī Ū Ṃ Ṅ Ñ Ṭ Ḍ Ṇ Ḷ

Copy-paste the letters or use keyboard mappings. When using the
Gentium Incantation font, you will see the marks as arrow
shapes. Without the font (in email, text editors, or here on Github)
the marks will simply display as the default bar shapes.

Using the above letters and marks chanting texts can be opened, copied and edited
even when this font is missing, or can't be applied (copying in email,
or missing fonts on other people's computers).

Without the font, the marks will simply show up as the default bar shapes.

## Unicode codepoints

The marks are implemented in the Unicode range for
[Modifier Tone Letters][2], using the codepoints for 'Left-stem tone
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

## Ligatures

- [x] `i.cDown`, [x] `i.cUp`, [ ] `i.cLongDown`, [ ] `i.cLongUp`,
- [x] `ī.cDown`, [x] `ī.cUp`, [ ] `ī.cLongDown`, [ ] `ī.cLongUp`,
- [x] `m.cDown`, [ ] `m.cUp`, [ ] `m.cLongDown`, [ ] `m.cLongUp`,
- [x] `M.cDown`, [ ] `M.cUp`, [ ] `M.cLongDown`, [ ] `M.cLongUp`,

## Sylistic Set 02

Decorative forms

- `bracketleft.ss02`
- `bracketright.ss02`

[1]: https://github.com/profound-labs/community-chanting-book

[2]: https://en.wikipedia.org/wiki/Modifier_Tone_Letters_(Unicode_block)

