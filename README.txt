SLASH

Indieweb-style static pages for krisyotam.com. Each subdirectory
is a standalone page served by nginx at its own route.


PAGES

  appearances/    Public appearances and events
  bio/            Bio page
  blank/          Blank page
  bio/            Bio page
  emails/         Email addresses
  elsewhere/      Profiles and presence elsewhere on the web
  nope/           Things I don't do
  orders/         Restaurant and store orders
  pfp/            Profile pictures
  playlist/       Music playlist
  slides/         Slide decks
  verify/         Identity verification
  wba/            Web boycott list with per-company breakdowns
  wish/           Wish list
  yep/            Things I do


STRUCTURE

Each page is a self-contained directory with an index.html and
optional style.css. The root index.html and style.css serve as the
slash pages index.


DEPLOY

Each directory maps to a route on krisyotam.com. Nginx serves them
directly as static files. Only the changed subdirectory needs to be
synced on update.


CONTRIBUTING

No external contributions accepted.


LICENSE

Private. All rights reserved.
