<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta name="author" content="Рахматулла Ерасыл">
	<meta name="keyword" content="Обучение, учёба, математика, знание">
	<title>MathLab</title>
</head>
<body>
	<header id="header">
		<p><b>MathLab — ваш онлайн-сервис для решения математических задач!</b></p>
		1 + 1 = ?
	</header>

	<p id="text-1" class="text"><b>На нашем сайте вы сможете быстро находить ответы на простые и сложные математические примеры. Просто выберите тип задачи внизу и мы предоставим вам решение.</b></p>

	<p id="text-2" class="text">
		Цель сайта - за 1 минуту вы должны решить задачу которого вы выберите внизу нажав на нужную вам уровень.
	</p>



	<p id="button-text">Выберите уровень:</p>
	1 уровень. Только сложения
	<p><button id="additionButton" onclick="onAdditionButton()">сложения</button></p>
	2 уровень. Только деление
	<p><button id="department" onclick="ondepartmentButton()">отделение</button></p>
	3 уровень. Только умножение
	<p><button id="multiplication" onclick="onMultiplicationButton()">умножения</button></p>
	4 уровень. Только деление
	<p><button id="division" onclick="onDivisionButton()">деление</button></p>

	5 уровень. Всё в одном
	<p><button id="allMath" onclick="onAllMathButton()">Начать ---></button></p>


	<header id="header">
		<p id="gmail"><a href="mailto: erasylgames09@gmail.com" title="Gmail"> Связатся с нами!</a></p>
		<p>Whatsapp: 8 707 376 50 75</p>
		<p>Telegram: @ErasylMain</p>
	</header>
</body>

<body>
	<script src="scripts/main.js"></script>
	<link rel="stylesheet" href="main.css">
</body>
</html>
