<script lang="ts">
    import { Col, Container, Row } from 'sveltestrap';
import FavoritCard from '../Card/favoritCard.svelte';

    let src = 'https://bisnismuda.id/assets/content/20200809011323000000crowdfunding.png';
	let name = 'crowdfundingLogo';
  </script>
 
 
<Container fluid class="mt-3">
    <h4>unit usaha favorit</h4>
    <FavoritCard/>
</Container>
