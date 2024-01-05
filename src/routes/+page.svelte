<div class="bg-black text-white h-full w-full">
	<header class="h-[70px] py-[24px] flex justify-center fixed w-full backdrop">
		<div class="container h-full flex flex-row justify-between w-[1240px]">
			<div class="flex flex-row gap-1">
				<div class="uppercase font-black text-[16px] text-neutral-200">Flyby aeroastro</div>
			</div>

			<div>
				<a href="#" class="py-[24px] px-[22px]">회사소개</a>
				<a href="#" class="py-[24px] px-[22px]">우주발사체</a>
				<a href="#" class="py-[24px] px-[22px]">함께하기</a>
				<a href="#" class="py-[24px] px-[22px]">후원문의</a>
				<a href="#" class="py-[24px] px-[22px]">투자문의</a>
				<a href="#" class="py-[24px] px-[22px]">소마만들기</a>
			</div>

			<div class="font-semibold">
				<a class="py-[24px] px-[22px]">예약</a>
			</div>
		</div>
	</header>
	<!-- <div class="h-48"></div> -->

	<section class="h-full w-full bg-black flex justify-center">
		<div class="container flex flex-col items-center w-[1240px] justify-center">
			<img src="logo.webp" class="w-32" />

			<h2 class="headline hero text-center text-[96px] font-semibold text-neutral-200">
				Our mission
			</h2>

			<h3 class="text-[28px] text-center mt-[6px] font-medium text-[#a1a1a6]">
				플라이바이 항공우주는 2023년에 설립된 민간 기업으로서,
				<br />
				연간 100회가 넘는 소형 위성 발사 서비스를 구축하는 것을 목표하고 있습니다.
				<br />
				고체 로켓, 하이브리드 로켓, 액체 로켓 등 다양한 추진 기술을 연구하고 있으며
				<br />
				재활용 기술의 핵심인 수직이착륙 기술과 메탄 연료를 사용하는 엔진을 개발할 것입니다.
			</h3>
		</div>
	</section>

	<section class="h-full w-full bg-black flex justify-center">
		<div class="container flex flex-col w-[1240px] justify-center">
			<div class="text-[80px] font-bold">500-n class hybrid rocket</div>
			<div class="mt-[0.6rem] text-[28px] font-medium text-[#a1a1a6]">
				500 N급 하이브리드 엔진은 파라핀 계열 연료를
				<br />
				테스트하기 위한 LAB-SCALE 엔진입니다.
				<br />
				파라핀 계열 연료는 타 연료에 비해 후퇴율(연료가
				<br />
				타들어가는 속도)이 3배 정도 높은 고효율 연료로서,
				<br />
				하이브리드 로켓 엔진의 새로운 연료로 주목받고 있습니다.
			</div>
			<div class="w-full flex flex-row items-end mt-12 -ml-12">
				<img class="w-[500px]" src="500-n_hybrid_front.png" />
				<img class="w-[500px] -mt-[56px]" src="500-n_hybrid_back.png" />
			</div>
		</div>
	</section>

	<section class="h-full w-full bg-black flex justify-center">
		<div class="container flex flex-row w-[1240px] justify-between items-center">
			<img class="h-[80%] w-full object-contain" src="hybrid_vtol_rocket.png" />

			<div>
				<div class="text-[96px] font-bold strong leading-tight">
					Hybrid
					<br />
					Vtol Rocket
				</div>
				<div class="mt-[2rem] w-[36rem] text-[28px] font-semibold text-[#cecece]">
					앞서 제작한 하이브리드 엔진을 바탕으로,
					<br />
					수직 이착륙 기술을 입증하기 위한 로켓을 제작할 것입니다.
					<br />
					<br />
					재활용 로켓에 필수적인 수직 이착륙을 실현하려면,
					<br />
					추력 조절이 용이한 엔진이 필요합니다.
					<br />
					<br />
					따라서 하이브리드 엔진이 간단하면서도
					<br />
					넓은 추력 조절 범위를 가지고 있어 적당하다고 판단했습니다.
					<br />
					<br />
					이러한 기술은 향후 액체로켓을 이용한 수직이착륙
					<br />
					발사체를 만드는 기반이 될 것입니다.
				</div>
			</div>
		</div>
	</section>

	<section class="h-full w-full bg-black flex justify-center">
		<div class="container flex flex-col w-[1240px] justify-center">
			<div class="text-[40px] font-semibold text-[#cecece]">Hybrid</div>
			<div class="text-[96px] font-semibold strong leading-none">
				Vertical Takeoff <br />& Landing
			</div>
			<div class="flex flex-row">
				<img class="w-[70%] object-contain mt-24" src="vertical_takeoff_and_landing.png" />
				<div class="mt-28 -ml-20 w-full text-[28px] font-semibold text-[#cecece]">
					5월 이후 추력 제어의 기술적 실증을 위해
					<br />

					재착륙 기체를 제작/실험할 것이며
					<br />
					<br />
					이는 한국에서 두번째로 시도하는
					<br />

					하이브리드 수직 이착륙입니다
				</div>
			</div>
		</div>
	</section>
</div>

<style>
	.backdrop {
		backdrop-filter: saturate(180%) blur(20px);
		-webkit-backdrop-filter: saturate(180%) blur(20px);
		background-color: rgba(0, 0, 0, 0.4);
		/* text-shadow: 0 0 25px rgba(0,0,0,1), 0 0 25px rgba(0,0,0,1); */
	}

	.hero {
		/* background: radial-gradient(#eff1ff, black); */
		background: radial-gradient(#f1f1f1, black);
		background-size: 100% 200%;
		background-position: 50% 100%;
		-webkit-background-clip: text;
		background-clip: text;
		-webkit-text-fill-color: transparent;
	}

	.strong {
		background-image: linear-gradient(180deg, #c9b8e5 0%, #a17ccf);
		/* background-image: linear-gradient(180deg, #ffb6ff 0%, #b344ff); */
		background-color: #ffb6ff;
		/* background-size: 100% 300%; */
		/* background-position: 50% 0; */
		-webkit-background-clip: text;
		background-clip: text;
		-webkit-text-fill-color: transparent;
	}

	.brilliant {
		color: transparent;
		-webkit-background-clip: text;
		background-clip: text;
		background-image: linear-gradient(180deg, #ffe993, #eb831c);
	}
</style>
