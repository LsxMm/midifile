---
layout: default
title: C++ library for parsing Standard MIDI Files
---

<h2> Downloading and Installing </h2>

Download the zip or tar file from the buttons at the top of the page
and unpack and type <tt>make</tt> in the base directory of the midifile 
package.  Or if you use git, download on the terminal with these commands:

``` bash
git pull https://github.com/craigsapp/midifile
cd midifile
make
```

<!-- TUTORIAL LIST ------------------------------------------------- -->

<details open>
<summary style="outline:none;">
   <span style="font-weight:600; font-size:130%;"><a href="tutorial">Tutorials</a></span>
</summary>

{% include tutorial/tutoriallist.html %}

</details>

<!-- CLASS LIST ---------------------------------------------------- -->

<details open>
<summary style="outline:none;">
   <span style="font-weight:600; font-size:130%;"><a href="class">Class documentation</a></span>
</summary>

<script>
window.addEventListener('load', function(event) {
   var list = document.querySelectorAll('a');
   for (var i=0; i<list.length; i++) {
      var attrib = list[i].getAttribute('href');
      if (attrib.match(/^Binasc/)) {
         list[i].setAttribute('href', 'class/' + attrib);
      } else if (attrib.match(/^Options/)) {
         list[i].setAttribute('href', 'class/' + attrib);
      } else if (attrib.match(/^MidiMessage/)) {
         list[i].setAttribute('href', 'class/' + attrib);
      } else if (attrib.match(/^MidiEvent/)) {
         list[i].setAttribute('href', 'class/' + attrib);
      } else if (attrib.match(/^MidiEventList/)) {
         list[i].setAttribute('href', 'class/' + attrib);
      } else if (attrib.match(/^MidiFile/)) {
         list[i].setAttribute('href', 'class/' + attrib);
      }
   }
});
</script>

{% include class/classlist.html %}

</details>
