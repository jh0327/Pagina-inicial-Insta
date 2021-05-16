*{
	padding: 0;
	margin: 0;
	box-sizing: border-box;
	text-decoration: none;
	font-family: sans-serif;
	font-size: 14px;
}

body {
	width: 100%;
    margin: 0;
	min-height: 100vh;
    justify-content: center;
	padding: 0;
    display: flex;
	background-color: rgb(243, 243, 243);
}

.Instagram-wrapper {
	display: flex;
	justify-content: start;
	width: 60%;
	height: 100vh;
	align-items: center;
}

.Instagram-phone {
	display: flex;
	align-items: center;
	justify-content: center;
	width: 50%;
}

.Instagram-phone img {
	height: 30rem;
}

.profile-photo {
	display: flex;
	border-radius: 50%;
	justify-content: center;
	align-items: center;
	overflow: hidden;
}

.Instagram-continue {
	display: flex;
	align-items: center; /* horizontal */
	justify-content: space-around; /* vertical */
	flex-direction: column;
	width: 50%;
	min-height: 34rem;
}

.group {
	display: flex;
	align-items: center; /* horizontal */
	justify-content: space-between; /* vertical */
	flex-direction: column;
	background-color: #ffffff;
	width: 100%;
	padding: 0.3rem 0;
	border: 1px solid lightgray;
}

.group: nth-child(1) {
	min-height: 19rem;
}

.profile-photo img {
	height: 6rem;
}

.Instagram-logo {
	height: 10rem;
}

.instagram-login {
	background-color: #0095f6;
	color: #ffffff;
	padding: 8px;
	border-radius: 4px;
}

.instagram-logout {
	color: #0095f6;
	margin-top: 1rem;
}

.not-account {
	color: rgb(160, 160, 160);
}

.link-blue {
	color: #0095f6;
}

.Get-the-app {
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	width: 100%;
	padding: 1.3rem 0;
}

.download {
	display: flex;
	width: 100%;
	justify-content: space-evenly;
	align-items: center;
	padding: 1rem;
}

.download img {
	height: 3rem;
	width: 10rem;
	background-size: cover;
}

/* media queries */

@media(max-width: 1024px) {
	.Instagram-wrapper {
		width: 90%;
    }
}


@media(max-width: 650px) {
	body {
		background: #ffffff;
    }

    .Instagram-wrapper {
		width: 90%;
    }

    .Instagram-phone {
		display: none;
    }

    .Instagram-continue {
		width: 100% ;
    }

    .group {
		border: 1px solid transparent;
    }
}

	

	




