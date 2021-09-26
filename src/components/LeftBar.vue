<template>
  <aside class="left-bar">
    <div class="left-bar__header">
      <a href="#" class="left-bar__logo-link">
        <svg role="img" viewBox="0 0 78 24" class="left-bar__logo">
          <path
            fill="#fff"
            d="M18.871 10.64C15.056 8.35 8.764 8.139 5.122 9.256a1.105 1.105 0 0 1-1.38-.745 1.121 1.121 0 0 1 .737-1.396c4.18-1.283 11.13-1.035 15.522 1.6.526.316.699 1.002.387 1.533a1.1 1.1 0 0 1-1.517.392zm-.125 3.392a.917.917 0 0 1-1.269.307c-3.18-1.977-8.03-2.549-11.793-1.394a.922.922 0 0 1-1.151-.622.936.936 0 0 1 .615-1.163c4.298-1.319 9.642-.68 13.295 1.59.433.27.57.844.303 1.282zm-1.448 3.257a.732.732 0 0 1-1.014.248c-2.78-1.717-6.277-2.105-10.397-1.153a.737.737 0 0 1-.883-.561.745.745 0 0 1 .555-.893c4.508-1.042 8.375-.593 11.495 1.334a.75.75 0 0 1 .244 1.025zM11.871.034C5.334.034.036 5.39.036 11.997c0 6.608 5.298 11.963 11.835 11.963 6.536 0 11.835-5.355 11.835-11.963C23.706 5.39 18.407.034 11.87.034zm20.363 11.044c-2.043-.493-2.407-.838-2.407-1.565 0-.686.64-1.148 1.59-1.148.921 0 1.835.351 2.793 1.073.029.022.065.03.101.025a.132.132 0 0 0 .088-.055l.998-1.422a.137.137 0 0 0-.025-.184c-1.14-.925-2.424-1.374-3.925-1.374-2.206 0-3.747 1.338-3.747 3.253 0 2.054 1.33 2.78 3.627 3.342 1.955.455 2.285.837 2.285 1.519 0 .755-.667 1.225-1.741 1.225-1.193 0-2.166-.406-3.254-1.359a.132.132 0 0 0-.19.015l-1.119 1.346a.135.135 0 0 0 .013.188c1.267 1.143 2.824 1.746 4.504 1.746 2.378 0 3.914-1.313 3.914-3.345 0-1.718-1.015-2.668-3.505-3.28m10.61 2.302c0 1.45-.884 2.463-2.15 2.463-1.25 0-2.194-1.058-2.194-2.463 0-1.404.943-2.462 2.195-2.462 1.245 0 2.149 1.035 2.149 2.462zm-1.726-4.34c-1.03 0-1.876.411-2.573 1.252v-.946a.135.135 0 0 0-.133-.136h-1.83a.135.135 0 0 0-.134.136V19.86c0 .075.06.136.134.136h1.83a.135.135 0 0 0 .133-.136v-3.319c.698.791 1.543 1.177 2.573 1.177 1.915 0 3.853-1.49 3.853-4.338 0-2.849-1.938-4.34-3.853-4.34zm8.822 6.818c-1.312 0-2.3-1.065-2.3-2.478 0-1.418.954-2.448 2.27-2.448 1.32 0 2.315 1.066 2.315 2.48 0 1.417-.96 2.446-2.285 2.446zm0-6.817c-2.466 0-4.398 1.92-4.398 4.37 0 2.424 1.919 4.324 4.368 4.324 2.474 0 4.412-1.913 4.412-4.355 0-2.433-1.924-4.34-4.382-4.34zm9.648.169h-2.013V7.13a.134.134 0 0 0-.134-.136h-1.83a.135.135 0 0 0-.133.135V9.21h-.88a.134.134 0 0 0-.133.136v1.59c0 .074.06.135.133.135h.88v4.113c0 1.662.818 2.505 2.432 2.505.656 0 1.2-.137 1.714-.432a.135.135 0 0 0 .068-.117v-1.514a.136.136 0 0 0-.064-.115.133.133 0 0 0-.13-.006c-.353.18-.693.262-1.074.262-.587 0-.85-.27-.85-.873V11.07h2.014a.135.135 0 0 0 .134-.136v-1.59a.134.134 0 0 0-.134-.135m7.015.009v-.255c0-.752.285-1.088.925-1.088.381 0 .688.077 1.031.193a.133.133 0 0 0 .12-.02.135.135 0 0 0 .056-.11V6.38a.135.135 0 0 0-.095-.13 4.977 4.977 0 0 0-1.52-.22c-1.69 0-2.584.962-2.584 2.78v.392h-.879a.135.135 0 0 0-.134.135v1.598c0 .075.06.136.134.136h.88v6.344c0 .075.059.135.133.135h1.83c.073 0 .133-.06.133-.135V11.07h1.709l2.617 6.342c-.297.667-.59.8-.988.8-.323 0-.662-.098-1.01-.29a.136.136 0 0 0-.106-.01.136.136 0 0 0-.079.073l-.62 1.375a.135.135 0 0 0 .057.175 3.82 3.82 0 0 0 1.955.506c1.35 0 2.097-.636 2.756-2.348l3.174-8.291a.137.137 0 0 0-.014-.126.133.133 0 0 0-.11-.059h-1.905a.135.135 0 0 0-.127.091l-1.951 5.634-2.137-5.638a.133.133 0 0 0-.125-.087h-3.126m-4.067-.007h-1.83a.135.135 0 0 0-.133.136v8.069c0 .075.06.135.134.135h1.83c.073 0 .133-.06.133-.135v-8.07a.135.135 0 0 0-.134-.135m-.906-3.674a1.32 1.32 0 0 0-1.312 1.326 1.32 1.32 0 0 0 1.313 1.327 1.32 1.32 0 0 0 1.312-1.327c0-.733-.588-1.326-1.312-1.326m16.104 4.477H77.4v.432h.335c.167 0 .267-.083.267-.216 0-.141-.1-.216-.267-.216zm.217.616l.365.516h-.308l-.327-.473H77.4v.473h-.257V9.778h.602c.314 0 .521.163.521.436a.407.407 0 0 1-.314.415zm-.285-1.305c-.66 0-1.159.53-1.159 1.179 0 .648.496 1.171 1.152 1.171.66 0 1.16-.53 1.16-1.179 0-.648-.497-1.171-1.153-1.171zm-.007 2.48a1.29 1.29 0 0 1-1.287-1.301c0-.714.57-1.309 1.294-1.309a1.29 1.29 0 0 1 1.287 1.301c0 .714-.57 1.31-1.294 1.31z"
          ></path></svg
      ></a>
      <nav class="left-bar__nav">
        <ul class="left-bar__nav-list">
          <li class="left-bar__nav-item">
            <a
              class="
                left-bar__nav-link
                left-bar__nav-link--active
                left-bar__nav-link--main
              "
              href="#"
              >Главная</a
            >
          </li>
          <li class="left-bar__nav-item">
            <a class="left-bar__nav-link left-bar__nav-link--search" href="#"
              >Поиск</a
            >
          </li>
          <li class="left-bar__nav-item">
            <a class="left-bar__nav-link left-bar__nav-link--lib" href="#"
              >Моя медиатека</a
            >
          </li>
        </ul>
      </nav>
      <div class="left-bar__buttons">
        <button class="left-bar__create-pl">
          <div class="left-bar__create-pl-img">
            <svg
              role="img"
              height="12"
              width="12"
              viewBox="0 0 16 16"
              class="Svg-sc-1bi12j5-0 gSLhUO"
            >
              <path d="M14 7H9V2H7v5H2v2h5v5h2V9h5z"></path>
              <path fill="none" d="M0 0h16v16H0z"></path>
            </svg>
          </div>
          Создать плейлист
        </button>
        <div class="left-bar__fav-wrapper">
          <div class="left-bar__fav-img">
            <svg
              role="img"
              height="12"
              width="12"
              viewBox="0 0 16 16"
              fill="transparent"
            >
              <path fill="" d="M0 0h16v16H0z"></path>
              <path
                fill="white"
                d="M13.797 2.727a4.057 4.057 0 00-5.488-.253.558.558 0 01-.31.112.531.531 0 01-.311-.112 4.054 4.054 0 00-5.487.253c-.77.77-1.194 1.794-1.194 2.883s.424 2.113 1.168 2.855l4.462 5.223a1.791 1.791 0 002.726 0l4.435-5.195a4.052 4.052 0 001.195-2.883 4.057 4.057 0 00-1.196-2.883z"
              ></path>
            </svg>
          </div>

          <a href="#" class="left-bar__fav-link">Любимые треки</a>
        </div>
      </div>
    </div>
    <!-- <div class="left-bar__pl-wrapper">
      <ul class="left-bar__pl">
        <li class="left-bar__pl-item">
          <a class="left-bar__pl-link" href="#">Playlist.</a>
        </li>
        <li class="left-bar__pl-item">
          <a class="left-bar__pl-link" href="#">Playlist.</a>
        </li>
        <li class="left-bar__pl-item">
          <a class="left-bar__pl-link" href="#">Playlist.</a>
        </li>
        <li class="left-bar__pl-item">
          <a class="left-bar__pl-link" href="#">Playlist.</a>
        </li>
        <li class="left-bar__pl-item">
          <a class="left-bar__pl-link" href="#">Playlist.</a>
        </li>
        <li class="left-bar__pl-item">
          <a class="left-bar__pl-link" href="#">Playlist.</a>
        </li>
      </ul>
    </div> -->
    <!-- <a href="#" class="left-bar__down-link">Установить приложение</a> -->
  </aside>
</template>

<style lang="scss" scoped>
.left-bar {
  width: 340px;
  background-color: #000;
  min-height: 100%;
  padding-top: 30px;
  &__logo {
    width: 140px;
  }
  &__logo-link {
    width: 233px;
    display: block;
    margin: 0 auto;
  }
  &__nav {
    margin-top: 30px;
    padding-right: 5px;
    padding-left: 5px;
  }
  &__nav-item {
    &:not(:last-child) {
      margin-bottom: 5px;
    }
  }
  &__nav-list {
    margin: 0;
    padding: 0;
    list-style: none;
  }
  &__nav-link--active {
    background-color: #282828;
    border-radius: 5px;
  }
  &__nav-link {
    height: 40px;
    display: flex;
    font-size: 14px;
    align-items: center;
    text-decoration: none;
    color: #8c8c8c;
    font-weight: bold;
    &:hover {
      background-color: #282828;
      border-radius: 5px;
    }
    &::before {
      content: "";
      display: block;
      margin-right: 10px;
      margin-left: 10px;
      width: 24px;
      height: 24px;
    }
  }
  &__nav-link--main {
    &::before {
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' width='24' height='24' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M 256.274 60.84 L 84.324 166.237 L 84.324 443.063 L 193.27 443.063 L 193.27 293.73 L 320.228 293.73 L 320.228 443.063 L 428.222 443.063 L 428.222 165.476 L 256.274 60.84 Z M 256.274 35.95 L 448.452 149.145 L 448.452 464.395 L 300 464.395 L 300 315.062 L 213.499 315.062 L 213.499 464.395 L 64.095 464.395 L 64.095 150.161 L 256.274 35.95 Z' fill='white'%3E%3C/path%3E%3C/svg%3E");
    }
  }
  &__nav-link--search {
    &::before {
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' width='24' height='24' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M349.714 347.937l93.714 109.969-16.254 13.969-93.969-109.969q-48.508 36.825-109.207 36.825-36.826 0-70.476-14.349t-57.905-38.603-38.603-57.905-14.349-70.476 14.349-70.476 38.603-57.905 57.905-38.603 70.476-14.349 70.476 14.349 57.905 38.603 38.603 57.905 14.349 70.476q0 37.841-14.73 71.619t-40.889 58.921zM224 377.397q43.428 0 80.254-21.461t58.286-58.286 21.461-80.254-21.461-80.254-58.286-58.285-80.254-21.46-80.254 21.46-58.285 58.285-21.46 80.254 21.46 80.254 58.285 58.286 80.254 21.461z' fill='%23fff' fill-rule='evenodd'%3E%3C/path%3E%3C/svg%3E");
    }
  }
  &__nav-link--lib {
    &::before {
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' width='24' height='24' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M291.301 81.778l166.349 373.587-19.301 8.635-166.349-373.587zM64 463.746v-384h21.334v384h-21.334zM192 463.746v-384h21.334v384h-21.334z' fill='%23fff'%3E%3C/path%3E%3C/svg%3E");
    }
  }
  &__buttons {
    margin-top: 20px;
    padding-left: 15px;
  }
  &__create-pl {
    width: 100%;
    background: transparent;
    border: none;
    color: #8c8c8c;
    cursor: pointer;
    text-align: left;
    padding: 0;
    display: flex;
    align-items: center;
    margin: 0 auto;
  }
  &__create-pl-img {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 25px;
    width: 25px;
    background-color: #b2b2b2;
    margin-right: 10px;
  }
  &__fav-wrapper {
    margin-top: 15px;
    display: flex;
    align-items: center;
  }
  &__fav-img {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 25px;
    width: 25px;
    background: linear-gradient(135deg, #450af5, #c4efd9);
    margin-right: 10px;
  }
  &__fav-link {
    text-decoration: none;
    color: #8c8c8c;
  }
}
</style>
