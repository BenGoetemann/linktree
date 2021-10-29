<template>
  <div class="container">
    <nuxt-link class="backLink" to="../"><div>← BACK</div></nuxt-link>
    <Headline
      headline="Paul Gerlinger Live"
      showLine="true"
      date="23. Juli 2021"
    />
    <br />
    <Paragraph
      content="Es gibt Künstler, die bestechen mit einem durchgestylten Gesamtkonzept, mit
    schriller Überpräsenz, mit Songs, die eigentlich nur Vehikel für ein Image
    sind. Und dann gibt es Paul Gerlinger."
    />
    <YouTubePlayer test="E07NzAejzHw" />
    <Paragraph
      content='Die erste Reaktion auf seinen markanten Gesang ist oft: "Moment mal, der klingt doch wie …", und man kann es den Menschen nicht verdenken. Paul Gerlingers Stimme ist spröde und tief, da gibt es kein Entkommen. Der 25-jährige Songwriter aus Mannheim singt in "Kein Tag" den Satz "Ein Glas Wein und Zigaretten können jeden Abend retten", und ganz offensichtlich wurden so bereits einige Abende gerettet.'
    />
    <Paragraph
      content="Doch das ist seine Stimme - egal, mit wem man sie denn vergleichen möchte - und viel interessanter ist sowieso der Weg und die Umstände, die Gerlinger überhaupt zur Musik brachten."
    />
    <Paragraph
      content='Es gibt drei Männer, die Paul in Kindertagen künstlerisch geprägt haben: seine beiden Großväter und der Lyriker Eugen Roth. "Einer meiner Großväter hat mir schon früh Roths Gedichte näher gebracht, der andere ist ein gottgleicher Pianist. Auch der Rest meiner Familie ist sehr musik- und sprachaffin", erzählt er. Schon in der Grundschule beginnt er, Gedichte zu schreiben. Oft auch als Strafarbeit. Im selben Alter lernt er auch, das Klavier zu spielen, aber letztlich ist ihm das zu konservativ. Die Gedichte machen ihm mehr Spaß.'
    />
    <Picture
      src="https://i.postimg.cc/bYCYkM7m/216641699-1772227339627666-7380797441628910716-n.jpg"
      alt="Ein Bild von Paul Gerlinger"
      description="Lea Bräuer"
    />
    <Paragraph
      content='Und so widmet sich Paul erst mit 15 wieder der Musik: Er bringt sich das Gitarrenspielen selbst bei, seine ersten eigenen Songs entstehen erst gut fünf Jahre später. Er spielt in dieser Zeit gut 150 Konzerte, macht sich in der Region einen Namen. Beeindruckend wird das auch durch den Fakt, dass Paul Gerlinger "im echten Leben" Standortleiter eines Logistik-Unternehmens ist.'
    />
    <Paragraph
      content='"Nur wenn ich traurig bin, kann ich auch glücklich sein" - gesungen von einem Bachelor-Studenten klänge das vielleicht, zu neudeutsch, schnell cringe-worthy. Kann man das ernst nehmen? Aber aus Pauls Kehle gesungen klingt diese Zeile: Erlebt. Weil das echte Leben das mit einem machen kann.'
    />
    <Picture
      src="https://i.postimg.cc/XvHGnjyn/Bildschirmfoto-2021-10-28-um-15-26-02.webp"
      alt="Ein Bild von Paul Gerlinger"
      description="Riccardo Prevete"
    />
    <Paragraph
      content="Doch keine Angst, bei der omnipräsenten Melancholie in seiner Musik blitzt immer ein trockener, beinahe zynischer, Humor durch, der die Schwere verträglich macht."
    />
    <Paragraph
      content='2021 veröffentlicht Paul Gerlinger seine Debüt-EP "Gut Allein". Eine bewusst analoge Produktion, in der seine eindrückliche Stimme ein gemütliches Bett in den wunderschönen Arrangements aus Gitarre, Cello, Kontrabass, Piano, Violine und Posaune findet. Derart aufwendige, warme Produktionen sind im elektronisch geprägten Heute selten geworden und vor allem im Newcomer-Bereich eine echte Rarität. Am 05.03.2021 wurde die erste Single “Gut Allein” veröffentlicht. Ein Song, dem im aktuellen Zeitgeschehen nochmal mehr eine besondere Bedeutung bekommt. "Und du willst Zweisamkeit, doch ich bin zweifelsfrei Einsamkeit in Person - kein Vergleich: Du bist immer gut drauf, selten schlechte Gedanken Mich bringt alles ins Wanken und ich geh darin auf! Du bist gut im gemeinsam sein - Und ich? Ich war immer gut allein!"'
    />
    <Profile
      image="https://i.postimg.cc/MZQq4DXD/152791473-1671333816383686-1154438547629773065-n.jpg"
      artistAlias="Paul Gerlinger"
      :genres="['Singer/Songwriter', 'Indie', 'Blues']"
      spotify="https://open.spotify.com/artist/3Jh90nIsxexWk4CfSv8EBV?si=b-63HKPZT-OcMvQUeWuPyQ"
      youtube="https://www.youtube.com/channel/UCh1X_6H1KavKfko4gTY8hSA"
      instagram="https://www.instagram.com/paulgerlingermusik/"
      website="https://www.paulgerlinger.de/"
      facebook="https://www.facebook.com/paulgerlingermusik"
    />
    <Headline headline="Download Pingr" showLine="true" />
    <Platforms />
    <Headline headline="Follow us" />
    <Footer />
    <nuxt-link to="../"><div>← BACK</div></nuxt-link>
  </div>
</template>

<script>
import Platforms from "~/components/Platforms.vue";
export default {
  components: { Platforms },
};
</script>
<style>
.backLink {
  margin-top: 30px;
}
</style>
