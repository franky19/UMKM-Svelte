<script lang="ts">
    import { Col, Row } from 'sveltestrap';
// import FavoritCard from '../Card/favoritCard.svelte';
import RekomendasiCard from '../Card/rekomendasiCard.svelte';
import UnitUsahaCard from '../Card/UnitUsahaCard.svelte';

    let src = 'https://bisnismuda.id/assets/content/20200809011323000000crowdfunding.png';
	let name = 'crowdfundingLogo';
  </script>
 
 
<Row class="mt-5">
    <Col xs="12" md="8">
      <h4>unit usaha</h4>
      <h5>berikut adalah beberapa unit usaha yang membutuhkan dana dan penjelasan singkat mengenai usaha tersebut</h5>
        <UnitUsahaCard/>
    </Col>
    <Col xs="12" md="3">
        <h4>rekomendasi untuk anda</h4>
        <RekomendasiCard/>
    </Col>
</Row>
