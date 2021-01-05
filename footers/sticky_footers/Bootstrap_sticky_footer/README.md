bootstrap megoldás sticky footer-re:

hasonló az absolute position megoldáshoz, de itt nem kell wrapper dive-et alkalmazni, mert a html elemet használja pozicionált konténerként.
itt is fix magasságűú foooter kell! annyi alsó margin-t állítunk a body-nak amilyen magasra szeretnénk a footer-t.

html {
  min-height: %;
  position: relative;
}

body {
  margin-bottom: 50px;
}

.footer {
  position: absolute;
  width: 100%;
  bottom: 0;
  height: 50px;
}