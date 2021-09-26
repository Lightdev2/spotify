<template>
  <div class="login">
    <div class="login__logo-wrapper">
      <a href="#" class="login__logo-link">
        <svg role="img" viewBox="0 0 78 24" class="login__logo">
          <path
            d="M18.871 10.64C15.056 8.35 8.764 8.139 5.122 9.256a1.105 1.105 0 0 1-1.38-.745 1.121 1.121 0 0 1 .737-1.396c4.18-1.283 11.13-1.035 15.522 1.6.526.316.699 1.002.387 1.533a1.1 1.1 0 0 1-1.517.392zm-.125 3.392a.917.917 0 0 1-1.269.307c-3.18-1.977-8.03-2.549-11.793-1.394a.922.922 0 0 1-1.151-.622.936.936 0 0 1 .615-1.163c4.298-1.319 9.642-.68 13.295 1.59.433.27.57.844.303 1.282zm-1.448 3.257a.732.732 0 0 1-1.014.248c-2.78-1.717-6.277-2.105-10.397-1.153a.737.737 0 0 1-.883-.561.745.745 0 0 1 .555-.893c4.508-1.042 8.375-.593 11.495 1.334a.75.75 0 0 1 .244 1.025zM11.871.034C5.334.034.036 5.39.036 11.997c0 6.608 5.298 11.963 11.835 11.963 6.536 0 11.835-5.355 11.835-11.963C23.706 5.39 18.407.034 11.87.034zm20.363 11.044c-2.043-.493-2.407-.838-2.407-1.565 0-.686.64-1.148 1.59-1.148.921 0 1.835.351 2.793 1.073.029.022.065.03.101.025a.132.132 0 0 0 .088-.055l.998-1.422a.137.137 0 0 0-.025-.184c-1.14-.925-2.424-1.374-3.925-1.374-2.206 0-3.747 1.338-3.747 3.253 0 2.054 1.33 2.78 3.627 3.342 1.955.455 2.285.837 2.285 1.519 0 .755-.667 1.225-1.741 1.225-1.193 0-2.166-.406-3.254-1.359a.132.132 0 0 0-.19.015l-1.119 1.346a.135.135 0 0 0 .013.188c1.267 1.143 2.824 1.746 4.504 1.746 2.378 0 3.914-1.313 3.914-3.345 0-1.718-1.015-2.668-3.505-3.28m10.61 2.302c0 1.45-.884 2.463-2.15 2.463-1.25 0-2.194-1.058-2.194-2.463 0-1.404.943-2.462 2.195-2.462 1.245 0 2.149 1.035 2.149 2.462zm-1.726-4.34c-1.03 0-1.876.411-2.573 1.252v-.946a.135.135 0 0 0-.133-.136h-1.83a.135.135 0 0 0-.134.136V19.86c0 .075.06.136.134.136h1.83a.135.135 0 0 0 .133-.136v-3.319c.698.791 1.543 1.177 2.573 1.177 1.915 0 3.853-1.49 3.853-4.338 0-2.849-1.938-4.34-3.853-4.34zm8.822 6.818c-1.312 0-2.3-1.065-2.3-2.478 0-1.418.954-2.448 2.27-2.448 1.32 0 2.315 1.066 2.315 2.48 0 1.417-.96 2.446-2.285 2.446zm0-6.817c-2.466 0-4.398 1.92-4.398 4.37 0 2.424 1.919 4.324 4.368 4.324 2.474 0 4.412-1.913 4.412-4.355 0-2.433-1.924-4.34-4.382-4.34zm9.648.169h-2.013V7.13a.134.134 0 0 0-.134-.136h-1.83a.135.135 0 0 0-.133.135V9.21h-.88a.134.134 0 0 0-.133.136v1.59c0 .074.06.135.133.135h.88v4.113c0 1.662.818 2.505 2.432 2.505.656 0 1.2-.137 1.714-.432a.135.135 0 0 0 .068-.117v-1.514a.136.136 0 0 0-.064-.115.133.133 0 0 0-.13-.006c-.353.18-.693.262-1.074.262-.587 0-.85-.27-.85-.873V11.07h2.014a.135.135 0 0 0 .134-.136v-1.59a.134.134 0 0 0-.134-.135m7.015.009v-.255c0-.752.285-1.088.925-1.088.381 0 .688.077 1.031.193a.133.133 0 0 0 .12-.02.135.135 0 0 0 .056-.11V6.38a.135.135 0 0 0-.095-.13 4.977 4.977 0 0 0-1.52-.22c-1.69 0-2.584.962-2.584 2.78v.392h-.879a.135.135 0 0 0-.134.135v1.598c0 .075.06.136.134.136h.88v6.344c0 .075.059.135.133.135h1.83c.073 0 .133-.06.133-.135V11.07h1.709l2.617 6.342c-.297.667-.59.8-.988.8-.323 0-.662-.098-1.01-.29a.136.136 0 0 0-.106-.01.136.136 0 0 0-.079.073l-.62 1.375a.135.135 0 0 0 .057.175 3.82 3.82 0 0 0 1.955.506c1.35 0 2.097-.636 2.756-2.348l3.174-8.291a.137.137 0 0 0-.014-.126.133.133 0 0 0-.11-.059h-1.905a.135.135 0 0 0-.127.091l-1.951 5.634-2.137-5.638a.133.133 0 0 0-.125-.087h-3.126m-4.067-.007h-1.83a.135.135 0 0 0-.133.136v8.069c0 .075.06.135.134.135h1.83c.073 0 .133-.06.133-.135v-8.07a.135.135 0 0 0-.134-.135m-.906-3.674a1.32 1.32 0 0 0-1.312 1.326 1.32 1.32 0 0 0 1.313 1.327 1.32 1.32 0 0 0 1.312-1.327c0-.733-.588-1.326-1.312-1.326m16.104 4.477H77.4v.432h.335c.167 0 .267-.083.267-.216 0-.141-.1-.216-.267-.216zm.217.616l.365.516h-.308l-.327-.473H77.4v.473h-.257V9.778h.602c.314 0 .521.163.521.436a.407.407 0 0 1-.314.415zm-.285-1.305c-.66 0-1.159.53-1.159 1.179 0 .648.496 1.171 1.152 1.171.66 0 1.16-.53 1.16-1.179 0-.648-.497-1.171-1.153-1.171zm-.007 2.48a1.29 1.29 0 0 1-1.287-1.301c0-.714.57-1.309 1.294-1.309a1.29 1.29 0 0 1 1.287 1.301c0 .714-.57 1.31-1.294 1.31z"
          ></path></svg
      ></a>
    </div>

    <div class="login__wrapper">
      <div class="login__content">
        <h2 class="login__title">Чтобы продолжить, войдите в Spotify.</h2>
        <button class="login__button login__button--fb">
          Войти через Facebook
        </button>
        <button class="login__button login__button--apple">
          Войти через Apple
        </button>
        <button class="login__button login__button--google">
          Войти через Google
        </button>
      </div>
      <span class="login__divider">или</span>
      <form action="post" class="login__form">
        <label>
          Эл. почта или имя пользователя
          <input type="text" placeholder="Эл. почта или имя пользователя" />
        </label>
        <label>
          Пароль
          <input type="text" placeholder="Пароль" />
        </label>
        <a class="login__form-link" href="#">Забыли пароль?</a>
        <div class="login__form-footer">
          <label>
            <input type="checkbox" name="" id="" />
            Запомнить меня
          </label>
          <router-link class="login__enter" :to="{ name: 'player' }"
            >Войти</router-link
          >
        </div>
      </form>
      <h3 class="login_noacc">Нет аккаунта?</h3>
      <router-link class="login__link" :to="{ name: 'register' }"
        >Регистрация в Spotify</router-link
      >
    </div>
  </div>
</template>

<style lang="scss" scoped>
.login {
  padding-top: 30px;
  padding-bottom: 10px;
  &__wrapper {
    max-width: 450px;
    margin: 0 auto;
    @media screen and (max-width: 500px) {
      padding-right: 10px;
      padding-left: 10px;
    }
  }
  &__logo {
    width: 200px;
  }
  &__logo-wrapper {
    border-bottom: 1px solid #f1f1f2;
  }
  &__logo-link {
    display: block;
    text-align: center;
    margin-bottom: 20px;
    padding-bottom: 15px;
  }
  &__content {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  &__button {
    width: 100%;
    border-radius: 500px;
    text-transform: uppercase;
    border: none;
    cursor: pointer;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    &::before {
      content: "";
      display: block;
      width: 18px;
      height: 18px;
      margin-right: 5px;
    }
    &:active,
    &:focus {
      transition: box-shadow 0.3s cubic-bezier(0.165, 0.84, 0.44, 1);
      outline: none;
      border: 4px solid #fff;
      box-shadow: 0px 0px 0px 2px #000;
    }
    margin-bottom: 10px;
  }
  &__button--fb {
    background-color: #3b5998;
    color: white;
    &::before {
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' version='1.1' id='Capa_1' x='0px' y='0px' viewBox='0 0 167.657 167.657' style='enable-background:new 0 0 167.657 167.657;' xml:space='preserve'%3E%3Cg%3E%3Cpath style='fill:%23fff;' d='M83.829,0.349C37.532,0.349,0,37.881,0,84.178c0,41.523,30.222,75.911,69.848,82.57v-65.081H49.626 v-23.42h20.222V60.978c0-20.037,12.238-30.956,30.115-30.956c8.562,0,15.92,0.638,18.056,0.919v20.944l-12.399,0.006 c-9.72,0-11.594,4.618-11.594,11.397v14.947h23.193l-3.025,23.42H94.026v65.653c41.476-5.048,73.631-40.312,73.631-83.154 C167.657,37.881,130.125,0.349,83.829,0.349z'/%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3C/svg%3E");
    }
  }
  &__button--apple {
    background-color: #000;
    color: white;
    &::before {
      fill: white;
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' version='1.1' id='Capa_1' x='0px' y='0px' viewBox='0 0 22.773 22.773' style='enable-background:new 0 0 22.773 22.773;filter: white;fill: white;' xml:space='preserve'%3E%3Cg%3E%3Cg%3E%3Cpath d='M15.769,0c0.053,0,0.106,0,0.162,0c0.13,1.606-0.483,2.806-1.228,3.675c-0.731,0.863-1.732,1.7-3.351,1.573 c-0.108-1.583,0.506-2.694,1.25-3.561C13.292,0.879,14.557,0.16,15.769,0z'/%3E%3Cpath d='M20.67,16.716c0,0.016,0,0.03,0,0.045c-0.455,1.378-1.104,2.559-1.896,3.655c-0.723,0.995-1.609,2.334-3.191,2.334 c-1.367,0-2.275-0.879-3.676-0.903c-1.482-0.024-2.297,0.735-3.652,0.926c-0.155,0-0.31,0-0.462,0 c-0.995-0.144-1.798-0.932-2.383-1.642c-1.725-2.098-3.058-4.808-3.306-8.276c0-0.34,0-0.679,0-1.019 c0.105-2.482,1.311-4.5,2.914-5.478c0.846-0.52,2.009-0.963,3.304-0.765c0.555,0.086,1.122,0.276,1.619,0.464 c0.471,0.181,1.06,0.502,1.618,0.485c0.378-0.011,0.754-0.208,1.135-0.347c1.116-0.403,2.21-0.865,3.652-0.648 c1.733,0.262,2.963,1.032,3.723,2.22c-1.466,0.933-2.625,2.339-2.427,4.74C17.818,14.688,19.086,15.964,20.67,16.716z'/%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3C/svg%3E");
    }
  }
  &__button--google {
    background-color: transparent;
    border: 2px solid grey;
    &:hover {
      background-color: grey;
      color: white;
    }
    &::before {
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' version='1.1' id='Layer_1' x='0px' y='0px' viewBox='0 0 512 512' style='enable-background:new 0 0 512 512;' xml:space='preserve'%3E%3Cpath style='fill:%23167EE6;' d='M492.668,211.489l-208.84-0.01c-9.222,0-16.697,7.474-16.697,16.696v66.715 c0,9.22,7.475,16.696,16.696,16.696h117.606c-12.878,33.421-36.914,61.41-67.58,79.194L384,477.589 c80.442-46.523,128-128.152,128-219.53c0-13.011-0.959-22.312-2.877-32.785C507.665,217.317,500.757,211.489,492.668,211.489z'/%3E%3Cpath style='fill:%2312B347;' d='M256,411.826c-57.554,0-107.798-31.446-134.783-77.979l-86.806,50.034 C78.586,460.443,161.34,512,256,512c46.437,0,90.254-12.503,128-34.292v-0.119l-50.147-86.81 C310.915,404.083,284.371,411.826,256,411.826z'/%3E%3Cpath style='fill:%230F993E;' d='M384,477.708v-0.119l-50.147-86.81c-22.938,13.303-49.48,21.047-77.853,21.047V512 C302.437,512,346.256,499.497,384,477.708z'/%3E%3Cpath style='fill:%23FFD500;' d='M100.174,256c0-28.369,7.742-54.91,21.043-77.847l-86.806-50.034C12.502,165.746,0,209.444,0,256 s12.502,90.254,34.411,127.881l86.806-50.034C107.916,310.91,100.174,284.369,100.174,256z'/%3E%3Cpath style='fill:%23FF4B26;' d='M256,100.174c37.531,0,72.005,13.336,98.932,35.519c6.643,5.472,16.298,5.077,22.383-1.008 l47.27-47.27c6.904-6.904,6.412-18.205-0.963-24.603C378.507,23.673,319.807,0,256,0C161.34,0,78.586,51.557,34.411,128.119 l86.806,50.034C148.202,131.62,198.446,100.174,256,100.174z'/%3E%3Cpath style='fill:%23D93F21;' d='M354.932,135.693c6.643,5.472,16.299,5.077,22.383-1.008l47.27-47.27 c6.903-6.904,6.411-18.205-0.963-24.603C378.507,23.672,319.807,0,256,0v100.174C293.53,100.174,328.005,113.51,354.932,135.693z'/%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3Cg%3E%3C/g%3E%3C/svg%3E");
    }
  }
  &__title {
    font-size: 14px;
    margin-top: 30px;
    margin-bottom: 20px;
    text-align: center;
  }
  &__divider {
    display: table;
    width: 100%;
    text-align: center;
    margin-top: 10px;
    &::before,
    &::after {
      content: "";
      display: table-cell;
      width: 42%;
      border-top: 1px solid rgb(204, 204, 204);
      position: relative;
      top: 0.57rem;
    }
  }
  &__form {
    margin-top: 20px;
    border-bottom: 1px solid #f1f1f2;
    padding-bottom: 20px;
  }
  &__form label {
    display: flex;
    flex-direction: column;
    font-weight: bold;
    font-size: 14px;
    color: #22303b;
    margin-bottom: 10px;
  }
  &__form input {
    margin-top: 10px;
    height: 40px;
    padding-left: 10px;
  }
  &__form-link {
    color: #6d7072;
    font-size: 14px;
    display: block;
    margin-top: 20px;
    &:hover {
      color: #1ed760;
    }
  }
  &__form-footer {
    margin-top: 20px;
    display: flex;
    justify-content: space-between;
  }
  &__form-footer label {
    margin: 0;
    display: flex;
    flex-direction: row;
    align-items: center;
    font-weight: normal;
    color: #65686b;
    width: 50%;
  }
  &__form-footer input {
    margin: 0;
    margin-right: 5px;
  }
  &__enter {
    border: none;
    height: 50px;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    background-color: #15883e;
    width: 50%;
    border-radius: 500px;
    text-transform: uppercase;
    font-weight: bold;
    cursor: pointer;
    &:hover {
      background-color: #1ed760;
    }
  }
  &_noacc {
    text-align: center;
    color: #222326;
  }
  &__link {
    text-transform: uppercase;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 2px solid grey;
    font-weight: bold;
    border-radius: 500px;
    height: 40px;
    color: grey;
    text-decoration: none;
  }
}
</style>
