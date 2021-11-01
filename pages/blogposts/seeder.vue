<template>
  <div class="container">
   <nuxt-link class="backLink" to="/"><div>← BACK</div></nuxt-link>
    <Headline
      headline="Seeder DJ Set"
      showLine="true"
      date="31. Juli 2021"
    />
    <br />
    <Paragraph
      content="Frieder und Simon. Mannheims hottest DJ Duo, Mannheims cutest DJ Duo. Zwei der Persönlichkeiten hinter dem legendären Peer23, den Kulturtragflächen und dem Bündnis Kulturschaffender Mannheim."
    />
    <YouTubePlayer test="sPMrr-dznho" />
    <Paragraph
      content='In Mannheim gibt es kaum Menschen, die so viel für die Kunst- und Kulturszene geben, wie das Kollektiv hinter dem Peer23. Frieder und Simon gehören somit zu jenen Persönlichkeiten Mannheims, die fast ihre gesamte Freizeit damit verbringen Mannheims Kunst- und Kulturszene fairer, nachhaltiger und schöner für alle Beteiligten zu gestalten - wenn sie keine Musik machen. Kurz gesagt: Ohne sie hätte Mannheim lang nicht so viel zu bieten!'
    />
        <Paragraph
      content='Die beiden legen aber nicht nur auf und schmeißen nebenher diverse wertvolle Kulturinitiativen, sie produzieren auch ihre eigene Musik. Somit nicht einfach nur DJs, sondern richtige Musiker!'
    />
  
    <Picture
      src="https://i.postimg.cc/tJtS1dfB/Bildschirmfoto-2021-11-01-um-00-15-07.jpg"
      alt="Eine Luftaufnahme der Party"
      description="Riccardo Prevete"
    />
      <Paragraph
      content="Ihr Sound findet sich in szenischem Minimal House, der richtig viel Spaß macht. Eines der legendärsten Sets der beiden Peer Boys gab es auf auf dem Nachtwandel an der Haltestelle Rheinstraße. Über 300 Leute außer Rand und Band und die Seeder Jungs, wie immer, am grinsen. Ein Moment den sie bewiesenermaßen mit Leichtigkeit reproduzieren können."
    />
    <Paragraph
      content='Am 31.07.2021 haben Seeder für uns auf der Pia23 im Peer23 x Pingr Release Party minimalistische House Grooves gespielt, die perfekt zur gechillten Atmosphäre gepasst haben. Schwer dabei die Füße stillzuhalten, wie man später im Video sieht!'
    />
    <Paragraph
      content='Wenn man die Persönlichkeiten der Jungs in Stichpunkten beschreiben müsste, könnte man das folgendermaßen: achtsam, aufmerksam, locker, zuvorkommend, einfach durch und durch sympathisch! Eigenschaften, die Frieder und Simon richtig cool machen!'
    />
    <Picture
      src="https://i.postimg.cc/MK8WkstQ/Gruppe-1.jpg"
      alt="Ein Bild von Frieder und Simon"
      description="Natascha Shanaja"
    />
    <Paragraph
      content="Zeitgenossen mit denen man sicher regelmäßig Partynächte verbringen möchte, denn sie sind garantiert voll mit positiver Energie - und das spiegelt sich in ihrer Musik wieder."
    />
    <Profile
      image="https://i.postimg.cc/zXsKvqQ3/82131877-1038892489802950-7581758682178781184-n.jpg"
      artistAlias="Seeder"
      :genres="['Rominimal', 'Minimal House', 'Micro House']"
      instagram="https://www.instagram.com/seeder_68/"
      facebook="https://www.facebook.com/seederofficial/"
      soundcloud="https://soundcloud.com/seeder_official"
    />
    <Headline headline="Download Pingr" showLine="true" />
    <Platforms />
    <Headline headline="Follow us" />
    <Footer />
   <nuxt-link to="/"><div>← BACK</div></nuxt-link>
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
