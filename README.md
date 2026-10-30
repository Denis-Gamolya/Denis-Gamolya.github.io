# Denis Gamolya — Portfolio

Personal portfolio of game programming, systems design, and development tools.

Published at https://denis-gamolya.github.io/ using GitHub Pages from the root
of the main branch. The site is plain HTML/CSS, with local fonts, icons, images,
and screenshots. There is no build step or JavaScript dependency.

## Content flow

```text
Profile sidebar                 Projects
  Email / LinkedIn / GitHub      Ultrawide Toggle -> Download / GitHub
                                  Retcon -> Play game / GitHub
                                Other projects
                                  Celeste Gameplay Viewer / Twine / Unity -> GitHub
```

Edit index.html to update copy and links. Assets live in assets/ and use
relative paths. The Ultrawide Toggle screenshot comes from its repository.
Its full aspect ratio is preserved so the original-frame overlay remains visible.
Private project repositories will become accessible when their owner makes
them public; this site does not change repository visibility.

Inter font: https://fonts.google.com/specimen/Inter (SIL Open Font License).
Bootstrap Icons: https://github.com/twbs/icons (MIT).


Project descriptions are based on each project's README. Ultrawide Toggle's
install button links to https://gamebanana.com/mods/733482, resolved from its
README's install link. The custom character skin in the screenshot is not
included with the mod. Retcon retains its existing Netlify play URL.


Retcon's voting screenshot is supplied by Denis and stored unchanged in
assets/retcon-voting.png. Its full frame is preserved; select the image to see
it at full size. Both featured images use matching 16:9 presentation frames with object-fit:
contain. Each screenshot is shown in full, with neutral letterboxing where
its native aspect differs; selecting either image opens its full-size file.


The public site offers an Email link rather than a downloadable resume.
Resume PDFs are excluded from this repository.


Other projects have short, regular-text captions. The Gameplay Viewer caption
was supplied by Denis; Twine and Unity summaries are grounded in their repository source:
Twine_Detective_Game/Twine_Detective.html and Assets/PlayerMovement.cs,
Assets/PlayerRespawn.cs, Assets/CameraControl.cs, respectively. No new features are claimed.
