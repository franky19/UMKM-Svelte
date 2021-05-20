<script>
 import Nav from '../../Component/Nav/Nav.svelte'
 import Carousel from '../../Component/Carousel/Carousel.svelte'
 import { Container } from 'sveltestrap';
import IkhtiarUsaha from '../../Component/IkhtiarUsaha/IkhtiarUsaha.svelte';
import UnitUsahaCard from '../../Component/IkhtiarUsaha/UnitUsahaList.svelte';
// import FavoritList from '../../Component/IkhtiarUsaha/FavoritList.svelte';
</script>


<Container fluid>
  <Carousel />
  <IkhtiarUsaha/>
  <UnitUsahaCard/>
  <!-- <FavoritList/> -->
</Container>

