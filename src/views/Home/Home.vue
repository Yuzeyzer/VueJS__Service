<template>
  <div class="container">
    <h2>Хотите предложить тему для нового видео?</h2>
    <div class="add-form">
      <div class="add-form__title">
        <input autocomplete="off" placeholder="Заголовок темы" type="text" name="title" id="title" />
      </div>
      <div class="add-form__text">
        <textarea
          placeholder="Опишите подробнее, какую тему вы хотите предложить для следующего видео"
          name="text"
          id="text"
          rows="5"
        ></textarea>
      </div>
      <div class="add-form__footer">
        <div class="add-form__footer-clear">
          <svg
            width="14"
            height="14"
            viewBox="0 0 14 14"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M8.64341 6.99901L13.6552 1.99813C13.8747 1.77862 13.998 1.48091 13.998 1.17048C13.998 0.860046 13.8747 0.562331 13.6552 0.342824C13.4358 0.123318 13.1381 0 12.8277 0C12.5173 0 12.2196 0.123318 12.0002 0.342824L7 5.35536L1.99983 0.342824C1.78036 0.123318 1.48268 -2.31288e-09 1.1723 0C0.861913 2.31288e-09 0.56424 0.123318 0.344765 0.342824C0.125289 0.562331 0.00198911 0.860046 0.00198911 1.17048C0.00198911 1.48091 0.125289 1.77862 0.344765 1.99813L5.35659 6.99901L0.344765 11.9999C0.235521 12.1083 0.148811 12.2372 0.0896384 12.3792C0.0304655 12.5213 0 12.6736 0 12.8275C0 12.9814 0.0304655 13.1338 0.0896384 13.2758C0.148811 13.4179 0.235521 13.5468 0.344765 13.6552C0.453117 13.7644 0.582027 13.8512 0.724059 13.9103C0.866091 13.9695 1.01843 14 1.1723 14C1.32616 14 1.47851 13.9695 1.62054 13.9103C1.76257 13.8512 1.89148 13.7644 1.99983 13.6552L7 8.64265L12.0002 13.6552C12.1085 13.7644 12.2374 13.8512 12.3795 13.9103C12.5215 13.9695 12.6738 14 12.8277 14C12.9816 14 13.1339 13.9695 13.2759 13.9103C13.418 13.8512 13.5469 13.7644 13.6552 13.6552C13.7645 13.5468 13.8512 13.4179 13.9104 13.2758C13.9695 13.1338 14 12.9814 14 12.8275C14 12.6736 13.9695 12.5213 13.9104 12.3792C13.8512 12.2372 13.7645 12.1083 13.6552 11.9999L8.64341 6.99901Z"
              fill="#C9C9C9"
            />
          </svg>
        </div>
        <button class="add-form__footer-button">Отправить</button>
      </div>
    </div>
    <ul class="tabs">
      <li>Последние</li>
      <li>Выполненные</li>
      <li>Закрыто</li>
    </ul>
    <div class="ideas">
      <div class="ideas__item">
        <div class="idead__ited-details">
          <h3 class="ideas__item-title">Рассказать про Axios</h3>
          <p
            class="ideas__item-text"
          >Хотелось бы более детально узнать о том, как работает axios и чем он лучше</p>
          <div class="ideas__item-footer">
            <ul>
              <li>
                <svg
                  width="14"
                  height="14"
                  viewBox="0 0 14 14"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M3.31579 3.31579C3.31579 5.14389 4.80347 6.63158 6.63158 6.63158C8.45968 6.63158 9.94737 5.14389 9.94737 3.31579C9.94737 1.48768 8.45968 0 6.63158 0C4.80347 0 3.31579 1.48768 3.31579 3.31579ZM12.5263 14H13.2632V13.2632C13.2632 10.4197 10.9487 8.10526 8.10526 8.10526H5.15789C2.31368 8.10526 0 10.4197 0 13.2632V14H12.5263Z"
                    fill="#979797"
                  />
                </svg>
                Гость
              </li>
              <li>
                <svg
                  width="14"
                  height="16"
                  viewBox="0 0 14 16"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M0 14.5C0 15.3281 0.671875 16 1.5 16H12.5C13.3281 16 14 15.3281 14 14.5V6H0V14.5ZM10 8.375C10 8.16875 10.1688 8 10.375 8H11.625C11.8312 8 12 8.16875 12 8.375V9.625C12 9.83125 11.8312 10 11.625 10H10.375C10.1688 10 10 9.83125 10 9.625V8.375ZM10 12.375C10 12.1688 10.1688 12 10.375 12H11.625C11.8312 12 12 12.1688 12 12.375V13.625C12 13.8312 11.8312 14 11.625 14H10.375C10.1688 14 10 13.8312 10 13.625V12.375ZM6 8.375C6 8.16875 6.16875 8 6.375 8H7.625C7.83125 8 8 8.16875 8 8.375V9.625C8 9.83125 7.83125 10 7.625 10H6.375C6.16875 10 6 9.83125 6 9.625V8.375ZM6 12.375C6 12.1688 6.16875 12 6.375 12H7.625C7.83125 12 8 12.1688 8 12.375V13.625C8 13.8312 7.83125 14 7.625 14H6.375C6.16875 14 6 13.8312 6 13.625V12.375ZM2 8.375C2 8.16875 2.16875 8 2.375 8H3.625C3.83125 8 4 8.16875 4 8.375V9.625C4 9.83125 3.83125 10 3.625 10H2.375C2.16875 10 2 9.83125 2 9.625V8.375ZM2 12.375C2 12.1688 2.16875 12 2.375 12H3.625C3.83125 12 4 12.1688 4 12.375V13.625C4 13.8312 3.83125 14 3.625 14H2.375C2.16875 14 2 13.8312 2 13.625V12.375ZM12.5 2H11V0.5C11 0.225 10.775 0 10.5 0H9.5C9.225 0 9 0.225 9 0.5V2H5V0.5C5 0.225 4.775 0 4.5 0H3.5C3.225 0 3 0.225 3 0.5V2H1.5C0.671875 2 0 2.67188 0 3.5V5H14V3.5C14 2.67188 13.3281 2 12.5 2Z"
                    fill="#979797"
                  />
                </svg>
                24.10.2020
              </li>
            </ul>
          </div>
        </div>
        <div class="ideas__item-like like">
          <div class="like__circle">
            <svg
              width="26"
              height="27"
              viewBox="0 0 26 27"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M0.200001 14.52C0.200001 14.2048 0.262079 13.8928 0.38269 13.6016C0.503301 13.3104 0.680084 13.0458 0.902945 12.823C1.12581 12.6001 1.39038 12.4233 1.68156 12.3027C1.97274 12.1821 2.28483 12.12 2.6 12.12C2.91517 12.12 3.22726 12.1821 3.51844 12.3027C3.80962 12.4233 4.0742 12.6001 4.29706 12.823C4.51992 13.0458 4.6967 13.3104 4.81731 13.6016C4.93792 13.8928 5 14.2048 5 14.52V24.12C5 24.7565 4.74714 25.367 4.29706 25.8171C3.84697 26.2672 3.23652 26.52 2.6 26.52C1.96348 26.52 1.35303 26.2672 0.902945 25.8171C0.452857 25.367 0.200001 24.7565 0.200001 24.12V14.52ZM6.6 14.2528V22.9408C6.59972 23.5355 6.76515 24.1185 7.07773 24.6243C7.3903 25.1302 7.83766 25.539 8.3696 25.8048L8.4496 25.8448C9.33742 26.2885 10.3163 26.5197 11.3088 26.52H19.9744C20.7144 26.5203 21.4317 26.2641 22.0041 25.795C22.5765 25.3259 22.9685 24.6729 23.1136 23.9472L25.0336 14.3472C25.1264 13.883 25.115 13.404 25.0003 12.9447C24.8856 12.4854 24.6705 12.0573 24.3703 11.6912C24.0702 11.3251 23.6926 11.0302 23.2647 10.8277C22.8369 10.6251 22.3694 10.5201 21.896 10.52H16.2V4.12001C16.2 3.27132 15.8629 2.45739 15.2627 1.85727C14.6626 1.25716 13.8487 0.920013 13 0.920013C12.5757 0.920013 12.1687 1.08858 11.8686 1.38864C11.5686 1.6887 11.4 2.09567 11.4 2.52001V3.58721C11.4 4.97198 10.9509 6.3194 10.12 7.42721L7.88 10.4128C7.04914 11.5206 6.6 12.868 6.6 14.2528Z"
                fill="#D3D4D6"
              />
            </svg>
          </div>
          <div class="like__count">12</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import "./style.scss";

@Component({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>