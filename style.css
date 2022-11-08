body {
	display: flex;
	justify-content: center;
	align-items: center;
	background: #2c3e50
}

.box {
	width: 1000px;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	display: flex;
	flex-direction: column;
}

#pinkboard {
	position: relative;
	margin: auto;
	height: 750px;
	width: 750px;
	animation: animate 1.2s infinite;
}

#pinkboard:before, #pinkboard:after {
	content: '';
	position: absolute;
	background: #d63031;
	width: 100px;
	height: 160px;
	border-top-left-radius: 50px;
	border-top-right-radius: 50px;
}

#pinkboard:before {
	left: 100px;
	transform: rotate(-45deg);
	transform-origin: 0 100%;
	box-shadow: 0 14px 28px rgba(0,0,0,0.25),
				0 10px 10px rgba(0,0,0,0.22);
}

#pinkboard:after {
	left: 0;
	transform: rotate(45deg);
	transform-origin: 100% 100%;
}

@keyframes animate {
	0% {
		transform: scale(1);
	}
	30% {
		transform: scale(.8);
	}
	60% {
		transform: scale(1.2);
	}
	100% {
		transform: scale(1);
	}
}
