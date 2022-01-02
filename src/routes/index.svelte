<script>
	import { fade } from 'svelte/transition';
	let visible = true;

</script>
<div class="imgbox">
	<img src="man.jpeg" alt="" class="containera">
	
	<div class="bll">
		<h1 class="bl">En Büyük</h1>
		<h1 class="bl">Maliyet Zamandır...</h1>
		
		<h1 class="bls">Doğru Personel Yerleştirmeşi ile Firmanıza Zaman Kazandırmak İçin Varız</h1>

	</div>
    
</div>

{#if visible}
	<p transition:fade>
		Fades in and out
	</p>
{/if}


<style>

    .containera {
        
        
  
  text-align: center;
  
  
  height: 100%;
  width: 100%;
  
}

	.agu {
		transition: opacity 2s;
    -webkit-transition: opacity 2s; /* Safari */
	}


	.bll  {
		
		
		position: absolute;
	top: 44%;
	
	left: 16px;
	

}


	@keyframes fadein {
		from { opacity: 0; }
		to   { opacity: 1; }
	}
	@-webkit-keyframes fadein {
    from { opacity: 0; }
    to   { opacity: 1; }
}

	.bl {
	

    -webkit-animation: fadein 2s; /* Safari, Chrome and Opera > 12.1 */
       -moz-animation: fadein 2s; /* Firefox < 16 */
        -ms-animation: fadein 2s; /* Internet Explorer */
         -o-animation: fadein 2s; /* Opera < 12.1 */
            animation: fadein 2s;
	

	font-family: sans-serif;
	color: white;
	font-size: 100%;
	margin-left: 100px;
	
	-webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: black;
	}	
	.bls {
	

    -webkit-animation: fadein 50s; /* Safari, Chrome and Opera > 12.1 */
       -moz-animation: fadein 30s; /* Firefox < 16 */
        -ms-animation: fadein 30s; /* Internet Explorer */
         -o-animation: fadein 30s; /* Opera < 12.1 */
            animation: fadein 5s;
	

	font-family: sans-serif;
	margin-left: 100px;
	color: white;
	font-size: 100%;
	-webkit-text-stroke-width: 1px;
    -webkit-text-stroke-color: black;
	}	


</style>