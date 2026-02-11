*,
*::before,
*::after {
  box-sizing: border-box;
}

html {
  block-size: 100%;
}

.page {
  inline-size: 1200px;
  block-size: 100%;
  margin: auto;
  color: #fff;
  font-family: 'Fira Sans Condensed', sans-serif;
  font-size: 18px;
  background-color: #1b1919;
}

h1,
h2,
h3,
h4,
p,
ul,
ol,
li,
blockquote,
fieldset {
  margin: 0;
  padding: 0;
}

ul,
ol {
  list-style: none;
}

/* Кастомный скроллбар */
.custom-scrollbar::-webkit-scrollbar {
  width: 4px;
}

.custom-scrollbar::-webkit-scrollbar-track {
  background: rgb(217 217 217 / 10%);
}

.custom-scrollbar::-webkit-scrollbar-thumb {
  background-color: #D9D9D9;
}

/* ШАГ 1: ЛЕЙАУТ */

.page {
  display: flex;
  justify-content: center;
  align-items: center;
  min-block-size: 100vh;
}

.content {
  display: grid;
  grid-template-columns: 1fr 399px;
  grid-template-rows: auto 1fr;
  grid-template-areas:
    "result search"
    "result list";
  column-gap: 30px;
  row-gap: 16px;
  align-items: end;
}

.result {
  grid-area: result;
}

.search-form {
  grid-area: search;
  display: flex;
  flex-direction: column;
  row-gap: 30px;
}

.content__details {
  grid-area: list;
  display: flex;
  flex-direction: column;
}

.content__list-container {
  block-size: 298px;
  overflow-y: auto;
  overflow-x: hidden;
  position: relative;
}

/* ШАГ 2: РАЗМЕРЫ КОНТЕЙНЕРОВ */

.result__video-container {
  inline-size: 100%;
  block-size: 386px;
  position: relative;
  margin-block-end: 16px;
  background-color: #000;
}

.result__video {
  inline-size: 100%;
  block-size: 100%;
  object-fit: cover;
}

.content__list {
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.content__list-item {
  padding-inline: 3px;
}

.content__video-card {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  gap: 16px;
}

.content__video-card-description-container {
  display: flex;
  flex-direction: column;
  row-gap: 6px;
  flex-grow: 1;
}

.content__video-card-thumbnail {
  inline-size: 194px;
  block-size: 103px;
  flex-shrink: 0;
}

.content__video-card-thumbnail img {
  inline-size: 100%;
  block-size: 100%;
  object-fit: cover;
  object-position: center;
}

/* ШАГ 3: ТИПОГРАФИКА */

.search-form__fieldset-title {
  font-size: 18px;
  font-weight: 400;
  margin-block-end: 5px;
  line-height: 1.3;
}

.title {
  font-family: "Oswald", sans-serif;
  font-size: 75px;
  font-weight: 700;
  text-transform: uppercase;
  line-height: 0.94;
  margin-block-end: 26px;
}

.content__accent {
  color: #545050;
}

.content__card-link {
  text-decoration: none;
  color: inherit;
  display: block;
}

.content__video-card-title {
  font-family: "Oswald", sans-serif;
  font-size: 24px;
  font-weight: 700;
  text-transform: uppercase;
  line-height: 1;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.content__video-card-description {
  font-size: 18px;
  line-height: 1.12;
  display: -webkit-box;
  -webkit-line-clamp: 4;
  -webkit-box-orient: vertical;
  overflow: hidden;
}

/* visually-hidden */

.visually-hidden {
  position: absolute;
  inline-size: 1px;
  block-size: 1px;
  overflow: hidden;
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  white-space: nowrap;
}

/* ШАГ 4: ФОРМЫ */

.search-form__fieldset {
  border: none;
}

.search-form__fieldset:nth-child(1),
.search-form__fieldset:nth-child(2) {
  flex-grow: 1;
}

.search-form__checkbox-list {
  display: flex;
  gap: 15px;
  margin-block-start: 5px;
}

.search-form__label {
  display: flex;
  align-items: center;
  gap: 8px;
  width: fit-content;
}

.search-form__textfield {
  inline-size: 225px;
  border: none;
  border-block: 1px solid #fff;
  padding-block: 2px;
  padding-inline: 0;
  background-color: transparent;
  color: #fff;
  font: inherit;
  appearance: none;
}

.search-form__label:has(.search-form__textfield:focus-visible) {
  outline: 1px solid #fff;
  outline-offset: 2px;
}

.search-form__textfield:focus {
  outline: none;
}

/* ЧЕКБОКс */

.search-form__pseudo-checkbox {
  inline-size: 19px;
  block-size: 19px;
  border: 1px solid #fff;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}

.search-form__pseudo-checkbox::after {
  content: "";
  inline-size: 15px;
  block-size: 15px;
  background-color: #fff;
  opacity: 0;
}

.search-form__checkbox:checked + .search-form__pseudo-checkbox::after {
  opacity: 1;
}

.search-form__label:has(.search-form__checkbox:focus-visible) {
  outline: 1px solid #fff;
  outline-offset: 2px;
}

.search-form__checkbox:focus {
  outline: none;
}

.search-form__label:hover .search-form__label-text {
  text-decoration: underline;
}

/* ШАГ 5: КНОПКИ */

.button {
  border: 1px solid #fff;
  background-color: transparent;
  color: #fff;
  font: inherit;
  text-transform: uppercase;
  cursor: pointer;
  padding: 0;
}

.search-form__submit-button {
  inline-size: 194px;
  block-size: 34px;
}

.more-button {
  inline-size: 100%;
  block-size: 34px;
  margin-block-start: 30px;
}

.button:hover {
  text-decoration: underline;
}

.button:active {
  background-color: #545050;
}

.button:focus {
  outline: none;
}

.button:focus-visible {
  outline: 1px solid #fff;
  outline-offset: 2px;
}

/* ШАГ 6: КАРТОЧКИ */

.content__card-link_current {
  background-color: #545050;
}

.content__card-link:hover {
  text-decoration: underline;
}

.content__card-link:active {
  background-color: #545050;
}

.content__card-link:focus {
  outline: none;
}

.content__card-link:focus-visible {
  outline: 1px solid #fff;
  outline-offset: 2px;
}

/* ШАГ 7-8: КЛИКАБЕЛЬНОСТЬ И ПОЗИЦОНИРОВАНИЕ */

.result__video-container,
.content__list-container {
  position: relative;
}
