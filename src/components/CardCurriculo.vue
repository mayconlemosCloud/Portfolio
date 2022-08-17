<template>
  <v-container>
    <v-row> </v-row>
  </v-container>
</template>

<style>
.container {
  position: absolute;
  top: 5em;
  left: 5em;
}

.button {
  width: 10em;
  height: 6em;
  border-radius: 1em;
  background: #8e9eab;
  background: linear-gradient(bottom, #8e9eab 0%, #d4d8d8 20%, #eef2f3 65%);
  background: -webkit-linear-gradient(
    bottom,
    #8e9eab 0%,
    #d4d8d8 20%,
    #eef2f3 65%
  );
  box-shadow: 2px 2px 11px 0px rgba(163, 161, 163, 1);
  -webkit-box-shadow: 2px 2px 11px 0px rgba(163, 161, 163, 1);
  -moz-box-shadow: 2px 2px 11px 0px rgba(163, 161, 163, 1);
  padding: 0.5em 1em 0.5em 1em;
}

.arrow {
  position: relative;
  top: 3%;
}

.down {
  position: absolute;
  width: 0.5em;
  height: 3em;
  background-color: lightgrey;
  border-radius: 2em;
  left: 47%;
  margin-top: 3%;
}

.left {
  position: absolute;
  width: 0.5em;
  height: 1.5em;
  background-color: lightgrey;
  border-radius: 2em;
  left: 42%;
  margin-top: 24%;
  transform: rotate(-35deg);
}

.right {
  position: absolute;
  width: 0.5em;
  height: 1.5em;
  background-color: lightgrey;
  border-radius: 2em;
  left: 52%;
  margin-top: 24%;
  transform: rotate(35deg);
}

.load {
  position: absolute;
  width: 3em;
  height: 0.5em;
  background-color: lightgrey;
  border-radius: 2em;
  left: 36%;
  top: 70%;
  box-shadow: 1px 1px 5px 0px rgba(163, 161, 163, 1);
  -webkit-box-shadow: 1px 1px 5px 0px rgba(163, 161, 163, 1);
  -moz-box-shadow: 1px 1px 5px 0px rgba(163, 161, 163, 1);
}

.bounce {
  -moz-animation: bounce 2s infinite;
  -webkit-animation: bounce 2s infinite;
  animation: bounce 2s infinite;
}

@-moz-keyframes bounce {
  0%,
  10%,
  50%,
  80%,
  100% {
    -moz-transform: translateY(0);
    transform: translateY(0);
  }
  40% {
    -moz-transform: translateY(-10px);
    transform: translateY(-10px);
  }
  60% {
    -moz-transform: translateY(-5px);
    transform: translateY(-5px);
  }
}
@-webkit-keyframes bounce {
  0%,
  20%,
  50%,
  80%,
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
  40% {
    -webkit-transform: translateY(-10px);
    transform: translateY(-10px);
  }
  60% {
    -webkit-transform: translateY(-5px);
    transform: translateY(-5px);
  }
}
@keyframes bounce {
  0%,
  20%,
  50%,
  80%,
  100% {
    -moz-transform: translateY(0);
    -ms-transform: translateY(0);
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
  40% {
    -moz-transform: translateY(-10px);
    -ms-transform: translateY(-10px);
    -webkit-transform: translateY(-10px);
    transform: translateY(-10px);
  }
}
</style>
