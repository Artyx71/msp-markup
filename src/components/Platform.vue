<template>
	<div class="main">
		<div class="wrap">
			<div class="platform">
				<div class="platform__left">
					<h1 class="platform__left-head">
						Платформа <br />
						<span class="transparent white">для вашего</span> бизнеса
					</h1>
					<p class="platform__left-parag">
						Экономим ваше время,<br />
						чтобы вы могли предпринимать
					</p>
					<div class="platform__left-block">
						<img src="../assets/img/case.png" alt="" />
						<h2>Регистрация бизнеса онлайн</h2>
						<p>
							Зарегистрируйте ИП или ООО <br />
							без добавленных услуг
						</p>
						<a class="platform__left-block-link" href="">
							<img src="../assets/img/plus.png" alt="" />
							<p>Создать бизнес</p>
						</a>
					</div>
				</div>
				<div class="platform__right">
					<img src="../assets/img/house.png" alt="" />
				</div>
			</div>
		</div>
	</div>
</template>
<style>
.main {
	background: linear-gradient(#474b95, #7552ae);
	margin-bottom: 80px;
	height: 910px;
}

.platform {
	display: flex;
	align-items: center;
}

.platform__left {
	display: flex;
	flex-direction: column;
}

.platform__left-head {
	margin-bottom: 17px;
	font-weight: 700;
	font-size: 59px;
	max-width: 705px;
	color: #fff;
	-webkit-text-stroke: 1px #000;
}

.white {
	color: transparent;
	-webkit-text-stroke: 1px white;
}

.platform__left-parag {
	margin-bottom: 110px;
	color: #9385c8;
	font-size: 14px;
}

.platform__left-block {
	max-width: 384px;
	display: flex;
	flex-direction: column;
	gap: 15px;
	padding: 45px 34px;
	background-color: #fff;
	border-radius: 12px;
}

.platform__left-block h2 {
	font-weight: 700;
	font-size: 26px;
	max-width: 315px;
}

.platform__left-block p {
	font-size: 16px;
	font-weight: 500;
	max-width: 315px;
}

.platform__left-block img {
	max-width: 51px;
}

.platform__left-block-link {
	display: flex;
	justify-content: center;
	align-items: center;
	margin-top: 40px;
	padding: 12px 0px;
	border: 1px solid #9d87f1;
	border-radius: 12px;
	color: #9d87f1;
}

.platform__left-block-link img {
	margin-right: 8px;
}
</style>
