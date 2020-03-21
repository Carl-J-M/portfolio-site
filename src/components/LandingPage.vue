<template>
  <div class="page-container">
      <div class="media-links">
        <img src="https://cdn.onlinewebfonts.com/svg/img_137494.png" alt="linkedIn logo" class="logo">
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="github logo" class="logo">
      </div>
      <div class="splash-text flexItem hero">carlscampfire.com</div>
      <div class="flexItem subheading">Carl Mensah</div>

      <img class="flexItem avatar"
      src='https://avataaars.io/?avatarStyle=Circle&topType=LongHairDreads&accessoriesType=Blank&hairColor=Auburn&facialHairType=BeardLight&facialHairColor=Auburn&clotheType=ShirtVNeck&clotheColor=Black&eyeType=Default&eyebrowType=RaisedExcited&mouthType=Default&skinColor=Brown'>
            <div class="flexItem subheading">Software Developer | Web Designer</div>
      <div class="flexItem">Edinburgh, Scotland</div>
      <div class="call-to-action flexItem">VIEW WORK</div>

  </div>
</template>

<script>
export default {
  name: 'LandingPage'
}
</script>

<style scoped>
.address {
  font-size: 1.6em;
  color: grey;
}
.avatar {
  max-height: 140px;
  max-width: 140px;
  filter: contrast(160%);
}
.greeting {
  font-size: 2em;
}
.page-container {
  height: 100vh;

  display: flex;
  flex-direction: column;

  text-align: center;
  align-items: center;
  justify-content: center;

  background: #F2994A;  /* fallback for old browsers */
   background: -webkit-linear-gradient(to bottom, #F2C94C, #F2994A);  /* Chrome 10-25, Safari 5.1-6 */
   background: linear-gradient(to bottom, #F2C94C, #F2994A); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */


}
.splash-text {
  color: #fff;
  font-size: 2.5em;
}
.call-to-action {
  color: white;
  background-color: #2c3e50;
  font-size: 1em;
  border-radius: 0.1em;
  padding: 0.6em;
  margin: 20px 0px;
  font-family: 'Quicksand', sans-serif;
}

.logo {
  max-height: 50px;
  max-width: 50px;
  padding: 0px 10px;
}

.hero {
  letter-spacing: 0.2em;
  font-size: 14px;
  color: grey;
  margin-bottom: 5%;
}
.media-links {
  margin-top: none;
}
.subheading {
  font-size: 2em;
}

</style>
