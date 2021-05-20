<script lang="ts">
    import { Col, Container, Row } from 'sveltestrap';
    import { Button } from 'sveltestrap';

    let src = 'https://bisnismuda.id/assets/content/20200809011323000000crowdfunding.png';
	let name = 'crowdfundingLogo';
  </script>

<!-- <div>
    <div>
        <img {src} alt="{name}" style="height: {'25%'};width:{'50%'}" >
    </div>
    <div class="d-flex justify-content-start">
        <button type="button">submit</button>
        <button type="button">reset</button>
    </div>
</div> -->

  <!-- <div>
        <div style="height: {'20%'}">
          
        </div>
        <div>
            gdgdjg
          </div>
  </div> -->
    <Row style="margin-top: {'25px'};">
        <Col xs="6">
           <img {src} alt="{name}" style="height: {'100%'};width:{'100%'}" >
        </Col>
        <Col xs="6" >
            <h1>Crowdfunding</h1>
            <h4>website ini akan menghubungkan
                pihak umkm dan pendana untuk 
                membantu pendanaan</h4>
                <div class="button-group">
                    <button type="button" class="col-xs-3">Ajukan Pendanaan</button>
                    <button type="button">Berikan Bantuan Pendanaan</button>
                </div>
        </Col>
    </Row>
  