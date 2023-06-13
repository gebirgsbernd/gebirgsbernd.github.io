# gebirgsbernd.github.io
My personal website / portfolio
With Jekyll and Github - Hurray ...

Weil ich nur alle zwei Monate was an der Seite mache, vergesse ich immer zwischendurch die einfachsten Sachen.

Lokalen Server starten:
<pre><code>
jekyll serve
</code></pre>


Nach stoppen des lokalen Servers *vor* dem Einchecken 
<pre><code>
jekyll cleanup 
</code></pre>


Beispiel : Ein einzelnes Bild in eine Seite einbinden:
<pre><code>
![Yuneeko](/assets/yuneeko/15.jpg){: .center-image }
</code></pre>

Bild als Link
<pre><code>
[![Alt text for broken image link](/assets/logo.png)](https://example.com)
</code></pre>


JEKYLL Neu Installieren - schaust du hier:
https://jekyllrb.com/docs/installation/macos/

Fehlt in der Doc:
Nach update auf RUBY 3.0 fehlt was, was bei 2.6 noch dabei war. 
Manuell nachinstallieren  gem install webrick


Und nur einmal im Jahr muss ich einen neuen Rechner einrichten und das REPO NEU ZIEHEN

git clone https://github.com/gebirgsbernd/gebirgsbernd.github.io.git
