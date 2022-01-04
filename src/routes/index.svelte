<script>
	import { fade } from 'svelte/transition';
	let visible = true;

</script>

<div class="imgbox">
	<img src="arkaplan2.jpg" alt="" class="containera">
	
	
    
</div>



<div class="">
	<div class="one">
		<h2>Biz Kimiz?</h2>
		<p class="parg">Yüksek kalitede hızlı hizmet sunmayı ilke edinmiş bir firma olarak, müşteri memnuniyet garantisi ile işe alım danışmanlık hizmeti veriyor ve biz buna Workforce İnsan Kaynakları Garantisi diyoruz.

Her firmanın beklentilerinin farklı olduğu bilinci ile firmanızın kurum kültürünü, aradığını yetkinlikleri doğru analiz ederek tecrübeli işe alım ekibimiz adaylar ile yetkinlik bazlı mülakatlar yapıyor, stratejik iş hedeflerinize en uygun adayları size sunuyoruz.

İşe alım ve seçme yerleştirme süreçlerindeki en hassas noktanın iletişim olduğunun bilinci ile hareket ediyoruz.

Başarımızın kilit noktası; 17 yıllık bilgi birikimimiz, tecrübeli işe alım ekibimiz ile iş ortaklarımızın ve adaylarımızın beklentilerini doğru analiz etmemizden ve firmaları uzun süreli iş ortağımız olarak görmemizden geçiyor.

İyi iletişim, güven ve süreklilik ilkelerinden yola çıkarak iş ortaklarımıza şirketlerine katkı sağlayacak adayları yönlendirirken, adaylarımızı da hayalindeki iş fırsatına sahip olmasını sağlıyoruz.

En büyük maliyetin zaman olduğunun bilinci ile beklentilerinizi karşılayacak ve kurum kültürünüze uygun adayları bulmak için hızlı hareket ederek doğru adayları headhunt yaparak ilerliyoruz.

Bugüne kadar imza attığımız başarı hikayeleri ile İş ortaklarımızın işe alım süreçlerinde bizi sürekli tercih etmelerinin gururu ile işimizi severek yapıyoruz.</p>
	</div>
	
	<div class="two">
		<h2>Çalışma Prensiplerimiz</h2>
		<p class="parg">İşe alım sürecinde iş ortağının ihtiyaçlarını tespit etmek amacıyla doğru soruları sorarak gerekli önerilerde bulunuruz.

İş ilanına başvuru beklemeden headhunt yaparak ilerleriz ve ihtiyacınız olan yetenekle işe alım sürecinizi yönetiriz. İddialıyız en başarılı headhunter işe alım danışmanlık firmasıyız.

İşe alım sürecinin aday mülakatları, referans araştırması ve iş teklifi dahil olmak üzere tüm operasyon süreçlerinizde hizmet vermekteyiz. İş ortağımızın talebi ve ihtiyacı doğrultusunda dil testi, kişilik envanteri çözümleri üretmekteyiz.

İş ortağımız ve adaylarımızın tüm bilgileri bizde gizliliğini korumaktadır. İş ortağımızın sözlü veya yazılı onayı olmadan referans olarak göstermemekteyiz.

Birlikte çalıştığımız iş ortaklarımızın personellerini kendi aday havuzumuza dahil etmeyiz.

En iyi bildiğimiz iş olan işe alım, seçme yerleştirme ve insan kaynakları yönetim hizmetlerini iyi iletişim ile yapar iş ortağımıza her aşamada en hızlı şekilde sözlü ve yazılı bilgi akışı sağlarız.</p>
	</div>
	<div class="three">
		<h2>Değerlerimiz, İlkelerimiz</h2>
		<p class="parg">İş ortaklarımız ve adaylarımız ile büyüyeceğimizi bilir, iş ortaklarımız ve adaylarımız ile aynı pencereden bakarız.

İş ortaklarımız ve adaylarımızın nokta atışı olmasından gurur duyarız.

Sonuç ve çözüm odaklı yaklaşımımız, iyi iletişim ve ilişkilerimiz ile müşteri memnuniyeti ve güvene dayalı sürekli işbirliği sağlarız.</p>
	</div>

</div>




<style>
	h2 {
		font-size: 100%;
	}
	.parg {
		margin:17px;
		font-family: Verdana, Geneva, Tahoma, sans-serif;
	}
	

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





.container {
  width: 80%;
  height: 200px;
  background: aqua;
  margin: auto;
  padding: 10px;
}

			.one {
                float:left; 
				background-color: red;
                width:33%;
                
            }
            .two{
                float:left; 
                background-color: red;
                width:33%;
                
            }
            .three{
                float:right;
                background-color: red;
                width:34%;
                
            }

</style>