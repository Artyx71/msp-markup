<template>
	<div class="business">
		<div class="wrap">
			<div class="analytics">
				<div class="analytics__top">
					<h2>Аналитика для бизнеса</h2>
					<p>
						Делимся актуальной статистикой и аналитикой для оценки, <br />
						прогнозирования и бизнес-планирования
					</p>
				</div>
				<div class="map">
					<h2>Федеральные округа</h2>
					<img src="../assets/img/map.png" alt="" />
				</div>
				<div class="analytics__bottom">
					<div class="scale">
						<h3>Таблица показателей</h3>
						<img src="../assets/img/scale.png" alt="" />
					</div>
					<div class="analytics__list-name">
						<div class="analytics__list-right">
							<p>Округа</p>
							<img src="../assets/img/arrows.png" alt="" />
						</div>
						<div class="analitycs__list-left">
							<ul>
								<li>
									<a href=""
										><p>Средний чек</p>

										<img src="../assets/img/faq.png" alt=""
									/></a>
								</li>
								<li>
									<a href=""
										><p>Совершенные операции</p>

										<img src="../assets/img/faq.png" alt=""
									/></a>
								</li>
								<li>
									<a href=""
										><p>Торговый оборот</p>

										<img src="../assets/img/faq.png" alt=""
									/></a>
								</li>
								<li>
									<a href=""
										><p>Налоговые отчисления</p>

										<img src="../assets/img/faq.png" alt=""
									/></a>
								</li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style>
.analytics {
	display: flex;
	flex-direction: column;
}

.analytics__top {
	display: flex;
	justify-content: space-between;
	margin-bottom: 50px;
	align-items: center;
}

.analytics__top h2 {
	font-size: 64px;
	font-weight: 700;
	max-width: 400px;
}

.analytics__top p {
	font-size: 20px;
	font-weight: 400;
}

.map {
	margin-bottom: 25px;
}

.map h2 {
	margin-bottom: 20px;
	font-size: 26px;
	font-weight: 700;
}

.analytics__list-head {
	display: flex;
}

.analytics__list-head li:first-child {
	flex-grow: 1;
}

.analytics__list-head li {
	margin-right: 90px;
}

.analytics__list-head li:last-child {
	margin-right: 0px;
}

.analytics__list-head li a {
	display: flex;
	gap: 10px;
}

.scale {
	display: flex;
	justify-content: space-between;
	align-items: center;
	margin-bottom: 35px;
}

.scale h3 {
	font-size: 24px;
	font-weight: 700;
}

.analytics__list-name {
	font-size: 12px;
	font-weight: 700;
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding-bottom: 14px;
	border-bottom: 2px solid #e9e9e9;
}

.analytics__list-right {
	display: flex;
	gap: 10px;
}

.analitycs__list-left ul {
	display: flex;
}
.analitycs__list-left li {
	margin-right: 90px;
}

.analitycs__list-left li a {
	display: flex;
	gap: 4px;
}

.analitycs__list-left li:last-child {
	margin-right: 0px;
}

@media (max-width: 968px) {
	.map img {
		max-width: 687px;
	}
}
</style>
