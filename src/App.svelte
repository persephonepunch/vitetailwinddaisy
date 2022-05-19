<script>
 
  import {fade} from 'svelte/transition';
  export let name="Peter";


</script>

<style>
.w-layout-grid {
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  -ms-grid-columns: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  -ms-grid-rows: auto auto;
  grid-template-rows: auto auto;
  grid-row-gap: 16px;
  grid-column-gap: 16px;
}

body {
  font-family: Manrope;
  color: #000;
  font-size: 1vw;
  line-height: 1.2em;
}

h1 {
  margin-top: 0px;
  margin-bottom: 0px;
  font-size: 4.25em;
  line-height: 1.1em;
}

h2 {
  margin-top: 0px;
  margin-bottom: 0px;
  font-size: 3.375em;
  line-height: 1.1em;
}

h3 {
  margin-top: 0px;
  margin-bottom: 0px;
  font-size: 2.25em;
  line-height: 1.2em;
}

h4 {
  margin-top: 0px;
  margin-bottom: 0px;
  font-size: 1.75em;
  line-height: 1.2em;
}

h5 {
  margin-top: 3em;
  margin-bottom: 1.1em;
  font-size: 1.2em;
  line-height: 1.2em;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

h6 {
  margin-top: 0px;
  margin-bottom: 0px;
  font-size: 1em;
  line-height: 1.2em;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

p {
  margin-bottom: 10px;
  line-height: 1.4em;
}

a {
  font-family: sofia-pro;
  color: #000;
  text-decoration: none;
}

ul {
  margin-top: 0px;
  margin-bottom: 10px;
  padding-left: 40px;
}

ol {
  margin-top: 0px;
  margin-bottom: 10px;
  padding-left: 40px;
}

blockquote {
  margin-bottom: 10px;
  padding: 10px 20px;
  border-left: 5px solid #e2e2e2;
  font-size: 18px;
  line-height: 22px;
}

figure {
  margin-bottom: 10px;
}

.p-sm-end {
  padding-bottom: 3em;
}

.container-w2 {
  width: 100%;
  max-width: 83.125em;
  margin-right: auto;
  margin-left: auto;
}

.title1 {
  margin-top: 31px;
  font-family: sofia-pro;
  color: #fff;
  font-size: 4.25em;
  line-height: 1.1em;
  font-weight: 200;
}

.p-xs-start {
  padding-top: 1.6em;
}

.container-w3 {
  width: 100%;
  max-width: 67em;
  margin-right: auto;
  margin-left: auto;
}

.title2 {
  margin-top: 38px;
  font-family: sofia-pro;
  font-size: 3.375em;
  line-height: 1.1em;
  font-weight: 600;
}

.gutter-outside {
  padding-right: 3.75em;
  padding-left: 3.75em;
}

.copy-medium {
  font-family: sofia-pro;
  color: #fff;
  font-size: 1.3em;
  line-height: 1.45em;
  font-weight: 400;
}

.copy-medium.text-grey {
  color: #707070;
}

.p-xxs-end {
  padding-bottom: 1.1em;
}

.p-xl-end {
  padding-bottom: 8.5em;
  border-bottom: 1px none #000;
  border-left: 0px none #000;
}

.p-xs-end {
  padding-bottom: 1.6em;
}

.p-xl-start {
  padding-top: 0em;
}

.header {
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-bottom: 0px solid #d3d3d3;
}

.container-w1 {
  width: 100%;
  max-width: 95em;
  margin-right: auto;
  margin-left: auto;
}

.container-w1.gutter-outside {
  max-width: 99em;
  padding-right: 1em;
  padding-left: 1em;
}

.footer {
  position: relative;
  height: 100%;
}

.section-tutorial.lineabove {
  border-top: 1px solid #000;
}

.text-center {
  text-align: center;
}

.section-intro {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #fd5a85;
  background-image: none;
}

.intro-description {
  padding-top: 2em;
}

.header-button {
  display: inline-block;
  padding: 1em 1.6em;
  border: 1px none #000;
  border-radius: 999em;
  background-color: #fd5a85;
  -webkit-transition: all 350ms cubic-bezier(.165, .84, .44, 1);
  transition: all 350ms cubic-bezier(.165, .84, .44, 1);
  color: #fff;
  font-size: 0.65em;
  line-height: 1;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-decoration: none;
  text-transform: uppercase;
}

.header-button:hover {
  padding-right: 3.5em;
  padding-left: 3.5em;
  color: #fff;
}

.header-button.secondary {
  border-style: solid;
  border-width: 1px;
  background-color: transparent;
  color: #000;
}

.section-blog-overview {
  overflow: hidden;
}

.blog-header-title {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-perspective: 3em;
  perspective: 3em;
  -webkit-perspective-origin: 50% 0%;
  perspective-origin: 50% 0%;
  font-family: Inconsolata, monospace;
  font-size: 10em;
  font-weight: 400;
  text-align: right;
  letter-spacing: -4px;
  text-transform: uppercase;
}

.blog-overview-grid {
  width: 100%;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  -ms-grid-columns: 1.75fr 1.75fr 1fr 1fr;
  grid-template-columns: 1.75fr 1.75fr 1fr 1fr;
  -ms-grid-rows: auto auto auto auto auto;
  grid-template-rows: auto auto auto auto auto;
  border-style: none;
  border-width: 1px 1px 0px 0px;
  border-color: #000;
}

.blog-teaser-item-wrapper {
  padding: 3.5em 2em;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  border-top: 0px none #000;
  border-right: 1px solid #000;
  border-bottom: 1px solid #000;
}

.blog-teaser-item-wrapper.quote {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding: 8em 4em;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-left: 1px solid rgba(0, 0, 0, 0.5);
  border-right-style: none;
  border-right-color: rgba(0, 0, 0, 0.5);
  border-bottom-style: solid;
  border-bottom-color: rgba(0, 0, 0, 0.5);
  text-align: center;
}

.blog-teaser-item-wrapper.page-teaser {
  padding-top: 2em;
  padding-bottom: 2em;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-top-style: solid;
  border-top-width: 1px;
}

.blog-teaser-item-wrapper.leftalso {
  border-left: 1px solid rgba(0, 0, 0, 0.5);
}

.blog-teaser-meta-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  font-size: 1.2em;
}

.blog-teaser-category {
  display: none;
  font-family: stolzl, sans-serif;
  font-size: 0.9em;
  font-weight: 400;
  letter-spacing: 0.05em;
  text-transform: uppercase;
}

.blog-teaser-date {
  display: none;
  font-family: stolzl, sans-serif;
  font-size: 0.9em;
}

.blog-teaser-image-wrapper {
  overflow: hidden;
  height: 100%;
  margin-top: 1.4em;
  margin-bottom: 1.4em;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}

.blog-teaser-text-wrapper {
  overflow: hidden;
  max-height: 4.2em;
}

.blog-teaser-title {
  display: inline;
  font-family: stolzl, sans-serif;
  line-height: 1.4em;
  font-weight: 700;
}

.blog-teaser-summary {
  display: inline;
  font-family: stolzl, sans-serif;
  line-height: 1.4em;
}

.blog-teaser-text-divider {
  display: inline;
  margin-right: 0.3em;
  margin-left: 0.3em;
  font-weight: 700;
}

.blog-teaser-quote {
  font-family: stolzl, sans-serif;
  font-size: 2.4em;
  line-height: 1.2;
  font-weight: 200;
  letter-spacing: 0.04em;
  text-transform: none;
}

.blog-teaser-item {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100%;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
}

.blog-teaser-list {
  height: 100%;
}

.blog-teaser-list-wrapper {
  height: 100%;
}

.blog-teaser-image {
  width: 100%;
  height: 100%;
  -webkit-transition: all 800ms cubic-bezier(.165, .84, .44, 1);
  transition: all 800ms cubic-bezier(.165, .84, .44, 1);
  -o-object-fit: cover;
  object-fit: cover;
}

.blog-teaser-title-wrapper {
  color: #000;
  text-decoration: none;
}

.page-teaser-image {
  position: absolute;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  width: 100%;
  height: 100%;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  -o-object-fit: cover;
  object-fit: cover;
}

.page-teaser-text-wrapper {
  position: relative;
  z-index: 2;
  padding: 6.5em 10.2em;
  font-family: sofia-pro;
  color: #fff;
  text-align: center;
}

.page-teaser-title {
  font-family: stolzl, sans-serif;
  font-size: 3.5em;
  line-height: 1.15em;
  font-weight: 100;
}

.social-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100%;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.social-title {
  font-family: stolzl, sans-serif;
  font-size: 1.2em;
  letter-spacing: 0.04em;
  text-transform: uppercase;
}

.social-link {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-top: 0.7em;
  margin-bottom: 0.7em;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-transition: all 200ms ease;
  transition: all 200ms ease;
  color: #000;
  font-size: 1.5em;
  text-decoration: none;
}

.social-link:hover {
  -webkit-transform: scale(1.2);
  -ms-transform: scale(1.2);
  transform: scale(1.2);
  color: #f39a0e;
}

.social-icon {
  width: 1.5em;
  height: 1.5em;
}

.social-icon:hover {
  color: #707070;
}

.quote-author-wrapper {
  margin-top: 1em;
}

.quote-author {
  margin-bottom: 30px;
  font-family: stolzl, sans-serif;
}

.page-teaser-subtitle {
  font-family: stolzl, sans-serif;
  font-size: 1.15em;
  font-weight: 500;
  letter-spacing: 0.25em;
  text-transform: uppercase;
}

.page-teaser-gradient {
  position: absolute;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: 1;
  background-image: linear-gradient(163deg, hsla(0, 0%, 100%, 0) 9%, rgba(60, 35, 1, 0.6) 83%);
}

.page-teaser-wrapper {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: 100%;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.blog-header-title-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: end;
  -webkit-justify-content: flex-end;
  -ms-flex-pack: end;
  justify-content: flex-end;
}

.blog-header-title-letter {
  display: block;
}

.blog-header-title-letter._1 {
  text-transform: none;
}

.blog-header-title-letter._2 {
  text-transform: none;
}

.blog-header-title-letter._3 {
  padding-right: 0.3em;
  text-transform: none;
}

.blog-header-title-letter._4 {
  text-transform: none;
}

.blog-header-divider-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: 1px;
  margin-top: 1em;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
}

.position-realtive {
  position: relative;
}

.grid-border-line-wrapper {
  position: absolute;
  left: 0%;
  top: 0%;
  right: auto;
  bottom: auto;
  width: 2px;
  height: 100%;
  background-color: #fff;
}

.grid-border-line-wrapper.right {
  left: auto;
  top: 0%;
  right: 0%;
  bottom: auto;
}

.grid-border-line {
  position: absolute;
  left: auto;
  top: 0%;
  right: 0%;
  bottom: auto;
  width: 1px;
  height: 100%;
  background-color: #000;
}

.blog-header-divider-inner {
  position: relative;
  width: 50%;
  height: 1px;
}

.blog-header-divider {
  position: absolute;
  left: auto;
  top: 0%;
  right: 0%;
  bottom: auto;
  width: 100%;
  height: 1px;
  background-color: #000;
}

.blog-header-divider.right {
  left: 0%;
  top: 0%;
  right: auto;
  bottom: auto;
  width: 100%;
}

.blog-teaser-image-inner {
  height: 100%;
}

.button {
  position: relative;
  overflow: hidden;
  margin-bottom: 0px;
  padding: 1.2em 2.5em;
  border: 0px none transparent;
  border-radius: 999em;
  background-color: #fff;
  background-image: linear-gradient(135deg, #000 13%, #0e0e0d 50%, #1a1b18 82%, #252525);
  -webkit-transition: all 500ms cubic-bezier(.165, .84, .44, 1);
  transition: all 500ms cubic-bezier(.165, .84, .44, 1);
  color: #fff;
  font-size: 1em;
  line-height: 1.1em;
  font-weight: 600;
  text-align: center;
  letter-spacing: 0.02em;
  text-decoration: none;
}

.button:hover {
  background-color: #f16161;
  background-image: linear-gradient(135deg, #000 13%, #0e0e0d 50%, #1a1b18 82%, #252525);
  box-shadow: inset 1px 1px 30em 0 #f8ffad;
  -webkit-transform: scale(1.06);
  -ms-transform: scale(1.06);
  transform: scale(1.06);
}

.button:active {
  -webkit-transform: scale(0.96);
  -ms-transform: scale(0.96);
  transform: scale(0.96);
}

.text-dark {
  color: #fff;
}

.header-button-wrapper {
  margin-right: 1em;
}

.header-inner {
  display: none;
  padding-top: 1em;
  padding-bottom: 1em;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.header-inner:hover {
  font-family: sofia-pro;
  color: #fff;
}

.header-left {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.infotext {
  color: #707070;
  font-size: 0.9em;
}

.text-grey {
  color: #707070;
}

.video-description {
  margin-top: 1em;
  margin-bottom: 4em;
}

.buynow {
  font-family: stolzl, sans-serif;
  font-weight: 400;
  text-decoration: none;
}

.buynow:hover {
  color: #968f8e;
}

.button-2 {
  background-color: #000;
  color: #fff;
  text-decoration: none;
}

.default-button {
  margin-top: 37px;
  padding: 13px 20px;
  background-color: #707070;
  font-family: stolzl, sans-serif;
  font-weight: 200;
}

.div-block {
  font-family: sofia-pro;
}

.formquarter {
  position: relative;
  min-height: 500px;
}

.formclear {
  height: 65px;
  background-color: transparent;
  -webkit-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
}

.abctradesmalls {
  padding: 44px;
  background-color: #fcf9f3;
}

.form-block-custom {
  color: #131313;
}

.abcform-grid {
  position: relative;
  grid-row-gap: 16px;
  -ms-grid-columns: 1fr;
  grid-template-columns: 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
  color: #131313;
}

.abctradewrap {
  position: relative;
  width: 100%;
  height: auto;
  border-top: 1px none #000;
  -o-object-fit: cover;
  object-fit: cover;
}

.grid-8 {
  grid-column-gap: 0px;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.abctradesmimagecontainer {
  position: relative;
  overflow: hidden;
  width: 20vw;
  height: 20vw;
}

.div-block-2 {
  width: 20vw;
  padding-top: 10px;
  padding-bottom: 31px;
}

.formcenter {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-top: 19px;
  margin-bottom: 30px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  font-family: sofia-pro;
  font-weight: 200;
}

.trade2 {
  margin-right: auto;
  margin-bottom: 45px;
  margin-left: auto;
  padding: 19px 5%;
  background-color: #fcf9f3;
}

.abclabel {
  color: #fff;
  font-size: 9px;
  font-weight: 400;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.smallhead {
  margin-bottom: 21px;
  font-family: stolzl, sans-serif;
  color: #fff;
  font-size: 0.9rem;
  font-weight: 300;
  letter-spacing: 0.2em;
  text-transform: none;
}

.button-abcgrid {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 200px;
  max-width: 200px;
  min-width: 150px;
  padding: 21px 0px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #707070;
  font-family: stolzl, sans-serif;
  color: #f7f5ed;
}

.button-abcgrid:hover {
  color: #000;
}

.button-abcgrid.reverse {
  width: 100%;
  max-width: none;
  background-color: #fff;
  color: #131313;
  font-size: 11px;
}

.trio {
  display: -ms-grid;
  display: grid;
  width: 90vw;
  max-width: 1200px;
  margin: 25px auto;
  padding-right: 2%;
  padding-left: 2%;
  grid-auto-columns: 1fr;
  grid-column-gap: 30px;
  grid-row-gap: 16px;
  -ms-grid-columns: 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.form-custom {
  position: relative;
  z-index: 90;
  display: -ms-grid;
  display: grid;
  overflow: visible;
  width: 80vw;
  max-width: 1500px;
  grid-auto-columns: 1fr;
  grid-column-gap: 16px;
  grid-row-gap: 16px;
  -ms-grid-columns: 1fr 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  -ms-grid-rows: auto auto;
  grid-template-rows: auto auto;
  -webkit-transform: translate(0px, 0px);
  -ms-transform: translate(0px, 0px);
  transform: translate(0px, 0px);
  -o-object-fit: cover;
  object-fit: cover;
}

.type {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  min-height: 50vw;
  padding-right: 15%;
  padding-left: 15%;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -o-object-fit: cover;
  object-fit: cover;
}

.abctradesmtext {
  font-family: sofia-pro;
  font-size: 0.9rem;
  line-height: 120%;
  font-weight: 400;
}

.abctradesmtext.bottommg {
  margin-bottom: 9px;
  font-family: sofia-pro;
  font-size: 0.8rem;
  font-weight: 300;
}

.image-7 {
  position: absolute;
  width: 100%;
  height: 100%;
  min-height: auto;
  -o-object-fit: cover;
  object-fit: cover;
}

.abctradehero {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  min-height: 550px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #fff;
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.44)), to(rgba(0, 0, 0, 0.44))), url('../images/static-pages-TRADE-HERO.jpeg');
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.44), rgba(0, 0, 0, 0.44)), url('../images/static-pages-TRADE-HERO.jpeg');
  background-position: 0px 0px, 50% 50%;
  background-size: auto, cover;
  font-family: sofia-pro;
  color: #131313;
}

.error-message-abctrade {
  background-color: #fcfcfc;
}

.abctradesmimage {
  width: 100%;
  height: 100%;
  max-width: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}

.abctradesmallsquarterwrap {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: auto;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.grid-9 {
  -ms-grid-columns: 1fr 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.text-block-11 {
  font-family: sofia-pro;
  font-size: 1.3em;
  line-height: 140%;
  font-weight: 400;
}

.copysub {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  min-height: 50vw;
  padding-right: 15%;
  padding-left: 15%;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -o-object-fit: cover;
  object-fit: cover;
}

.text-block-10 {
  font-family: sofia-pro;
  font-size: 1em;
  line-height: 140%;
  font-weight: 400;
}

.section {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  min-height: 90vh;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.5)), to(rgba(0, 0, 0, 0.5))), url('../images/©Jane-Beiles-9456-2.jpg');
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('../images/©Jane-Beiles-9456-2.jpg');
  background-position: 0px 0px, 50% 50%;
  background-size: auto, cover;
  font-family: stolzl, sans-serif;
}

.image-8 {
  background-color: rgba(0, 0, 0, 0.61);
}

.heading {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: stolzl, sans-serif;
  color: #fff;
  font-size: 3em;
  font-weight: 200;
  letter-spacing: 0.5em;
}

.heading.bold {
  font-weight: 100;
}

.h6small {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 8px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: stolzl, sans-serif;
  color: #fff;
  font-size: 1.3em;
  font-weight: 100;
  letter-spacing: 0.4em;
}

.section-2 {
  min-height: 90vh;
  border-style: none;
  border-width: 0px 1px 1px;
  border-color: #000;
  background-color: #f9fdfc;
}

.div-block-3 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 400px;
  height: 100px;
  margin-left: 2%;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.div-block-4 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-right: auto;
  margin-left: auto;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  border-bottom: 1px solid rgba(0, 0, 0, 0.4);
  background-color: #fff;
}

.div-block-5 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  min-height: 90vh;
  margin-bottom: 102px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  border-bottom: 1px solid rgba(0, 0, 0, 0.4);
}

.quoteleft {
  width: 5%;
  border-right: 1px solid rgba(0, 0, 0, 0.4);
}

.rightquote {
  width: 5%;
  border-left: 1px solid rgba(0, 0, 0, 0.4);
}

.containerline {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  max-width: 95em;
  margin-right: auto;
  margin-left: auto;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-right: 1px solid rgba(0, 0, 0, 0.4);
  border-left: 1px solid rgba(0, 0, 0, 0.4);
}

.containerline.gutter-outside {
  max-width: 99em;
  padding-right: 1em;
  padding-left: 1em;
}

.containerline-copy {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  max-width: 95em;
  margin-right: auto;
  margin-left: auto;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-right: 1px solid rgba(0, 0, 0, 0.4);
  border-left: 1px solid rgba(0, 0, 0, 0.83);
}

.containerline-copy.gutter-outside {
  max-width: 99em;
  padding-right: 1em;
  padding-left: 1em;
}

.marthaquote {
  max-width: 550px;
  margin-right: auto;
  margin-left: auto;
  font-family: stolzl, sans-serif;
  font-size: 2.5em;
  line-height: 2em;
  font-weight: 100;
}

.herotitle {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.homelogo {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.grid-10 {
  width: 500px;
  max-width: 700px;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.heading1 {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: stolzl, sans-serif;
  color: #fff;
  font-size: 3em;
  font-weight: 100;
  letter-spacing: 0.5em;
}

.heading1.bold {
  font-weight: 100;
}

.heading2 {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: stolzl, sans-serif;
  color: #fff;
  font-size: 3em;
  font-weight: 200;
  letter-spacing: 0.5em;
}

.heading2.bold {
  font-weight: 100;
}

.image-9 {
  width: 400px;
}

.gridabout {
  max-width: 1400px;
  margin-top: 26px;
  grid-column-gap: 35px;
  grid-row-gap: 35px;
}

.abouthead {
  margin-bottom: 32px;
  padding-bottom: 0px;
  font-family: stolzl, sans-serif;
  font-size: 2em;
  font-weight: 100;
}

.abouttext {
  margin-bottom: 19px;
  font-family: stolzl, sans-serif;
  font-size: 0.9vw;
  line-height: 150%;
  font-weight: 300;
}

.div-block-7 {
  padding-right: 5%;
  padding-left: 5%;
}

.section-3 {
  min-height: 90vh;
  margin-bottom: 81px;
  background-color: #f9fdfc;
}

.sectionabout {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  min-height: 90vh;
  margin-bottom: 0px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  border-top: 1px solid rgba(0, 0, 0, 0.5);
  border-bottom: 1px solid rgba(0, 0, 0, 0.4);
}

.html-embed {
  font-family: stolzl, sans-serif;
  font-weight: 100;
}

.section-home {
  position: relative;
  display: block;
  min-height: 90vh;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.5)), to(rgba(0, 0, 0, 0.5))), url('../images/©Jane-Beiles-9456-2.jpg');
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('../images/©Jane-Beiles-9456-2.jpg');
  background-position: 0px 0px, 50% 50%;
  background-size: auto, cover;
  font-family: stolzl, sans-serif;
}

.sectionhead {
  position: absolute;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: 100%;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.div-block-8 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-right: 2%;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  font-family: stolzl, sans-serif;
  font-weight: 200;
  cursor: pointer;
}

.link-block {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.heading-2 {
  font-family: stolzl, sans-serif;
  font-weight: 200;
}

.field-label {
  position: relative;
  font-family: stolzl, sans-serif;
  font-weight: 200;
}

.text-field {
  min-height: 60px;
  margin-bottom: 33px;
  font-family: stolzl, sans-serif;
}

.textarea {
  min-height: 150px;
  font-family: stolzl, sans-serif;
  font-weight: 300;
}

.section-form {
  min-height: 90vh;
  background-color: #fff;
}

.div-block-9 {
  padding: 123px;
  border-top: 0px none transparent;
}

.section-4 {
  padding: 79px;
}

.div-block-10 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.grid-11 {
  grid-column-gap: 16px;
}

.leftline {
  width: 1px;
  height: 100%;
  background-color: #000;
}

.social-icon-2 {
  width: 1.5em;
  height: 1.5em;
}

.page-teaser-title-2 {
  font-family: stolzl, sans-serif;
  font-size: 3.5em;
  line-height: 1.15em;
  font-weight: 100;
}

.blog-header-divider-2 {
  position: absolute;
  left: auto;
  top: 0%;
  right: 0%;
  bottom: auto;
  width: 100%;
  height: 1px;
  background-color: #000;
}

.blog-header-divider-2.right {
  left: 0%;
  top: 0%;
  right: auto;
  bottom: auto;
  width: 100%;
}

.page-teaser-text-wrapper-2 {
  position: relative;
  z-index: 2;
  padding: 6.5em 10.2em;
  color: #fff;
  text-align: center;
}

.p-xl-end-2 {
  margin-bottom: 10px;
  padding-bottom: 5.4em;
}

.social-title-2 {
  font-family: stolzl, sans-serif;
  font-size: 1.2em;
  letter-spacing: 0.04em;
  text-transform: uppercase;
}

.grid-border-line-wrapper-2 {
  position: absolute;
  left: 0%;
  top: 0%;
  right: auto;
  bottom: auto;
  width: 2px;
  height: 100%;
  background-color: #fff;
}

.grid-border-line-wrapper-2.right {
  left: auto;
  top: 0%;
  right: 0%;
  bottom: auto;
}

.blog-overview-grid-2 {
  width: 100%;
  grid-column-gap: 0px;
  grid-row-gap: 0px;
  -ms-grid-columns: 1.75fr 1.75fr 1fr 1fr;
  grid-template-columns: 1.75fr 1.75fr 1fr 1fr;
  -ms-grid-rows: auto auto auto auto auto;
  grid-template-rows: auto auto auto auto auto;
}

.blog-teaser-quote-2 {
  font-family: stolzl, sans-serif;
  font-size: 2.4em;
  line-height: 1.2;
  font-weight: 200;
  letter-spacing: 0.04em;
  text-transform: none;
}

.default-button-2 {
  padding: 13px 20px;
  background-color: #fd5a85;
}

.page-teaser-subtitle-2 {
  font-family: stolzl, sans-serif;
  font-size: 1.15em;
  font-weight: 500;
  letter-spacing: 0.25em;
  text-transform: uppercase;
}

.blog-teaser-item-wrapper-2 {
  padding: 3.5em 2em;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  border-right: 1px solid #000;
  border-bottom: 1px solid #000;
}

.blog-teaser-item-wrapper-2.page-teaser {
  padding-top: 2em;
  padding-bottom: 2em;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.blog-teaser-item-wrapper-2.quote {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding: 8em 4em;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  text-align: center;
}

.social-link-2 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-top: 0.7em;
  margin-bottom: 0.7em;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-transition: all 200ms ease;
  transition: all 200ms ease;
  color: #000;
  font-size: 1.5em;
  text-decoration: none;
}

.social-link-2:hover {
  -webkit-transform: scale(1.2);
  -ms-transform: scale(1.2);
  transform: scale(1.2);
  color: #f39a0e;
}

.grid-border-line-2 {
  position: absolute;
  left: auto;
  top: 0%;
  right: 0%;
  bottom: auto;
  width: 1px;
  height: 100%;
  background-color: #000;
}

.menu {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
}

.menu-left {
  position: relative;
  left: 0%;
  top: 0%;
  right: auto;
  bottom: auto;
  z-index: 99999999999;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100vh;
  padding-top: 10px;
  padding-bottom: 50px;
  padding-left: 10px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.menu-2 {
  position: static;
  left: 0%;
  top: 0%;
  right: auto;
  bottom: 0%;
  z-index: 99999;
  width: 60px;
  margin-top: 0px;
  margin-left: 0px;
  cursor: pointer;
}

.menu-left-2 {
  position: fixed;
  z-index: 99999999999;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100vh;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-left: 50px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.menu-3 {
  position: static;
  left: 0%;
  top: 0%;
  right: auto;
  bottom: 0%;
  z-index: 99999;
  width: 60px;
  margin-left: -20px;
  cursor: pointer;
}

.social-links {
  margin-bottom: 23px;
  opacity: 0.2;
  -webkit-transition: opacity 200ms ease;
  transition: opacity 200ms ease;
  font-family: stolzl, sans-serif;
  color: #fff;
  font-size: 13px;
  line-height: 130%;
  letter-spacing: 1.04px;
  text-decoration: none;
  text-transform: uppercase;
}

.social-links:hover {
  opacity: 1;
}

.social-links.w--current {
  margin-bottom: 23px;
  padding-bottom: 0px;
  opacity: 0.2;
  font-family: Montserrat, sans-serif;
  color: #fff;
  font-size: 13px;
  line-height: 130%;
  font-weight: 700;
  letter-spacing: 1.04px;
  text-decoration: none;
  text-transform: uppercase;
}

.social-links.w--current:hover {
  opacity: 1;
}

.overlay {
  position: fixed;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: 88888;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100vw;
  height: 100vh;
  max-width: 1110px;
  margin-right: auto;
  margin-left: auto;
  padding: 0px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.menu-bg {
  position: fixed;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: 8888;
  display: block;
  background-color: #3a3a3d;
}

.socials {
  position: static;
  left: 45%;
  right: auto;
  z-index: 9999999;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-right: 170px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: end;
  -webkit-align-items: flex-end;
  -ms-flex-align: end;
  align-items: flex-end;
}

.showreel-title {
  margin-bottom: 0px;
}

.showreel-title.project {
  color: #fff;
  font-size: 24px;
}

.showreel {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-top: 40px;
  color: #c45af4;
  font-size: 18px;
  line-height: 100%;
  text-decoration: none;
}

.showreel.project {
  margin-top: 70px;
}

.div-block-11 {
  width: 16px;
  height: 2px;
  margin-bottom: 5px;
  background-color: #c15bf3;
}

.link {
  padding-top: 12px;
  padding-bottom: 12px;
  opacity: 0.3;
  -webkit-transition: opacity 200ms ease;
  transition: opacity 200ms ease;
  font-family: stolzl, sans-serif;
  color: #fff;
  font-size: 64px;
  line-height: 110%;
  font-weight: 100;
  text-decoration: none;
}

.link:hover {
  opacity: 1;
}

.link.w--current {
  opacity: 1;
}

.image {
  margin-left: 20px;
  color: #fff;
}

.menu-links {
  position: static;
  left: 65px;
  z-index: 999999;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-left: 65px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
}

.section-line {
  padding-top: 125px;
  padding-bottom: 92px;
  border-top: 1px solid rgba(0, 0, 0, 0.5);
}

.text-block-12 {
  font-family: stolzl, sans-serif;
  font-weight: 200;
}

@media screen and (max-width: 991px) {
  body {
    font-size: 14px;
  }

  .gutter-outside {
    padding-right: 6vw;
    padding-left: 6vw;
  }

  .p-xl-start {
    padding-top: 0.125em;
  }

  .section-tutorial {
    border-top: 1px solid #d4d4d4;
  }

  .header-button:hover {
    padding-right: 1.6em;
    padding-left: 1.6em;
  }

  .header-button:active {
    -webkit-transform: scale(0.94);
    -ms-transform: scale(0.94);
    transform: scale(0.94);
  }

  .blog-header-title {
    font-size: 15vw;
    text-align: left;
  }

  .blog-overview-grid {
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
    -ms-grid-rows: auto;
    grid-template-rows: auto;
  }

  .blog-teaser-item-wrapper {
    padding-top: 4em;
    padding-bottom: 4em;
  }

  .blog-teaser-item-wrapper.quote {
    padding: 3em;
  }

  .blog-teaser-quote {
    font-size: 1.7em;
  }

  .page-teaser-text-wrapper {
    padding-right: 2em;
    padding-left: 2em;
  }

  .page-teaser-title {
    font-size: 2.8em;
  }

  .social-link:hover {
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
    color: #000;
  }

  .blog-header-title-wrapper {
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }

  .button:hover {
    box-shadow: none;
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
  }

  .button:active {
    -webkit-transform: scale(0.94);
    -ms-transform: scale(0.94);
    transform: scale(0.94);
  }

  .header-inner {
    padding-top: 2em;
  }

  .formquarter {
    min-height: auto;
  }

  .abcheroform {
    width: 90%;
  }

  .form-custom {
    grid-column-gap: 16px;
    grid-row-gap: 16px;
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
  }

  .type {
    position: relative;
    width: 100%;
    height: 100%;
    min-height: 400px;
    -o-object-fit: cover;
    object-fit: cover;
  }

  .image-7 {
    position: relative;
    max-height: 50vw;
    max-width: 50vw;
    min-height: 50vw;
    min-width: 50vw;
    -o-object-fit: cover;
    object-fit: cover;
  }

  .copysub {
    position: relative;
    width: 100%;
    height: 100%;
    min-height: 400px;
    -o-object-fit: cover;
    object-fit: cover;
  }

  .marthaquote {
    font-size: 1.8em;
  }

  .gridabout {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .div-block-6 {
    padding-right: 5%;
    padding-left: 5%;
  }

  .page-teaser-title-2 {
    font-size: 2.8em;
  }

  .page-teaser-text-wrapper-2 {
    padding-right: 2em;
    padding-left: 2em;
  }

  .blog-overview-grid-2 {
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
    -ms-grid-rows: auto;
    grid-template-rows: auto;
  }

  .blog-teaser-quote-2 {
    font-size: 1.7em;
  }

  .blog-teaser-item-wrapper-2 {
    padding-top: 4em;
    padding-bottom: 4em;
  }

  .blog-teaser-item-wrapper-2.quote {
    padding: 3em;
  }

  .social-link-2:hover {
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
    color: #000;
  }

  .menu-left {
    position: fixed;
    left: 0px;
  }

  .menu-left-2 {
    position: fixed;
    left: 0px;
  }

  .menu-bg {
    display: block;
  }

  .socials {
    left: 20%;
    margin-right: 140px;
  }

  .menu-links {
    margin-left: 140px;
  }
}

@media screen and (max-width: 767px) {
  body {
    font-size: 12px;
  }

  h1 {
    font-size: 3.2em;
  }

  h2 {
    font-size: 2.7em;
  }

  h3 {
    font-size: 2em;
  }

  h4 {
    font-size: 1.5em;
  }

  h5 {
    font-size: 1.1em;
  }

  h6 {
    font-size: 0.9em;
  }

  .p-sm-end {
    padding-bottom: 2.3em;
  }

  .title1 {
    font-size: 3.2em;
  }

  .p-xs-start {
    padding-top: 1.6em;
  }

  .title2 {
    font-size: 2.7em;
  }

  .gutter-outside {
    padding-right: 5vw;
    padding-left: 5vw;
  }

  .copy-medium {
    font-size: 1.3em;
    line-height: 1.4em;
  }

  .p-xl-end {
    padding-bottom: 6em;
  }

  .p-xs-end {
    padding-bottom: 1.6em;
  }

  .p-xl-start {
    padding-top: 0.125em;
  }

  .intro-description {
    padding-right: 0em;
    padding-left: 0em;
  }

  .blog-header-title {
    font-size: 16vw;
  }

  .blog-overview-grid {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .blog-teaser-item-wrapper {
    padding-right: 1em;
    padding-left: 1em;
  }

  .blog-teaser-item-wrapper.page-teaser {
    padding-top: 1em;
    padding-bottom: 1em;
  }

  .page-teaser-title {
    font-size: 2em;
  }

  .page-teaser-subtitle {
    font-size: 1em;
  }

  .blog-header-title-wrapper {
    padding-right: 0px;
    -webkit-box-pack: end;
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
  }

  .header-button-wrapper {
    margin-bottom: 1em;
  }

  .header-inner {
    -webkit-box-orient: horizontal;
    -webkit-box-direction: reverse;
    -webkit-flex-direction: row-reverse;
    -ms-flex-direction: row-reverse;
    flex-direction: row-reverse;
    -webkit-box-pack: justify;
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
    -webkit-flex-wrap: wrap-reverse;
    -ms-flex-wrap: wrap-reverse;
    flex-wrap: wrap-reverse;
    font-family: sofia-pro;
  }

  .header-left {
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .abctradesmimagecontainer {
    width: 30vw;
    height: 30vw;
  }

  .div-block-2 {
    width: 30vw;
  }

  .trio {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .image-7 {
    width: 40vw;
    height: 40vw;
    max-height: none;
    max-width: none;
    min-width: 20vw;
  }

  .grid-9 {
    -ms-grid-columns: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
  }

  .marthaquote {
    max-width: 450px;
  }

  .page-teaser-title-2 {
    font-size: 2em;
  }

  .p-xl-end-2 {
    padding-bottom: 6em;
  }

  .blog-overview-grid-2 {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .page-teaser-subtitle-2 {
    font-size: 1em;
  }

  .blog-teaser-item-wrapper-2 {
    padding-right: 1em;
    padding-left: 1em;
  }

  .blog-teaser-item-wrapper-2.page-teaser {
    padding-top: 1em;
    padding-bottom: 1em;
  }

  .menu-left {
    width: 100vw;
    height: auto;
    padding: 20px;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: end;
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .menu-2 {
    left: auto;
    top: 0%;
    right: 0%;
    bottom: auto;
    margin-top: 0px;
    margin-right: -20px;
    margin-left: 0px;
    padding-right: 0px;
  }

  .menu-left-2 {
    width: 100vw;
    height: auto;
    padding: 20px;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: end;
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .menu-3 {
    left: auto;
    top: 0%;
    right: 0%;
    bottom: auto;
    margin-top: 0px;
    margin-right: -20px;
    margin-left: 0px;
    padding-right: 0px;
  }

  .overlay {
    height: 100vh;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .menu-bg {
    display: block;
  }

  .socials {
    display: none;
  }

  .showreel-title.project {
    font-size: 18px;
  }

  .link {
    font-size: 48px;
  }

  .link.w--current {
    font-size: 48px;
  }
}

@media screen and (max-width: 479px) {
  .blog-overview-grid {
    overflow: hidden;
  }

  .blog-teaser-item-wrapper.quote {
    padding: 4.5em 1.7em;
  }

  .blog-teaser-quote {
    font-size: 1.4em;
  }

  .blog-header-title-letter._3 {
    letter-spacing: 1px;
  }

  .grid-8 {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .abctradesmimagecontainer {
    width: 60vw;
    height: 60vw;
  }

  .div-block-2 {
    width: 60vw;
  }

  .formcenter {
    padding-right: 10%;
    padding-left: 10%;
    text-align: center;
  }

  .form-custom {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .type {
    max-height: 300px;
    min-height: 300px;
    padding-right: 0%;
    padding-left: 0%;
  }

  .image-7 {
    width: 60vw;
    height: 60vw;
    min-height: 60vw;
    min-width: 60vw;
  }

  .grid-9 {
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
  }

  .copysub {
    min-height: auto;
    padding-right: 10%;
    padding-left: 10%;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }

  .heading {
    letter-spacing: 0.1em;
  }

  .h6small {
    letter-spacing: 0.1em;
  }

  .div-block-3 {
    width: 280px;
  }

  .div-block-4 {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .marthaquote {
    max-width: 280px;
  }

  .grid-10 {
    width: 300px;
  }

  .heading1 {
    font-size: 2.7em;
    letter-spacing: 0.1em;
  }

  .heading2 {
    font-size: 2.7em;
    letter-spacing: 0.1em;
  }

  .blog-overview-grid-2 {
    overflow: hidden;
  }

  .blog-teaser-quote-2 {
    font-size: 1.4em;
  }

  .blog-teaser-item-wrapper-2.quote {
    padding: 4.5em 1.7em;
  }

  .menu-left {
    padding: 10px 20px 0px;
  }

  .menu-left-2 {
    padding: 10px 20px 0px;
  }

  .overlay {
    left: auto;
    top: 0%;
    right: auto;
    bottom: 0%;
    height: 100vh;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
    -webkit-align-content: flex-start;
    -ms-flex-line-pack: start;
    align-content: flex-start;
  }

  .menu-links {
    left: auto;
    margin-right: 0px;
    margin-left: 20px;
  }
}

#w-node-_51edf76d-8681-5979-d198-1526d3bc134e-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-e707ba5e-f384-c819-3a9c-cb6c32115da8-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-d886bd2f-17fe-6ef1-1000-2efe4e2aca9b-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e235e9-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e235eb-d9dbd786 {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 2;
  grid-row-start: span 2;
  -ms-grid-row-span: 2;
  grid-row-end: span 2;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e235ff-d9dbd786 {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23611-d9dbd786 {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 2;
  grid-row-start: span 2;
  -ms-grid-row-span: 2;
  grid-row-end: span 2;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2361a-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 2;
  grid-row-start: span 2;
  -ms-grid-row-span: 2;
  grid-row-end: span 2;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2362e-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 2;
  grid-row-start: span 2;
  -ms-grid-row-span: 2;
  grid-row-end: span 2;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23642-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23655-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23668-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2367b-d9dbd786 {
  -ms-grid-column: span 3;
  grid-column-start: span 3;
  -ms-grid-column-span: 3;
  grid-column-end: span 3;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23689-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23697-d9dbd786 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-c1673f76-9cde-8fc7-8f57-4b2d04e236aa-d9dbd786 {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-d4bce059-c529-9e8d-38d8-6331d901703a-e7dbd787 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-cdf8d8db-3519-b3d0-ee34-c4a6e0fb110e-e7dbd787 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_60a12e0f-0816-e7c1-bd4e-2e1bb84550b3-e7dbd787 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_60a12e0f-0816-e7c1-bd4e-2e1bb84550b1-e7dbd787 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-a3bbf635-2231-c239-a25d-674885bc49b7-9bdbd789 {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-a3bbf635-2231-c239-a25d-674885bc49cb-9bdbd789 {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 2;
  grid-row-start: span 2;
  -ms-grid-row-span: 2;
  grid-row-end: span 2;
}

#w-node-a3bbf635-2231-c239-a25d-674885bc4a33-9bdbd789 {
  -ms-grid-column: span 3;
  grid-column-start: span 3;
  -ms-grid-column-span: 3;
  grid-column-end: span 3;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-a3bbf635-2231-c239-a25d-674885bc4a41-9bdbd789 {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-e2e5467c-c5ae-4ad7-b602-bc8be50db3f5-54dbd78a {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb7535-54dbd78a {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 2;
  grid-row-start: span 2;
  -ms-grid-row-span: 2;
  grid-row-end: span 2;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb7547-54dbd78a {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb7559-54dbd78a {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 2;
  grid-row-start: span 2;
  -ms-grid-row-span: 2;
  grid-row-end: span 2;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb7560-54dbd78a {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 2;
  grid-row-start: span 2;
  -ms-grid-row-span: 2;
  grid-row-end: span 2;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb7572-54dbd78a {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 2;
  grid-row-start: span 2;
  -ms-grid-row-span: 2;
  grid-row-end: span 2;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb7584-54dbd78a {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb7596-54dbd78a {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb75a8-54dbd78a {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb75ba-54dbd78a {
  -ms-grid-column: span 3;
  grid-column-start: span 3;
  -ms-grid-column-span: 3;
  grid-column-end: span 3;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb75c7-54dbd78a {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb75d5-54dbd78a {
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

#w-node-_117d1d6a-d362-3aba-1b79-676845fb75e7-54dbd78a {
  -ms-grid-column: span 2;
  grid-column-start: span 2;
  -ms-grid-column-span: 2;
  grid-column-end: span 2;
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
}

@media screen and (max-width: 991px) {
  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e235eb-d9dbd786 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e235ff-d9dbd786 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }

  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23611-d9dbd786 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2361a-d9dbd786 {
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2362e-d9dbd786 {
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2367b-d9dbd786 {
    -ms-grid-column: span 2;
    grid-column-start: span 2;
    -ms-grid-column-span: 2;
    grid-column-end: span 2;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23689-d9dbd786 {
    -ms-grid-column: span 2;
    grid-column-start: span 2;
    -ms-grid-column-span: 2;
    grid-column-end: span 2;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
    -webkit-box-ordinal-group: 10000;
    -webkit-order: 9999;
    -ms-flex-order: 9999;
    order: 9999;
  }

  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e236aa-d9dbd786 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }

  #w-node-a3bbf635-2231-c239-a25d-674885bc49b7-9bdbd789 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }

  #w-node-a3bbf635-2231-c239-a25d-674885bc49cb-9bdbd789 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-a3bbf635-2231-c239-a25d-674885bc4a33-9bdbd789 {
    -ms-grid-column: span 2;
    grid-column-start: span 2;
    -ms-grid-column-span: 2;
    grid-column-end: span 2;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-a3bbf635-2231-c239-a25d-674885bc4a41-9bdbd789 {
    -ms-grid-column: span 2;
    grid-column-start: span 2;
    -ms-grid-column-span: 2;
    grid-column-end: span 2;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
    -webkit-box-ordinal-group: 10000;
    -webkit-order: 9999;
    -ms-flex-order: 9999;
    order: 9999;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb7535-54dbd78a {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb7547-54dbd78a {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb7559-54dbd78a {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb7560-54dbd78a {
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb7572-54dbd78a {
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb75ba-54dbd78a {
    -ms-grid-column: span 2;
    grid-column-start: span 2;
    -ms-grid-column-span: 2;
    grid-column-end: span 2;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb75c7-54dbd78a {
    -ms-grid-column: span 2;
    grid-column-start: span 2;
    -ms-grid-column-span: 2;
    grid-column-end: span 2;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
    -webkit-box-ordinal-group: 10000;
    -webkit-order: 9999;
    -ms-flex-order: 9999;
    order: 9999;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb75e7-54dbd78a {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }
}

@media screen and (max-width: 767px) {
  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2367b-d9dbd786 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23689-d9dbd786 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }

  #w-node-a3bbf635-2231-c239-a25d-674885bc4a33-9bdbd789 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-a3bbf635-2231-c239-a25d-674885bc4a41-9bdbd789 {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb75ba-54dbd78a {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
    -ms-grid-row: span 1;
    grid-row-start: span 1;
    -ms-grid-row-span: 1;
    grid-row-end: span 1;
  }

  #w-node-_117d1d6a-d362-3aba-1b79-676845fb75c7-54dbd78a {
    -ms-grid-column: span 1;
    grid-column-start: span 1;
    -ms-grid-column-span: 1;
    grid-column-end: span 1;
  }
}

</style>

<nav class="navbar navbar-expand-lg shadow-lg py-2 bg-gray-50 relative flex items-center w-full justify-between">
  <div class="px-6">
    <button class="navbar-toggler border-0 py-3 lg:hidden leading-none text-xl bg-transparent text-gray-600 hover:text-gray-700 focus:text-gray-700 transition-shadow duration-150 ease-in-out" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContentZ" aria-controls="navbarSupportedContentZ" aria-expanded="false" aria-label="Toggle navigation">
      <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
        <path fill="currentColor" d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z"></path>
      </svg>
    </button>
    <div class="navbar-collapse collapse grow items-center" id="navbarSupportedContentZ">
      <ul class="navbar-nav mr-auto flex flex-row">
        <li class="nav-item">
          <a class="nav-link block pr-2 lg:px-2 py-2 text-gray-600 hover:text-gray-700 focus:text-gray-700 transition duration-150 ease-in-out" href="#!" data-mdb-ripple="true" data-mdb-ripple-color="light">Regular link</a>
        </li>
        <li class="nav-item dropdown static">
          <a class="nav-link block pr-2 lg:px-2 py-2 text-gray-600 hover:text-gray-700 focus:text-gray-700 transition duration-150 ease-in-out dropdown-toggle flex items-center whitespace-nowrap" href="#" data-mdb-ripple="true" data-mdb-ripple-color="light" type="button" id="dropdownMenuButtonZ" data-bs-toggle="dropdown"
          aria-expanded="false">Mega menu
            <svg  aria-hidden="true" focusable="false" data-prefix="fas" data-icon="caret-down" class="w-2 ml-2" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
              <path fill="currentColor" d="M31.3 192h257.3c17.8 0 26.7 21.5 14.1 34.1L174.1 354.8c-7.8 7.8-20.5 7.8-28.3 0L17.2 226.1C4.6 213.5 13.5 192 31.3 192z"></path>
            </svg>
          </a>
          <div class="dropdown-menu w-full mt-0 hidden shadow-lg bg-white absolute left-0 top-full" aria-labelledby="dropdownMenuButtonZ">
            <div class="px-6 lg:px-8 py-5">
              <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="bg-white text-gray-600">
                  <p class="block px-6 py-2 border-b border-gray-200 w-full uppercase font-semibold text-gray-700">Lorem ipsum</p>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Dolor sit
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Amet consectetur
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Cras justo odio
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Adipisicing elit
                  </a>
                </div>
                <div class="bg-white text-gray-600">
                  <p class="block px-6 py-2 border-b border-gray-200 w-full uppercase font-semibold text-gray-700">Explit voluptas</p>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Perspiciatis quo
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Cras justo odio
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Laudant maiores
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Provident dolor
                  </a>
                </div>
                <div class="bg-white text-gray-600">
                  <p class="block px-6 py-2 border-b border-gray-200 w-full uppercase font-semibold text-gray-700">Iste quaerato</p>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Cras justo odio
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Est iure
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Praesentium
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Laboriosam
                  </a>
                </div>
                <div class="bg-white text-gray-600">
                  <p class="block px-6 py-2 border-b border-gray-200 w-full uppercase font-semibold text-gray-700">Cras justo odio</p>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Saepe
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Vel alias
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 border-b border-gray-200 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Sunt doloribus
                  </a>
                  <a href="#!" aria-current="true" class="block px-6 py-2 w-full hover:bg-gray-50 hover:text-gray-700 transition duration-150 ease-in-out flex items-center">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" class="w-1.5 mr-1.5" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 192 512">
                      <path fill="currentColor" d="M0 384.662V127.338c0-17.818 21.543-26.741 34.142-14.142l128.662 128.662c7.81 7.81 7.81 20.474 0 28.284L34.142 398.804C21.543 411.404 0 402.48 0 384.662z"></path>
                    </svg>
                    Cum dolores
                  </a>
                </div>
              </div>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</nav>





<main>
  <div class="flex flex-col flex-1">





 <img src="https://hagenblack-11ty.netlify.app/assets/images/jane-beiles-9456-2-p-1080.jpeg" class="max-w-full h-auto" alt="..." />
 
  <button class="btn">Button</button>
  <button class="btn btn-primary">Button</button>
  <button class="btn btn-secondary">Button</button>
  <button class="btn btn-accent">Button</button>
  <button class="btn btn-ghost">Button</button>
  <button class="btn btn-link">Button</button>



  <div class="section-home wf-section">
    <div class="menu">
      <div class="menu-left">
        <div class="menu-2" data-w-id="f431000c-7aeb-331a-246e-d22ca9a44b66" data-animation-type="lottie" data-src="https://uploads-ssl.webflow.com/625836cf3bb30074b370a4e7/625836cf3bb3002e3170a52a_lf30_editor_XLPk4g.json" data-loop="0" data-direction="1" data-autoplay="1" data-is-ix2-target="0" data-renderer="svg" data-default-duration="4" data-duration="0"></div>
      </div>
      <div class="homelogo">
        <div class="open"></div>
        <div class="w-layout-grid grid-10"></div>
      </div>
    </div>
    <div class="sectionhead">
      <div>
        <div class="w-layout-grid grid-11">
          <div id="w-node-_51edf76d-8681-5979-d198-1526d3bc134e-d9dbd786">
            <h1 class="heading1">HAGEN</h1>
          </div>
          <div id="w-node-e707ba5e-f384-c819-3a9c-cb6c32115da8-d9dbd786">
            <h1 class="heading2">BLACK</h1>
          </div>
          <div id="w-node-d886bd2f-17fe-6ef1-1000-2efe4e2aca9b-d9dbd786">
            <h6 class="smallhead">INTERIOR DESIGN</h6>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="section-2 wf-section">
    <div class="div-block-4">
      <div class="div-block-3"></div>
      <div class="div-block-3"></div>
      <div class="div-block-8">
        <a href="/about" class="link-block w-inline-block">
          <h4 class="heading-2">Martha Hagen Black</h4>
        </a>
      </div>
    </div>
    <div class="div-block-5">
      <div class="containerline">
        <div>
          <h1 class="marthaquote">I believe that every well designed space be a thoughtful reflection of the people living in it</h1>
        </div>
      </div>
    </div>
  </div>
  <div class="global-css w-embed">
    <style>
  /* Timothy Ricks Wizardry reset */
  @media only screen and (min-width: 1600px) {
    body {font-size: 1em;}
  }
  /* Blog Teaser image hover effect */
  @media (min-width:992px) {
    .blog-teaser-image-wrapper:hover img {
      -webkit-transform: scale(1.1);
      -ms-transform: scale(1.1);
      transform: scale(1.1);
    }
  }
</style>
  </div>
  <div data-w-id="a5fdbc60-e01c-ca80-251d-a2954f9ab93d" style="opacity:0" class="header">
    <div class="container-w1 gutter-outside">
      <div class="header-inner">
        <div class="header-left">
          <div class="header-button-wrapper">
            <a href="#tutorial" class="header-button">Contact us</a>
          </div>
          <div class="header-button-wrapper">
            <a href="https://webflow.com/website/Free-Grid-Design-Template" target="_blank" class="header-button secondary">appointments</a>
          </div>
        </div>
        <div class="header-right">
          <div class="infotext">
            <a href="https://webflow-lernen.de/tutorials" target="_blank" class="text-grey"></a>
          </div>
        </div>
        <div>
          <a href="#" class="w-inline-block"></a>
        </div>
      </div>
    </div>
  </div>
  <div class="section-blog-overview">
    <div class="blog-header-wrapper">
      <div class="container-w1 gutter-outside">
        <div class="p-xl-start"></div>
      </div>
      <div class="blog-header-divider-wrapper">
        <div class="blog-header-divider-inner">
          <div class="blog-header-divider-2"></div>
        </div>
        <div class="blog-header-divider-inner">
          <div class="blog-header-divider-2 right"></div>
        </div>
      </div>
    </div>
    <div class="container-w1 gutter-outside">
      <div class="p-xl-end-2">
        <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e235e9-d9dbd786" class="position-realtive">
          <div class="w-layout-grid blog-overview-grid-2">
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e235eb-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="blog-teaser-list-wrapper w-dyn-list">
                <div role="list" class="blog-teaser-list w-dyn-items">
                  <div role="listitem" class="blog-teaser-item w-dyn-item">
                    <div class="blog-teaser-meta-wrapper">
                      <div class="blog-teaser-category"></div>
                      <div class="blog-teaser-date"> </div>
                    </div>
                    <a href="#" class="blog-teaser-image-wrapper w-inline-block">
                      <div class="blog-teaser-image-inner"><img src="" loading="lazy" alt="" class="blog-teaser-image"></div>
                    </a>
                    <div class="blog-teaser-text-wrapper">
                      <a href="#" class="blog-teaser-title-wrapper w-inline-block">
                        <div class="blog-teaser-title"></div>
                      </a>
                      <div class="blog-teaser-text-divider">–</div>
                      <p class="blog-teaser-summary"></p>
                    </div>
                  </div>
                </div>
                <div class="w-dyn-empty">
                  <div>No items found.</div>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e235ff-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="blog-teaser-list-wrapper w-dyn-list">
                <div role="list" class="blog-teaser-list w-dyn-items">
                  <div role="listitem" class="blog-teaser-item w-dyn-item">
                    <div class="blog-teaser-meta-wrapper">
                      <div class="blog-teaser-category"></div>
                    </div>
                    <a href="#" class="blog-teaser-image-wrapper w-inline-block">
                      <div class="blog-teaser-image-inner"><img src="" loading="lazy" alt="" class="blog-teaser-image"></div>
                    </a>
                    <div class="blog-teaser-text-wrapper">
                      <a href="#" class="blog-teaser-title-wrapper w-inline-block">
                        <div class="blog-teaser-title"></div>
                      </a>
                      <div class="blog-teaser-text-divider">–</div>
                      <p class="blog-teaser-summary"></p>
                    </div>
                  </div>
                </div>
                <div class="w-dyn-empty">
                  <div>No items found.</div>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23611-d9dbd786" class="blog-teaser-item-wrapper-2 quote">
              <div class="quote-wrapper">
                <p class="blog-teaser-quote-2">about us</p>
                <div class="quote-author-wrapper">
                  <div class="quote-author-2"> </div>
                  <a href="/about" class="button-abcgrid w-button">contact us</a>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2361a-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="blog-teaser-list-wrapper w-dyn-list">
                <div role="list" class="blog-teaser-list w-dyn-items">
                  <div role="listitem" class="blog-teaser-item w-dyn-item">
                    <div class="blog-teaser-meta-wrapper">
                      <div class="blog-teaser-category"></div>
                      <div class="blog-teaser-date"> </div>
                    </div>
                    <a href="#" class="blog-teaser-image-wrapper w-inline-block">
                      <div class="blog-teaser-image-inner"><img src="" loading="lazy" alt="" class="blog-teaser-image"></div>
                    </a>
                    <div class="blog-teaser-text-wrapper">
                      <a href="#" class="blog-teaser-title-wrapper w-inline-block">
                        <div class="blog-teaser-title"></div>
                      </a>
                      <div class="blog-teaser-text-divider">–</div>
                      <p class="blog-teaser-summary"></p>
                    </div>
                  </div>
                </div>
                <div class="w-dyn-empty">
                  <div>No items found.</div>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2362e-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="blog-teaser-list-wrapper w-dyn-list">
                <div role="list" class="blog-teaser-list w-dyn-items">
                  <div role="listitem" class="blog-teaser-item w-dyn-item">
                    <div class="blog-teaser-meta-wrapper">
                      <div class="blog-teaser-category"></div>
                      <div class="blog-teaser-date"> </div>
                    </div>
                    <a href="#" class="blog-teaser-image-wrapper w-inline-block">
                      <div class="blog-teaser-image-inner"><img src="" loading="lazy" alt="" class="blog-teaser-image"></div>
                    </a>
                    <div class="blog-teaser-text-wrapper">
                      <a href="#" class="blog-teaser-title-wrapper w-inline-block">
                        <div class="blog-teaser-title"></div>
                      </a>
                      <div class="blog-teaser-text-divider">–</div>
                      <p class="blog-teaser-summary"></p>
                    </div>
                  </div>
                </div>
                <div class="w-dyn-empty">
                  <div>No items found.</div>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23642-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="blog-teaser-list-wrapper w-dyn-list">
                <div role="list" class="blog-teaser-list w-dyn-items">
                  <div role="listitem" class="blog-teaser-item w-dyn-item">
                    <div class="blog-teaser-meta-wrapper">
                      <div class="blog-teaser-category"></div>
                      <div class="blog-teaser-date"></div>
                    </div>
                    <a href="#" class="blog-teaser-image-wrapper w-inline-block">
                      <div class="blog-teaser-image-inner"><img src="" loading="lazy" alt="" class="blog-teaser-image"></div>
                    </a>
                    <div class="blog-teaser-text-wrapper">
                      <a href="#" class="blog-teaser-title-wrapper w-inline-block">
                        <div class="blog-teaser-title"></div>
                      </a>
                      <div class="blog-teaser-text-divider">–</div>
                      <p class="blog-teaser-summary"></p>
                    </div>
                  </div>
                </div>
                <div class="w-dyn-empty">
                  <div>No items found.</div>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23655-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="blog-teaser-list-wrapper w-dyn-list">
                <div role="list" class="blog-teaser-list w-dyn-items">
                  <div role="listitem" class="blog-teaser-item w-dyn-item">
                    <div class="blog-teaser-meta-wrapper">
                      <div class="blog-teaser-category"></div>
                      <div class="blog-teaser-date"></div>
                    </div>
                    <a href="#" class="blog-teaser-image-wrapper w-inline-block">
                      <div class="blog-teaser-image-inner"><img src="" loading="lazy" alt="" class="blog-teaser-image"></div>
                    </a>
                    <div class="blog-teaser-text-wrapper">
                      <a href="#" class="blog-teaser-title-wrapper w-inline-block">
                        <div class="blog-teaser-title"></div>
                      </a>
                      <div class="blog-teaser-text-divider">–</div>
                      <p class="blog-teaser-summary"></p>
                    </div>
                  </div>
                </div>
                <div class="w-dyn-empty">
                  <div>No items found.</div>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23668-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="blog-teaser-list-wrapper w-dyn-list">
                <div role="list" class="blog-teaser-list w-dyn-items">
                  <div role="listitem" class="blog-teaser-item w-dyn-item">
                    <div class="blog-teaser-meta-wrapper">
                      <div class="blog-teaser-category"></div>
                      <div class="blog-teaser-date"></div>
                    </div>
                    <a href="#" class="blog-teaser-image-wrapper w-inline-block">
                      <div class="blog-teaser-image-inner"><img src="" loading="lazy" alt="" class="blog-teaser-image"></div>
                    </a>
                    <div class="blog-teaser-text-wrapper">
                      <a href="#" class="blog-teaser-title-wrapper w-inline-block">
                        <div class="blog-teaser-title"></div>
                      </a>
                      <div class="blog-teaser-text-divider">–</div>
                      <p class="blog-teaser-summary"></p>
                    </div>
                  </div>
                </div>
                <div class="w-dyn-empty">
                  <div>No items found.</div>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e2367b-d9dbd786" class="blog-teaser-item-wrapper-2 page-teaser">
              <div class="page-teaser-wrapper">
                <div class="page-teaser-text-wrapper-2">
                  <div class="p-xxs-end">
                    <div class="page-teaser-subtitle-2">unique products made for you</div>
                  </div>
                  <p class="page-teaser-title-2">design folio</p>
                  <div class="div-block-10">
                    <a href="#" class="button-abcgrid w-button">shop</a>
                  </div>
                  <div class="p-xs-start"></div>
                </div>
                <div class="page-teaser-gradient"></div><img src="images/01img6.jpg" loading="lazy" sizes="(max-width: 479px) 90vw, (max-width: 767px) 94vw, (max-width: 991px) 91vw, 93vw" srcset="images/01img6-p-500.jpeg 500w, images/01img6-p-800.jpeg 800w, images/01img6.jpg 864w" alt="" class="page-teaser-image">
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23689-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="social-wrapper">
                <div class="p-xs-end">
                  <div class="social-title-2">Follow Us</div>
                </div>
                <div class="social-icons-wrapper">
                  <a href="#" class="social-link-2 w-inline-block">
                    <div class="social-icon-2 w-embed"><svg width="100%" height="100%" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M16.5 6H13.5C12.9477 6 12.5 6.44772 12.5 7V10H16.5C16.6137 9.99748 16.7216 10.0504 16.7892 10.1419C16.8568 10.2334 16.8758 10.352 16.84 10.46L16.1 12.66C16.0318 12.8619 15.8431 12.9984 15.63 13H12.5V20.5C12.5 20.7761 12.2761 21 12 21H9.5C9.22386 21 9 20.7761 9 20.5V13H7.5C7.22386 13 7 12.7761 7 12.5V10.5C7 10.2239 7.22386 10 7.5 10H9V7C9 4.79086 10.7909 3 13 3H16.5C16.7761 3 17 3.22386 17 3.5V5.5C17 5.77614 16.7761 6 16.5 6Z" fill="CurrentColor"></path>
                      </svg></div>
                  </a>
                  <a href="#" class="social-link-2 w-inline-block">
                    <div class="social-icon-2 w-embed"><svg width="100%" height="100%" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M16 3H8C5.23858 3 3 5.23858 3 8V16C3 18.7614 5.23858 21 8 21H16C18.7614 21 21 18.7614 21 16V8C21 5.23858 18.7614 3 16 3ZM19.25 16C19.2445 17.7926 17.7926 19.2445 16 19.25H8C6.20735 19.2445 4.75549 17.7926 4.75 16V8C4.75549 6.20735 6.20735 4.75549 8 4.75H16C17.7926 4.75549 19.2445 6.20735 19.25 8V16ZM16.75 8.25C17.3023 8.25 17.75 7.80228 17.75 7.25C17.75 6.69772 17.3023 6.25 16.75 6.25C16.1977 6.25 15.75 6.69772 15.75 7.25C15.75 7.80228 16.1977 8.25 16.75 8.25ZM12 7.5C9.51472 7.5 7.5 9.51472 7.5 12C7.5 14.4853 9.51472 16.5 12 16.5C14.4853 16.5 16.5 14.4853 16.5 12C16.5027 10.8057 16.0294 9.65957 15.1849 8.81508C14.3404 7.97059 13.1943 7.49734 12 7.5ZM9.25 12C9.25 13.5188 10.4812 14.75 12 14.75C13.5188 14.75 14.75 13.5188 14.75 12C14.75 10.4812 13.5188 9.25 12 9.25C10.4812 9.25 9.25 10.4812 9.25 12Z" fill="CurrentColor"></path>
                      </svg></div>
                  </a>
                  <a href="#" class="social-link-2 w-inline-block">
                    <div class="social-icon-2 w-embed"><svg width="100%" height="100%" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M20.9728 6.7174C20.5084 7.33692 19.947 7.87733 19.3103 8.31776C19.3103 8.47959 19.3103 8.64142 19.3103 8.81225C19.3154 11.7511 18.1415 14.5691 16.0518 16.6345C13.962 18.6999 11.1312 19.8399 8.19405 19.7989C6.49599 19.8046 4.81967 19.4169 3.29642 18.6661C3.21428 18.6302 3.16131 18.549 3.16162 18.4593V18.3604C3.16162 18.2313 3.26623 18.1267 3.39527 18.1267C5.06442 18.0716 6.67402 17.4929 7.99634 16.4724C6.48553 16.4419 5.12619 15.5469 4.5006 14.1707C4.46901 14.0956 4.47884 14.0093 4.52657 13.9432C4.57429 13.8771 4.653 13.8407 4.73425 13.8471C5.19342 13.8932 5.65718 13.8505 6.1002 13.7212C4.43239 13.375 3.17921 11.9904 2.99986 10.2957C2.99349 10.2144 3.02992 10.1357 3.096 10.0879C3.16207 10.0402 3.24824 10.0303 3.32338 10.062C3.77094 10.2595 4.25409 10.3635 4.74324 10.3676C3.28184 9.40846 2.65061 7.58405 3.20655 5.92622C3.26394 5.76513 3.40181 5.64612 3.5695 5.61294C3.73718 5.57975 3.90996 5.63728 4.02432 5.76439C5.99639 7.86325 8.70604 9.11396 11.5819 9.25279C11.5083 8.95885 11.4721 8.65676 11.4741 8.35372C11.501 6.76472 12.4842 5.34921 13.9634 4.76987C15.4425 4.19054 17.1249 4.56203 18.223 5.71044C18.9714 5.56785 19.695 5.31645 20.3707 4.96421C20.4202 4.93331 20.483 4.93331 20.5325 4.96421C20.5634 5.01373 20.5634 5.07652 20.5325 5.12604C20.2052 5.87552 19.6523 6.50412 18.9509 6.92419C19.5651 6.85296 20.1685 6.70807 20.7482 6.49264C20.797 6.45942 20.8611 6.45942 20.9099 6.49264C20.9508 6.51134 20.9814 6.54711 20.9935 6.59042C21.0056 6.63373 20.998 6.68018 20.9728 6.7174Z" fill="CurrentColor"></path>
                      </svg></div>
                  </a>
                  <a href="#" class="social-link-2 w-inline-block">
                    <div class="social-icon-2 w-embed"><svg width="100%" height="100%" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M5 3H19C20.1046 3 21 3.89543 21 5V19C21 20.1046 20.1046 21 19 21H5C3.89543 21 3 20.1046 3 19V5C3 3.89543 3.89543 3 5 3ZM8 18C8.27614 18 8.5 17.7761 8.5 17.5V10.5C8.5 10.2239 8.27614 10 8 10H6.5C6.22386 10 6 10.2239 6 10.5V17.5C6 17.7761 6.22386 18 6.5 18H8ZM7.25 9C6.42157 9 5.75 8.32843 5.75 7.5C5.75 6.67157 6.42157 6 7.25 6C8.07843 6 8.75 6.67157 8.75 7.5C8.75 8.32843 8.07843 9 7.25 9ZM17.5 18C17.7761 18 18 17.7761 18 17.5V12.9C18.0325 11.3108 16.8576 9.95452 15.28 9.76C14.177 9.65925 13.1083 10.1744 12.5 11.1V10.5C12.5 10.2239 12.2761 10 12 10H10.5C10.2239 10 10 10.2239 10 10.5V17.5C10 17.7761 10.2239 18 10.5 18H12C12.2761 18 12.5 17.7761 12.5 17.5V13.75C12.5 12.9216 13.1716 12.25 14 12.25C14.8284 12.25 15.5 12.9216 15.5 13.75V17.5C15.5 17.7761 15.7239 18 16 18H17.5Z" fill="CurrentColor"></path>
                      </svg></div>
                  </a>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e23697-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="blog-teaser-list-wrapper w-dyn-list">
                <div role="list" class="blog-teaser-list w-dyn-items">
                  <div role="listitem" class="blog-teaser-item w-dyn-item">
                    <div class="blog-teaser-meta-wrapper">
                      <div class="blog-teaser-category"></div>
                      <div class="blog-teaser-date"></div>
                    </div>
                    <a href="#" class="blog-teaser-image-wrapper w-inline-block">
                      <div class="blog-teaser-image-inner"><img src="" loading="lazy" alt="" class="blog-teaser-image"></div>
                    </a>
                    <div class="blog-teaser-text-wrapper">
                      <a href="#" class="blog-teaser-title-wrapper w-inline-block">
                        <div class="blog-teaser-title"></div>
                      </a>
                      <div class="blog-teaser-text-divider">–</div>
                      <p class="blog-teaser-summary"></p>
                    </div>
                  </div>
                </div>
                <div class="w-dyn-empty">
                  <div>No items found.</div>
                </div>
              </div>
            </div>
            <div id="w-node-c1673f76-9cde-8fc7-8f57-4b2d04e236aa-d9dbd786" class="blog-teaser-item-wrapper-2">
              <div class="blog-teaser-list-wrapper w-dyn-list">
                <div role="list" class="blog-teaser-list w-dyn-items">
                  <div role="listitem" class="blog-teaser-item w-dyn-item">
                    <div class="blog-teaser-meta-wrapper">
                      <div class="blog-teaser-category"></div>
                      <div class="blog-teaser-date"></div>
                    </div>
                    <a href="#" class="blog-teaser-image-wrapper w-inline-block">
                      <div class="blog-teaser-image-inner"><img src="" loading="lazy" alt="" class="blog-teaser-image"></div>
                    </a>
                    <div class="blog-teaser-text-wrapper">
                      <a href="#" class="blog-teaser-title-wrapper w-inline-block">
                        <div class="blog-teaser-title"></div>
                      </a>
                      <div class="blog-teaser-text-divider">–</div>
                      <p class="blog-teaser-summary"></p>
                    </div>
                  </div>
                </div>
                <div class="w-dyn-empty">
                  <div>No items found.</div>
                </div>
              </div>
            </div>
          </div>
          <div class="grid-border-line-wrapper-2">
            <div class="grid-border-line-2"></div>
          </div>
          <div class="grid-border-line-wrapper-2 right">
            <div class="grid-border-line-2 right"></div>
          </div>
        </div>
      </div>
    </div>
    <div class="section-line wf-section">
      <div class="text-block-12"> </div>
    </div>
  </div>
  <div id="tutorial" class="section-tutorial lineabove wf-section"></div>
  <div class="abctradewrap"></div>
  <div class="footer wf-section"></div>

  <h1>Hello {name}</h1>


  <ul class="menu bg-base-100 w-56">
    <li><a>Item 1</a></li>
    <li><a class="active">Item 2</a></li>
    <li><a>Item 3</a></li>
  </ul>
</div>

</main>


