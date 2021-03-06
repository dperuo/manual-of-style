# Stuart P. Bentley Manual of Style

These are all things I do (or at least try to do) in my writing. The second person here (ie. "you") refers to the writer (which, as this is my personal manual of style, refers to me), though the reader is invited to try following this style themselves, so long as their motivation isn't just to impersonate me for the purposes of stylometric analysis (which, I mean, you *could* do, but I just *explicitly recognized it as something I'd expect someone to do*, so I've kind of got some deniability on that, *especially* if you mess up on something I *didn't* explicitly describe here).

The first person (ie. "I") is used here to refer to myself in the context of softer reasoning, ie. rules that describe higher-level stylistic concerns (like word choice).

## Formatting

Use plaintext formats with Markdown notation wherever possible. Where there's no way to avoid a rich-text interface (ie. when submissions must be submitted via Google Docs), use the native formatting facilities, as fastidiously and sparingly as possible.

Use asterisks ("*") for italics, except in environments where asterisks do *not* translate to italics (eg. Slack).

When natural syntax becomes *completely* unreadable to describe a complex construction (like a quote to contain an *example of quoted punctuation*), fall back to backtick-quoted `code` constructions (as would normally be used to encapsulate non-English syntax).

## Referring to punctuation and letters

In technical writing, where there is lack of consensus around a character's name (or other characters are included in a construct that includes such an ambiguous character, like `"." and ","`), refer to the character as a quoted string, ie. "." (instead of "period", "full stop", or "dot").

In prose, these are the incredibly boring names I use for each character in a vacuum:

- <code>`</code>: backtick
- `~`: tilde
- `!`: exclamation point
- `@`: at-sign
- `#`: hash (*not* "hashtag", hashtag refers to the construct of a hash *followed by a tag* thank you very much)
- `$`: dollar sign
- `%`: percent sign
- `^`: caret
- `&`: ampersand
- `*`: asterisk
- `(`: open parenthesis
- `)`: close parenthesis
- `[`: open square bracket
- `]`: close square bracket
- `{`: open curly brace
- `}`: close curly brace
- `<`: left angle
- `>`: right angle
- `-`: hyphen ([not a dash][dash], as I used to call it)
- `_`: underscore
- `=`: equals sign
- `+`: plus
- `'`: single quote
- `"`: double quote
- `|`: vertical bar
- `/`: slash (I don't specify "forward" slash because [getting this backwards](https://xkcd.com/727/) is like thinking "R" and "N" are written "Я" and "И")
- `\`: backslash
- `?`: question mark
- `:`: colon
- `;`: semicolon
- `,`: comma
- `.`: period

[dash]: https://en.wikipedia.org/wiki/Dash

Amidst other characters, I use "dot" for `.` and "apostrophe" for `'`.

## Whitespace and Punctuation

[There is only one space after a period.][Bill Hill] There is no space before an exclamation point or question mark. Slashes separating alternative clauses are surrounded by spaces; slashes used in the sense of a "compound word" (where the words around the slash are being used to describe something that is neither one nor the other) are placed directly next to the words in question, without spaces.

[Bill Hill]: https://channel9.msdn.com/Blogs/TheChannel9Team/Bill-Hill-There-is-only-one-space-after-a-period

In lieu of a proper [dash][], I use hyphens surrounded by spaces - like this - to offset parenthetical statements, or to separate dashed clauses - like this.

## Extended characters

Use ASCII-range characters such as `"`, `'`, and `...` instead of smarter Unicode variants (like the ELLIPSIS character or left/right-facing quotes), except in non-plaintext environments where doing so requires additional work, or in character-count-constrained environments like Twitter when needing to fit "..." into one character.

## Emphasis

Use *italics* (`<em>`) for emphasis *within a statement*. Use *bold* (`<strong>`) for emphasis *of a statement or substatement within a larger body of text*.

## Date notation

Use [ISO 8601](https://xkcd.com/1179/). It's unambiguous, it's standardized, and it collates correctly in lexical order. It's basically perfect.

## Referring to decades

Don't use apostrophes to refer to a span of years (eg. "1980s" instead of "1980's"). An apostrophe should only be used for the posessive of a singular year (eg. "2000's Bush v. Gore").

Always fully-qualify a year or decade by including its century (ie. "1920s" instead of "'20s"). At time of writing (early 2018), we're about two years out from a bunch of legacy writing on the excesses of "the twenties" becoming really ambiguous. This also makes it slightly easier to describe the span of years between 2000 and 2010 ("the noughties", as I call them).

## Emoji

Use `:smile:`. It reads more descriptively (especially to accessibility technologies), will be replaced with 😄 in environments like GitHub, and [doesn't have issues when nested in parentheses](https://xkcd.com/541/).

## Punctuating parenthetical statements and quotations

Place punctuation that is not part of the parenthesized statement / quotation outside of the parentheses or quotes. Place punctuation that *is* part of the parenthesized statement / quotation *within* parentheses or quotes. Omit punctuation in situations where the punctuation may be syntactically omitted, if the punctuation would otherwise be a duplicate of punctuation on the other side of the boundary (ie. `He said "This is confusing," followed by a pause and "this second clause".`).

Where the "X said" construct (ie. `Stuart said "Some copy-editor is going to be mad that I omitted that comma".`) can't be neatly avoided, don't place a comma before the quotation. (Since this defies a *lot* of convention, I generally avoid using such constructions like this, because it kind of draws attention to itself.)

## Nested quotes

Nest double quotes, so long as it's unambiguous based on whitespace boundaries (which it almost always is).

## Pronouns

Use singular "they" whenever there's any lack of consent/consensus around another pronoun (consensus here serving a soft indicator of subject consent).

## Parenthetical statements

Use "ie." where the phrase "that is" (or similar) could be used in spoken conversation. Use "eg." for examples (eg. this). Use "note" for notes (not "nb", which stands for "nota bene" and I've only ever seen one person use because it's only two fewer characters and completely opaque if you aren't already familiar with it).

Note that this means "ie." *may* be used to denote an example, if the example is being used *as a shorthand for the rule* (ie. the phrase "by which I mean" could precede it).

Commas *may* be used to separate a statement like "ie." or "eg." instead of parentheses when said statement is the last statement in the sentence, eg. this one. This should only be used when said final statement is *not an extricable part* of the sentence (ie. when it's not merely an elaboration or example, as this parenthetical statement is).

## Run-on sentences

**A sentence may be of any length without being considered a run-on sentence**, so long as all the clauses are properly subordinate. A sentence is only a run-on sentence if two statements can be separated into two sentences by replacing "," with ".".
