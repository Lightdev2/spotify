<template>
  <footer class="footer">
    <div>
      <div class="footer__song">
        <img
          src="https://via.placeholder.com/40
"
          alt=""
          class="footer__song-img"
        />
        <p class="footer__song-descr">
          <span class="footer__song-name">Song name</span>
          <span class="footer__song-artist">Artist</span>
        </p>
        <svg
          role="img"
          height="16"
          width="16"
          viewBox="0 0 16 16"
          class="footer__song-like"
        >
          <path fill="none" d="M0 0h16v16H0z"></path>
          <path
            d="M13.797 2.727a4.057 4.057 0 00-5.488-.253.558.558 0 01-.31.112.531.531 0 01-.311-.112 4.054 4.054 0 00-5.487.253c-.77.77-1.194 1.794-1.194 2.883s.424 2.113 1.168 2.855l4.462 5.223a1.791 1.791 0 002.726 0l4.435-5.195a4.052 4.052 0 001.195-2.883 4.057 4.057 0 00-1.196-2.883z"
          ></path>
        </svg>
      </div>
    </div>
    <div class="footer__player">
      <div class="footer__player-controls">
        <div class="footer__player-control">
          <svg
            role="img"
            height="16"
            width="16"
            viewBox="0 0 16 16"
            class="Svg-sc-1bi12j5-0 gSLhUO"
          >
            <path
              d="M4.5 6.8l.7-.8C4.1 4.7 2.5 4 .9 4v1c1.3 0 2.6.6 3.5 1.6l.1.2zm7.5 4.7c-1.2 0-2.3-.5-3.2-1.3l-.6.8c1 1 2.4 1.5 3.8 1.5V14l3.5-2-3.5-2v1.5zm0-6V7l3.5-2L12 3v1.5c-1.6 0-3.2.7-4.2 2l-3.4 3.9c-.9 1-2.2 1.6-3.5 1.6v1c1.6 0 3.2-.7 4.2-2l3.4-3.9c.9-1 2.2-1.6 3.5-1.6z"
            ></path>
          </svg>
        </div>
        <div class="footer__player-control">
          <svg
            role="img"
            height="16"
            width="16"
            viewBox="0 0 16 16"
            class="Svg-sc-1bi12j5-0 gSLhUO"
          >
            <path d="M13 2.5L5 7.119V3H3v10h2V8.881l8 4.619z"></path>
          </svg>
        </div>
        <div class="footer__player-control">
          <svg
            role="img"
            height="16"
            width="16"
            viewBox="0 0 16 16"
            class="Svg-sc-1bi12j5-0 gSLhUO"
          >
            <path d="M4.018 14L14.41 8 4.018 2z"></path>
          </svg>
        </div>
        <div class="footer__player-control">
          <svg
            role="img"
            height="16"
            width="16"
            viewBox="0 0 16 16"
            class="Svg-sc-1bi12j5-0 gSLhUO"
          >
            <path d="M11 3v4.119L3 2.5v11l8-4.619V13h2V3z"></path>
          </svg>
        </div>
        <div class="footer__player-control">
          <svg
            role="img"
            height="16"
            width="16"
            viewBox="0 0 16 16"
            class="Svg-sc-1bi12j5-0 gSLhUO"
          >
            <path
              d="M5.5 5H10v1.5l3.5-2-3.5-2V4H5.5C3 4 1 6 1 8.5c0 .6.1 1.2.4 1.8l.9-.5C2.1 9.4 2 9 2 8.5 2 6.6 3.6 5 5.5 5zm9.1 1.7l-.9.5c.2.4.3.8.3 1.3 0 1.9-1.6 3.5-3.5 3.5H6v-1.5l-3.5 2 3.5 2V13h4.5C13 13 15 11 15 8.5c0-.6-.1-1.2-.4-1.8z"
            ></path>
          </svg>
        </div>
      </div>
      <div class="footer__bar">
        <span class="footer__bar-time">0:00</span>
        <div class="footer__bar-progress"></div>
        <span class="footer__bar-time">3:24</span>
      </div>
    </div>
    <div class="footer__controls">
      <div class="footer__controls-img">
        <svg
          role="img"
          height="16"
          width="16"
          aria-label="Подключиться к устройству"
          viewBox="0 0 16 16"
          class="Svg-sc-1bi12j5-0 gSLhUO"
        >
          <path
            d="M0 3v8c0 .55.45 1 1 1h5v-1H1V3h5V2H1c-.55 0-1 .45-1 1zm3 11.5c0 .275.225.5.5.5H6v-1H3.5c-.275 0-.5.225-.5.5zM15 2H9c-.55 0-1 .45-1 1v11c0 .55.45 1 1 1h6c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 12H9V3h6v11zm-3-8a.75.75 0 100-1.5.75.75 0 000 1.5zm0 6a2 2 0 100-4 2 2 0 000 4zm0-3c.551 0 1 .449 1 1s-.449 1-1 1-1-.449-1-1 .449-1 1-1z"
          ></path>
        </svg>
      </div>
      <div class="footer__controls-img">
        <svg
          role="presentation"
          height="16"
          width="16"
          aria-label="Средняя громкость"
          id="volume-icon"
          viewBox="0 0 16 16"
          class="Svg-sc-1bi12j5-0 gSLhUO"
        >
          <path
            d="M0 11.032v-6h2.802l5.198-3v12l-5.198-3H0zm7 1.27v-8.54l-3.929 2.27H1v4h2.071L7 12.302zm4.464-2.314q.401-.925.401-1.956 0-1.032-.4-1.957-.402-.924-1.124-1.623L11 3.69q.873.834 1.369 1.957.496 1.123.496 2.385 0 1.262-.496 2.385-.496 1.123-1.369 1.956l-.659-.762q.722-.698 1.123-1.623z"
          ></path>
        </svg>
      </div>
      <div class="footer__controls-bar"></div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
.footer {
  width: 100%;
  height: 90px;
  background-color: #181818;
  display: flex;
  align-items: center;
  padding-left: 20px;
  padding-right: 20px;
  justify-content: space-between;
  &__item {
    display: flex;
  }
  &__song {
    display: flex;
    align-items: center;
  }
  &__song-img {
    width: 60px;
    height: 60px;
  }
  &__song-descr {
    margin: 0;
    padding: 0;
    margin-left: 10px;
  }
  &__song-name {
    color: #fff;
    display: block;
    font-size: 14px;
  }
  &__song-artist {
    color: #959595;
    font-size: 12px;
    margin-top: 5px;
  }
  &__song-like {
    margin-left: 20px;
    fill: #1db954;
  }
  &__player {
    width: 600px;
    display: flex;
    align-items: center;
    flex-direction: column;
    @media screen and (max-width: 1024px) {
      width: 400px;
    }
  }
  &__player-controls {
    display: flex;
    align-items: center;
    margin: 0 auto;
  }
  &__player-control {
    fill: #fff;
    &:not(:last-child) {
      margin-right: 20px;
    }
    &:nth-child(3) {
      height: 40px;
      width: 40px;
      fill: #000;
      border-radius: 100%;
      background-color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
    }
  }
  &__bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    margin-top: 10px;
  }
  &__bar-time {
    color: #959595;
    font-size: 12px;
  }
  &__bar-progress {
    width: 100%;
    height: 3px;
    background-color: #959595;
    border-radius: 30px;
    margin-right: 20px;
    margin-left: 20px;
  }
  &__controls {
    display: flex;
    width: 150px;
    align-items: center;
    @media screen and (max-width: 600px) {
      display: none;
    }
  }
  &__controls-img {
    margin-right: 15px;
    fill: #fff;
  }
  &__controls-bar {
    height: 3px;
    width: 100%;
    background-color: #959595;
    border-radius: 30px;
  }
}
</style>
