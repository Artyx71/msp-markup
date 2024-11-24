<template>
	<div class="head">
		<div class="wrap">
			<div class="header">
				<a href="" class="header__logo">
					<img src="../assets/img/logo.png" alt="" />
					<p>Цифровая платформа</p>
				</a>
				<nav class="header__menu">
					<ul class="header__menu-list">
						<li><a href="">Сервисы</a></li>
						<li><a href="">Бизнес-образование</a></li>
						<li><a href="">Аналитика</a></li>
					</ul>
				</nav>
				<a href="" class="header__btn">
					<img src="../assets/img/GosUsl.png" alt="" />
					<p>войти</p>
				</a>
				<div class="burger">
					<div class="burger__menu">
						<span></span><span></span><span></span>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style>
.wrap {
	width: 100%;
	max-width: 1200px;
	margin: 0 auto;
}

.header {
	display: flex;
	align-items: center;
	padding: 32px 10px;
}

.header__logo {
	display: flex;
	align-items: center;
	margin-right: 90px;
}

.header__logo img {
	margin-right: 10px;
}

.header__logo p {
	max-width: 90px;
}

.header__menu {
	flex-grow: 1;
}

.header__menu-list {
	display: flex;
	gap: 50px;
	font-size: 16px;
	font-weight: 600;
}

.header__btn {
	display: flex;
	align-items: center;
	background: #9d87f1;
	padding: 13px 32px 13px 32px;
	border-radius: 40px 40px 40px 40px;
	margin-right: 24px;
}

.header__btn p {
	color: #ffffff;
	font-size: 16px;
	font-weight: 600;
}

.header__btn img {
	margin-right: 10px;
}

.burger {
	display: none;
	width: 24px;
	height: 24px;
	position: relative;
}

.burger__menu span {
	height: 2px;
	width: 100%;
	background-color: #000000;
	border-radius: 25px;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	transition: 0.3s ease;
}

.burger__menu span:nth-child(1) {
	top: 25%;
}

.burger__menu span:nth-child(3) {
	top: 75%;
}

@media (max-width: 968px) {
	.wrap {
		max-width: 690px;
	}

	.header {
		padding: 32px 20px;
	}

	.header__menu {
		display: none;
	}

	.burger {
		display: block;
	}
}
</style>
