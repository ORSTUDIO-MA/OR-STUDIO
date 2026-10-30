<html lang="en"><head><style>
@font-face {
  font-family: "Optimistic";
  font-style: normal;
  font-weight: 400 600;
  font-display: swap;
  src: url("/fonts/OptimisticAI_VF_Optimized.woff2") format("woff2");
}
@font-face {
  font-family: "Optimistic Mono";
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: url("/fonts/OptimisticMono_W_TextRegular.woff2") format("woff2");
}
:where(html) {
  font-family: "Optimistic", system-ui, sans-serif;
}
:where(code, pre, kbd, samp) {
  font-family: "Optimistic Mono", ui-monospace, monospace;
}
</style>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>React Artifact</title>
  <style>@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Tajawal:wght@300;400;700;900&display=swap');

*, ::before, ::after{
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x:  ;
  --tw-pan-y:  ;
  --tw-pinch-zoom:  ;
  --tw-scroll-snap-strictness: proximity;
  --tw-gradient-from-position:  ;
  --tw-gradient-via-position:  ;
  --tw-gradient-to-position:  ;
  --tw-ordinal:  ;
  --tw-slashed-zero:  ;
  --tw-numeric-figure:  ;
  --tw-numeric-spacing:  ;
  --tw-numeric-fraction:  ;
  --tw-ring-inset:  ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur:  ;
  --tw-brightness:  ;
  --tw-contrast:  ;
  --tw-grayscale:  ;
  --tw-hue-rotate:  ;
  --tw-invert:  ;
  --tw-saturate:  ;
  --tw-sepia:  ;
  --tw-drop-shadow:  ;
  --tw-backdrop-blur:  ;
  --tw-backdrop-brightness:  ;
  --tw-backdrop-contrast:  ;
  --tw-backdrop-grayscale:  ;
  --tw-backdrop-hue-rotate:  ;
  --tw-backdrop-invert:  ;
  --tw-backdrop-opacity:  ;
  --tw-backdrop-saturate:  ;
  --tw-backdrop-sepia:  ;
  --tw-contain-size:  ;
  --tw-contain-layout:  ;
  --tw-contain-paint:  ;
  --tw-contain-style:  ;
}

::backdrop{
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x:  ;
  --tw-pan-y:  ;
  --tw-pinch-zoom:  ;
  --tw-scroll-snap-strictness: proximity;
  --tw-gradient-from-position:  ;
  --tw-gradient-via-position:  ;
  --tw-gradient-to-position:  ;
  --tw-ordinal:  ;
  --tw-slashed-zero:  ;
  --tw-numeric-figure:  ;
  --tw-numeric-spacing:  ;
  --tw-numeric-fraction:  ;
  --tw-ring-inset:  ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur:  ;
  --tw-brightness:  ;
  --tw-contrast:  ;
  --tw-grayscale:  ;
  --tw-hue-rotate:  ;
  --tw-invert:  ;
  --tw-saturate:  ;
  --tw-sepia:  ;
  --tw-drop-shadow:  ;
  --tw-backdrop-blur:  ;
  --tw-backdrop-brightness:  ;
  --tw-backdrop-contrast:  ;
  --tw-backdrop-grayscale:  ;
  --tw-backdrop-hue-rotate:  ;
  --tw-backdrop-invert:  ;
  --tw-backdrop-opacity:  ;
  --tw-backdrop-saturate:  ;
  --tw-backdrop-sepia:  ;
  --tw-contain-size:  ;
  --tw-contain-layout:  ;
  --tw-contain-paint:  ;
  --tw-contain-style:  ;
}

/*
! tailwindcss v3.4.18 | MIT License | https://tailwindcss.com
*/

/*
1. Prevent padding and border from affecting element width. (https://github.com/mozdevs/cssremedy/issues/4)
2. Allow adding a border to an element by just adding a border-width. (https://github.com/tailwindcss/tailwindcss/pull/116)
*/

*,
::before,
::after {
  box-sizing: border-box;
  /* 1 */
  border-width: 0;
  /* 2 */
  border-style: solid;
  /* 2 */
  border-color: #e5e7eb;
  /* 2 */
}

::before,
::after {
  --tw-content: '';
}

/*
1. Use a consistent sensible line-height in all browsers.
2. Prevent adjustments of font size after orientation changes in iOS.
3. Use a more readable tab size.
4. Use the user's configured `sans` font-family by default.
5. Use the user's configured `sans` font-feature-settings by default.
6. Use the user's configured `sans` font-variation-settings by default.
7. Disable tap highlights on iOS
*/

html,
:host {
  line-height: 1.5;
  /* 1 */
  -webkit-text-size-adjust: 100%;
  /* 2 */
  -moz-tab-size: 4;
  /* 3 */
  -o-tab-size: 4;
     tab-size: 4;
  /* 3 */
  font-family: ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  /* 4 */
  font-feature-settings: normal;
  /* 5 */
  font-variation-settings: normal;
  /* 6 */
  -webkit-tap-highlight-color: transparent;
  /* 7 */
}

/*
1. Remove the margin in all browsers.
2. Inherit line-height from `html` so users can set them as a class directly on the `html` element.
*/

body {
  margin: 0;
  /* 1 */
  line-height: inherit;
  /* 2 */
}

/*
1. Add the correct height in Firefox.
2. Correct the inheritance of border color in Firefox. (https://bugzilla.mozilla.org/show_bug.cgi?id=190655)
3. Ensure horizontal rules are visible by default.
*/

hr {
  height: 0;
  /* 1 */
  color: inherit;
  /* 2 */
  border-top-width: 1px;
  /* 3 */
}

/*
Add the correct text decoration in Chrome, Edge, and Safari.
*/

abbr:where([title]) {
  -webkit-text-decoration: underline dotted;
          text-decoration: underline dotted;
}

/*
Remove the default font size and weight for headings.
*/

h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: inherit;
  font-weight: inherit;
}

/*
Reset links to optimize for opt-in styling instead of opt-out.
*/

a {
  color: inherit;
  text-decoration: inherit;
}

/*
Add the correct font weight in Edge and Safari.
*/

b,
strong {
  font-weight: bolder;
}

/*
1. Use the user's configured `mono` font-family by default.
2. Use the user's configured `mono` font-feature-settings by default.
3. Use the user's configured `mono` font-variation-settings by default.
4. Correct the odd `em` font sizing in all browsers.
*/

code,
kbd,
samp,
pre {
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
  /* 1 */
  font-feature-settings: normal;
  /* 2 */
  font-variation-settings: normal;
  /* 3 */
  font-size: 1em;
  /* 4 */
}

/*
Add the correct font size in all browsers.
*/

small {
  font-size: 80%;
}

/*
Prevent `sub` and `sup` elements from affecting the line height in all browsers.
*/

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

/*
1. Remove text indentation from table contents in Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=999088, https://bugs.webkit.org/show_bug.cgi?id=201297)
2. Correct table border color inheritance in all Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=935729, https://bugs.webkit.org/show_bug.cgi?id=195016)
3. Remove gaps between table borders by default.
*/

table {
  text-indent: 0;
  /* 1 */
  border-color: inherit;
  /* 2 */
  border-collapse: collapse;
  /* 3 */
}

/*
1. Change the font styles in all browsers.
2. Remove the margin in Firefox and Safari.
3. Remove default padding in all browsers.
*/

button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
  /* 1 */
  font-feature-settings: inherit;
  /* 1 */
  font-variation-settings: inherit;
  /* 1 */
  font-size: 100%;
  /* 1 */
  font-weight: inherit;
  /* 1 */
  line-height: inherit;
  /* 1 */
  letter-spacing: inherit;
  /* 1 */
  color: inherit;
  /* 1 */
  margin: 0;
  /* 2 */
  padding: 0;
  /* 3 */
}

/*
Remove the inheritance of text transform in Edge and Firefox.
*/

button,
select {
  text-transform: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Remove default button styles.
*/

button,
input:where([type='button']),
input:where([type='reset']),
input:where([type='submit']) {
  -webkit-appearance: button;
  /* 1 */
  background-color: transparent;
  /* 2 */
  background-image: none;
  /* 2 */
}

/*
Use the modern Firefox focus style for all focusable elements.
*/

:-moz-focusring {
  outline: auto;
}

/*
Remove the additional `:invalid` styles in Firefox. (https://github.com/mozilla/gecko-dev/blob/2f9eacd9d3d995c937b4251a5557d95d494c9be1/layout/style/res/forms.css#L728-L737)
*/

:-moz-ui-invalid {
  box-shadow: none;
}

/*
Add the correct vertical alignment in Chrome and Firefox.
*/

progress {
  vertical-align: baseline;
}

/*
Correct the cursor style of increment and decrement buttons in Safari.
*/

::-webkit-inner-spin-button,
::-webkit-outer-spin-button {
  height: auto;
}

/*
1. Correct the odd appearance in Chrome and Safari.
2. Correct the outline style in Safari.
*/

[type='search'] {
  -webkit-appearance: textfield;
  /* 1 */
  outline-offset: -2px;
  /* 2 */
}

/*
Remove the inner padding in Chrome and Safari on macOS.
*/

::-webkit-search-decoration {
  -webkit-appearance: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Change font properties to `inherit` in Safari.
*/

::-webkit-file-upload-button {
  -webkit-appearance: button;
  /* 1 */
  font: inherit;
  /* 2 */
}

/*
Add the correct display in Chrome and Safari.
*/

summary {
  display: list-item;
}

/*
Removes the default spacing and border for appropriate elements.
*/

blockquote,
dl,
dd,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
figure,
p,
pre {
  margin: 0;
}

fieldset {
  margin: 0;
  padding: 0;
}

legend {
  padding: 0;
}

ol,
ul,
menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

/*
Reset default styling for dialogs.
*/

dialog {
  padding: 0;
}

/*
Prevent resizing textareas horizontally by default.
*/

textarea {
  resize: vertical;
}

/*
1. Reset the default placeholder opacity in Firefox. (https://github.com/tailwindlabs/tailwindcss/issues/3300)
2. Set the default placeholder color to the user's configured gray 400 color.
*/

input::-moz-placeholder, textarea::-moz-placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

input::placeholder,
textarea::placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

/*
Set the default cursor for buttons.
*/

button,
[role="button"] {
  cursor: pointer;
}

/*
Make sure disabled buttons don't get the pointer cursor.
*/

:disabled {
  cursor: default;
}

/*
1. Make replaced elements `display: block` by default. (https://github.com/mozdevs/cssremedy/issues/14)
2. Add `vertical-align: middle` to align replaced elements more sensibly by default. (https://github.com/jensimmons/cssremedy/issues/14#issuecomment-634934210)
   This can trigger a poorly considered lint error in some tools but is included by design.
*/

img,
svg,
video,
canvas,
audio,
iframe,
embed,
object {
  display: block;
  /* 1 */
  vertical-align: middle;
  /* 2 */
}

/*
Constrain images and videos to the parent width and preserve their intrinsic aspect ratio. (https://github.com/mozdevs/cssremedy/issues/14)
*/

img,
video {
  max-width: 100%;
  height: auto;
}

/* Make elements with the HTML hidden attribute stay hidden by default */

[hidden]:where(:not([hidden="until-found"])) {
  display: none;
}

.pointer-events-none{
  pointer-events: none;
}

.fixed{
  position: fixed;
}

.absolute{
  position: absolute;
}

.relative{
  position: relative;
}

.sticky{
  position: sticky;
}

.inset-0{
  inset: 0px;
}

.-left-\[200px\]{
  left: -200px;
}

.-right-\[200px\]{
  right: -200px;
}

.-top-\[300px\]{
  top: -300px;
}

.bottom-0{
  bottom: 0px;
}

.bottom-20{
  bottom: 5rem;
}

.bottom-6{
  bottom: 1.5rem;
}

.left-0{
  left: 0px;
}

.left-1\/2{
  left: 50%;
}

.left-1\/3{
  left: 33.333333%;
}

.left-3{
  left: 0.75rem;
}

.left-6{
  left: 1.5rem;
}

.right-0{
  right: 0px;
}

.right-3{
  right: 0.75rem;
}

.right-6{
  right: 1.5rem;
}

.top-0{
  top: 0px;
}

.top-20{
  top: 5rem;
}

.top-3{
  top: 0.75rem;
}

.top-6{
  top: 1.5rem;
}

.top-\[40\%\]{
  top: 40%;
}

.z-10{
  z-index: 10;
}

.z-40{
  z-index: 40;
}

.z-\[100\]{
  z-index: 100;
}

.z-\[200\]{
  z-index: 200;
}

.z-\[300\]{
  z-index: 300;
}

.z-\[9999\]{
  z-index: 9999;
}

.mx-auto{
  margin-left: auto;
  margin-right: auto;
}

.mb-10{
  margin-bottom: 2.5rem;
}

.mb-3{
  margin-bottom: 0.75rem;
}

.mb-4{
  margin-bottom: 1rem;
}

.mb-6{
  margin-bottom: 1.5rem;
}

.mt-1{
  margin-top: 0.25rem;
}

.mt-10{
  margin-top: 2.5rem;
}

.mt-12{
  margin-top: 3rem;
}

.mt-2{
  margin-top: 0.5rem;
}

.mt-3{
  margin-top: 0.75rem;
}

.mt-4{
  margin-top: 1rem;
}

.mt-5{
  margin-top: 1.25rem;
}

.mt-6{
  margin-top: 1.5rem;
}

.mt-8{
  margin-top: 2rem;
}

.mt-\[2px\]{
  margin-top: 2px;
}

.block{
  display: block;
}

.inline-block{
  display: inline-block;
}

.flex{
  display: flex;
}

.inline-flex{
  display: inline-flex;
}

.table{
  display: table;
}

.grid{
  display: grid;
}

.hidden{
  display: none;
}

.aspect-\[16\/9\]{
  aspect-ratio: 16/9;
}

.aspect-\[4\/3\]{
  aspect-ratio: 4/3;
}

.aspect-\[4\/5\]{
  aspect-ratio: 4/5;
}

.h-1\.5{
  height: 0.375rem;
}

.h-16{
  height: 4rem;
}

.h-2{
  height: 0.5rem;
}

.h-5{
  height: 1.25rem;
}

.h-6{
  height: 1.5rem;
}

.h-7{
  height: 1.75rem;
}

.h-8{
  height: 2rem;
}

.h-9{
  height: 2.25rem;
}

.h-\[1px\]{
  height: 1px;
}

.h-\[2px\]{
  height: 2px;
}

.h-\[40px\]{
  height: 40px;
}

.h-\[500px\]{
  height: 500px;
}

.h-\[600px\]{
  height: 600px;
}

.h-\[60px\]{
  height: 60px;
}

.h-\[64px\]{
  height: 64px;
}

.h-\[800px\]{
  height: 800px;
}

.h-full{
  height: 100%;
}

.min-h-screen{
  min-height: 100vh;
}

.w-1\.5{
  width: 0.375rem;
}

.w-16{
  width: 4rem;
}

.w-2{
  width: 0.5rem;
}

.w-5{
  width: 1.25rem;
}

.w-6{
  width: 1.5rem;
}

.w-7{
  width: 1.75rem;
}

.w-8{
  width: 2rem;
}

.w-9{
  width: 2.25rem;
}

.w-\[1px\]{
  width: 1px;
}

.w-\[40px\]{
  width: 40px;
}

.w-\[500px\]{
  width: 500px;
}

.w-\[600px\]{
  width: 600px;
}

.w-\[60px\]{
  width: 60px;
}

.w-\[78\%\]{
  width: 78%;
}

.w-\[800px\]{
  width: 800px;
}

.w-full{
  width: 100%;
}

.max-w-\[1200px\]{
  max-width: 1200px;
}

.max-w-\[1280px\]{
  max-width: 1280px;
}

.max-w-\[260px\]{
  max-width: 260px;
}

.max-w-\[340px\]{
  max-width: 340px;
}

.max-w-\[360px\]{
  max-width: 360px;
}

.max-w-\[420px\]{
  max-width: 420px;
}

.max-w-\[480px\]{
  max-width: 480px;
}

.max-w-\[520px\]{
  max-width: 520px;
}

.max-w-\[600px\]{
  max-width: 600px;
}

.flex-1{
  flex: 1 1 0%;
}

.flex-\[2\]{
  flex: 2;
}

.shrink-0{
  flex-shrink: 0;
}

.-translate-x-1\/2{
  --tw-translate-x: -50%;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.rotate-45{
  --tw-rotate: 45deg;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

@keyframes pulse{
  50%{
    opacity: .5;
  }
}

.animate-pulse{
  animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}

.cursor-pointer{
  cursor: pointer;
}

.select-none{
  -webkit-user-select: none;
     -moz-user-select: none;
          user-select: none;
}

.resize-none{
  resize: none;
}

.grid-cols-2{
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.grid-cols-3{
  grid-template-columns: repeat(3, minmax(0, 1fr));
}

.grid-cols-\[1\.4fr_0\.6fr\]{
  grid-template-columns: 1.4fr 0.6fr;
}

.flex-col{
  flex-direction: column;
}

.flex-wrap{
  flex-wrap: wrap;
}

.items-start{
  align-items: flex-start;
}

.items-end{
  align-items: flex-end;
}

.items-center{
  align-items: center;
}

.items-baseline{
  align-items: baseline;
}

.justify-end{
  justify-content: flex-end;
}

.justify-center{
  justify-content: center;
}

.justify-between{
  justify-content: space-between;
}

.gap-1{
  gap: 0.25rem;
}

.gap-10{
  gap: 2.5rem;
}

.gap-12{
  gap: 3rem;
}

.gap-2{
  gap: 0.5rem;
}

.gap-3{
  gap: 0.75rem;
}

.gap-4{
  gap: 1rem;
}

.gap-5{
  gap: 1.25rem;
}

.gap-6{
  gap: 1.5rem;
}

.gap-8{
  gap: 2rem;
}

.space-y-10 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(2.5rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(2.5rem * var(--tw-space-y-reverse));
}

.space-y-2 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(0.5rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(0.5rem * var(--tw-space-y-reverse));
}

.space-y-3 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(0.75rem * var(--tw-space-y-reverse));
}

.space-y-4 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(1rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(1rem * var(--tw-space-y-reverse));
}

.space-y-6 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(1.5rem * var(--tw-space-y-reverse));
}

.overflow-auto{
  overflow: auto;
}

.overflow-hidden{
  overflow: hidden;
}

.overflow-x-clip{
  overflow-x: clip;
}

.truncate{
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.whitespace-pre-line{
  white-space: pre-line;
}

.rounded{
  border-radius: 0.25rem;
}

.rounded-\[10px\]{
  border-radius: 10px;
}

.rounded-\[12px\]{
  border-radius: 12px;
}

.rounded-\[14px\]{
  border-radius: 14px;
}

.rounded-\[16px\]{
  border-radius: 16px;
}

.rounded-\[18px\]{
  border-radius: 18px;
}

.rounded-\[19px\]{
  border-radius: 19px;
}

.rounded-\[20px\]{
  border-radius: 20px;
}

.rounded-\[24px\]{
  border-radius: 24px;
}

.rounded-\[28px\]{
  border-radius: 28px;
}

.rounded-\[6px\]{
  border-radius: 6px;
}

.rounded-\[8px\]{
  border-radius: 8px;
}

.rounded-full{
  border-radius: 9999px;
}

.rounded-t-\[19px\]{
  border-top-left-radius: 19px;
  border-top-right-radius: 19px;
}

.border{
  border-width: 1px;
}

.border-y{
  border-top-width: 1px;
  border-bottom-width: 1px;
}

.border-b{
  border-bottom-width: 1px;
}

.border-t{
  border-top-width: 1px;
}

.border-\[\#25D366\]\/30{
  border-color: rgb(37 211 102 / 0.3);
}

.border-\[\#FF0033\]{
  --tw-border-opacity: 1;
  border-color: rgb(255 0 51 / var(--tw-border-opacity, 1));
}

.border-\[\#FF0033\]\/20{
  border-color: rgb(255 0 51 / 0.2);
}

.border-\[\#FF0033\]\/30{
  border-color: rgb(255 0 51 / 0.3);
}

.border-\[rgba\(255\2c 0\2c 51\2c 0\.2\)\]{
  border-color: rgba(255,0,51,0.2);
}

.border-white\/10{
  border-color: rgb(255 255 255 / 0.1);
}

.border-white\/15{
  border-color: rgb(255 255 255 / 0.15);
}

.border-white\/5{
  border-color: rgb(255 255 255 / 0.05);
}

.border-white\/\[0\.06\]{
  border-color: rgb(255 255 255 / 0.06);
}

.border-white\/\[0\.07\]{
  border-color: rgb(255 255 255 / 0.07);
}

.border-white\/\[0\.08\]{
  border-color: rgb(255 255 255 / 0.08);
}

.bg-\[\#0a0a0a\]{
  --tw-bg-opacity: 1;
  background-color: rgb(10 10 10 / var(--tw-bg-opacity, 1));
}

.bg-\[\#111\]{
  --tw-bg-opacity: 1;
  background-color: rgb(17 17 17 / var(--tw-bg-opacity, 1));
}

.bg-\[\#121212\]{
  --tw-bg-opacity: 1;
  background-color: rgb(18 18 18 / var(--tw-bg-opacity, 1));
}

.bg-\[\#1a1a1a\]{
  --tw-bg-opacity: 1;
  background-color: rgb(26 26 26 / var(--tw-bg-opacity, 1));
}

.bg-\[\#25D366\]\/20{
  background-color: rgb(37 211 102 / 0.2);
}

.bg-\[\#FF0033\]{
  --tw-bg-opacity: 1;
  background-color: rgb(255 0 51 / var(--tw-bg-opacity, 1));
}

.bg-\[\#FF0033\]\/10{
  background-color: rgb(255 0 51 / 0.1);
}

.bg-\[\#FF0033\]\/15{
  background-color: rgb(255 0 51 / 0.15);
}

.bg-\[\#FF0033\]\/20{
  background-color: rgb(255 0 51 / 0.2);
}

.bg-\[rgba\(255\2c 0\2c 51\2c 0\.08\)\]{
  background-color: rgba(255,0,51,0.08);
}

.bg-black{
  --tw-bg-opacity: 1;
  background-color: rgb(0 0 0 / var(--tw-bg-opacity, 1));
}

.bg-black\/50{
  background-color: rgb(0 0 0 / 0.5);
}

.bg-black\/60{
  background-color: rgb(0 0 0 / 0.6);
}

.bg-black\/80{
  background-color: rgb(0 0 0 / 0.8);
}

.bg-black\/90{
  background-color: rgb(0 0 0 / 0.9);
}

.bg-white{
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity, 1));
}

.bg-white\/10{
  background-color: rgb(255 255 255 / 0.1);
}

.bg-white\/5{
  background-color: rgb(255 255 255 / 0.05);
}

.bg-white\/\[0\.02\]{
  background-color: rgb(255 255 255 / 0.02);
}

.bg-white\/\[0\.03\]{
  background-color: rgb(255 255 255 / 0.03);
}

.bg-white\/\[0\.04\]{
  background-color: rgb(255 255 255 / 0.04);
}

.bg-white\/\[0\.06\]{
  background-color: rgb(255 255 255 / 0.06);
}

.bg-white\/\[0\.08\]{
  background-color: rgb(255 255 255 / 0.08);
}

.bg-\[radial-gradient\(circle_at_30\%_20\%\2c rgba\(255\2c 0\2c 51\2c 0\.35\)\2c transparent_60\%\)\]{
  background-image: radial-gradient(circle at 30% 20%,rgba(255,0,51,0.35),transparent 60%);
}

.bg-\[radial-gradient\(circle_at_70\%_30\%\2c rgba\(255\2c 0\2c 51\2c 0\.25\)\2c transparent_60\%\)\]{
  background-image: radial-gradient(circle at 70% 30%,rgba(255,0,51,0.25),transparent 60%);
}

.bg-\[radial-gradient\(circle_at_80\%_20\%\2c rgba\(255\2c 0\2c 51\2c 0\.35\)\2c transparent_50\%\)\]{
  background-image: radial-gradient(circle at 80% 20%,rgba(255,0,51,0.35),transparent 50%);
}

.bg-\[radial-gradient\(circle_at_center\2c rgba\(255\2c 0\2c 51\2c 0\.12\)\2c transparent_70\%\)\]{
  background-image: radial-gradient(circle at center,rgba(255,0,51,0.12),transparent 70%);
}

.bg-\[radial-gradient\(circle_at_center\2c rgba\(255\2c 0\2c 51\2c 0\.18\)\2c transparent_70\%\)\]{
  background-image: radial-gradient(circle at center,rgba(255,0,51,0.18),transparent 70%);
}

.bg-\[radial-gradient\(circle_at_center\2c rgba\(255\2c 255\2c 255\2c 0\.03\)\2c transparent_70\%\)\]{
  background-image: radial-gradient(circle at center,rgba(255,255,255,0.03),transparent 70%);
}

.bg-gradient-to-b{
  background-image: linear-gradient(to bottom, var(--tw-gradient-stops));
}

.bg-gradient-to-br{
  background-image: linear-gradient(to bottom right, var(--tw-gradient-stops));
}

.bg-gradient-to-t{
  background-image: linear-gradient(to top, var(--tw-gradient-stops));
}

.bg-gradient-to-tr{
  background-image: linear-gradient(to top right, var(--tw-gradient-stops));
}

.from-\[\#111\]{
  --tw-gradient-from: #111 var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(17 17 17 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}

.from-\[\#FF0033\]{
  --tw-gradient-from: #FF0033 var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(255 0 51 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}

.from-\[\#FF0033\]\/30{
  --tw-gradient-from: rgb(255 0 51 / 0.3) var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(255 0 51 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}

.from-black{
  --tw-gradient-from: #000 var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(0 0 0 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}

.from-black\/60{
  --tw-gradient-from: rgb(0 0 0 / 0.6) var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(0 0 0 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}

.from-transparent{
  --tw-gradient-from: transparent var(--tw-gradient-from-position);
  --tw-gradient-to: rgb(0 0 0 / 0) var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), var(--tw-gradient-to);
}

.via-\[\#1a0a0f\]{
  --tw-gradient-to: rgb(26 10 15 / 0)  var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), #1a0a0f var(--tw-gradient-via-position), var(--tw-gradient-to);
}

.via-\[\#FF0033\]\/40{
  --tw-gradient-to: rgb(255 0 51 / 0)  var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), rgb(255 0 51 / 0.4) var(--tw-gradient-via-position), var(--tw-gradient-to);
}

.via-black\/20{
  --tw-gradient-to: rgb(0 0 0 / 0)  var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), rgb(0 0 0 / 0.2) var(--tw-gradient-via-position), var(--tw-gradient-to);
}

.via-black\/30{
  --tw-gradient-to: rgb(0 0 0 / 0)  var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), rgb(0 0 0 / 0.3) var(--tw-gradient-via-position), var(--tw-gradient-to);
}

.via-black\/40{
  --tw-gradient-to: rgb(0 0 0 / 0)  var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), rgb(0 0 0 / 0.4) var(--tw-gradient-via-position), var(--tw-gradient-to);
}

.via-transparent{
  --tw-gradient-to: rgb(0 0 0 / 0)  var(--tw-gradient-to-position);
  --tw-gradient-stops: var(--tw-gradient-from), transparent var(--tw-gradient-via-position), var(--tw-gradient-to);
}

.to-\[\#FF0033\]\/10{
  --tw-gradient-to: rgb(255 0 51 / 0.1) var(--tw-gradient-to-position);
}

.to-\[\#FF0033\]\/30{
  --tw-gradient-to: rgb(255 0 51 / 0.3) var(--tw-gradient-to-position);
}

.to-\[\#FF0033\]\/40{
  --tw-gradient-to: rgb(255 0 51 / 0.4) var(--tw-gradient-to-position);
}

.to-transparent{
  --tw-gradient-to: transparent var(--tw-gradient-to-position);
}

.to-white\/10{
  --tw-gradient-to: rgb(255 255 255 / 0.1) var(--tw-gradient-to-position);
}

.object-cover{
  -o-object-fit: cover;
     object-fit: cover;
}

.p-10{
  padding: 2.5rem;
}

.p-2{
  padding: 0.5rem;
}

.p-3{
  padding: 0.75rem;
}

.p-4{
  padding: 1rem;
}

.p-5{
  padding: 1.25rem;
}

.p-6{
  padding: 1.5rem;
}

.p-7{
  padding: 1.75rem;
}

.p-8{
  padding: 2rem;
}

.p-\[1px\]{
  padding: 1px;
}

.px-2{
  padding-left: 0.5rem;
  padding-right: 0.5rem;
}

.px-2\.5{
  padding-left: 0.625rem;
  padding-right: 0.625rem;
}

.px-3{
  padding-left: 0.75rem;
  padding-right: 0.75rem;
}

.px-4{
  padding-left: 1rem;
  padding-right: 1rem;
}

.px-5{
  padding-left: 1.25rem;
  padding-right: 1.25rem;
}

.px-6{
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}

.px-8{
  padding-left: 2rem;
  padding-right: 2rem;
}

.py-1{
  padding-top: 0.25rem;
  padding-bottom: 0.25rem;
}

.py-10{
  padding-top: 2.5rem;
  padding-bottom: 2.5rem;
}

.py-2{
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}

.py-20{
  padding-top: 5rem;
  padding-bottom: 5rem;
}

.py-3{
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
}

.py-4{
  padding-top: 1rem;
  padding-bottom: 1rem;
}

.py-5{
  padding-top: 1.25rem;
  padding-bottom: 1.25rem;
}

.py-6{
  padding-top: 1.5rem;
  padding-bottom: 1.5rem;
}

.py-\[10px\]{
  padding-top: 10px;
  padding-bottom: 10px;
}

.py-\[14px\]{
  padding-top: 14px;
  padding-bottom: 14px;
}

.pb-10{
  padding-bottom: 2.5rem;
}

.pb-20{
  padding-bottom: 5rem;
}

.pb-5{
  padding-bottom: 1.25rem;
}

.pt-16{
  padding-top: 4rem;
}

.pt-3{
  padding-top: 0.75rem;
}

.pt-4{
  padding-top: 1rem;
}

.pt-8{
  padding-top: 2rem;
}

.text-center{
  text-align: center;
}

.text-right{
  text-align: right;
}

.text-\[10px\]{
  font-size: 10px;
}

.text-\[11px\]{
  font-size: 11px;
}

.text-\[12px\]{
  font-size: 12px;
}

.text-\[13px\]{
  font-size: 13px;
}

.text-\[14px\]{
  font-size: 14px;
}

.text-\[14vw\]{
  font-size: 14vw;
}

.text-\[15px\]{
  font-size: 15px;
}

.text-\[16px\]{
  font-size: 16px;
}

.text-\[18px\]{
  font-size: 18px;
}

.text-\[28px\]{
  font-size: 28px;
}

.text-\[32px\]{
  font-size: 32px;
}

.text-\[36px\]{
  font-size: 36px;
}

.text-\[42px\]{
  font-size: 42px;
}

.text-\[48px\]{
  font-size: 48px;
}

.text-\[9px\]{
  font-size: 9px;
}

.font-\[900\]{
  font-weight: 900;
}

.font-black{
  font-weight: 900;
}

.font-bold{
  font-weight: 700;
}

.font-light{
  font-weight: 300;
}

.leading-\[0\.85\]{
  line-height: 0.85;
}

.leading-\[0\.95\]{
  line-height: 0.95;
}

.leading-\[0\.9\]{
  line-height: 0.9;
}

.leading-\[1\.4\]{
  line-height: 1.4;
}

.leading-\[1\.6\]{
  line-height: 1.6;
}

.leading-\[1\.7\]{
  line-height: 1.7;
}

.leading-\[1\.8\]{
  line-height: 1.8;
}

.leading-\[1\.9\]{
  line-height: 1.9;
}

.leading-none{
  line-height: 1;
}

.leading-relaxed{
  line-height: 1.625;
}

.tracking-\[-0\.04em\]{
  letter-spacing: -0.04em;
}

.tracking-\[0\.15em\]{
  letter-spacing: 0.15em;
}

.tracking-\[0\.25em\]{
  letter-spacing: 0.25em;
}

.tracking-\[0\.2em\]{
  letter-spacing: 0.2em;
}

.tracking-\[0\.35em\]{
  letter-spacing: 0.35em;
}

.tracking-\[0\.3em\]{
  letter-spacing: 0.3em;
}

.tracking-\[0\.4em\]{
  letter-spacing: 0.4em;
}

.tracking-widest{
  letter-spacing: 0.1em;
}

.text-\[\#FF0033\]{
  --tw-text-opacity: 1;
  color: rgb(255 0 51 / var(--tw-text-opacity, 1));
}

.text-\[\#FFD700\]{
  --tw-text-opacity: 1;
  color: rgb(255 215 0 / var(--tw-text-opacity, 1));
}

.text-\[\#ff8a9e\]{
  --tw-text-opacity: 1;
  color: rgb(255 138 158 / var(--tw-text-opacity, 1));
}

.text-black{
  --tw-text-opacity: 1;
  color: rgb(0 0 0 / var(--tw-text-opacity, 1));
}

.text-white{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}

.text-white\/20{
  color: rgb(255 255 255 / 0.2);
}

.text-white\/30{
  color: rgb(255 255 255 / 0.3);
}

.text-white\/40{
  color: rgb(255 255 255 / 0.4);
}

.text-white\/50{
  color: rgb(255 255 255 / 0.5);
}

.text-white\/60{
  color: rgb(255 255 255 / 0.6);
}

.text-white\/70{
  color: rgb(255 255 255 / 0.7);
}

.text-white\/80{
  color: rgb(255 255 255 / 0.8);
}

.text-white\/\[0\.06\]{
  color: rgb(255 255 255 / 0.06);
}

.opacity-20{
  opacity: 0.2;
}

.opacity-60{
  opacity: 0.6;
}

.opacity-80{
  opacity: 0.8;
}

.mix-blend-overlay{
  mix-blend-mode: overlay;
}

.mix-blend-luminosity{
  mix-blend-mode: luminosity;
}

.shadow-\[0_0_10px_\#FF0033\]{
  --tw-shadow: 0 0 10px #FF0033;
  --tw-shadow-colored: 0 0 10px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.shadow-\[0_0_16px_rgba\(255\2c 0\2c 51\2c 0\.6\)\]{
  --tw-shadow: 0 0 16px rgba(255,0,51,0.6);
  --tw-shadow-colored: 0 0 16px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.shadow-\[0_0_30px_rgba\(255\2c 0\2c 51\2c 0\.3\)\]{
  --tw-shadow: 0 0 30px rgba(255,0,51,0.3);
  --tw-shadow-colored: 0 0 30px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.shadow-\[0_0_8px_\#FF0033\]{
  --tw-shadow: 0 0 8px #FF0033;
  --tw-shadow-colored: 0 0 8px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.outline-none{
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.filter{
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
}

.backdrop-blur{
  --tw-backdrop-blur: blur(8px);
  backdrop-filter: var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);
}

.backdrop-blur-\[12px\]{
  --tw-backdrop-blur: blur(12px);
  backdrop-filter: var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);
}

.backdrop-blur-\[18px\]{
  --tw-backdrop-blur: blur(18px);
  backdrop-filter: var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);
}

.backdrop-blur-xl{
  --tw-backdrop-blur: blur(24px);
  backdrop-filter: var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);
}

.transition{
  transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.duration-700{
  transition-duration: 700ms;
}

:root {
  --bg: #000000;
  --card: #111111;
  --card-2: #181818;
  --blood: #FF0033;
  --blood-glow: rgba(255,0,51,0.5);
  --text: #ffffff;
  --muted: #8a8a8a;
  --border: rgba(255,255,255,0.08);
}

* {
  font-family: 'Tajawal', sans-serif;
}

.font-orbitron {
  font-family: 'Orbitron', sans-serif;
}

.font-tajawal {
  font-family: 'Tajawal', sans-serif;
}

html {
  scroll-behavior: smooth;
}

body {
  background: var(--bg);
  color: var(--text);
  overflow-x: clip;
  -webkit-font-smoothing: antialiased;
}

/* Grain */

.grain::before {
  content: '';
  position: fixed;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noiseFilter'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noiseFilter)'/%3E%3C/svg%3E");
  opacity: 0.035;
  pointer-events: none;
  z-index: 9999;
  mix-blend-mode: screen;
}

.glow-red {
  box-shadow: 0 0 30px var(--blood-glow), 0 0 80px rgba(255,0,51,0.15);
}

.glow-text {
  text-shadow: 0 0 20px rgba(255,0,51,0.6), 0 0 40px rgba(255,0,51,0.2);
}

.btn-blood {
  background: var(--blood);
  color: white;
  transition: all 0.3s cubic-bezier(0.23,1,0.32,1);
  position: relative;
  overflow: hidden;
}

.btn-blood:hover {
  box-shadow: 0 0 30px var(--blood), 0 0 60px rgba(255,0,51,0.4);
  transform: scale(1.03);
}

.btn-blood::after {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(100deg, transparent 20%, rgba(255,255,255,0.2) 50%, transparent 80%);
  transform: translateX(-100%);
  transition: transform 0.6s;
}

.btn-blood:hover::after {
  transform: translateX(100%);
}

.glass {
  background: linear-gradient(180deg, rgba(17,17,17,0.9) 0%, rgba(17,17,17,0.6) 100%);
  backdrop-filter: blur(24px) saturate(1.2);
  -webkit-backdrop-filter: blur(24px) saturate(1.2);
  border: 1px solid var(--border);
}

.orb {
  position: absolute;
  border-radius: 50%;
  filter: blur(80px);
  pointer-events: none;
}

/* custom scrollbar */

::-webkit-scrollbar {
  width: 6px;
  height: 6px;
}

::-webkit-scrollbar-thumb {
  background: #222;
  border-radius: 10px;
}

::-webkit-scrollbar-thumb:hover {
  background: var(--blood);
}

@keyframes glitch {
  0% {
    transform: translate(0);
  }

  20% {
    transform: translate(-1px, 1px);
  }

  40% {
    transform: translate(-1px, -1px);
  }

  60% {
    transform: translate(1px, 1px);
  }

  80% {
    transform: translate(1px, -1px);
  }

  100% {
    transform: translate(0);
  }
}

.selection\:bg-\[\#FF0033\] *::-moz-selection{
  --tw-bg-opacity: 1;
  background-color: rgb(255 0 51 / var(--tw-bg-opacity, 1));
}

.selection\:bg-\[\#FF0033\] *::selection{
  --tw-bg-opacity: 1;
  background-color: rgb(255 0 51 / var(--tw-bg-opacity, 1));
}

.selection\:text-white *::-moz-selection{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}

.selection\:text-white *::selection{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}

.selection\:bg-\[\#FF0033\]::-moz-selection{
  --tw-bg-opacity: 1;
  background-color: rgb(255 0 51 / var(--tw-bg-opacity, 1));
}

.selection\:bg-\[\#FF0033\]::selection{
  --tw-bg-opacity: 1;
  background-color: rgb(255 0 51 / var(--tw-bg-opacity, 1));
}

.selection\:text-white::-moz-selection{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}

.selection\:text-white::selection{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}

.hover\:border-\[\#FF0033\]\/30:hover{
  border-color: rgb(255 0 51 / 0.3);
}

.hover\:bg-\[\#25D366\]\/30:hover{
  background-color: rgb(37 211 102 / 0.3);
}

.hover\:bg-\[\#FF0033\]\/20:hover{
  background-color: rgb(255 0 51 / 0.2);
}

.hover\:bg-white\/10:hover{
  background-color: rgb(255 255 255 / 0.1);
}

.hover\:bg-white\/15:hover{
  background-color: rgb(255 255 255 / 0.15);
}

.hover\:bg-white\/5:hover{
  background-color: rgb(255 255 255 / 0.05);
}

.hover\:bg-white\/90:hover{
  background-color: rgb(255 255 255 / 0.9);
}

.hover\:bg-white\/\[0\.02\]:hover{
  background-color: rgb(255 255 255 / 0.02);
}

.hover\:bg-white\/\[0\.06\]:hover{
  background-color: rgb(255 255 255 / 0.06);
}

.hover\:bg-white\/\[0\.1\]:hover{
  background-color: rgb(255 255 255 / 0.1);
}

.hover\:text-\[\#FF0033\]:hover{
  --tw-text-opacity: 1;
  color: rgb(255 0 51 / var(--tw-text-opacity, 1));
}

.hover\:text-white:hover{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}

.focus\:border-\[\#FF0033\]\/50:focus{
  border-color: rgb(255 0 51 / 0.5);
}

.focus\:shadow-\[0_0_0_3px_rgba\(255\2c 0\2c 51\2c 0\.15\)\]:focus{
  --tw-shadow: 0 0 0 3px rgba(255,0,51,0.15);
  --tw-shadow-colored: 0 0 0 3px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.group:hover .group-hover\:scale-\[1\.05\]{
  --tw-scale-x: 1.05;
  --tw-scale-y: 1.05;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

@media (min-width: 768px){
  .md\:block{
    display: block;
  }

  .md\:flex{
    display: flex;
  }

  .md\:hidden{
    display: none;
  }

  .md\:aspect-\[4\/5\]{
    aspect-ratio: 4/5;
  }

  .md\:grid-cols-2{
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .md\:grid-cols-3{
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .md\:grid-cols-\[0\.9fr_1\.1fr\]{
    grid-template-columns: 0.9fr 1.1fr;
  }

  .md\:grid-cols-\[1\.1fr_0\.9fr\]{
    grid-template-columns: 1.1fr 0.9fr;
  }

  .md\:grid-cols-\[1\.2fr_0\.8fr\]{
    grid-template-columns: 1.2fr 0.8fr;
  }

  .md\:flex-row{
    flex-direction: row;
  }

  .md\:p-14{
    padding: 3.5rem;
  }

  .md\:p-7{
    padding: 1.75rem;
  }

  .md\:p-8{
    padding: 2rem;
  }

  .md\:px-4{
    padding-left: 1rem;
    padding-right: 1rem;
  }

  .md\:px-8{
    padding-left: 2rem;
    padding-right: 2rem;
  }

  .md\:pt-28{
    padding-top: 7rem;
  }

  .md\:text-\[13px\]{
    font-size: 13px;
  }

  .md\:text-\[20px\]{
    font-size: 20px;
  }

  .md\:text-\[42px\]{
    font-size: 42px;
  }

  .md\:text-\[52px\]{
    font-size: 52px;
  }

  .md\:text-\[56px\]{
    font-size: 56px;
  }

  .md\:text-\[64px\]{
    font-size: 64px;
  }

  .md\:text-\[84px\]{
    font-size: 84px;
  }
}

@media (min-width: 1024px){
  .lg\:grid-cols-4{
    grid-template-columns: repeat(4, minmax(0, 1fr));
  }
}
</style>
</head>
<body>
  <div id="root"></div>
  
  <script type="module">var Qc=Object.create;var{getPrototypeOf:Hc,defineProperty:uu,getOwnPropertyNames:Wc}=Object;var Ac=Object.prototype.hasOwnProperty;var Ye=(e,n,t)=>{t=e!=null?Qc(Hc(e)):{};let r=n||!e||!e.__esModule?uu(t,"default",{value:e,enumerable:!0}):t;for(let l of Wc(e))if(!Ac.call(r,l))uu(r,l,{get:()=>e[l],enumerable:!0});return r};var Fr=(e,n)=>()=>(n||e((n={exports:{}}).exports,n),n.exports);var Kc=(e,n)=>{for(var t in n)uu(e,t,{get:n[t],enumerable:!0,configurable:!0,set:(r)=>n[t]=()=>r})};var Yc=(e,n)=>()=>(e&&(n=e(e=0)),n);var zn=Fr((id)=>{var Tt=Symbol.for("react.element"),Xc=Symbol.for("react.portal"),Gc=Symbol.for("react.fragment"),Zc=Symbol.for("react.strict_mode"),Jc=Symbol.for("react.profiler"),qc=Symbol.for("react.provider"),xc=Symbol.for("react.context"),jc=Symbol.for("react.forward_ref"),bc=Symbol.for("react.suspense"),ed=Symbol.for("react.memo"),nd=Symbol.for("react.lazy"),Ui=Symbol.iterator;function td(e){if(e===null||typeof e!=="object")return null;return e=Ui&&e[Ui]||e["@@iterator"],typeof e==="function"?e:null}var $i={isMounted:function(){return!1},enqueueForceUpdate:function(){},enqueueReplaceState:function(){},enqueueSetState:function(){}},Qi=Object.assign,Hi={};function Zn(e,n,t){this.props=e,this.context=n,this.refs=Hi,this.updater=t||$i}Zn.prototype.isReactComponent={};Zn.prototype.setState=function(e,n){if(typeof e!=="object"&&typeof e!=="function"&&e!=null)throw Error("setState(...): takes an object of state variables to update or a function which returns an object of state variables.");this.updater.enqueueSetState(this,e,n,"setState")};Zn.prototype.forceUpdate=function(e){this.updater.enqueueForceUpdate(this,e,"forceUpdate")};function Wi(){}Wi.prototype=Zn.prototype;function iu(e,n,t){this.props=e,this.context=n,this.refs=Hi,this.updater=t||$i}var au=iu.prototype=new Wi;au.constructor=iu;Qi(au,Zn.prototype);au.isPureReactComponent=!0;var Vi=Array.isArray,Ai=Object.prototype.hasOwnProperty,su={current:null},Ki={key:!0,ref:!0,__self:!0,__source:!0};function Yi(e,n,t){var r,l={},u=null,o=null;if(n!=null)for(r in n.ref!==void 0&&(o=n.ref),n.key!==void 0&&(u=""+n.key),n)Ai.call(n,r)&&!Ki.hasOwnProperty(r)&&(l[r]=n[r]);var i=arguments.length-2;if(i===1)l.children=t;else if(1<i){for(var a=Array(i),c=0;c<i;c++)a[c]=arguments[c+2];l.children=a}if(e&&e.defaultProps)for(r in i=e.defaultProps,i)l[r]===void 0&&(l[r]=i[r]);return{$$typeof:Tt,type:e,key:u,ref:o,props:l,_owner:su.current}}function rd(e,n){return{$$typeof:Tt,type:e.type,key:n,ref:e.ref,props:e.props,_owner:e._owner}}function fu(e){return typeof e==="object"&&e!==null&&e.$$typeof===Tt}function ld(e){var n={"=":"=0",":":"=2"};return"$"+e.replace(/[=:]/g,function(t){return n[t]})}var Bi=/\/+/g;function ou(e,n){return typeof e==="object"&&e!==null&&e.key!=null?ld(""+e.key):n.toString(36)}function Ur(e,n,t,r,l){var u=typeof e;if(u==="undefined"||u==="boolean")e=null;var o=!1;if(e===null)o=!0;else switch(u){case"string":case"number":o=!0;break;case"object":switch(e.$$typeof){case Tt:case Xc:o=!0}}if(o)return o=e,l=l(o),e=r===""?"."+ou(o,0):r,Vi(l)?(t="",e!=null&&(t=e.replace(Bi,"$&/")+"/"),Ur(l,n,t,"",function(c){return c})):l!=null&&(fu(l)&&(l=rd(l,t+(!l.key||o&&o.key===l.key?"":(""+l.key).replace(Bi,"$&/")+"/")+e)),n.push(l)),1;if(o=0,r=r===""?".":r+":",Vi(e))for(var i=0;i<e.length;i++){u=e[i];var a=r+ou(u,i);o+=Ur(u,n,t,a,l)}else if(a=td(e),typeof a==="function")for(e=a.call(e),i=0;!(u=e.next()).done;)u=u.value,a=r+ou(u,i++),o+=Ur(u,n,t,a,l);else if(u==="object")throw n=String(e),Error("Objects are not valid as a React child (found: "+(n==="[object Object]"?"object with keys {"+Object.keys(e).join(", ")+"}":n)+"). If you meant to render a collection of children, use an array instead.");return o}function Or(e,n,t){if(e==null)return e;var r=[],l=0;return Ur(e,r,"","",function(u){return n.call(t,u,l++)}),r}function ud(e){if(e._status===-1){var n=e._result;n=n(),n.then(function(t){if(e._status===0||e._status===-1)e._status=1,e._result=t},function(t){if(e._status===0||e._status===-1)e._status=2,e._result=t}),e._status===-1&&(e._status=0,e._result=n)}if(e._status===1)return e._result.default;throw e._result}var ae={current:null},Vr={transition:null},od={ReactCurrentDispatcher:ae,ReactCurrentBatchConfig:Vr,ReactCurrentOwner:su};function Xi(){throw Error("act(...) is not supported in production builds of React.")}id.Children={map:Or,forEach:function(e,n,t){Or(e,function(){n.apply(this,arguments)},t)},count:function(e){var n=0;return Or(e,function(){n++}),n},toArray:function(e){return Or(e,function(n){return n})||[]},only:function(e){if(!fu(e))throw Error("React.Children.only expected to receive a single React element child.");return e}};id.Component=Zn;id.Fragment=Gc;id.Profiler=Jc;id.PureComponent=iu;id.StrictMode=Zc;id.Suspense=bc;id.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED=od;id.act=Xi;id.cloneElement=function(e,n,t){if(e===null||e===void 0)throw Error("React.cloneElement(...): The argument must be a React element, but you passed "+e+".");var r=Qi({},e.props),l=e.key,u=e.ref,o=e._owner;if(n!=null){if(n.ref!==void 0&&(u=n.ref,o=su.current),n.key!==void 0&&(l=""+n.key),e.type&&e.type.defaultProps)var i=e.type.defaultProps;for(a in n)Ai.call(n,a)&&!Ki.hasOwnProperty(a)&&(r[a]=n[a]===void 0&&i!==void 0?i[a]:n[a])}var a=arguments.length-2;if(a===1)r.children=t;else if(1<a){i=Array(a);for(var c=0;c<a;c++)i[c]=arguments[c+2];r.children=i}return{$$typeof:Tt,type:e.type,key:l,ref:u,props:r,_owner:o}};id.createContext=function(e){return e={$$typeof:xc,_currentValue:e,_currentValue2:e,_threadCount:0,Provider:null,Consumer:null,_defaultValue:null,_globalName:null},e.Provider={$$typeof:qc,_context:e},e.Consumer=e};id.createElement=Yi;id.createFactory=function(e){var n=Yi.bind(null,e);return n.type=e,n};id.createRef=function(){return{current:null}};id.forwardRef=function(e){return{$$typeof:jc,render:e}};id.isValidElement=fu;id.lazy=function(e){return{$$typeof:nd,_payload:{_status:-1,_result:e},_init:ud}};id.memo=function(e,n){return{$$typeof:ed,type:e,compare:n===void 0?null:n}};id.startTransition=function(e){var n=Vr.transition;Vr.transition={};try{e()}finally{Vr.transition=n}};id.unstable_act=Xi;id.useCallback=function(e,n){return ae.current.useCallback(e,n)};id.useContext=function(e){return ae.current.useContext(e)};id.useDebugValue=function(){};id.useDeferredValue=function(e){return ae.current.useDeferredValue(e)};id.useEffect=function(e,n){return ae.current.useEffect(e,n)};id.useId=function(){return ae.current.useId()};id.useImperativeHandle=function(e,n,t){return ae.current.useImperativeHandle(e,n,t)};id.useInsertionEffect=function(e,n){return ae.current.useInsertionEffect(e,n)};id.useLayoutEffect=function(e,n){return ae.current.useLayoutEffect(e,n)};id.useMemo=function(e,n){return ae.current.useMemo(e,n)};id.useReducer=function(e,n,t){return ae.current.useReducer(e,n,t)};id.useRef=function(e){return ae.current.useRef(e)};id.useState=function(e){return ae.current.useState(e)};id.useSyncExternalStore=function(e,n,t){return ae.current.useSyncExternalStore(e,n,t)};id.useTransition=function(){return ae.current.useTransition()};id.version="18.3.1"});var bi=Fr((Yd)=>{function du(e,n){var t=e.length;e.push(n);e:for(;0<t;){var r=t-1>>>1,l=e[r];if(0<Br(l,n))e[r]=n,e[t]=l,t=r;else break e}}function Re(e){return e.length===0?null:e[0]}function Wr(e){if(e.length===0)return null;var n=e[0],t=e.pop();if(t!==n){e[0]=t;e:for(var r=0,l=e.length,u=l>>>1;r<u;){var o=2*(r+1)-1,i=e[o],a=o+1,c=e[a];if(0>Br(i,t))a<l&&0>Br(c,i)?(e[r]=c,e[a]=t,r=a):(e[r]=i,e[o]=t,r=o);else if(a<l&&0>Br(c,t))e[r]=c,e[a]=t,r=a;else break e}}return n}function Br(e,n){var t=e.sortIndex-n.sortIndex;return t!==0?t:e.id-n.id}if(typeof performance==="object"&&typeof performance.now==="function")pu=performance,Yd.unstable_now=function(){return pu.now()};else $r=Date,vu=$r.now(),Yd.unstable_now=function(){return $r.now()-vu};var pu,$r,vu,Be=[],rn=[],Kd=1,ke=null,re=3,Ar=!1,Pn=!1,Dt=!1,Zi=typeof setTimeout==="function"?setTimeout:null,Ji=typeof clearTimeout==="function"?clearTimeout:null,Gi=typeof setImmediate<"u"?setImmediate:null;typeof navigator<"u"&&navigator.scheduling!==void 0&&navigator.scheduling.isInputPending!==void 0&&navigator.scheduling.isInputPending.bind(navigator.scheduling);function hu(e){for(var n=Re(rn);n!==null;){if(n.callback===null)Wr(rn);else if(n.startTime<=e)Wr(rn),n.sortIndex=n.expirationTime,du(Be,n);else break;n=Re(rn)}}function mu(e){if(Dt=!1,hu(e),!Pn)if(Re(Be)!==null)Pn=!0,Su(gu);else{var n=Re(rn);n!==null&&wu(mu,n.startTime-e)}}function gu(e,n){Pn=!1,Dt&&(Dt=!1,Ji(Mt),Mt=-1),Ar=!0;var t=re;try{hu(n);for(ke=Re(Be);ke!==null&&(!(ke.expirationTime>n)||e&&!ji());){var r=ke.callback;if(typeof r==="function"){ke.callback=null,re=ke.priorityLevel;var l=r(ke.expirationTime<=n);n=Yd.unstable_now(),typeof l==="function"?ke.callback=l:ke===Re(Be)&&Wr(Be),hu(n)}else Wr(Be);ke=Re(Be)}if(ke!==null)var u=!0;else{var o=Re(rn);o!==null&&wu(mu,o.startTime-n),u=!1}return u}finally{ke=null,re=t,Ar=!1}}var Kr=!1,Qr=null,Mt=-1,qi=5,xi=-1;function ji(){return Yd.unstable_now()-xi<qi?!1:!0}function cu(){if(Qr!==null){var e=Yd.unstable_now();xi=e;var n=!0;try{n=Qr(!0,e)}finally{n?Rt():(Kr=!1,Qr=null)}}else Kr=!1}var Rt;if(typeof Gi==="function")Rt=function(){Gi(cu)};else if(typeof MessageChannel<"u")Hr=new MessageChannel,yu=Hr.port2,Hr.port1.onmessage=cu,Rt=function(){yu.postMessage(null)};else Rt=function(){Zi(cu,0)};var Hr,yu;function Su(e){Qr=e,Kr||(Kr=!0,Rt())}function wu(e,n){Mt=Zi(function(){e(Yd.unstable_now())},n)}Yd.unstable_IdlePriority=5;Yd.unstable_ImmediatePriority=1;Yd.unstable_LowPriority=4;Yd.unstable_NormalPriority=3;Yd.unstable_Profiling=null;Yd.unstable_UserBlockingPriority=2;Yd.unstable_cancelCallback=function(e){e.callback=null};Yd.unstable_continueExecution=function(){Pn||Ar||(Pn=!0,Su(gu))};Yd.unstable_forceFrameRate=function(e){0>e||125<e?console.error("forceFrameRate takes a positive int between 0 and 125, forcing frame rates higher than 125 fps is not supported"):qi=0<e?Math.floor(1000/e):5};Yd.unstable_getCurrentPriorityLevel=function(){return re};Yd.unstable_getFirstCallbackNode=function(){return Re(Be)};Yd.unstable_next=function(e){switch(re){case 1:case 2:case 3:var n=3;break;default:n=re}var t=re;re=n;try{return e()}finally{re=t}};Yd.unstable_pauseExecution=function(){};Yd.unstable_requestPaint=function(){};Yd.unstable_runWithPriority=function(e,n){switch(e){case 1:case 2:case 3:case 4:case 5:break;default:e=3}var t=re;re=e;try{return n()}finally{re=t}};Yd.unstable_scheduleCallback=function(e,n,t){var r=Yd.unstable_now();switch(typeof t==="object"&&t!==null?(t=t.delay,t=typeof t==="number"&&0<t?r+t:r):t=r,e){case 1:var l=-1;break;case 2:l=250;break;case 5:l=1073741823;break;case 4:l=1e4;break;default:l=5000}return l=t+l,e={id:Kd++,callback:n,priorityLevel:e,startTime:t,expirationTime:l,sortIndex:-1},t>r?(e.sortIndex=t,du(rn,e),Re(Be)===null&&e===Re(rn)&&(Dt?(Ji(Mt),Mt=-1):Dt=!0,wu(mu,t-r))):(e.sortIndex=l,du(Be,e),Pn||Ar||(Pn=!0,Su(gu))),e};Yd.unstable_shouldYield=ji;Yd.unstable_wrapCallback=function(e){var n=re;return function(){var t=re;re=n;try{return e.apply(this,arguments)}finally{re=t}}}});var Pi={};Kc(Pi,{version:()=>vc,unstable_renderSubtreeIntoContainer:()=>pc,unstable_batchedUpdates:()=>dc,unmountComponentAtNode:()=>cc,render:()=>fc,hydrateRoot:()=>sc,hydrate:()=>ac,flushSync:()=>ic,findDOMNode:()=>oc,createRoot:()=>uc,createPortal:()=>lc,__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED:()=>rc});function w(e){for(var n="https://reactjs.org/docs/error-decoder.html?invariant="+e,t=1;t<arguments.length;t++)n+="&args[]="+encodeURIComponent(arguments[t]);return"Minified React error #"+e+"; visit "+n+" for the full message or use the non-minified dev environment for full errors and additional helpful warnings."}function Hn(e,n){yt(e,n),yt(e+"Capture",n)}function yt(e,n){tr[e]=n;for(e=0;e<n.length;e++)us.add(n[e])}function cp(e){if(Wu.call(na,e))return!0;if(Wu.call(ea,e))return!1;if(fp.test(e))return na[e]=!0;return ea[e]=!0,!1}function dp(e,n,t,r){if(t!==null&&t.type===0)return!1;switch(typeof n){case"function":case"symbol":return!0;case"boolean":if(r)return!1;if(t!==null)return!t.acceptsBooleans;return e=e.toLowerCase().slice(0,5),e!=="data-"&&e!=="aria-";default:return!1}}function pp(e,n,t,r){if(n===null||typeof n>"u"||dp(e,n,t,r))return!0;if(r)return!1;if(t!==null)switch(t.type){case 3:return!n;case 4:return n===!1;case 5:return isNaN(n);case 6:return isNaN(n)||1>n}return!1}function ce(e,n,t,r,l,u,o){this.acceptsBooleans=n===2||n===3||n===4,this.attributeName=r,this.attributeNamespace=l,this.mustUseProperty=t,this.propertyName=e,this.type=n,this.sanitizeURL=u,this.removeEmptyString=o}function Bo(e){return e[1].toUpperCase()}function $o(e,n,t,r){var l=te.hasOwnProperty(n)?te[n]:null;if(l!==null?l.type!==0:r||!(2<n.length)||n[0]!=="o"&&n[0]!=="O"||n[1]!=="n"&&n[1]!=="N")pp(n,t,l,r)&&(t=null),r||l===null?cp(n)&&(t===null?e.removeAttribute(n):e.setAttribute(n,""+t)):l.mustUseProperty?e[l.propertyName]=t===null?l.type===3?!1:"":t:(n=l.attributeName,r=l.attributeNamespace,t===null?e.removeAttribute(n):(l=l.type,t=l===3||l===4&&t===!0?"":""+t,r?e.setAttributeNS(r,n,t):e.setAttribute(n,t)))}function It(e){if(e===null||typeof e!=="object")return null;return e=ta&&e[ta]||e["@@iterator"],typeof e==="function"?e:null}function $t(e){if(ku===void 0)try{throw Error()}catch(t){var n=t.stack.trim().match(/\n( *(at )?)/);ku=n&&n[1]||""}return`
`+ku+e}function Cu(e,n){if(!e||Eu)return"";Eu=!0;var t=Error.prepareStackTrace;Error.prepareStackTrace=void 0;try{if(n)if(n=function(){throw Error()},Object.defineProperty(n.prototype,"props",{set:function(){throw Error()}}),typeof Reflect==="object"&&Reflect.construct){try{Reflect.construct(n,[])}catch(c){var r=c}Reflect.construct(e,[],n)}else{try{n.call()}catch(c){r=c}e.call(n.prototype)}else{try{throw Error()}catch(c){r=c}e()}}catch(c){if(c&&r&&typeof c.stack==="string"){for(var l=c.stack.split(`
`),u=r.stack.split(`
`),o=l.length-1,i=u.length-1;1<=o&&0<=i&&l[o]!==u[i];)i--;for(;1<=o&&0<=i;o--,i--)if(l[o]!==u[i]){if(o!==1||i!==1)do if(o--,i--,0>i||l[o]!==u[i]){var a=`
`+l[o].replace(" at new "," at ");return e.displayName&&a.includes("<anonymous>")&&(a=a.replace("<anonymous>",e.displayName)),a}while(1<=o&&0<=i);break}}}finally{Eu=!1,Error.prepareStackTrace=t}return(e=e?e.displayName||e.name:"")?$t(e):""}function vp(e){switch(e.tag){case 5:return $t(e.type);case 16:return $t("Lazy");case 13:return $t("Suspense");case 19:return $t("SuspenseList");case 0:case 2:case 15:return e=Cu(e.type,!1),e;case 11:return e=Cu(e.type.render,!1),e;case 1:return e=Cu(e.type,!0),e;default:return""}}function Xu(e){if(e==null)return null;if(typeof e==="function")return e.displayName||e.name||null;if(typeof e==="string")return e;switch(e){case bn:return"Fragment";case jn:return"Portal";case Au:return"Profiler";case Qo:return"StrictMode";case Ku:return"Suspense";case Yu:return"SuspenseList"}if(typeof e==="object")switch(e.$$typeof){case is:return(e.displayName||"Context")+".Consumer";case os:return(e._context.displayName||"Context")+".Provider";case Ho:var n=e.render;return e=e.displayName,e||(e=n.displayName||n.name||"",e=e!==""?"ForwardRef("+e+")":"ForwardRef"),e;case Wo:return n=e.displayName||null,n!==null?n:Xu(e.type)||"Memo";case un:n=e._payload,e=e._init;try{return Xu(e(n))}catch(t){}}return null}function hp(e){var n=e.type;switch(e.tag){case 24:return"Cache";case 9:return(n.displayName||"Context")+".Consumer";case 10:return(n._context.displayName||"Context")+".Provider";case 18:return"DehydratedFragment";case 11:return e=n.render,e=e.displayName||e.name||"",n.displayName||(e!==""?"ForwardRef("+e+")":"ForwardRef");case 7:return"Fragment";case 5:return n;case 4:return"Portal";case 3:return"Root";case 6:return"Text";case 16:return Xu(n);case 8:return n===Qo?"StrictMode":"Mode";case 22:return"Offscreen";case 12:return"Profiler";case 21:return"Scope";case 13:return"Suspense";case 19:return"SuspenseList";case 25:return"TracingMarker";case 1:case 0:case 17:case 2:case 14:case 15:if(typeof n==="function")return n.displayName||n.name||null;if(typeof n==="string")return n}return null}function wn(e){switch(typeof e){case"boolean":case"number":case"string":case"undefined":return e;case"object":return e;default:return""}}function ss(e){var n=e.type;return(e=e.nodeName)&&e.toLowerCase()==="input"&&(n==="checkbox"||n==="radio")}function yp(e){var n=ss(e)?"checked":"value",t=Object.getOwnPropertyDescriptor(e.constructor.prototype,n),r=""+e[n];if(!e.hasOwnProperty(n)&&typeof t<"u"&&typeof t.get==="function"&&typeof t.set==="function"){var{get:l,set:u}=t;return Object.defineProperty(e,n,{configurable:!0,get:function(){return l.call(this)},set:function(o){r=""+o,u.call(this,o)}}),Object.defineProperty(e,n,{enumerable:t.enumerable}),{getValue:function(){return r},setValue:function(o){r=""+o},stopTracking:function(){e._valueTracker=null,delete e[n]}}}}function Xr(e){e._valueTracker||(e._valueTracker=yp(e))}function fs(e){if(!e)return!1;var n=e._valueTracker;if(!n)return!0;var t=n.getValue(),r="";return e&&(r=ss(e)?e.checked?"true":"false":e.value),e=r,e!==t?(n.setValue(e),!0):!1}function ml(e){if(e=e||(typeof document<"u"?document:void 0),typeof e>"u")return null;try{return e.activeElement||e.body}catch(n){return e.body}}function Gu(e,n){var t=n.checked;return X({},n,{defaultChecked:void 0,defaultValue:void 0,value:void 0,checked:t!=null?t:e._wrapperState.initialChecked})}function ra(e,n){var t=n.defaultValue==null?"":n.defaultValue,r=n.checked!=null?n.checked:n.defaultChecked;t=wn(n.value!=null?n.value:t),e._wrapperState={initialChecked:r,initialValue:t,controlled:n.type==="checkbox"||n.type==="radio"?n.checked!=null:n.value!=null}}function cs(e,n){n=n.checked,n!=null&&$o(e,"checked",n,!1)}function Zu(e,n){cs(e,n);var t=wn(n.value),r=n.type;if(t!=null)if(r==="number"){if(t===0&&e.value===""||e.value!=t)e.value=""+t}else e.value!==""+t&&(e.value=""+t);else if(r==="submit"||r==="reset"){e.removeAttribute("value");return}n.hasOwnProperty("value")?Ju(e,n.type,t):n.hasOwnProperty("defaultValue")&&Ju(e,n.type,wn(n.defaultValue)),n.checked==null&&n.defaultChecked!=null&&(e.defaultChecked=!!n.defaultChecked)}function la(e,n,t){if(n.hasOwnProperty("value")||n.hasOwnProperty("defaultValue")){var r=n.type;if(!(r!=="submit"&&r!=="reset"||n.value!==void 0&&n.value!==null))return;n=""+e._wrapperState.initialValue,t||n===e.value||(e.value=n),e.defaultValue=n}t=e.name,t!==""&&(e.name=""),e.defaultChecked=!!e._wrapperState.initialChecked,t!==""&&(e.name=t)}function Ju(e,n,t){if(n!=="number"||ml(e.ownerDocument)!==e)t==null?e.defaultValue=""+e._wrapperState.initialValue:e.defaultValue!==""+t&&(e.defaultValue=""+t)}function ft(e,n,t,r){if(e=e.options,n){n={};for(var l=0;l<t.length;l++)n["$"+t[l]]=!0;for(t=0;t<e.length;t++)l=n.hasOwnProperty("$"+e[t].value),e[t].selected!==l&&(e[t].selected=l),l&&r&&(e[t].defaultSelected=!0)}else{t=""+wn(t),n=null;for(l=0;l<e.length;l++){if(e[l].value===t){e[l].selected=!0,r&&(e[l].defaultSelected=!0);return}n!==null||e[l].disabled||(n=e[l])}n!==null&&(n.selected=!0)}}function qu(e,n){if(n.dangerouslySetInnerHTML!=null)throw Error(w(91));return X({},n,{value:void 0,defaultValue:void 0,children:""+e._wrapperState.initialValue})}function ua(e,n){var t=n.value;if(t==null){if(t=n.children,n=n.defaultValue,t!=null){if(n!=null)throw Error(w(92));if(Qt(t)){if(1<t.length)throw Error(w(93));t=t[0]}n=t}n==null&&(n=""),t=n}e._wrapperState={initialValue:wn(t)}}function ds(e,n){var t=wn(n.value),r=wn(n.defaultValue);t!=null&&(t=""+t,t!==e.value&&(e.value=t),n.defaultValue==null&&e.defaultValue!==t&&(e.defaultValue=t)),r!=null&&(e.defaultValue=""+r)}function oa(e){var n=e.textContent;n===e._wrapperState.initialValue&&n!==""&&n!==null&&(e.value=n)}function ps(e){switch(e){case"svg":return"http://www.w3.org/2000/svg";case"math":return"http://www.w3.org/1998/Math/MathML";default:return"http://www.w3.org/1999/xhtml"}}function xu(e,n){return e==null||e==="http://www.w3.org/1999/xhtml"?ps(n):e==="http://www.w3.org/2000/svg"&&n==="foreignObject"?"http://www.w3.org/1999/xhtml":e}function rr(e,n){if(n){var t=e.firstChild;if(t&&t===e.lastChild&&t.nodeType===3){t.nodeValue=n;return}}e.textContent=n}function hs(e,n,t){return n==null||typeof n==="boolean"||n===""?"":t||typeof n!=="number"||n===0||Gt.hasOwnProperty(e)&&Gt[e]?(""+n).trim():n+"px"}function ys(e,n){e=e.style;for(var t in n)if(n.hasOwnProperty(t)){var r=t.indexOf("--")===0,l=hs(t,n[t],r);t==="float"&&(t="cssFloat"),r?e.setProperty(t,l):e[t]=l}}function ju(e,n){if(n){if(gp[e]&&(n.children!=null||n.dangerouslySetInnerHTML!=null))throw Error(w(137,e));if(n.dangerouslySetInnerHTML!=null){if(n.children!=null)throw Error(w(60));if(typeof n.dangerouslySetInnerHTML!=="object"||!("__html"in n.dangerouslySetInnerHTML))throw Error(w(61))}if(n.style!=null&&typeof n.style!=="object")throw Error(w(62))}}function bu(e,n){if(e.indexOf("-")===-1)return typeof n.is==="string";switch(e){case"annotation-xml":case"color-profile":case"font-face":case"font-face-src":case"font-face-uri":case"font-face-format":case"font-face-name":case"missing-glyph":return!1;default:return!0}}function Ao(e){return e=e.target||e.srcElement||window,e.correspondingUseElement&&(e=e.correspondingUseElement),e.nodeType===3?e.parentNode:e}function ia(e){if(e=kr(e)){if(typeof no!=="function")throw Error(w(280));var n=e.stateNode;n&&(n=Yl(n),no(e.stateNode,e.type,n))}}function ms(e){ct?dt?dt.push(e):dt=[e]:ct=e}function gs(){if(ct){var e=ct,n=dt;if(dt=ct=null,ia(e),n)for(e=0;e<n.length;e++)ia(n[e])}}function Ss(e,n){return e(n)}function ws(){}function ks(e,n,t){if(_u)return e(n,t);_u=!0;try{return Ss(e,n,t)}finally{if(_u=!1,ct!==null||dt!==null)ws(),gs()}}function lr(e,n){var t=e.stateNode;if(t===null)return null;var r=Yl(t);if(r===null)return null;t=r[n];e:switch(n){case"onClick":case"onClickCapture":case"onDoubleClick":case"onDoubleClickCapture":case"onMouseDown":case"onMouseDownCapture":case"onMouseMove":case"onMouseMoveCapture":case"onMouseUp":case"onMouseUpCapture":case"onMouseEnter":(r=!r.disabled)||(e=e.type,r=!(e==="button"||e==="input"||e==="select"||e==="textarea")),e=!r;break e;default:e=!1}if(e)return null;if(t&&typeof t!=="function")throw Error(w(231,n,typeof t));return t}function Sp(e,n,t,r,l,u,o,i,a){var c=Array.prototype.slice.call(arguments,3);try{n.apply(t,c)}catch(y){this.onError(y)}}function kp(e,n,t,r,l,u,o,i,a){Zt=!1,gl=null,Sp.apply(wp,arguments)}function Ep(e,n,t,r,l,u,o,i,a){if(kp.apply(this,arguments),Zt){if(Zt){var c=gl;Zt=!1,gl=null}else throw Error(w(198));Sl||(Sl=!0,ro=c)}}function Wn(e){var n=e,t=e;if(e.alternate)for(;n.return;)n=n.return;else{e=n;do n=e,(n.flags&4098)!==0&&(t=n.return),e=n.return;while(e)}return n.tag===3?t:null}function Es(e){if(e.tag===13){var n=e.memoizedState;if(n===null&&(e=e.alternate,e!==null&&(n=e.memoizedState)),n!==null)return n.dehydrated}return null}function aa(e){if(Wn(e)!==e)throw Error(w(188))}function Cp(e){var n=e.alternate;if(!n){if(n=Wn(e),n===null)throw Error(w(188));return n!==e?null:e}for(var t=e,r=n;;){var l=t.return;if(l===null)break;var u=l.alternate;if(u===null){if(r=l.return,r!==null){t=r;continue}break}if(l.child===u.child){for(u=l.child;u;){if(u===t)return aa(l),e;if(u===r)return aa(l),n;u=u.sibling}throw Error(w(188))}if(t.return!==r.return)t=l,r=u;else{for(var o=!1,i=l.child;i;){if(i===t){o=!0,t=l,r=u;break}if(i===r){o=!0,r=l,t=u;break}i=i.sibling}if(!o){for(i=u.child;i;){if(i===t){o=!0,t=u,r=l;break}if(i===r){o=!0,r=u,t=l;break}i=i.sibling}if(!o)throw Error(w(189))}}if(t.alternate!==r)throw Error(w(190))}if(t.tag!==3)throw Error(w(188));return t.stateNode.current===t?e:n}function Cs(e){return e=Cp(e),e!==null?_s(e):null}function _s(e){if(e.tag===5||e.tag===6)return e;for(e=e.child;e!==null;){var n=_s(e);if(n!==null)return n;e=e.sibling}return null}function Tp(e){if(We&&typeof We.onCommitFiberRoot==="function")try{We.onCommitFiberRoot(Hl,e,void 0,(e.current.flags&128)===128)}catch(n){}}function Mp(e){return e>>>=0,e===0?32:31-(Rp(e)/Dp|0)|0}function Ht(e){switch(e&-e){case 1:return 1;case 2:return 2;case 4:return 4;case 8:return 8;case 16:return 16;case 32:return 32;case 64:case 128:case 256:case 512:case 1024:case 2048:case 4096:case 8192:case 16384:case 32768:case 65536:case 131072:case 262144:case 524288:case 1048576:case 2097152:return e&4194240;case 4194304:case 8388608:case 16777216:case 33554432:case 67108864:return e&130023424;case 134217728:return 134217728;case 268435456:return 268435456;case 536870912:return 536870912;case 1073741824:return 1073741824;default:return e}}function kl(e,n){var t=e.pendingLanes;if(t===0)return 0;var r=0,l=e.suspendedLanes,u=e.pingedLanes,o=t&268435455;if(o!==0){var i=o&~l;i!==0?r=Ht(i):(u&=o,u!==0&&(r=Ht(u)))}else o=t&~l,o!==0?r=Ht(o):u!==0&&(r=Ht(u));if(r===0)return 0;if(n!==0&&n!==r&&(n&l)===0&&(l=r&-r,u=n&-n,l>=u||l===16&&(u&4194240)!==0))return n;if((r&4)!==0&&(r|=t&16),n=e.entangledLanes,n!==0)for(e=e.entanglements,n&=r;0<n;)t=31-Fe(n),l=1<<t,r|=e[t],n&=~l;return r}function Ip(e,n){switch(e){case 1:case 2:case 4:return n+250;case 8:case 16:case 32:case 64:case 128:case 256:case 512:case 1024:case 2048:case 4096:case 8192:case 16384:case 32768:case 65536:case 131072:case 262144:case 524288:case 1048576:case 2097152:return n+5000;case 4194304:case 8388608:case 16777216:case 33554432:case 67108864:return-1;case 134217728:case 268435456:case 536870912:case 1073741824:return-1;default:return-1}}function Lp(e,n){for(var{suspendedLanes:t,pingedLanes:r,expirationTimes:l,pendingLanes:u}=e;0<u;){var o=31-Fe(u),i=1<<o,a=l[o];if(a===-1){if((i&t)===0||(i&r)!==0)l[o]=Ip(i,n)}else a<=n&&(e.expiredLanes|=i);u&=~i}}function lo(e){return e=e.pendingLanes&-1073741825,e!==0?e:e&1073741824?1073741824:0}function Ts(){var e=Zr;return Zr<<=1,(Zr&4194240)===0&&(Zr=64),e}function Nu(e){for(var n=[],t=0;31>t;t++)n.push(e);return n}function Sr(e,n,t){e.pendingLanes|=n,n!==536870912&&(e.suspendedLanes=0,e.pingedLanes=0),e=e.eventTimes,n=31-Fe(n),e[n]=t}function Fp(e,n){var t=e.pendingLanes&~n;e.pendingLanes=n,e.suspendedLanes=0,e.pingedLanes=0,e.expiredLanes&=n,e.mutableReadLanes&=n,e.entangledLanes&=n,n=e.entanglements;var r=e.eventTimes;for(e=e.expirationTimes;0<t;){var l=31-Fe(t),u=1<<l;n[l]=0,r[l]=-1,e[l]=-1,t&=~u}}function Yo(e,n){var t=e.entangledLanes|=n;for(e=e.entanglements;t;){var r=31-Fe(t),l=1<<r;l&n|e[r]&n&&(e[r]|=n),t&=~l}}function Rs(e){return e&=-e,1<e?4<e?(e&268435455)!==0?16:536870912:4:1}function fa(e,n){switch(e){case"focusin":case"focusout":dn=null;break;case"dragenter":case"dragleave":pn=null;break;case"mouseover":case"mouseout":vn=null;break;case"pointerover":case"pointerout":ur.delete(n.pointerId);break;case"gotpointercapture":case"lostpointercapture":or.delete(n.pointerId)}}function Lt(e,n,t,r,l,u){if(e===null||e.nativeEvent!==u)return e={blockedOn:n,domEventName:t,eventSystemFlags:r,nativeEvent:u,targetContainers:[l]},n!==null&&(n=kr(n),n!==null&&Xo(n)),e;return e.eventSystemFlags|=r,n=e.targetContainers,l!==null&&n.indexOf(l)===-1&&n.push(l),e}function Up(e,n,t,r,l){switch(n){case"focusin":return dn=Lt(dn,e,n,t,r,l),!0;case"dragenter":return pn=Lt(pn,e,n,t,r,l),!0;case"mouseover":return vn=Lt(vn,e,n,t,r,l),!0;case"pointerover":var u=l.pointerId;return ur.set(u,Lt(ur.get(u)||null,e,n,t,r,l)),!0;case"gotpointercapture":return u=l.pointerId,or.set(u,Lt(or.get(u)||null,e,n,t,r,l)),!0}return!1}function Fs(e){var n=Mn(e.target);if(n!==null){var t=Wn(n);if(t!==null){if(n=t.tag,n===13){if(n=Es(t),n!==null){e.blockedOn=n,Ls(e.priority,function(){Ms(t)});return}}else if(n===3&&t.stateNode.current.memoizedState.isDehydrated){e.blockedOn=t.tag===3?t.stateNode.containerInfo:null;return}}}e.blockedOn=null}function ol(e){if(e.blockedOn!==null)return!1;for(var n=e.targetContainers;0<n.length;){var t=oo(e.domEventName,e.eventSystemFlags,n[0],e.nativeEvent);if(t===null){t=e.nativeEvent;var r=new t.constructor(t.type,t);eo=r,t.target.dispatchEvent(r),eo=null}else return n=kr(t),n!==null&&Xo(n),e.blockedOn=t,!1;n.shift()}return!0}function ca(e,n,t){ol(e)&&t.delete(n)}function Vp(){uo=!1,dn!==null&&ol(dn)&&(dn=null),pn!==null&&ol(pn)&&(pn=null),vn!==null&&ol(vn)&&(vn=null),ur.forEach(ca),or.forEach(ca)}function Ft(e,n){e.blockedOn===n&&(e.blockedOn=null,uo||(uo=!0,Q.unstable_scheduleCallback(Q.unstable_NormalPriority,Vp)))}function ir(e){function n(l){return Ft(l,e)}if(0<qr.length){Ft(qr[0],e);for(var t=1;t<qr.length;t++){var r=qr[t];r.blockedOn===e&&(r.blockedOn=null)}}dn!==null&&Ft(dn,e),pn!==null&&Ft(pn,e),vn!==null&&Ft(vn,e),ur.forEach(n),or.forEach(n);for(t=0;t<an.length;t++)r=an[t],r.blockedOn===e&&(r.blockedOn=null);for(;0<an.length&&(t=an[0],t.blockedOn===null);)Fs(t),t.blockedOn===null&&an.shift()}function Bp(e,n,t,r){var l=O,u=pt.transition;pt.transition=null;try{O=1,Go(e,n,t,r)}finally{O=l,pt.transition=u}}function $p(e,n,t,r){var l=O,u=pt.transition;pt.transition=null;try{O=4,Go(e,n,t,r)}finally{O=l,pt.transition=u}}function Go(e,n,t,r){if(El){var l=oo(e,n,t,r);if(l===null)Mu(e,n,r,Cl,t),fa(e,r);else if(Up(l,e,n,t,r))r.stopPropagation();else if(fa(e,r),n&4&&-1<Op.indexOf(e)){for(;l!==null;){var u=kr(l);if(u!==null&&Ds(u),u=oo(e,n,t,r),u===null&&Mu(e,n,r,Cl,t),u===l)break;l=u}l!==null&&r.stopPropagation()}else Mu(e,n,r,null,t)}}function oo(e,n,t,r){if(Cl=null,e=Ao(r),e=Mn(e),e!==null)if(n=Wn(e),n===null)e=null;else if(t=n.tag,t===13){if(e=Es(n),e!==null)return e;e=null}else if(t===3){if(n.stateNode.current.memoizedState.isDehydrated)return n.tag===3?n.stateNode.containerInfo:null;e=null}else n!==e&&(e=null);return Cl=e,null}function Os(e){switch(e){case"cancel":case"click":case"close":case"contextmenu":case"copy":case"cut":case"auxclick":case"dblclick":case"dragend":case"dragstart":case"drop":case"focusin":case"focusout":case"input":case"invalid":case"keydown":case"keypress":case"keyup":case"mousedown":case"mouseup":case"paste":case"pause":case"play":case"pointercancel":case"pointerdown":case"pointerup":case"ratechange":case"reset":case"resize":case"seeked":case"submit":case"touchcancel":case"touchend":case"touchstart":case"volumechange":case"change":case"selectionchange":case"textInput":case"compositionstart":case"compositionend":case"compositionupdate":case"beforeblur":case"afterblur":case"beforeinput":case"blur":case"fullscreenchange":case"focus":case"hashchange":case"popstate":case"select":case"selectstart":return 1;case"drag":case"dragenter":case"dragexit":case"dragleave":case"dragover":case"mousemove":case"mouseout":case"mouseover":case"pointermove":case"pointerout":case"pointerover":case"scroll":case"toggle":case"touchmove":case"wheel":case"mouseenter":case"mouseleave":case"pointerenter":case"pointerleave":return 4;case"message":switch(zp()){case Ko:return 1;case zs:return 4;case wl:case Pp:return 16;case Ps:return 536870912;default:return 16}default:return 16}}function Us(){if(il)return il;var e,n=Zo,t=n.length,r,l="value"in fn?fn.value:fn.textContent,u=l.length;for(e=0;e<t&&n[e]===l[e];e++);var o=t-e;for(r=1;r<=o&&n[t-r]===l[u-r];r++);return il=l.slice(e,1<r?1-r:void 0)}function al(e){var n=e.keyCode;return"charCode"in e?(e=e.charCode,e===0&&n===13&&(e=13)):e=n,e===10&&(e=13),32<=e||e===13?e:0}function xr(){return!0}function da(){return!1}function we(e){function n(t,r,l,u,o){this._reactName=t,this._targetInst=l,this.type=r,this.nativeEvent=u,this.target=o,this.currentTarget=null;for(var i in e)e.hasOwnProperty(i)&&(t=e[i],this[i]=t?t(u):u[i]);return this.isDefaultPrevented=(u.defaultPrevented!=null?u.defaultPrevented:u.returnValue===!1)?xr:da,this.isPropagationStopped=da,this}return X(n.prototype,{preventDefault:function(){this.defaultPrevented=!0;var t=this.nativeEvent;t&&(t.preventDefault?t.preventDefault():typeof t.returnValue!=="unknown"&&(t.returnValue=!1),this.isDefaultPrevented=xr)},stopPropagation:function(){var t=this.nativeEvent;t&&(t.stopPropagation?t.stopPropagation():typeof t.cancelBubble!=="unknown"&&(t.cancelBubble=!0),this.isPropagationStopped=xr)},persist:function(){},isPersistent:xr}),n}function jp(e){var n=this.nativeEvent;return n.getModifierState?n.getModifierState(e):(e=xp[e])?!!n[e]:!1}function qo(){return jp}function Bs(e,n){switch(e){case"keyup":return a0.indexOf(n.keyCode)!==-1;case"keydown":return n.keyCode!==229;case"keypress":case"mousedown":case"focusout":return!0;default:return!1}}function $s(e){return e=e.detail,typeof e==="object"&&"data"in e?e.data:null}function f0(e,n){switch(e){case"compositionend":return $s(n);case"keypress":if(n.which!==32)return null;return ma=!0,ya;case"textInput":return e=n.data,e===ya&&ma?null:e;default:return null}}function c0(e,n){if(et)return e==="compositionend"||!xo&&Bs(e,n)?(e=Us(),il=Zo=fn=null,et=!1,e):null;switch(e){case"paste":return null;case"keypress":if(!(n.ctrlKey||n.altKey||n.metaKey)||n.ctrlKey&&n.altKey){if(n.char&&1<n.char.length)return n.char;if(n.which)return String.fromCharCode(n.which)}return null;case"compositionend":return Vs&&n.locale!=="ko"?null:n.data;default:return null}}function ga(e){var n=e&&e.nodeName&&e.nodeName.toLowerCase();return n==="input"?!!d0[e.type]:n==="textarea"?!0:!1}function Qs(e,n,t,r){ms(r),n=_l(n,"onChange"),0<n.length&&(t=new Jo("onChange","change",null,t,r),e.push({event:t,listeners:n}))}function p0(e){xs(e,0)}function Al(e){var n=rt(e);if(fs(n))return e}function v0(e,n){if(e==="change")return n}function Sa(){qt&&(qt.detachEvent("onpropertychange",Ws),ar=qt=null)}function Ws(e){if(e.propertyName==="value"&&Al(ar)){var n=[];Qs(n,ar,e,Ao(e)),ks(p0,n)}}function h0(e,n,t){e==="focusin"?(Sa(),qt=n,ar=t,qt.attachEvent("onpropertychange",Ws)):e==="focusout"&&Sa()}function y0(e){if(e==="selectionchange"||e==="keyup"||e==="keydown")return Al(ar)}function m0(e,n){if(e==="click")return Al(n)}function g0(e,n){if(e==="input"||e==="change")return Al(n)}function S0(e,n){return e===n&&(e!==0||1/e===1/n)||e!==e&&n!==n}function sr(e,n){if(Ue(e,n))return!0;if(typeof e!=="object"||e===null||typeof n!=="object"||n===null)return!1;var t=Object.keys(e),r=Object.keys(n);if(t.length!==r.length)return!1;for(r=0;r<t.length;r++){var l=t[r];if(!Wu.call(n,l)||!Ue(e[l],n[l]))return!1}return!0}function wa(e){for(;e&&e.firstChild;)e=e.firstChild;return e}function ka(e,n){var t=wa(e);e=0;for(var r;t;){if(t.nodeType===3){if(r=e+t.textContent.length,e<=n&&r>=n)return{node:t,offset:n-e};e=r}e:{for(;t;){if(t.nextSibling){t=t.nextSibling;break e}t=t.parentNode}t=void 0}t=wa(t)}}function As(e,n){return e&&n?e===n?!0:e&&e.nodeType===3?!1:n&&n.nodeType===3?As(e,n.parentNode):("contains"in e)?e.contains(n):e.compareDocumentPosition?!!(e.compareDocumentPosition(n)&16):!1:!1}function Ks(){for(var e=window,n=ml();n instanceof e.HTMLIFrameElement;){try{var t=typeof n.contentWindow.location.href==="string"}catch(r){t=!1}if(t)e=n.contentWindow;else break;n=ml(e.document)}return n}function jo(e){var n=e&&e.nodeName&&e.nodeName.toLowerCase();return n&&(n==="input"&&(e.type==="text"||e.type==="search"||e.type==="tel"||e.type==="url"||e.type==="password")||n==="textarea"||e.contentEditable==="true")}function w0(e){var n=Ks(),t=e.focusedElem,r=e.selectionRange;if(n!==t&&t&&t.ownerDocument&&As(t.ownerDocument.documentElement,t)){if(r!==null&&jo(t)){if(n=r.start,e=r.end,e===void 0&&(e=n),"selectionStart"in t)t.selectionStart=n,t.selectionEnd=Math.min(e,t.value.length);else if(e=(n=t.ownerDocument||document)&&n.defaultView||window,e.getSelection){e=e.getSelection();var l=t.textContent.length,u=Math.min(r.start,l);r=r.end===void 0?u:Math.min(r.end,l),!e.extend&&u>r&&(l=r,r=u,u=l),l=ka(t,u);var o=ka(t,r);l&&o&&(e.rangeCount!==1||e.anchorNode!==l.node||e.anchorOffset!==l.offset||e.focusNode!==o.node||e.focusOffset!==o.offset)&&(n=n.createRange(),n.setStart(l.node,l.offset),e.removeAllRanges(),u>r?(e.addRange(n),e.extend(o.node,o.offset)):(n.setEnd(o.node,o.offset),e.addRange(n)))}}n=[];for(e=t;e=e.parentNode;)e.nodeType===1&&n.push({element:e,left:e.scrollLeft,top:e.scrollTop});typeof t.focus==="function"&&t.focus();for(t=0;t<n.length;t++)e=n[t],e.element.scrollLeft=e.left,e.element.scrollTop=e.top}}function Ea(e,n,t){var r=t.window===t?t.document:t.nodeType===9?t:t.ownerDocument;ao||nt==null||nt!==ml(r)||(r=nt,("selectionStart"in r)&&jo(r)?r={start:r.selectionStart,end:r.selectionEnd}:(r=(r.ownerDocument&&r.ownerDocument.defaultView||window).getSelection(),r={anchorNode:r.anchorNode,anchorOffset:r.anchorOffset,focusNode:r.focusNode,focusOffset:r.focusOffset}),xt&&sr(xt,r)||(xt=r,r=_l(io,"onSelect"),0<r.length&&(n=new Jo("onSelect","select",null,n,t),e.push({event:n,listeners:r}),n.target=nt)))}function jr(e,n){var t={};return t[e.toLowerCase()]=n.toLowerCase(),t["Webkit"+e]="webkit"+n,t["Moz"+e]="moz"+n,t}function Kl(e){if(Ru[e])return Ru[e];if(!tt[e])return e;var n=tt[e],t;for(t in n)if(n.hasOwnProperty(t)&&t in Ys)return Ru[e]=n[t];return e}function En(e,n){qs.set(e,n),Hn(n,[e])}function _a(e,n,t){var r=e.type||"unknown-event";e.currentTarget=t,Ep(r,n,void 0,e),e.currentTarget=null}function xs(e,n){n=(n&4)!==0;for(var t=0;t<e.length;t++){var r=e[t],l=r.event;r=r.listeners;e:{var u=void 0;if(n)for(var o=r.length-1;0<=o;o--){var i=r[o],a=i.instance,c=i.currentTarget;if(i=i.listener,a!==u&&l.isPropagationStopped())break e;_a(l,i,c),u=a}else for(o=0;o<r.length;o++){if(i=r[o],a=i.instance,c=i.currentTarget,i=i.listener,a!==u&&l.isPropagationStopped())break e;_a(l,i,c),u=a}}}if(Sl)throw e=ro,Sl=!1,ro=null,e}function V(e,n){var t=n[yo];t===void 0&&(t=n[yo]=new Set);var r=e+"__bubble";t.has(r)||(js(n,e,2,!1),t.add(r))}function Du(e,n,t){var r=0;n&&(r|=4),js(t,e,r,n)}function fr(e){if(!e[br]){e[br]=!0,us.forEach(function(t){t!=="selectionchange"&&(E0.has(t)||Du(t,!1,e),Du(t,!0,e))});var n=e.nodeType===9?e:e.ownerDocument;n===null||n[br]||(n[br]=!0,Du("selectionchange",!1,n))}}function js(e,n,t,r){switch(Os(n)){case 1:var l=Bp;break;case 4:l=$p;break;default:l=Go}t=l.bind(null,n,t,e),l=void 0,!to||n!=="touchstart"&&n!=="touchmove"&&n!=="wheel"||(l=!0),r?l!==void 0?e.addEventListener(n,t,{capture:!0,passive:l}):e.addEventListener(n,t,!0):l!==void 0?e.addEventListener(n,t,{passive:l}):e.addEventListener(n,t,!1)}function Mu(e,n,t,r,l){var u=r;if((n&1)===0&&(n&2)===0&&r!==null)e:for(;;){if(r===null)return;var o=r.tag;if(o===3||o===4){var i=r.stateNode.containerInfo;if(i===l||i.nodeType===8&&i.parentNode===l)break;if(o===4)for(o=r.return;o!==null;){var a=o.tag;if(a===3||a===4){if(a=o.stateNode.containerInfo,a===l||a.nodeType===8&&a.parentNode===l)return}o=o.return}for(;i!==null;){if(o=Mn(i),o===null)return;if(a=o.tag,a===5||a===6){r=u=o;continue e}i=i.parentNode}}r=r.return}ks(function(){var c=u,y=Ao(t),g=[];e:{var m=qs.get(e);if(m!==void 0){var k=Jo,C=e;switch(e){case"keypress":if(al(t)===0)break e;case"keydown":case"keyup":k=e0;break;case"focusin":C="focus",k=Tu;break;case"focusout":C="blur",k=Tu;break;case"beforeblur":case"afterblur":k=Tu;break;case"click":if(t.button===2)break e;case"auxclick":case"dblclick":case"mousedown":case"mousemove":case"mouseup":case"mouseout":case"mouseover":case"contextmenu":k=pa;break;case"drag":case"dragend":case"dragenter":case"dragexit":case"dragleave":case"dragover":case"dragstart":case"drop":k=Wp;break;case"touchcancel":case"touchend":case"touchmove":case"touchstart":k=r0;break;case Xs:case Gs:case Zs:k=Yp;break;case Js:k=u0;break;case"scroll":k=Qp;break;case"wheel":k=i0;break;case"copy":case"cut":case"paste":k=Gp;break;case"gotpointercapture":case"lostpointercapture":case"pointercancel":case"pointerdown":case"pointermove":case"pointerout":case"pointerover":case"pointerup":k=ha}var E=(n&4)!==0,W=!E&&e==="scroll",d=E?m!==null?m+"Capture":null:m;E=[];for(var f=c,p;f!==null;){p=f;var S=p.stateNode;if(p.tag===5&&S!==null&&(p=S,d!==null&&(S=lr(f,d),S!=null&&E.push(cr(f,S,p)))),W)break;f=f.return}0<E.length&&(m=new k(m,C,null,t,y),g.push({event:m,listeners:E}))}}if((n&7)===0){e:{if(m=e==="mouseover"||e==="pointerover",k=e==="mouseout"||e==="pointerout",m&&t!==eo&&(C=t.relatedTarget||t.fromElement)&&(Mn(C)||C[je]))break e;if(k||m){if(m=y.window===y?y:(m=y.ownerDocument)?m.defaultView||m.parentWindow:window,k){if(C=t.relatedTarget||t.toElement,k=c,C=C?Mn(C):null,C!==null&&(W=Wn(C),C!==W||C.tag!==5&&C.tag!==6))C=null}else k=null,C=c;if(k!==C){if(E=pa,S="onMouseLeave",d="onMouseEnter",f="mouse",e==="pointerout"||e==="pointerover")E=ha,S="onPointerLeave",d="onPointerEnter",f="pointer";if(W=k==null?m:rt(k),p=C==null?m:rt(C),m=new E(S,f+"leave",k,t,y),m.target=W,m.relatedTarget=p,S=null,Mn(y)===c&&(E=new E(d,f+"enter",C,t,y),E.target=p,E.relatedTarget=W,S=E),W=S,k&&C)n:{E=k,d=C,f=0;for(p=E;p;p=qn(p))f++;p=0;for(S=d;S;S=qn(S))p++;for(;0<f-p;)E=qn(E),f--;for(;0<p-f;)d=qn(d),p--;for(;f--;){if(E===d||d!==null&&E===d.alternate)break n;E=qn(E),d=qn(d)}E=null}else E=null;k!==null&&Na(g,m,k,E,!1),C!==null&&W!==null&&Na(g,W,C,E,!0)}}}e:{if(m=c?rt(c):window,k=m.nodeName&&m.nodeName.toLowerCase(),k==="select"||k==="input"&&m.type==="file")var z=v0;else if(ga(m))if(Hs)z=g0;else{z=y0;var P=h0}else(k=m.nodeName)&&k.toLowerCase()==="input"&&(m.type==="checkbox"||m.type==="radio")&&(z=m0);if(z&&(z=z(e,c))){Qs(g,z,t,y);break e}P&&P(e,m,c),e==="focusout"&&(P=m._wrapperState)&&P.controlled&&m.type==="number"&&Ju(m,"number",m.value)}switch(P=c?rt(c):window,e){case"focusin":if(ga(P)||P.contentEditable==="true")nt=P,io=c,xt=null;break;case"focusout":xt=io=nt=null;break;case"mousedown":ao=!0;break;case"contextmenu":case"mouseup":case"dragend":ao=!1,Ea(g,t,y);break;case"selectionchange":if(k0)break;case"keydown":case"keyup":Ea(g,t,y)}var _;if(xo)e:{switch(e){case"compositionstart":var T="onCompositionStart";break e;case"compositionend":T="onCompositionEnd";break e;case"compositionupdate":T="onCompositionUpdate";break e}T=void 0}else et?Bs(e,t)&&(T="onCompositionEnd"):e==="keydown"&&t.keyCode===229&&(T="onCompositionStart");if(T&&(Vs&&t.locale!=="ko"&&(et||T!=="onCompositionStart"?T==="onCompositionEnd"&&et&&(_=Us()):(fn=y,Zo=("value"in fn)?fn.value:fn.textContent,et=!0)),P=_l(c,T),0<P.length&&(T=new va(T,e,null,t,y),g.push({event:T,listeners:P}),_?T.data=_:(_=$s(t),_!==null&&(T.data=_)))),_=s0?f0(e,t):c0(e,t))c=_l(c,"onBeforeInput"),0<c.length&&(y=new va("onBeforeInput","beforeinput",null,t,y),g.push({event:y,listeners:c}),y.data=_)}xs(g,n)})}function cr(e,n,t){return{instance:e,listener:n,currentTarget:t}}function _l(e,n){for(var t=n+"Capture",r=[];e!==null;){var l=e,u=l.stateNode;l.tag===5&&u!==null&&(l=u,u=lr(e,t),u!=null&&r.unshift(cr(e,u,l)),u=lr(e,n),u!=null&&r.push(cr(e,u,l))),e=e.return}return r}function qn(e){if(e===null)return null;do e=e.return;while(e&&e.tag!==5);return e?e:null}function Na(e,n,t,r,l){for(var u=n._reactName,o=[];t!==null&&t!==r;){var i=t,a=i.alternate,c=i.stateNode;if(a!==null&&a===r)break;i.tag===5&&c!==null&&(i=c,l?(a=lr(t,u),a!=null&&o.unshift(cr(t,a,i))):l||(a=lr(t,u),a!=null&&o.push(cr(t,a,i)))),t=t.return}o.length!==0&&e.push({event:n,listeners:o})}function za(e){return(typeof e==="string"?e:""+e).replace(C0,`
`).replace(_0,"")}function el(e,n,t){if(n=za(n),za(e)!==n&&t)throw Error(w(425))}function Nl(){}function vo(e,n){return e==="textarea"||e==="noscript"||typeof n.children==="string"||typeof n.children==="number"||typeof n.dangerouslySetInnerHTML==="object"&&n.dangerouslySetInnerHTML!==null&&n.dangerouslySetInnerHTML.__html!=null}function P0(e){setTimeout(function(){throw e})}function Iu(e,n){var t=n,r=0;do{var l=t.nextSibling;if(e.removeChild(t),l&&l.nodeType===8)if(t=l.data,t==="/$"){if(r===0){e.removeChild(l),ir(n);return}r--}else t!=="$"&&t!=="$?"&&t!=="$!"||r++;t=l}while(t);ir(n)}function hn(e){for(;e!=null;e=e.nextSibling){var n=e.nodeType;if(n===1||n===3)break;if(n===8){if(n=e.data,n==="$"||n==="$!"||n==="$?")break;if(n==="/$")return null}}return e}function Ta(e){e=e.previousSibling;for(var n=0;e;){if(e.nodeType===8){var t=e.data;if(t==="$"||t==="$!"||t==="$?"){if(n===0)return e;n--}else t==="/$"&&n++}e=e.previousSibling}return null}function Mn(e){var n=e[He];if(n)return n;for(var t=e.parentNode;t;){if(n=t[je]||t[He]){if(t=n.alternate,n.child!==null||t!==null&&t.child!==null)for(e=Ta(e);e!==null;){if(t=e[He])return t;e=Ta(e)}return n}e=t,t=e.parentNode}return null}function kr(e){return e=e[He]||e[je],!e||e.tag!==5&&e.tag!==6&&e.tag!==13&&e.tag!==3?null:e}function rt(e){if(e.tag===5||e.tag===6)return e.stateNode;throw Error(w(33))}function Yl(e){return e[dr]||null}function Cn(e){return{current:e}}function B(e){0>lt||(e.current=mo[lt],mo[lt]=null,lt--)}function U(e,n){lt++,mo[lt]=e.current,e.current=n}function mt(e,n){var t=e.type.contextTypes;if(!t)return kn;var r=e.stateNode;if(r&&r.__reactInternalMemoizedUnmaskedChildContext===n)return r.__reactInternalMemoizedMaskedChildContext;var l={},u;for(u in t)l[u]=n[u];return r&&(e=e.stateNode,e.__reactInternalMemoizedUnmaskedChildContext=n,e.__reactInternalMemoizedMaskedChildContext=l),l}function he(e){return e=e.childContextTypes,e!==null&&e!==void 0}function zl(){B(ve),B(ie)}function Ra(e,n,t){if(ie.current!==kn)throw Error(w(168));U(ie,n),U(ve,t)}function bs(e,n,t){var r=e.stateNode;if(n=n.childContextTypes,typeof r.getChildContext!=="function")return t;r=r.getChildContext();for(var l in r)if(!(l in n))throw Error(w(108,hp(e)||"Unknown",l));return X({},t,r)}function Pl(e){return e=(e=e.stateNode)&&e.__reactInternalMemoizedMergedChildContext||kn,Un=ie.current,U(ie,e),U(ve,ve.current),!0}function Da(e,n,t){var r=e.stateNode;if(!r)throw Error(w(169));t?(e=bs(e,n,Un),r.__reactInternalMemoizedMergedChildContext=e,B(ve),B(ie),U(ie,e)):B(ve),U(ve,t)}function ef(e){Ge===null?Ge=[e]:Ge.push(e)}function D0(e){Xl=!0,ef(e)}function _n(){if(!Lu&&Ge!==null){Lu=!0;var e=0,n=O;try{var t=Ge;for(O=1;e<t.length;e++){var r=t[e];do r=r(!0);while(r!==null)}Ge=null,Xl=!1}catch(l){throw Ge!==null&&(Ge=Ge.slice(e+1)),Ns(Ko,_n),l}finally{O=n,Lu=!1}}return null}function Rn(e,n){ut[ot++]=Rl,ut[ot++]=Tl,Tl=e,Rl=n}function nf(e,n,t){Ee[Ce++]=Ze,Ee[Ce++]=Je,Ee[Ce++]=Vn,Vn=e;var r=Ze;e=Je;var l=32-Fe(r)-1;r&=~(1<<l),t+=1;var u=32-Fe(n)+l;if(30<u){var o=l-l%5;u=(r&(1<<o)-1).toString(32),r>>=o,l-=o,Ze=1<<32-Fe(n)+l|t<<l|r,Je=u+e}else Ze=1<<u|t<<l|r,Je=e}function bo(e){e.return!==null&&(Rn(e,1),nf(e,1,0))}function ei(e){for(;e===Tl;)Tl=ut[--ot],ut[ot]=null,Rl=ut[--ot],ut[ot]=null;for(;e===Vn;)Vn=Ee[--Ce],Ee[Ce]=null,Je=Ee[--Ce],Ee[Ce]=null,Ze=Ee[--Ce],Ee[Ce]=null}function tf(e,n){var t=_e(5,null,null,0);t.elementType="DELETED",t.stateNode=n,t.return=e,n=e.deletions,n===null?(e.deletions=[t],e.flags|=16):n.push(t)}function Ma(e,n){switch(e.tag){case 5:var t=e.type;return n=n.nodeType!==1||t.toLowerCase()!==n.nodeName.toLowerCase()?null:n,n!==null?(e.stateNode=n,Se=e,ge=hn(n.firstChild),!0):!1;case 6:return n=e.pendingProps===""||n.nodeType!==3?null:n,n!==null?(e.stateNode=n,Se=e,ge=null,!0):!1;case 13:return n=n.nodeType!==8?null:n,n!==null?(t=Vn!==null?{id:Ze,overflow:Je}:null,e.memoizedState={dehydrated:n,treeContext:t,retryLane:1073741824},t=_e(18,null,null,0),t.stateNode=n,t.return=e,e.child=t,Se=e,ge=null,!0):!1;default:return!1}}function go(e){return(e.mode&1)!==0&&(e.flags&128)===0}function So(e){if($){var n=ge;if(n){var t=n;if(!Ma(e,n)){if(go(e))throw Error(w(418));n=hn(t.nextSibling);var r=Se;n&&Ma(e,n)?tf(r,t):(e.flags=e.flags&-4097|2,$=!1,Se=e)}}else{if(go(e))throw Error(w(418));e.flags=e.flags&-4097|2,$=!1,Se=e}}}function Ia(e){for(e=e.return;e!==null&&e.tag!==5&&e.tag!==3&&e.tag!==13;)e=e.return;Se=e}function nl(e){if(e!==Se)return!1;if(!$)return Ia(e),$=!0,!1;var n;if((n=e.tag!==3)&&!(n=e.tag!==5)&&(n=e.type,n=n!=="head"&&n!=="body"&&!vo(e.type,e.memoizedProps)),n&&(n=ge)){if(go(e))throw rf(),Error(w(418));for(;n;)tf(e,n),n=hn(n.nextSibling)}if(Ia(e),e.tag===13){if(e=e.memoizedState,e=e!==null?e.dehydrated:null,!e)throw Error(w(317));e:{e=e.nextSibling;for(n=0;e;){if(e.nodeType===8){var t=e.data;if(t==="/$"){if(n===0){ge=hn(e.nextSibling);break e}n--}else t!=="$"&&t!=="$!"&&t!=="$?"||n++}e=e.nextSibling}ge=null}}else ge=Se?hn(e.stateNode.nextSibling):null;return!0}function rf(){for(var e=ge;e;)e=hn(e.nextSibling)}function gt(){ge=Se=null,$=!1}function ni(e){Le===null?Le=[e]:Le.push(e)}function Ut(e,n,t){if(e=t.ref,e!==null&&typeof e!=="function"&&typeof e!=="object"){if(t._owner){if(t=t._owner,t){if(t.tag!==1)throw Error(w(309));var r=t.stateNode}if(!r)throw Error(w(147,e));var l=r,u=""+e;if(n!==null&&n.ref!==null&&typeof n.ref==="function"&&n.ref._stringRef===u)return n.ref;return n=function(o){var i=l.refs;o===null?delete i[u]:i[u]=o},n._stringRef=u,n}if(typeof e!=="string")throw Error(w(284));if(!t._owner)throw Error(w(290,e))}return e}function tl(e,n){throw e=Object.prototype.toString.call(n),Error(w(31,e==="[object Object]"?"object with keys {"+Object.keys(n).join(", ")+"}":e))}function La(e){var n=e._init;return n(e._payload)}function lf(e){function n(d,f){if(e){var p=d.deletions;p===null?(d.deletions=[f],d.flags|=16):p.push(f)}}function t(d,f){if(!e)return null;for(;f!==null;)n(d,f),f=f.sibling;return null}function r(d,f){for(d=new Map;f!==null;)f.key!==null?d.set(f.key,f):d.set(f.index,f),f=f.sibling;return d}function l(d,f){return d=Sn(d,f),d.index=0,d.sibling=null,d}function u(d,f,p){if(d.index=p,!e)return d.flags|=1048576,f;if(p=d.alternate,p!==null)return p=p.index,p<f?(d.flags|=2,f):p;return d.flags|=2,f}function o(d){return e&&d.alternate===null&&(d.flags|=2),d}function i(d,f,p,S){if(f===null||f.tag!==6)return f=Qu(p,d.mode,S),f.return=d,f;return f=l(f,p),f.return=d,f}function a(d,f,p,S){var z=p.type;if(z===bn)return y(d,f,p.props.children,S,p.key);if(f!==null&&(f.elementType===z||typeof z==="object"&&z!==null&&z.$$typeof===un&&La(z)===f.type))return S=l(f,p.props),S.ref=Ut(d,f,p),S.return=d,S;return S=yl(p.type,p.key,p.props,null,d.mode,S),S.ref=Ut(d,f,p),S.return=d,S}function c(d,f,p,S){if(f===null||f.tag!==4||f.stateNode.containerInfo!==p.containerInfo||f.stateNode.implementation!==p.implementation)return f=Hu(p,d.mode,S),f.return=d,f;return f=l(f,p.children||[]),f.return=d,f}function y(d,f,p,S,z){if(f===null||f.tag!==7)return f=On(p,d.mode,S,z),f.return=d,f;return f=l(f,p),f.return=d,f}function g(d,f,p){if(typeof f==="string"&&f!==""||typeof f==="number")return f=Qu(""+f,d.mode,p),f.return=d,f;if(typeof f==="object"&&f!==null){switch(f.$$typeof){case Yr:return p=yl(f.type,f.key,f.props,null,d.mode,p),p.ref=Ut(d,null,f),p.return=d,p;case jn:return f=Hu(f,d.mode,p),f.return=d,f;case un:var S=f._init;return g(d,S(f._payload),p)}if(Qt(f)||It(f))return f=On(f,d.mode,p,null),f.return=d,f;tl(d,f)}return null}function m(d,f,p,S){var z=f!==null?f.key:null;if(typeof p==="string"&&p!==""||typeof p==="number")return z!==null?null:i(d,f,""+p,S);if(typeof p==="object"&&p!==null){switch(p.$$typeof){case Yr:return p.key===z?a(d,f,p,S):null;case jn:return p.key===z?c(d,f,p,S):null;case un:return z=p._init,m(d,f,z(p._payload),S)}if(Qt(p)||It(p))return z!==null?null:y(d,f,p,S,null);tl(d,p)}return null}function k(d,f,p,S,z){if(typeof S==="string"&&S!==""||typeof S==="number")return d=d.get(p)||null,i(f,d,""+S,z);if(typeof S==="object"&&S!==null){switch(S.$$typeof){case Yr:return d=d.get(S.key===null?p:S.key)||null,a(f,d,S,z);case jn:return d=d.get(S.key===null?p:S.key)||null,c(f,d,S,z);case un:var P=S._init;return k(d,f,p,P(S._payload),z)}if(Qt(S)||It(S))return d=d.get(p)||null,y(f,d,S,z,null);tl(f,S)}return null}function C(d,f,p,S){for(var z=null,P=null,_=f,T=f=0,A=null;_!==null&&T<p.length;T++){_.index>T?(A=_,_=null):A=_.sibling;var I=m(d,_,p[T],S);if(I===null){_===null&&(_=A);break}e&&_&&I.alternate===null&&n(d,_),f=u(I,f,T),P===null?z=I:P.sibling=I,P=I,_=A}if(T===p.length)return t(d,_),$&&Rn(d,T),z;if(_===null){for(;T<p.length;T++)_=g(d,p[T],S),_!==null&&(f=u(_,f,T),P===null?z=_:P.sibling=_,P=_);return $&&Rn(d,T),z}for(_=r(d,_);T<p.length;T++)A=k(_,d,T,p[T],S),A!==null&&(e&&A.alternate!==null&&_.delete(A.key===null?T:A.key),f=u(A,f,T),P===null?z=A:P.sibling=A,P=A);return e&&_.forEach(function(Ve){return n(d,Ve)}),$&&Rn(d,T),z}function E(d,f,p,S){var z=It(p);if(typeof z!=="function")throw Error(w(150));if(p=z.call(p),p==null)throw Error(w(151));for(var P=z=null,_=f,T=f=0,A=null,I=p.next();_!==null&&!I.done;T++,I=p.next()){_.index>T?(A=_,_=null):A=_.sibling;var Ve=m(d,_,I.value,S);if(Ve===null){_===null&&(_=A);break}e&&_&&Ve.alternate===null&&n(d,_),f=u(Ve,f,T),P===null?z=Ve:P.sibling=Ve,P=Ve,_=A}if(I.done)return t(d,_),$&&Rn(d,T),z;if(_===null){for(;!I.done;T++,I=p.next())I=g(d,I.value,S),I!==null&&(f=u(I,f,T),P===null?z=I:P.sibling=I,P=I);return $&&Rn(d,T),z}for(_=r(d,_);!I.done;T++,I=p.next())I=k(_,d,T,I.value,S),I!==null&&(e&&I.alternate!==null&&_.delete(I.key===null?T:I.key),f=u(I,f,T),P===null?z=I:P.sibling=I,P=I);return e&&_.forEach(function(Kn){return n(d,Kn)}),$&&Rn(d,T),z}function W(d,f,p,S){if(typeof p==="object"&&p!==null&&p.type===bn&&p.key===null&&(p=p.props.children),typeof p==="object"&&p!==null){switch(p.$$typeof){case Yr:e:{for(var z=p.key,P=f;P!==null;){if(P.key===z){if(z=p.type,z===bn){if(P.tag===7){t(d,P.sibling),f=l(P,p.props.children),f.return=d,d=f;break e}}else if(P.elementType===z||typeof z==="object"&&z!==null&&z.$$typeof===un&&La(z)===P.type){t(d,P.sibling),f=l(P,p.props),f.ref=Ut(d,P,p),f.return=d,d=f;break e}t(d,P);break}else n(d,P);P=P.sibling}p.type===bn?(f=On(p.props.children,d.mode,S,p.key),f.return=d,d=f):(S=yl(p.type,p.key,p.props,null,d.mode,S),S.ref=Ut(d,f,p),S.return=d,d=S)}return o(d);case jn:e:{for(P=p.key;f!==null;){if(f.key===P)if(f.tag===4&&f.stateNode.containerInfo===p.containerInfo&&f.stateNode.implementation===p.implementation){t(d,f.sibling),f=l(f,p.children||[]),f.return=d,d=f;break e}else{t(d,f);break}else n(d,f);f=f.sibling}f=Hu(p,d.mode,S),f.return=d,d=f}return o(d);case un:return P=p._init,W(d,f,P(p._payload),S)}if(Qt(p))return C(d,f,p,S);if(It(p))return E(d,f,p,S);tl(d,p)}return typeof p==="string"&&p!==""||typeof p==="number"?(p=""+p,f!==null&&f.tag===6?(t(d,f.sibling),f=l(f,p),f.return=d,d=f):(t(d,f),f=Qu(p,d.mode,S),f.return=d,d=f),o(d)):t(d,f)}return W}function ri(){ti=it=Ml=null}function li(e){var n=Dl.current;B(Dl),e._currentValue=n}function wo(e,n,t){for(;e!==null;){var r=e.alternate;if((e.childLanes&n)!==n?(e.childLanes|=n,r!==null&&(r.childLanes|=n)):r!==null&&(r.childLanes&n)!==n&&(r.childLanes|=n),e===t)break;e=e.return}}function vt(e,n){Ml=e,ti=it=null,e=e.dependencies,e!==null&&e.firstContext!==null&&((e.lanes&n)!==0&&(pe=!0),e.firstContext=null)}function ze(e){var n=e._currentValue;if(ti!==e)if(e={context:e,memoizedValue:n,next:null},it===null){if(Ml===null)throw Error(w(308));it=e,Ml.dependencies={lanes:0,firstContext:e}}else it=it.next=e;return n}function ui(e){In===null?In=[e]:In.push(e)}function of(e,n,t,r){var l=n.interleaved;return l===null?(t.next=t,ui(n)):(t.next=l.next,l.next=t),n.interleaved=t,be(e,r)}function be(e,n){e.lanes|=n;var t=e.alternate;t!==null&&(t.lanes|=n),t=e;for(e=e.return;e!==null;)e.childLanes|=n,t=e.alternate,t!==null&&(t.childLanes|=n),t=e,e=e.return;return t.tag===3?t.stateNode:null}function oi(e){e.updateQueue={baseState:e.memoizedState,firstBaseUpdate:null,lastBaseUpdate:null,shared:{pending:null,interleaved:null,lanes:0},effects:null}}function af(e,n){e=e.updateQueue,n.updateQueue===e&&(n.updateQueue={baseState:e.baseState,firstBaseUpdate:e.firstBaseUpdate,lastBaseUpdate:e.lastBaseUpdate,shared:e.shared,effects:e.effects})}function qe(e,n){return{eventTime:e,lane:n,tag:0,payload:null,callback:null,next:null}}function yn(e,n,t){var r=e.updateQueue;if(r===null)return null;if(r=r.shared,(L&2)!==0){var l=r.pending;return l===null?n.next=n:(n.next=l.next,l.next=n),r.pending=n,be(e,t)}return l=r.interleaved,l===null?(n.next=n,ui(r)):(n.next=l.next,l.next=n),r.interleaved=n,be(e,t)}function fl(e,n,t){if(n=n.updateQueue,n!==null&&(n=n.shared,(t&4194240)!==0)){var r=n.lanes;r&=e.pendingLanes,t|=r,n.lanes=t,Yo(e,t)}}function Fa(e,n){var{updateQueue:t,alternate:r}=e;if(r!==null&&(r=r.updateQueue,t===r)){var l=null,u=null;if(t=t.firstBaseUpdate,t!==null){do{var o={eventTime:t.eventTime,lane:t.lane,tag:t.tag,payload:t.payload,callback:t.callback,next:null};u===null?l=u=o:u=u.next=o,t=t.next}while(t!==null);u===null?l=u=n:u=u.next=n}else l=u=n;t={baseState:r.baseState,firstBaseUpdate:l,lastBaseUpdate:u,shared:r.shared,effects:r.effects},e.updateQueue=t;return}e=t.lastBaseUpdate,e===null?t.firstBaseUpdate=n:e.next=n,t.lastBaseUpdate=n}function Il(e,n,t,r){var l=e.updateQueue;on=!1;var{firstBaseUpdate:u,lastBaseUpdate:o}=l,i=l.shared.pending;if(i!==null){l.shared.pending=null;var a=i,c=a.next;a.next=null,o===null?u=c:o.next=c,o=a;var y=e.alternate;y!==null&&(y=y.updateQueue,i=y.lastBaseUpdate,i!==o&&(i===null?y.firstBaseUpdate=c:i.next=c,y.lastBaseUpdate=a))}if(u!==null){var g=l.baseState;o=0,y=c=a=null,i=u;do{var{lane:m,eventTime:k}=i;if((r&m)===m){y!==null&&(y=y.next={eventTime:k,lane:0,tag:i.tag,payload:i.payload,callback:i.callback,next:null});e:{var C=e,E=i;switch(m=n,k=t,E.tag){case 1:if(C=E.payload,typeof C==="function"){g=C.call(k,g,m);break e}g=C;break e;case 3:C.flags=C.flags&-65537|128;case 0:if(C=E.payload,m=typeof C==="function"?C.call(k,g,m):C,m===null||m===void 0)break e;g=X({},g,m);break e;case 2:on=!0}}i.callback!==null&&i.lane!==0&&(e.flags|=64,m=l.effects,m===null?l.effects=[i]:m.push(i))}else k={eventTime:k,lane:m,tag:i.tag,payload:i.payload,callback:i.callback,next:null},y===null?(c=y=k,a=g):y=y.next=k,o|=m;if(i=i.next,i===null)if(i=l.shared.pending,i===null)break;else m=i,i=m.next,m.next=null,l.lastBaseUpdate=m,l.shared.pending=null}while(1);if(y===null&&(a=g),l.baseState=a,l.firstBaseUpdate=c,l.lastBaseUpdate=y,n=l.shared.interleaved,n!==null){l=n;do o|=l.lane,l=l.next;while(l!==n)}else u===null&&(l.shared.lanes=0);$n|=o,e.lanes=o,e.memoizedState=g}}function Oa(e,n,t){if(e=n.effects,n.effects=null,e!==null)for(n=0;n<e.length;n++){var r=e[n],l=r.callback;if(l!==null){if(r.callback=null,r=t,typeof l!=="function")throw Error(w(191,l));l.call(r)}}}function Ln(e){if(e===Er)throw Error(w(174));return e}function ii(e,n){switch(U(vr,n),U(pr,e),U(Ae,Er),e=n.nodeType,e){case 9:case 11:n=(n=n.documentElement)?n.namespaceURI:xu(null,"");break;default:e=e===8?n.parentNode:n,n=e.namespaceURI||null,e=e.tagName,n=xu(n,e)}B(Ae),U(Ae,n)}function wt(){B(Ae),B(pr),B(vr)}function sf(e){Ln(vr.current);var n=Ln(Ae.current),t=xu(n,e.type);n!==t&&(U(pr,e),U(Ae,t))}function ai(e){pr.current===e&&(B(Ae),B(pr))}function Ll(e){for(var n=e;n!==null;){if(n.tag===13){var t=n.memoizedState;if(t!==null&&(t=t.dehydrated,t===null||t.data==="$?"||t.data==="$!"))return n}else if(n.tag===19&&n.memoizedProps.revealOrder!==void 0){if((n.flags&128)!==0)return n}else if(n.child!==null){n.child.return=n,n=n.child;continue}if(n===e)break;for(;n.sibling===null;){if(n.return===null||n.return===e)return null;n=n.return}n.sibling.return=n.return,n=n.sibling}return null}function si(){for(var e=0;e<Fu.length;e++)Fu[e]._workInProgressVersionPrimary=null;Fu.length=0}function le(){throw Error(w(321))}function fi(e,n){if(n===null)return!1;for(var t=0;t<n.length&&t<e.length;t++)if(!Ue(e[t],n[t]))return!1;return!0}function ci(e,n,t,r,l,u){if(Bn=u,Y=n,n.memoizedState=null,n.updateQueue=null,n.lanes=0,cl.current=e===null||e.memoizedState===null?U0:V0,e=t(r,l),jt){u=0;do{if(jt=!1,hr=0,25<=u)throw Error(w(301));u+=1,j=q=null,n.updateQueue=null,cl.current=B0,e=t(r,l)}while(jt)}if(cl.current=Ol,n=q!==null&&q.next!==null,Bn=0,j=q=Y=null,Fl=!1,n)throw Error(w(300));return e}function di(){var e=hr!==0;return hr=0,e}function Qe(){var e={memoizedState:null,baseState:null,baseQueue:null,queue:null,next:null};return j===null?Y.memoizedState=j=e:j=j.next=e,j}function Pe(){if(q===null){var e=Y.alternate;e=e!==null?e.memoizedState:null}else e=q.next;var n=j===null?Y.memoizedState:j.next;if(n!==null)j=n,q=e;else{if(e===null)throw Error(w(310));q=e,e={memoizedState:q.memoizedState,baseState:q.baseState,baseQueue:q.baseQueue,queue:q.queue,next:null},j===null?Y.memoizedState=j=e:j=j.next=e}return j}function yr(e,n){return typeof n==="function"?n(e):n}function Uu(e){var n=Pe(),t=n.queue;if(t===null)throw Error(w(311));t.lastRenderedReducer=e;var r=q,l=r.baseQueue,u=t.pending;if(u!==null){if(l!==null){var o=l.next;l.next=u.next,u.next=o}r.baseQueue=l=u,t.pending=null}if(l!==null){u=l.next,r=r.baseState;var i=o=null,a=null,c=u;do{var y=c.lane;if((Bn&y)===y)a!==null&&(a=a.next={lane:0,action:c.action,hasEagerState:c.hasEagerState,eagerState:c.eagerState,next:null}),r=c.hasEagerState?c.eagerState:e(r,c.action);else{var g={lane:y,action:c.action,hasEagerState:c.hasEagerState,eagerState:c.eagerState,next:null};a===null?(i=a=g,o=r):a=a.next=g,Y.lanes|=y,$n|=y}c=c.next}while(c!==null&&c!==u);a===null?o=r:a.next=i,Ue(r,n.memoizedState)||(pe=!0),n.memoizedState=r,n.baseState=o,n.baseQueue=a,t.lastRenderedState=r}if(e=t.interleaved,e!==null){l=e;do u=l.lane,Y.lanes|=u,$n|=u,l=l.next;while(l!==e)}else l===null&&(t.lanes=0);return[n.memoizedState,t.dispatch]}function Vu(e){var n=Pe(),t=n.queue;if(t===null)throw Error(w(311));t.lastRenderedReducer=e;var{dispatch:r,pending:l}=t,u=n.memoizedState;if(l!==null){t.pending=null;var o=l=l.next;do u=e(u,o.action),o=o.next;while(o!==l);Ue(u,n.memoizedState)||(pe=!0),n.memoizedState=u,n.baseQueue===null&&(n.baseState=u),t.lastRenderedState=u}return[u,r]}function ff(){}function cf(e,n){var t=Y,r=Pe(),l=n(),u=!Ue(r.memoizedState,l);if(u&&(r.memoizedState=l,pe=!0),r=r.queue,pi(vf.bind(null,t,r,e),[e]),r.getSnapshot!==n||u||j!==null&&j.memoizedState.tag&1){if(t.flags|=2048,mr(9,pf.bind(null,t,r,l,n),void 0,null),b===null)throw Error(w(349));(Bn&30)!==0||df(t,n,l)}return l}function df(e,n,t){e.flags|=16384,e={getSnapshot:n,value:t},n=Y.updateQueue,n===null?(n={lastEffect:null,stores:null},Y.updateQueue=n,n.stores=[e]):(t=n.stores,t===null?n.stores=[e]:t.push(e))}function pf(e,n,t,r){n.value=t,n.getSnapshot=r,hf(n)&&yf(e)}function vf(e,n,t){return t(function(){hf(n)&&yf(e)})}function hf(e){var n=e.getSnapshot;e=e.value;try{var t=n();return!Ue(e,t)}catch(r){return!0}}function yf(e){var n=be(e,1);n!==null&&Oe(n,e,1,-1)}function Ua(e){var n=Qe();return typeof e==="function"&&(e=e()),n.memoizedState=n.baseState=e,e={pending:null,interleaved:null,lanes:0,dispatch:null,lastRenderedReducer:yr,lastRenderedState:e},n.queue=e,e=e.dispatch=O0.bind(null,Y,e),[n.memoizedState,e]}function mr(e,n,t,r){return e={tag:e,create:n,destroy:t,deps:r,next:null},n=Y.updateQueue,n===null?(n={lastEffect:null,stores:null},Y.updateQueue=n,n.lastEffect=e.next=e):(t=n.lastEffect,t===null?n.lastEffect=e.next=e:(r=t.next,t.next=e,e.next=r,n.lastEffect=e)),e}function mf(){return Pe().memoizedState}function dl(e,n,t,r){var l=Qe();Y.flags|=e,l.memoizedState=mr(1|n,t,void 0,r===void 0?null:r)}function Gl(e,n,t,r){var l=Pe();r=r===void 0?null:r;var u=void 0;if(q!==null){var o=q.memoizedState;if(u=o.destroy,r!==null&&fi(r,o.deps)){l.memoizedState=mr(n,t,u,r);return}}Y.flags|=e,l.memoizedState=mr(1|n,t,u,r)}function Va(e,n){return dl(8390656,8,e,n)}function pi(e,n){return Gl(2048,8,e,n)}function gf(e,n){return Gl(4,2,e,n)}function Sf(e,n){return Gl(4,4,e,n)}function wf(e,n){if(typeof n==="function")return e=e(),n(e),function(){n(null)};if(n!==null&&n!==void 0)return e=e(),n.current=e,function(){n.current=null}}function kf(e,n,t){return t=t!==null&&t!==void 0?t.concat([e]):null,Gl(4,4,wf.bind(null,n,e),t)}function vi(){}function Ef(e,n){var t=Pe();n=n===void 0?null:n;var r=t.memoizedState;if(r!==null&&n!==null&&fi(n,r[1]))return r[0];return t.memoizedState=[e,n],e}function Cf(e,n){var t=Pe();n=n===void 0?null:n;var r=t.memoizedState;if(r!==null&&n!==null&&fi(n,r[1]))return r[0];return e=e(),t.memoizedState=[e,n],e}function _f(e,n,t){if((Bn&21)===0)return e.baseState&&(e.baseState=!1,pe=!0),e.memoizedState=t;return Ue(t,n)||(t=Ts(),Y.lanes|=t,$n|=t,e.baseState=!0),n}function L0(e,n){var t=O;O=t!==0&&4>t?t:4,e(!0);var r=Ou.transition;Ou.transition={};try{e(!1),n()}finally{O=t,Ou.transition=r}}function Nf(){return Pe().memoizedState}function F0(e,n,t){var r=gn(e);if(t={lane:r,action:t,hasEagerState:!1,eagerState:null,next:null},zf(e))Pf(n,t);else if(t=of(e,n,t,r),t!==null){var l=fe();Oe(t,e,r,l),Tf(t,n,r)}}function O0(e,n,t){var r=gn(e),l={lane:r,action:t,hasEagerState:!1,eagerState:null,next:null};if(zf(e))Pf(n,l);else{var u=e.alternate;if(e.lanes===0&&(u===null||u.lanes===0)&&(u=n.lastRenderedReducer,u!==null))try{var o=n.lastRenderedState,i=u(o,t);if(l.hasEagerState=!0,l.eagerState=i,Ue(i,o)){var a=n.interleaved;a===null?(l.next=l,ui(n)):(l.next=a.next,a.next=l),n.interleaved=l;return}}catch(c){}finally{}t=of(e,n,l,r),t!==null&&(l=fe(),Oe(t,e,r,l),Tf(t,n,r))}}function zf(e){var n=e.alternate;return e===Y||n!==null&&n===Y}function Pf(e,n){jt=Fl=!0;var t=e.pending;t===null?n.next=n:(n.next=t.next,t.next=n),e.pending=n}function Tf(e,n,t){if((t&4194240)!==0){var r=n.lanes;r&=e.pendingLanes,t|=r,n.lanes=t,Yo(e,t)}}function Me(e,n){if(e&&e.defaultProps){n=X({},n),e=e.defaultProps;for(var t in e)n[t]===void 0&&(n[t]=e[t]);return n}return n}function ko(e,n,t,r){n=e.memoizedState,t=t(r,n),t=t===null||t===void 0?n:X({},n,t),e.memoizedState=t,e.lanes===0&&(e.updateQueue.baseState=t)}function Ba(e,n,t,r,l,u,o){return e=e.stateNode,typeof e.shouldComponentUpdate==="function"?e.shouldComponentUpdate(r,u,o):n.prototype&&n.prototype.isPureReactComponent?!sr(t,r)||!sr(l,u):!0}function Rf(e,n,t){var r=!1,l=kn,u=n.contextType;return typeof u==="object"&&u!==null?u=ze(u):(l=he(n)?Un:ie.current,r=n.contextTypes,u=(r=r!==null&&r!==void 0)?mt(e,l):kn),n=new n(t,u),e.memoizedState=n.state!==null&&n.state!==void 0?n.state:null,n.updater=Zl,e.stateNode=n,n._reactInternals=e,r&&(e=e.stateNode,e.__reactInternalMemoizedUnmaskedChildContext=l,e.__reactInternalMemoizedMaskedChildContext=u),n}function $a(e,n,t,r){e=n.state,typeof n.componentWillReceiveProps==="function"&&n.componentWillReceiveProps(t,r),typeof n.UNSAFE_componentWillReceiveProps==="function"&&n.UNSAFE_componentWillReceiveProps(t,r),n.state!==e&&Zl.enqueueReplaceState(n,n.state,null)}function Eo(e,n,t,r){var l=e.stateNode;l.props=t,l.state=e.memoizedState,l.refs={},oi(e);var u=n.contextType;typeof u==="object"&&u!==null?l.context=ze(u):(u=he(n)?Un:ie.current,l.context=mt(e,u)),l.state=e.memoizedState,u=n.getDerivedStateFromProps,typeof u==="function"&&(ko(e,n,u,t),l.state=e.memoizedState),typeof n.getDerivedStateFromProps==="function"||typeof l.getSnapshotBeforeUpdate==="function"||typeof l.UNSAFE_componentWillMount!=="function"&&typeof l.componentWillMount!=="function"||(n=l.state,typeof l.componentWillMount==="function"&&l.componentWillMount(),typeof l.UNSAFE_componentWillMount==="function"&&l.UNSAFE_componentWillMount(),n!==l.state&&Zl.enqueueReplaceState(l,l.state,null),Il(e,t,l,r),l.state=e.memoizedState),typeof l.componentDidMount==="function"&&(e.flags|=4194308)}function kt(e,n){try{var t="",r=n;do t+=vp(r),r=r.return;while(r);var l=t}catch(u){l=`
Error generating stack: `+u.message+`
`+u.stack}return{value:e,source:n,stack:l,digest:null}}function Bu(e,n,t){return{value:e,source:null,stack:t!=null?t:null,digest:n!=null?n:null}}function Co(e,n){try{console.error(n.value)}catch(t){setTimeout(function(){throw t})}}function Df(e,n,t){t=qe(-1,t),t.tag=3,t.payload={element:null};var r=n.value;return t.callback=function(){Vl||(Vl=!0,Lo=r),Co(e,n)},t}function Mf(e,n,t){t=qe(-1,t),t.tag=3;var r=e.type.getDerivedStateFromError;if(typeof r==="function"){var l=n.value;t.payload=function(){return r(l)},t.callback=function(){Co(e,n)}}var u=e.stateNode;return u!==null&&typeof u.componentDidCatch==="function"&&(t.callback=function(){Co(e,n),typeof r!=="function"&&(mn===null?mn=new Set([this]):mn.add(this));var o=n.stack;this.componentDidCatch(n.value,{componentStack:o!==null?o:""})}),t}function Qa(e,n,t){var r=e.pingCache;if(r===null){r=e.pingCache=new $0;var l=new Set;r.set(n,l)}else l=r.get(n),l===void 0&&(l=new Set,r.set(n,l));l.has(t)||(l.add(t),e=b0.bind(null,e,n,t),n.then(e,e))}function Ha(e){do{var n;if(n=e.tag===13)n=e.memoizedState,n=n!==null?n.dehydrated!==null?!0:!1:!0;if(n)return e;e=e.return}while(e!==null);return null}function Wa(e,n,t,r,l){if((e.mode&1)===0)return e===n?e.flags|=65536:(e.flags|=128,t.flags|=131072,t.flags&=-52805,t.tag===1&&(t.alternate===null?t.tag=17:(n=qe(-1,1),n.tag=2,yn(t,n,1))),t.lanes|=1),e;return e.flags|=65536,e.lanes=l,e}function se(e,n,t,r){n.child=e===null?uf(n,null,t,r):St(n,e.child,t,r)}function Aa(e,n,t,r,l){t=t.render;var u=n.ref;if(vt(n,l),r=ci(e,n,t,r,u,l),t=di(),e!==null&&!pe)return n.updateQueue=e.updateQueue,n.flags&=-2053,e.lanes&=~l,en(e,n,l);return $&&t&&bo(n),n.flags|=1,se(e,n,r,l),n.child}function Ka(e,n,t,r,l){if(e===null){var u=t.type;if(typeof u==="function"&&!Ei(u)&&u.defaultProps===void 0&&t.compare===null&&t.defaultProps===void 0)return n.tag=15,n.type=u,If(e,n,u,r,l);return e=yl(t.type,null,r,n,n.mode,l),e.ref=n.ref,e.return=n,n.child=e}if(u=e.child,(e.lanes&l)===0){var o=u.memoizedProps;if(t=t.compare,t=t!==null?t:sr,t(o,r)&&e.ref===n.ref)return en(e,n,l)}return n.flags|=1,e=Sn(u,r),e.ref=n.ref,e.return=n,n.child=e}function If(e,n,t,r,l){if(e!==null){var u=e.memoizedProps;if(sr(u,r)&&e.ref===n.ref)if(pe=!1,n.pendingProps=r=u,(e.lanes&l)!==0)(e.flags&131072)!==0&&(pe=!0);else return n.lanes=e.lanes,en(e,n,l)}return _o(e,n,t,r,l)}function Lf(e,n,t){var r=n.pendingProps,l=r.children,u=e!==null?e.memoizedState:null;if(r.mode==="hidden")if((n.mode&1)===0)n.memoizedState={baseLanes:0,cachePool:null,transitions:null},U(st,me),me|=t;else{if((t&1073741824)===0)return e=u!==null?u.baseLanes|t:t,n.lanes=n.childLanes=1073741824,n.memoizedState={baseLanes:e,cachePool:null,transitions:null},n.updateQueue=null,U(st,me),me|=e,null;n.memoizedState={baseLanes:0,cachePool:null,transitions:null},r=u!==null?u.baseLanes:t,U(st,me),me|=r}else u!==null?(r=u.baseLanes|t,n.memoizedState=null):r=t,U(st,me),me|=r;return se(e,n,l,t),n.child}function Ff(e,n){var t=n.ref;if(e===null&&t!==null||e!==null&&e.ref!==t)n.flags|=512,n.flags|=2097152}function _o(e,n,t,r,l){var u=he(t)?Un:ie.current;if(u=mt(n,u),vt(n,l),t=ci(e,n,t,r,u,l),r=di(),e!==null&&!pe)return n.updateQueue=e.updateQueue,n.flags&=-2053,e.lanes&=~l,en(e,n,l);return $&&r&&bo(n),n.flags|=1,se(e,n,t,l),n.child}function Ya(e,n,t,r,l){if(he(t)){var u=!0;Pl(n)}else u=!1;if(vt(n,l),n.stateNode===null)pl(e,n),Rf(n,t,r),Eo(n,t,r,l),r=!0;else if(e===null){var{stateNode:o,memoizedProps:i}=n;o.props=i;var a=o.context,c=t.contextType;typeof c==="object"&&c!==null?c=ze(c):(c=he(t)?Un:ie.current,c=mt(n,c));var y=t.getDerivedStateFromProps,g=typeof y==="function"||typeof o.getSnapshotBeforeUpdate==="function";g||typeof o.UNSAFE_componentWillReceiveProps!=="function"&&typeof o.componentWillReceiveProps!=="function"||(i!==r||a!==c)&&$a(n,o,r,c),on=!1;var m=n.memoizedState;o.state=m,Il(n,r,o,l),a=n.memoizedState,i!==r||m!==a||ve.current||on?(typeof y==="function"&&(ko(n,t,y,r),a=n.memoizedState),(i=on||Ba(n,t,i,r,m,a,c))?(g||typeof o.UNSAFE_componentWillMount!=="function"&&typeof o.componentWillMount!=="function"||(typeof o.componentWillMount==="function"&&o.componentWillMount(),typeof o.UNSAFE_componentWillMount==="function"&&o.UNSAFE_componentWillMount()),typeof o.componentDidMount==="function"&&(n.flags|=4194308)):(typeof o.componentDidMount==="function"&&(n.flags|=4194308),n.memoizedProps=r,n.memoizedState=a),o.props=r,o.state=a,o.context=c,r=i):(typeof o.componentDidMount==="function"&&(n.flags|=4194308),r=!1)}else{o=n.stateNode,af(e,n),i=n.memoizedProps,c=n.type===n.elementType?i:Me(n.type,i),o.props=c,g=n.pendingProps,m=o.context,a=t.contextType,typeof a==="object"&&a!==null?a=ze(a):(a=he(t)?Un:ie.current,a=mt(n,a));var k=t.getDerivedStateFromProps;(y=typeof k==="function"||typeof o.getSnapshotBeforeUpdate==="function")||typeof o.UNSAFE_componentWillReceiveProps!=="function"&&typeof o.componentWillReceiveProps!=="function"||(i!==g||m!==a)&&$a(n,o,r,a),on=!1,m=n.memoizedState,o.state=m,Il(n,r,o,l);var C=n.memoizedState;i!==g||m!==C||ve.current||on?(typeof k==="function"&&(ko(n,t,k,r),C=n.memoizedState),(c=on||Ba(n,t,c,r,m,C,a)||!1)?(y||typeof o.UNSAFE_componentWillUpdate!=="function"&&typeof o.componentWillUpdate!=="function"||(typeof o.componentWillUpdate==="function"&&o.componentWillUpdate(r,C,a),typeof o.UNSAFE_componentWillUpdate==="function"&&o.UNSAFE_componentWillUpdate(r,C,a)),typeof o.componentDidUpdate==="function"&&(n.flags|=4),typeof o.getSnapshotBeforeUpdate==="function"&&(n.flags|=1024)):(typeof o.componentDidUpdate!=="function"||i===e.memoizedProps&&m===e.memoizedState||(n.flags|=4),typeof o.getSnapshotBeforeUpdate!=="function"||i===e.memoizedProps&&m===e.memoizedState||(n.flags|=1024),n.memoizedProps=r,n.memoizedState=C),o.props=r,o.state=C,o.context=a,r=c):(typeof o.componentDidUpdate!=="function"||i===e.memoizedProps&&m===e.memoizedState||(n.flags|=4),typeof o.getSnapshotBeforeUpdate!=="function"||i===e.memoizedProps&&m===e.memoizedState||(n.flags|=1024),r=!1)}return No(e,n,t,r,u,l)}function No(e,n,t,r,l,u){Ff(e,n);var o=(n.flags&128)!==0;if(!r&&!o)return l&&Da(n,t,!1),en(e,n,u);r=n.stateNode,Q0.current=n;var i=o&&typeof t.getDerivedStateFromError!=="function"?null:r.render();return n.flags|=1,e!==null&&o?(n.child=St(n,e.child,null,u),n.child=St(n,null,i,u)):se(e,n,i,u),n.memoizedState=r.state,l&&Da(n,t,!0),n.child}function Of(e){var n=e.stateNode;n.pendingContext?Ra(e,n.pendingContext,n.pendingContext!==n.context):n.context&&Ra(e,n.context,!1),ii(e,n.containerInfo)}function Xa(e,n,t,r,l){return gt(),ni(l),n.flags|=256,se(e,n,t,r),n.child}function Po(e){return{baseLanes:e,cachePool:null,transitions:null}}function Uf(e,n,t){var r=n.pendingProps,l=K.current,u=!1,o=(n.flags&128)!==0,i;if((i=o)||(i=e!==null&&e.memoizedState===null?!1:(l&2)!==0),i)u=!0,n.flags&=-129;else if(e===null||e.memoizedState!==null)l|=1;if(U(K,l&1),e===null){if(So(n),e=n.memoizedState,e!==null&&(e=e.dehydrated,e!==null))return(n.mode&1)===0?n.lanes=1:e.data==="$!"?n.lanes=8:n.lanes=1073741824,null;return o=r.children,e=r.fallback,u?(r=n.mode,u=n.child,o={mode:"hidden",children:o},(r&1)===0&&u!==null?(u.childLanes=0,u.pendingProps=o):u=xl(o,r,0,null),e=On(e,r,t,null),u.return=n,e.return=n,u.sibling=e,n.child=u,n.child.memoizedState=Po(t),n.memoizedState=zo,e):hi(n,o)}if(l=e.memoizedState,l!==null&&(i=l.dehydrated,i!==null))return H0(e,n,o,r,i,l,t);if(u){u=r.fallback,o=n.mode,l=e.child,i=l.sibling;var a={mode:"hidden",children:r.children};return(o&1)===0&&n.child!==l?(r=n.child,r.childLanes=0,r.pendingProps=a,n.deletions=null):(r=Sn(l,a),r.subtreeFlags=l.subtreeFlags&14680064),i!==null?u=Sn(i,u):(u=On(u,o,t,null),u.flags|=2),u.return=n,r.return=n,r.sibling=u,n.child=r,r=u,u=n.child,o=e.child.memoizedState,o=o===null?Po(t):{baseLanes:o.baseLanes|t,cachePool:null,transitions:o.transitions},u.memoizedState=o,u.childLanes=e.childLanes&~t,n.memoizedState=zo,r}return u=e.child,e=u.sibling,r=Sn(u,{mode:"visible",children:r.children}),(n.mode&1)===0&&(r.lanes=t),r.return=n,r.sibling=null,e!==null&&(t=n.deletions,t===null?(n.deletions=[e],n.flags|=16):t.push(e)),n.child=r,n.memoizedState=null,r}function hi(e,n){return n=xl({mode:"visible",children:n},e.mode,0,null),n.return=e,e.child=n}function rl(e,n,t,r){return r!==null&&ni(r),St(n,e.child,null,t),e=hi(n,n.pendingProps.children),e.flags|=2,n.memoizedState=null,e}function H0(e,n,t,r,l,u,o){if(t){if(n.flags&256)return n.flags&=-257,r=Bu(Error(w(422))),rl(e,n,o,r);if(n.memoizedState!==null)return n.child=e.child,n.flags|=128,null;return u=r.fallback,l=n.mode,r=xl({mode:"visible",children:r.children},l,0,null),u=On(u,l,o,null),u.flags|=2,r.return=n,u.return=n,r.sibling=u,n.child=r,(n.mode&1)!==0&&St(n,e.child,null,o),n.child.memoizedState=Po(o),n.memoizedState=zo,u}if((n.mode&1)===0)return rl(e,n,o,null);if(l.data==="$!"){if(r=l.nextSibling&&l.nextSibling.dataset,r)var i=r.dgst;return r=i,u=Error(w(419)),r=Bu(u,r,void 0),rl(e,n,o,r)}if(i=(o&e.childLanes)!==0,pe||i){if(r=b,r!==null){switch(o&-o){case 4:l=2;break;case 16:l=8;break;case 64:case 128:case 256:case 512:case 1024:case 2048:case 4096:case 8192:case 16384:case 32768:case 65536:case 131072:case 262144:case 524288:case 1048576:case 2097152:case 4194304:case 8388608:case 16777216:case 33554432:case 67108864:l=32;break;case 536870912:l=268435456;break;default:l=0}l=(l&(r.suspendedLanes|o))!==0?0:l,l!==0&&l!==u.retryLane&&(u.retryLane=l,be(e,l),Oe(r,e,l,-1))}return ki(),r=Bu(Error(w(421))),rl(e,n,o,r)}if(l.data==="$?")return n.flags|=128,n.child=e.child,n=ev.bind(null,e),l._reactRetry=n,null;return e=u.treeContext,ge=hn(l.nextSibling),Se=n,$=!0,Le=null,e!==null&&(Ee[Ce++]=Ze,Ee[Ce++]=Je,Ee[Ce++]=Vn,Ze=e.id,Je=e.overflow,Vn=n),n=hi(n,r.children),n.flags|=4096,n}function Ga(e,n,t){e.lanes|=n;var r=e.alternate;r!==null&&(r.lanes|=n),wo(e.return,n,t)}function $u(e,n,t,r,l){var u=e.memoizedState;u===null?e.memoizedState={isBackwards:n,rendering:null,renderingStartTime:0,last:r,tail:t,tailMode:l}:(u.isBackwards=n,u.rendering=null,u.renderingStartTime=0,u.last=r,u.tail=t,u.tailMode=l)}function Vf(e,n,t){var r=n.pendingProps,l=r.revealOrder,u=r.tail;if(se(e,n,r.children,t),r=K.current,(r&2)!==0)r=r&1|2,n.flags|=128;else{if(e!==null&&(e.flags&128)!==0)e:for(e=n.child;e!==null;){if(e.tag===13)e.memoizedState!==null&&Ga(e,t,n);else if(e.tag===19)Ga(e,t,n);else if(e.child!==null){e.child.return=e,e=e.child;continue}if(e===n)break e;for(;e.sibling===null;){if(e.return===null||e.return===n)break e;e=e.return}e.sibling.return=e.return,e=e.sibling}r&=1}if(U(K,r),(n.mode&1)===0)n.memoizedState=null;else switch(l){case"forwards":t=n.child;for(l=null;t!==null;)e=t.alternate,e!==null&&Ll(e)===null&&(l=t),t=t.sibling;t=l,t===null?(l=n.child,n.child=null):(l=t.sibling,t.sibling=null),$u(n,!1,l,t,u);break;case"backwards":t=null,l=n.child;for(n.child=null;l!==null;){if(e=l.alternate,e!==null&&Ll(e)===null){n.child=l;break}e=l.sibling,l.sibling=t,t=l,l=e}$u(n,!0,t,null,u);break;case"together":$u(n,!1,null,null,void 0);break;default:n.memoizedState=null}return n.child}function pl(e,n){(n.mode&1)===0&&e!==null&&(e.alternate=null,n.alternate=null,n.flags|=2)}function en(e,n,t){if(e!==null&&(n.dependencies=e.dependencies),$n|=n.lanes,(t&n.childLanes)===0)return null;if(e!==null&&n.child!==e.child)throw Error(w(153));if(n.child!==null){e=n.child,t=Sn(e,e.pendingProps),n.child=t;for(t.return=n;e.sibling!==null;)e=e.sibling,t=t.sibling=Sn(e,e.pendingProps),t.return=n;t.sibling=null}return n.child}function W0(e,n,t){switch(n.tag){case 3:Of(n),gt();break;case 5:sf(n);break;case 1:he(n.type)&&Pl(n);break;case 4:ii(n,n.stateNode.containerInfo);break;case 10:var r=n.type._context,l=n.memoizedProps.value;U(Dl,r._currentValue),r._currentValue=l;break;case 13:if(r=n.memoizedState,r!==null){if(r.dehydrated!==null)return U(K,K.current&1),n.flags|=128,null;if((t&n.child.childLanes)!==0)return Uf(e,n,t);return U(K,K.current&1),e=en(e,n,t),e!==null?e.sibling:null}U(K,K.current&1);break;case 19:if(r=(t&n.childLanes)!==0,(e.flags&128)!==0){if(r)return Vf(e,n,t);n.flags|=128}if(l=n.memoizedState,l!==null&&(l.rendering=null,l.tail=null,l.lastEffect=null),U(K,K.current),r)break;else return null;case 22:case 23:return n.lanes=0,Lf(e,n,t)}return en(e,n,t)}function Vt(e,n){if(!$)switch(e.tailMode){case"hidden":n=e.tail;for(var t=null;n!==null;)n.alternate!==null&&(t=n),n=n.sibling;t===null?e.tail=null:t.sibling=null;break;case"collapsed":t=e.tail;for(var r=null;t!==null;)t.alternate!==null&&(r=t),t=t.sibling;r===null?n||e.tail===null?e.tail=null:e.tail.sibling=null:r.sibling=null}}function ue(e){var n=e.alternate!==null&&e.alternate.child===e.child,t=0,r=0;if(n)for(var l=e.child;l!==null;)t|=l.lanes|l.childLanes,r|=l.subtreeFlags&14680064,r|=l.flags&14680064,l.return=e,l=l.sibling;else for(l=e.child;l!==null;)t|=l.lanes|l.childLanes,r|=l.subtreeFlags,r|=l.flags,l.return=e,l=l.sibling;return e.subtreeFlags|=r,e.childLanes=t,n}function A0(e,n,t){var r=n.pendingProps;switch(ei(n),n.tag){case 2:case 16:case 15:case 0:case 11:case 7:case 8:case 12:case 9:case 14:return ue(n),null;case 1:return he(n.type)&&zl(),ue(n),null;case 3:if(r=n.stateNode,wt(),B(ve),B(ie),si(),r.pendingContext&&(r.context=r.pendingContext,r.pendingContext=null),e===null||e.child===null)nl(n)?n.flags|=4:e===null||e.memoizedState.isDehydrated&&(n.flags&256)===0||(n.flags|=1024,Le!==null&&(Uo(Le),Le=null));return To(e,n),ue(n),null;case 5:ai(n);var l=Ln(vr.current);if(t=n.type,e!==null&&n.stateNode!=null)$f(e,n,t,r,l),e.ref!==n.ref&&(n.flags|=512,n.flags|=2097152);else{if(!r){if(n.stateNode===null)throw Error(w(166));return ue(n),null}if(e=Ln(Ae.current),nl(n)){r=n.stateNode,t=n.type;var u=n.memoizedProps;switch(r[He]=n,r[dr]=u,e=(n.mode&1)!==0,t){case"dialog":V("cancel",r),V("close",r);break;case"iframe":case"object":case"embed":V("load",r);break;case"video":case"audio":for(l=0;l<Xt.length;l++)V(Xt[l],r);break;case"source":V("error",r);break;case"img":case"image":case"link":V("error",r),V("load",r);break;case"details":V("toggle",r);break;case"input":ra(r,u),V("invalid",r);break;case"select":r._wrapperState={wasMultiple:!!u.multiple},V("invalid",r);break;case"textarea":ua(r,u),V("invalid",r)}ju(t,u),l=null;for(var o in u)if(u.hasOwnProperty(o)){var i=u[o];o==="children"?typeof i==="string"?r.textContent!==i&&(u.suppressHydrationWarning!==!0&&el(r.textContent,i,e),l=["children",i]):typeof i==="number"&&r.textContent!==""+i&&(u.suppressHydrationWarning!==!0&&el(r.textContent,i,e),l=["children",""+i]):tr.hasOwnProperty(o)&&i!=null&&o==="onScroll"&&V("scroll",r)}switch(t){case"input":Xr(r),la(r,u,!0);break;case"textarea":Xr(r),oa(r);break;case"select":case"option":break;default:typeof u.onClick==="function"&&(r.onclick=Nl)}r=l,n.updateQueue=r,r!==null&&(n.flags|=4)}else{o=l.nodeType===9?l:l.ownerDocument,e==="http://www.w3.org/1999/xhtml"&&(e=ps(t)),e==="http://www.w3.org/1999/xhtml"?t==="script"?(e=o.createElement("div"),e.innerHTML="<script><\/script>",e=e.removeChild(e.firstChild)):typeof r.is==="string"?e=o.createElement(t,{is:r.is}):(e=o.createElement(t),t==="select"&&(o=e,r.multiple?o.multiple=!0:r.size&&(o.size=r.size))):e=o.createElementNS(e,t),e[He]=n,e[dr]=r,Bf(e,n,!1,!1),n.stateNode=e;e:{switch(o=bu(t,r),t){case"dialog":V("cancel",e),V("close",e),l=r;break;case"iframe":case"object":case"embed":V("load",e),l=r;break;case"video":case"audio":for(l=0;l<Xt.length;l++)V(Xt[l],e);l=r;break;case"source":V("error",e),l=r;break;case"img":case"image":case"link":V("error",e),V("load",e),l=r;break;case"details":V("toggle",e),l=r;break;case"input":ra(e,r),l=Gu(e,r),V("invalid",e);break;case"option":l=r;break;case"select":e._wrapperState={wasMultiple:!!r.multiple},l=X({},r,{value:void 0}),V("invalid",e);break;case"textarea":ua(e,r),l=qu(e,r),V("invalid",e);break;default:l=r}ju(t,l),i=l;for(u in i)if(i.hasOwnProperty(u)){var a=i[u];u==="style"?ys(e,a):u==="dangerouslySetInnerHTML"?(a=a?a.__html:void 0,a!=null&&vs(e,a)):u==="children"?typeof a==="string"?(t!=="textarea"||a!=="")&&rr(e,a):typeof a==="number"&&rr(e,""+a):u!=="suppressContentEditableWarning"&&u!=="suppressHydrationWarning"&&u!=="autoFocus"&&(tr.hasOwnProperty(u)?a!=null&&u==="onScroll"&&V("scroll",e):a!=null&&$o(e,u,a,o))}switch(t){case"input":Xr(e),la(e,r,!1);break;case"textarea":Xr(e),oa(e);break;case"option":r.value!=null&&e.setAttribute("value",""+wn(r.value));break;case"select":e.multiple=!!r.multiple,u=r.value,u!=null?ft(e,!!r.multiple,u,!1):r.defaultValue!=null&&ft(e,!!r.multiple,r.defaultValue,!0);break;default:typeof l.onClick==="function"&&(e.onclick=Nl)}switch(t){case"button":case"input":case"select":case"textarea":r=!!r.autoFocus;break e;case"img":r=!0;break e;default:r=!1}}r&&(n.flags|=4)}n.ref!==null&&(n.flags|=512,n.flags|=2097152)}return ue(n),null;case 6:if(e&&n.stateNode!=null)Qf(e,n,e.memoizedProps,r);else{if(typeof r!=="string"&&n.stateNode===null)throw Error(w(166));if(t=Ln(vr.current),Ln(Ae.current),nl(n)){if(r=n.stateNode,t=n.memoizedProps,r[He]=n,u=r.nodeValue!==t){if(e=Se,e!==null)switch(e.tag){case 3:el(r.nodeValue,t,(e.mode&1)!==0);break;case 5:e.memoizedProps.suppressHydrationWarning!==!0&&el(r.nodeValue,t,(e.mode&1)!==0)}}u&&(n.flags|=4)}else r=(t.nodeType===9?t:t.ownerDocument).createTextNode(r),r[He]=n,n.stateNode=r}return ue(n),null;case 13:if(B(K),r=n.memoizedState,e===null||e.memoizedState!==null&&e.memoizedState.dehydrated!==null){if($&&ge!==null&&(n.mode&1)!==0&&(n.flags&128)===0)rf(),gt(),n.flags|=98560,u=!1;else if(u=nl(n),r!==null&&r.dehydrated!==null){if(e===null){if(!u)throw Error(w(318));if(u=n.memoizedState,u=u!==null?u.dehydrated:null,!u)throw Error(w(317));u[He]=n}else gt(),(n.flags&128)===0&&(n.memoizedState=null),n.flags|=4;ue(n),u=!1}else Le!==null&&(Uo(Le),Le=null),u=!0;if(!u)return n.flags&65536?n:null}if((n.flags&128)!==0)return n.lanes=t,n;return r=r!==null,r!==(e!==null&&e.memoizedState!==null)&&r&&(n.child.flags|=8192,(n.mode&1)!==0&&(e===null||(K.current&1)!==0?x===0&&(x=3):ki())),n.updateQueue!==null&&(n.flags|=4),ue(n),null;case 4:return wt(),To(e,n),e===null&&fr(n.stateNode.containerInfo),ue(n),null;case 10:return li(n.type._context),ue(n),null;case 17:return he(n.type)&&zl(),ue(n),null;case 19:if(B(K),u=n.memoizedState,u===null)return ue(n),null;if(r=(n.flags&128)!==0,o=u.rendering,o===null)if(r)Vt(u,!1);else{if(x!==0||e!==null&&(e.flags&128)!==0)for(e=n.child;e!==null;){if(o=Ll(e),o!==null){n.flags|=128,Vt(u,!1),r=o.updateQueue,r!==null&&(n.updateQueue=r,n.flags|=4),n.subtreeFlags=0,r=t;for(t=n.child;t!==null;)u=t,e=r,u.flags&=14680066,o=u.alternate,o===null?(u.childLanes=0,u.lanes=e,u.child=null,u.subtreeFlags=0,u.memoizedProps=null,u.memoizedState=null,u.updateQueue=null,u.dependencies=null,u.stateNode=null):(u.childLanes=o.childLanes,u.lanes=o.lanes,u.child=o.child,u.subtreeFlags=0,u.deletions=null,u.memoizedProps=o.memoizedProps,u.memoizedState=o.memoizedState,u.updateQueue=o.updateQueue,u.type=o.type,e=o.dependencies,u.dependencies=e===null?null:{lanes:e.lanes,firstContext:e.firstContext}),t=t.sibling;return U(K,K.current&1|2),n.child}e=e.sibling}u.tail!==null&&Z()>Et&&(n.flags|=128,r=!0,Vt(u,!1),n.lanes=4194304)}else{if(!r)if(e=Ll(o),e!==null){if(n.flags|=128,r=!0,t=e.updateQueue,t!==null&&(n.updateQueue=t,n.flags|=4),Vt(u,!0),u.tail===null&&u.tailMode==="hidden"&&!o.alternate&&!$)return ue(n),null}else 2*Z()-u.renderingStartTime>Et&&t!==1073741824&&(n.flags|=128,r=!0,Vt(u,!1),n.lanes=4194304);u.isBackwards?(o.sibling=n.child,n.child=o):(t=u.last,t!==null?t.sibling=o:n.child=o,u.last=o)}if(u.tail!==null)return n=u.tail,u.rendering=n,u.tail=n.sibling,u.renderingStartTime=Z(),n.sibling=null,t=K.current,U(K,r?t&1|2:t&1),n;return ue(n),null;case 22:case 23:return wi(),r=n.memoizedState!==null,e!==null&&e.memoizedState!==null!==r&&(n.flags|=8192),r&&(n.mode&1)!==0?(me&1073741824)!==0&&(ue(n),n.subtreeFlags&6&&(n.flags|=8192)):ue(n),null;case 24:return null;case 25:return null}throw Error(w(156,n.tag))}function K0(e,n){switch(ei(n),n.tag){case 1:return he(n.type)&&zl(),e=n.flags,e&65536?(n.flags=e&-65537|128,n):null;case 3:return wt(),B(ve),B(ie),si(),e=n.flags,(e&65536)!==0&&(e&128)===0?(n.flags=e&-65537|128,n):null;case 5:return ai(n),null;case 13:if(B(K),e=n.memoizedState,e!==null&&e.dehydrated!==null){if(n.alternate===null)throw Error(w(340));gt()}return e=n.flags,e&65536?(n.flags=e&-65537|128,n):null;case 19:return B(K),null;case 4:return wt(),null;case 10:return li(n.type._context),null;case 22:case 23:return wi(),null;case 24:return null;default:return null}}function at(e,n){var t=e.ref;if(t!==null)if(typeof t==="function")try{t(null)}catch(r){G(e,n,r)}else t.current=null}function Ro(e,n,t){try{t()}catch(r){G(e,n,r)}}function X0(e,n){if(co=El,e=Ks(),jo(e)){if("selectionStart"in e)var t={start:e.selectionStart,end:e.selectionEnd};else e:{t=(t=e.ownerDocument)&&t.defaultView||window;var r=t.getSelection&&t.getSelection();if(r&&r.rangeCount!==0){t=r.anchorNode;var{anchorOffset:l,focusNode:u}=r;r=r.focusOffset;try{t.nodeType,u.nodeType}catch(S){t=null;break e}var o=0,i=-1,a=-1,c=0,y=0,g=e,m=null;n:for(;;){for(var k;;){if(g!==t||l!==0&&g.nodeType!==3||(i=o+l),g!==u||r!==0&&g.nodeType!==3||(a=o+r),g.nodeType===3&&(o+=g.nodeValue.length),(k=g.firstChild)===null)break;m=g,g=k}for(;;){if(g===e)break n;if(m===t&&++c===l&&(i=o),m===u&&++y===r&&(a=o),(k=g.nextSibling)!==null)break;g=m,m=g.parentNode}g=k}t=i===-1||a===-1?null:{start:i,end:a}}else t=null}t=t||{start:0,end:0}}else t=null;po={focusedElem:e,selectionRange:t},El=!1;for(N=n;N!==null;)if(n=N,e=n.child,(n.subtreeFlags&1028)!==0&&e!==null)e.return=n,N=e;else for(;N!==null;){n=N;try{var C=n.alternate;if((n.flags&1024)!==0)switch(n.tag){case 0:case 11:case 15:break;case 1:if(C!==null){var{memoizedProps:E,memoizedState:W}=C,d=n.stateNode,f=d.getSnapshotBeforeUpdate(n.elementType===n.type?E:Me(n.type,E),W);d.__reactInternalSnapshotBeforeUpdate=f}break;case 3:var p=n.stateNode.containerInfo;p.nodeType===1?p.textContent="":p.nodeType===9&&p.documentElement&&p.removeChild(p.documentElement);break;case 5:case 6:case 4:case 17:break;default:throw Error(w(163))}}catch(S){G(n,n.return,S)}if(e=n.sibling,e!==null){e.return=n.return,N=e;break}N=n.return}return C=Za,Za=!1,C}function bt(e,n,t){var r=n.updateQueue;if(r=r!==null?r.lastEffect:null,r!==null){var l=r=r.next;do{if((l.tag&e)===e){var u=l.destroy;l.destroy=void 0,u!==void 0&&Ro(n,t,u)}l=l.next}while(l!==r)}}function Jl(e,n){if(n=n.updateQueue,n=n!==null?n.lastEffect:null,n!==null){var t=n=n.next;do{if((t.tag&e)===e){var r=t.create;t.destroy=r()}t=t.next}while(t!==n)}}function Do(e){var n=e.ref;if(n!==null){var t=e.stateNode;switch(e.tag){case 5:e=t;break;default:e=t}typeof n==="function"?n(e):n.current=e}}function Hf(e){var n=e.alternate;n!==null&&(e.alternate=null,Hf(n)),e.child=null,e.deletions=null,e.sibling=null,e.tag===5&&(n=e.stateNode,n!==null&&(delete n[He],delete n[dr],delete n[yo],delete n[T0],delete n[R0])),e.stateNode=null,e.return=null,e.dependencies=null,e.memoizedProps=null,e.memoizedState=null,e.pendingProps=null,e.stateNode=null,e.updateQueue=null}function Wf(e){return e.tag===5||e.tag===3||e.tag===4}function Ja(e){e:for(;;){for(;e.sibling===null;){if(e.return===null||Wf(e.return))return null;e=e.return}e.sibling.return=e.return;for(e=e.sibling;e.tag!==5&&e.tag!==6&&e.tag!==18;){if(e.flags&2)continue e;if(e.child===null||e.tag===4)continue e;else e.child.return=e,e=e.child}if(!(e.flags&2))return e.stateNode}}function Mo(e,n,t){var r=e.tag;if(r===5||r===6)e=e.stateNode,n?t.nodeType===8?t.parentNode.insertBefore(e,n):t.insertBefore(e,n):(t.nodeType===8?(n=t.parentNode,n.insertBefore(e,t)):(n=t,n.appendChild(e)),t=t._reactRootContainer,t!==null&&t!==void 0||n.onclick!==null||(n.onclick=Nl));else if(r!==4&&(e=e.child,e!==null))for(Mo(e,n,t),e=e.sibling;e!==null;)Mo(e,n,t),e=e.sibling}function Io(e,n,t){var r=e.tag;if(r===5||r===6)e=e.stateNode,n?t.insertBefore(e,n):t.appendChild(e);else if(r!==4&&(e=e.child,e!==null))for(Io(e,n,t),e=e.sibling;e!==null;)Io(e,n,t),e=e.sibling}function ln(e,n,t){for(t=t.child;t!==null;)Af(e,n,t),t=t.sibling}function Af(e,n,t){if(We&&typeof We.onCommitFiberUnmount==="function")try{We.onCommitFiberUnmount(Hl,t)}catch(i){}switch(t.tag){case 5:oe||at(t,n);case 6:var r=ee,l=Ie;ee=null,ln(e,n,t),ee=r,Ie=l,ee!==null&&(Ie?(e=ee,t=t.stateNode,e.nodeType===8?e.parentNode.removeChild(t):e.removeChild(t)):ee.removeChild(t.stateNode));break;case 18:ee!==null&&(Ie?(e=ee,t=t.stateNode,e.nodeType===8?Iu(e.parentNode,t):e.nodeType===1&&Iu(e,t),ir(e)):Iu(ee,t.stateNode));break;case 4:r=ee,l=Ie,ee=t.stateNode.containerInfo,Ie=!0,ln(e,n,t),ee=r,Ie=l;break;case 0:case 11:case 14:case 15:if(!oe&&(r=t.updateQueue,r!==null&&(r=r.lastEffect,r!==null))){l=r=r.next;do{var u=l,o=u.destroy;u=u.tag,o!==void 0&&((u&2)!==0?Ro(t,n,o):(u&4)!==0&&Ro(t,n,o)),l=l.next}while(l!==r)}ln(e,n,t);break;case 1:if(!oe&&(at(t,n),r=t.stateNode,typeof r.componentWillUnmount==="function"))try{r.props=t.memoizedProps,r.state=t.memoizedState,r.componentWillUnmount()}catch(i){G(t,n,i)}ln(e,n,t);break;case 21:ln(e,n,t);break;case 22:t.mode&1?(oe=(r=oe)||t.memoizedState!==null,ln(e,n,t),oe=r):ln(e,n,t);break;default:ln(e,n,t)}}function qa(e){var n=e.updateQueue;if(n!==null){e.updateQueue=null;var t=e.stateNode;t===null&&(t=e.stateNode=new Y0),n.forEach(function(r){var l=nv.bind(null,e,r);t.has(r)||(t.add(r),r.then(l,l))})}}function De(e,n){var t=n.deletions;if(t!==null)for(var r=0;r<t.length;r++){var l=t[r];try{var u=e,o=n,i=o;e:for(;i!==null;){switch(i.tag){case 5:ee=i.stateNode,Ie=!1;break e;case 3:ee=i.stateNode.containerInfo,Ie=!0;break e;case 4:ee=i.stateNode.containerInfo,Ie=!0;break e}i=i.return}if(ee===null)throw Error(w(160));Af(u,o,l),ee=null,Ie=!1;var a=l.alternate;a!==null&&(a.return=null),l.return=null}catch(c){G(l,n,c)}}if(n.subtreeFlags&12854)for(n=n.child;n!==null;)Kf(n,e),n=n.sibling}function Kf(e,n){var{alternate:t,flags:r}=e;switch(e.tag){case 0:case 11:case 14:case 15:if(De(n,e),$e(e),r&4){try{bt(3,e,e.return),Jl(3,e)}catch(E){G(e,e.return,E)}try{bt(5,e,e.return)}catch(E){G(e,e.return,E)}}break;case 1:De(n,e),$e(e),r&512&&t!==null&&at(t,t.return);break;case 5:if(De(n,e),$e(e),r&512&&t!==null&&at(t,t.return),e.flags&32){var l=e.stateNode;try{rr(l,"")}catch(E){G(e,e.return,E)}}if(r&4&&(l=e.stateNode,l!=null)){var u=e.memoizedProps,o=t!==null?t.memoizedProps:u,i=e.type,a=e.updateQueue;if(e.updateQueue=null,a!==null)try{i==="input"&&u.type==="radio"&&u.name!=null&&cs(l,u),bu(i,o);var c=bu(i,u);for(o=0;o<a.length;o+=2){var y=a[o],g=a[o+1];y==="style"?ys(l,g):y==="dangerouslySetInnerHTML"?vs(l,g):y==="children"?rr(l,g):$o(l,y,g,c)}switch(i){case"input":Zu(l,u);break;case"textarea":ds(l,u);break;case"select":var m=l._wrapperState.wasMultiple;l._wrapperState.wasMultiple=!!u.multiple;var k=u.value;k!=null?ft(l,!!u.multiple,k,!1):m!==!!u.multiple&&(u.defaultValue!=null?ft(l,!!u.multiple,u.defaultValue,!0):ft(l,!!u.multiple,u.multiple?[]:"",!1))}l[dr]=u}catch(E){G(e,e.return,E)}}break;case 6:if(De(n,e),$e(e),r&4){if(e.stateNode===null)throw Error(w(162));l=e.stateNode,u=e.memoizedProps;try{l.nodeValue=u}catch(E){G(e,e.return,E)}}break;case 3:if(De(n,e),$e(e),r&4&&t!==null&&t.memoizedState.isDehydrated)try{ir(n.containerInfo)}catch(E){G(e,e.return,E)}break;case 4:De(n,e),$e(e);break;case 13:De(n,e),$e(e),l=e.child,l.flags&8192&&(u=l.memoizedState!==null,l.stateNode.isHidden=u,!u||l.alternate!==null&&l.alternate.memoizedState!==null||(gi=Z())),r&4&&qa(e);break;case 22:if(y=t!==null&&t.memoizedState!==null,e.mode&1?(oe=(c=oe)||y,De(n,e),oe=c):De(n,e),$e(e),r&8192){if(c=e.memoizedState!==null,(e.stateNode.isHidden=c)&&!y&&(e.mode&1)!==0)for(N=e,y=e.child;y!==null;){for(g=N=y;N!==null;){switch(m=N,k=m.child,m.tag){case 0:case 11:case 14:case 15:bt(4,m,m.return);break;case 1:at(m,m.return);var C=m.stateNode;if(typeof C.componentWillUnmount==="function"){r=m,t=m.return;try{n=r,C.props=n.memoizedProps,C.state=n.memoizedState,C.componentWillUnmount()}catch(E){G(r,t,E)}}break;case 5:at(m,m.return);break;case 22:if(m.memoizedState!==null){ja(g);continue}}k!==null?(k.return=m,N=k):ja(g)}y=y.sibling}e:for(y=null,g=e;;){if(g.tag===5){if(y===null){y=g;try{l=g.stateNode,c?(u=l.style,typeof u.setProperty==="function"?u.setProperty("display","none","important"):u.display="none"):(i=g.stateNode,a=g.memoizedProps.style,o=a!==void 0&&a!==null&&a.hasOwnProperty("display")?a.display:null,i.style.display=hs("display",o))}catch(E){G(e,e.return,E)}}}else if(g.tag===6){if(y===null)try{g.stateNode.nodeValue=c?"":g.memoizedProps}catch(E){G(e,e.return,E)}}else if((g.tag!==22&&g.tag!==23||g.memoizedState===null||g===e)&&g.child!==null){g.child.return=g,g=g.child;continue}if(g===e)break e;for(;g.sibling===null;){if(g.return===null||g.return===e)break e;y===g&&(y=null),g=g.return}y===g&&(y=null),g.sibling.return=g.return,g=g.sibling}}break;case 19:De(n,e),$e(e),r&4&&qa(e);break;case 21:break;default:De(n,e),$e(e)}}function $e(e){var n=e.flags;if(n&2){try{e:{for(var t=e.return;t!==null;){if(Wf(t)){var r=t;break e}t=t.return}throw Error(w(160))}switch(r.tag){case 5:var l=r.stateNode;r.flags&32&&(rr(l,""),r.flags&=-33);var u=Ja(e);Io(e,u,l);break;case 3:case 4:var o=r.stateNode.containerInfo,i=Ja(e);Mo(e,i,o);break;default:throw Error(w(161))}}catch(a){G(e,e.return,a)}e.flags&=-3}n&4096&&(e.flags&=-4097)}function G0(e,n,t){N=e,Yf(e,n,t)}function Yf(e,n,t){for(var r=(e.mode&1)!==0;N!==null;){var l=N,u=l.child;if(l.tag===22&&r){var o=l.memoizedState!==null||ll;if(!o){var i=l.alternate,a=i!==null&&i.memoizedState!==null||oe;i=ll;var c=oe;if(ll=o,(oe=a)&&!c)for(N=l;N!==null;)o=N,a=o.child,o.tag===22&&o.memoizedState!==null?ba(l):a!==null?(a.return=o,N=a):ba(l);for(;u!==null;)N=u,Yf(u,n,t),u=u.sibling;N=l,ll=i,oe=c}xa(e,n,t)}else(l.subtreeFlags&8772)!==0&&u!==null?(u.return=l,N=u):xa(e,n,t)}}function xa(e){for(;N!==null;){var n=N;if((n.flags&8772)!==0){var t=n.alternate;try{if((n.flags&8772)!==0)switch(n.tag){case 0:case 11:case 15:oe||Jl(5,n);break;case 1:var r=n.stateNode;if(n.flags&4&&!oe)if(t===null)r.componentDidMount();else{var l=n.elementType===n.type?t.memoizedProps:Me(n.type,t.memoizedProps);r.componentDidUpdate(l,t.memoizedState,r.__reactInternalSnapshotBeforeUpdate)}var u=n.updateQueue;u!==null&&Oa(n,u,r);break;case 3:var o=n.updateQueue;if(o!==null){if(t=null,n.child!==null)switch(n.child.tag){case 5:t=n.child.stateNode;break;case 1:t=n.child.stateNode}Oa(n,o,t)}break;case 5:var i=n.stateNode;if(t===null&&n.flags&4){t=i;var a=n.memoizedProps;switch(n.type){case"button":case"input":case"select":case"textarea":a.autoFocus&&t.focus();break;case"img":a.src&&(t.src=a.src)}}break;case 6:break;case 4:break;case 12:break;case 13:if(n.memoizedState===null){var c=n.alternate;if(c!==null){var y=c.memoizedState;if(y!==null){var g=y.dehydrated;g!==null&&ir(g)}}}break;case 19:case 17:case 21:case 22:case 23:case 25:break;default:throw Error(w(163))}oe||n.flags&512&&Do(n)}catch(m){G(n,n.return,m)}}if(n===e){N=null;break}if(t=n.sibling,t!==null){t.return=n.return,N=t;break}N=n.return}}function ja(e){for(;N!==null;){var n=N;if(n===e){N=null;break}var t=n.sibling;if(t!==null){t.return=n.return,N=t;break}N=n.return}}function ba(e){for(;N!==null;){var n=N;try{switch(n.tag){case 0:case 11:case 15:var t=n.return;try{Jl(4,n)}catch(a){G(n,t,a)}break;case 1:var r=n.stateNode;if(typeof r.componentDidMount==="function"){var l=n.return;try{r.componentDidMount()}catch(a){G(n,l,a)}}var u=n.return;try{Do(n)}catch(a){G(n,u,a)}break;case 5:var o=n.return;try{Do(n)}catch(a){G(n,o,a)}}}catch(a){G(n,n.return,a)}if(n===e){N=null;break}var i=n.sibling;if(i!==null){i.return=n.return,N=i;break}N=n.return}}function fe(){return(L&6)!==0?Z():vl!==-1?vl:vl=Z()}function gn(e){if((e.mode&1)===0)return 1;if((L&2)!==0&&ne!==0)return ne&-ne;if(M0.transition!==null)return hl===0&&(hl=Ts()),hl;if(e=O,e!==0)return e;return e=window.event,e=e===void 0?16:Os(e.type),e}function Oe(e,n,t,r){if(50<nr)throw nr=0,Fo=null,Error(w(185));if(Sr(e,t,r),(L&2)===0||e!==b)e===b&&((L&2)===0&&(ql|=t),x===4&&sn(e,ne)),ye(e,r),t===1&&L===0&&(n.mode&1)===0&&(Et=Z()+500,Xl&&_n())}function ye(e,n){var t=e.callbackNode;Lp(e,n);var r=kl(e,e===b?ne:0);if(r===0)t!==null&&sa(t),e.callbackNode=null,e.callbackPriority=0;else if(n=r&-r,e.callbackPriority!==n){if(t!=null&&sa(t),n===1)e.tag===0?D0(es.bind(null,e)):ef(es.bind(null,e)),z0(function(){(L&6)===0&&_n()}),t=null;else{switch(Rs(r)){case 1:t=Ko;break;case 4:t=zs;break;case 16:t=wl;break;case 536870912:t=Ps;break;default:t=wl}t=bf(t,Xf.bind(null,e))}e.callbackPriority=n,e.callbackNode=t}}function Xf(e,n){if(vl=-1,hl=0,(L&6)!==0)throw Error(w(327));var t=e.callbackNode;if(ht()&&e.callbackNode!==t)return null;var r=kl(e,e===b?ne:0);if(r===0)return null;if((r&30)!==0||(r&e.expiredLanes)!==0||n)n=$l(e,r);else{n=r;var l=L;L|=2;var u=Zf();if(b!==e||ne!==n)Xe=null,Et=Z()+500,Fn(e,n);do try{x0();break}catch(i){Gf(e,i)}while(1);ri(),Ul.current=u,L=l,J!==null?n=0:(b=null,ne=0,n=x)}if(n!==0){if(n===2&&(l=lo(e),l!==0&&(r=l,n=Oo(e,l))),n===1)throw t=gr,Fn(e,0),sn(e,r),ye(e,Z()),t;if(n===6)sn(e,r);else{if(l=e.current.alternate,(r&30)===0&&!J0(l)&&(n=$l(e,r),n===2&&(u=lo(e),u!==0&&(r=u,n=Oo(e,u))),n===1))throw t=gr,Fn(e,0),sn(e,r),ye(e,Z()),t;switch(e.finishedWork=l,e.finishedLanes=r,n){case 0:case 1:throw Error(w(345));case 2:Dn(e,de,Xe);break;case 3:if(sn(e,r),(r&130023424)===r&&(n=gi+500-Z(),10<n)){if(kl(e,0)!==0)break;if(l=e.suspendedLanes,(l&r)!==r){fe(),e.pingedLanes|=e.suspendedLanes&l;break}e.timeoutHandle=ho(Dn.bind(null,e,de,Xe),n);break}Dn(e,de,Xe);break;case 4:if(sn(e,r),(r&4194240)===r)break;n=e.eventTimes;for(l=-1;0<r;){var o=31-Fe(r);u=1<<o,o=n[o],o>l&&(l=o),r&=~u}if(r=l,r=Z()-r,r=(120>r?120:480>r?480:1080>r?1080:1920>r?1920:3000>r?3000:4320>r?4320:1960*Z0(r/1960))-r,10<r){e.timeoutHandle=ho(Dn.bind(null,e,de,Xe),r);break}Dn(e,de,Xe);break;case 5:Dn(e,de,Xe);break;default:throw Error(w(329))}}}return ye(e,Z()),e.callbackNode===t?Xf.bind(null,e):null}function Oo(e,n){var t=er;return e.current.memoizedState.isDehydrated&&(Fn(e,n).flags|=256),e=$l(e,n),e!==2&&(n=de,de=t,n!==null&&Uo(n)),e}function Uo(e){de===null?de=e:de.push.apply(de,e)}function J0(e){for(var n=e;;){if(n.flags&16384){var t=n.updateQueue;if(t!==null&&(t=t.stores,t!==null))for(var r=0;r<t.length;r++){var l=t[r],u=l.getSnapshot;l=l.value;try{if(!Ue(u(),l))return!1}catch(o){return!1}}}if(t=n.child,n.subtreeFlags&16384&&t!==null)t.return=n,n=t;else{if(n===e)break;for(;n.sibling===null;){if(n.return===null||n.return===e)return!0;n=n.return}n.sibling.return=n.return,n=n.sibling}}return!0}function sn(e,n){n&=~mi,n&=~ql,e.suspendedLanes|=n,e.pingedLanes&=~n;for(e=e.expirationTimes;0<n;){var t=31-Fe(n),r=1<<t;e[t]=-1,n&=~r}}function es(e){if((L&6)!==0)throw Error(w(327));ht();var n=kl(e,0);if((n&1)===0)return ye(e,Z()),null;var t=$l(e,n);if(e.tag!==0&&t===2){var r=lo(e);r!==0&&(n=r,t=Oo(e,r))}if(t===1)throw t=gr,Fn(e,0),sn(e,n),ye(e,Z()),t;if(t===6)throw Error(w(345));return e.finishedWork=e.current.alternate,e.finishedLanes=n,Dn(e,de,Xe),ye(e,Z()),null}function Si(e,n){var t=L;L|=1;try{return e(n)}finally{L=t,L===0&&(Et=Z()+500,Xl&&_n())}}function Qn(e){cn!==null&&cn.tag===0&&(L&6)===0&&ht();var n=L;L|=1;var t=Ne.transition,r=O;try{if(Ne.transition=null,O=1,e)return e()}finally{O=r,Ne.transition=t,L=n,(L&6)===0&&_n()}}function wi(){me=st.current,B(st)}function Fn(e,n){e.finishedWork=null,e.finishedLanes=0;var t=e.timeoutHandle;if(t!==-1&&(e.timeoutHandle=-1,N0(t)),J!==null)for(t=J.return;t!==null;){var r=t;switch(ei(r),r.tag){case 1:r=r.type.childContextTypes,r!==null&&r!==void 0&&zl();break;case 3:wt(),B(ve),B(ie),si();break;case 5:ai(r);break;case 4:wt();break;case 13:B(K);break;case 19:B(K);break;case 10:li(r.type._context);break;case 22:case 23:wi()}t=t.return}if(b=e,J=e=Sn(e.current,null),ne=me=n,x=0,gr=null,mi=ql=$n=0,de=er=null,In!==null){for(n=0;n<In.length;n++)if(t=In[n],r=t.interleaved,r!==null){t.interleaved=null;var l=r.next,u=t.pending;if(u!==null){var o=u.next;u.next=l,r.next=o}t.pending=r}In=null}return e}function Gf(e,n){do{var t=J;try{if(ri(),cl.current=Ol,Fl){for(var r=Y.memoizedState;r!==null;){var l=r.queue;l!==null&&(l.pending=null),r=r.next}Fl=!1}if(Bn=0,j=q=Y=null,jt=!1,hr=0,yi.current=null,t===null||t.return===null){x=1,gr=n,J=null;break}e:{var u=e,o=t.return,i=t,a=n;if(n=ne,i.flags|=32768,a!==null&&typeof a==="object"&&typeof a.then==="function"){var c=a,y=i,g=y.tag;if((y.mode&1)===0&&(g===0||g===11||g===15)){var m=y.alternate;m?(y.updateQueue=m.updateQueue,y.memoizedState=m.memoizedState,y.lanes=m.lanes):(y.updateQueue=null,y.memoizedState=null)}var k=Ha(o);if(k!==null){k.flags&=-257,Wa(k,o,i,u,n),k.mode&1&&Qa(u,c,n),n=k,a=c;var C=n.updateQueue;if(C===null){var E=new Set;E.add(a),n.updateQueue=E}else C.add(a);break e}else{if((n&1)===0){Qa(u,c,n),ki();break e}a=Error(w(426))}}else if($&&i.mode&1){var W=Ha(o);if(W!==null){(W.flags&65536)===0&&(W.flags|=256),Wa(W,o,i,u,n),ni(kt(a,i));break e}}u=a=kt(a,i),x!==4&&(x=2),er===null?er=[u]:er.push(u),u=o;do{switch(u.tag){case 3:u.flags|=65536,n&=-n,u.lanes|=n;var d=Df(u,a,n);Fa(u,d);break e;case 1:i=a;var{type:f,stateNode:p}=u;if((u.flags&128)===0&&(typeof f.getDerivedStateFromError==="function"||p!==null&&typeof p.componentDidCatch==="function"&&(mn===null||!mn.has(p)))){u.flags|=65536,n&=-n,u.lanes|=n;var S=Mf(u,i,n);Fa(u,S);break e}}u=u.return}while(u!==null)}qf(t)}catch(z){n=z,J===t&&t!==null&&(J=t=t.return);continue}break}while(1)}function Zf(){var e=Ul.current;return Ul.current=Ol,e===null?Ol:e}function ki(){if(x===0||x===3||x===2)x=4;b===null||($n&268435455)===0&&(ql&268435455)===0||sn(b,ne)}function $l(e,n){var t=L;L|=2;var r=Zf();if(b!==e||ne!==n)Xe=null,Fn(e,n);do try{q0();break}catch(l){Gf(e,l)}while(1);if(ri(),L=t,Ul.current=r,J!==null)throw Error(w(261));return b=null,ne=0,x}function q0(){for(;J!==null;)Jf(J)}function x0(){for(;J!==null&&!_p();)Jf(J)}function Jf(e){var n=jf(e.alternate,e,me);e.memoizedProps=e.pendingProps,n===null?qf(e):J=n,yi.current=null}function qf(e){var n=e;do{var t=n.alternate;if(e=n.return,(n.flags&32768)===0){if(t=A0(t,n,me),t!==null){J=t;return}}else{if(t=K0(t,n),t!==null){t.flags&=32767,J=t;return}if(e!==null)e.flags|=32768,e.subtreeFlags=0,e.deletions=null;else{x=6,J=null;return}}if(n=n.sibling,n!==null){J=n;return}J=n=e}while(n!==null);x===0&&(x=5)}function Dn(e,n,t){var r=O,l=Ne.transition;try{Ne.transition=null,O=1,j0(e,n,t,r)}finally{Ne.transition=l,O=r}return null}function j0(e,n,t,r){do ht();while(cn!==null);if((L&6)!==0)throw Error(w(327));t=e.finishedWork;var l=e.finishedLanes;if(t===null)return null;if(e.finishedWork=null,e.finishedLanes=0,t===e.current)throw Error(w(177));e.callbackNode=null,e.callbackPriority=0;var u=t.lanes|t.childLanes;if(Fp(e,u),e===b&&(J=b=null,ne=0),(t.subtreeFlags&2064)===0&&(t.flags&2064)===0||ul||(ul=!0,bf(wl,function(){return ht(),null})),u=(t.flags&15990)!==0,(t.subtreeFlags&15990)!==0||u){u=Ne.transition,Ne.transition=null;var o=O;O=1;var i=L;L|=4,yi.current=null,X0(e,t),Kf(t,e),w0(po),El=!!co,po=co=null,e.current=t,G0(t,e,l),Np(),L=i,O=o,Ne.transition=u}else e.current=t;if(ul&&(ul=!1,cn=e,Bl=l),u=e.pendingLanes,u===0&&(mn=null),Tp(t.stateNode,r),ye(e,Z()),n!==null)for(r=e.onRecoverableError,t=0;t<n.length;t++)l=n[t],r(l.value,{componentStack:l.stack,digest:l.digest});if(Vl)throw Vl=!1,e=Lo,Lo=null,e;return(Bl&1)!==0&&e.tag!==0&&ht(),u=e.pendingLanes,(u&1)!==0?e===Fo?nr++:(nr=0,Fo=e):nr=0,_n(),null}function ht(){if(cn!==null){var e=Rs(Bl),n=Ne.transition,t=O;try{if(Ne.transition=null,O=16>e?16:e,cn===null)var r=!1;else{if(e=cn,cn=null,Bl=0,(L&6)!==0)throw Error(w(331));var l=L;L|=4;for(N=e.current;N!==null;){var u=N,o=u.child;if((N.flags&16)!==0){var i=u.deletions;if(i!==null){for(var a=0;a<i.length;a++){var c=i[a];for(N=c;N!==null;){var y=N;switch(y.tag){case 0:case 11:case 15:bt(8,y,u)}var g=y.child;if(g!==null)g.return=y,N=g;else for(;N!==null;){y=N;var{sibling:m,return:k}=y;if(Hf(y),y===c){N=null;break}if(m!==null){m.return=k,N=m;break}N=k}}}var C=u.alternate;if(C!==null){var E=C.child;if(E!==null){C.child=null;do{var W=E.sibling;E.sibling=null,E=W}while(E!==null)}}N=u}}if((u.subtreeFlags&2064)!==0&&o!==null)o.return=u,N=o;else e:for(;N!==null;){if(u=N,(u.flags&2048)!==0)switch(u.tag){case 0:case 11:case 15:bt(9,u,u.return)}var d=u.sibling;if(d!==null){d.return=u.return,N=d;break e}N=u.return}}var f=e.current;for(N=f;N!==null;){o=N;var p=o.child;if((o.subtreeFlags&2064)!==0&&p!==null)p.return=o,N=p;else e:for(o=f;N!==null;){if(i=N,(i.flags&2048)!==0)try{switch(i.tag){case 0:case 11:case 15:Jl(9,i)}}catch(z){G(i,i.return,z)}if(i===o){N=null;break e}var S=i.sibling;if(S!==null){S.return=i.return,N=S;break e}N=i.return}}if(L=l,_n(),We&&typeof We.onPostCommitFiberRoot==="function")try{We.onPostCommitFiberRoot(Hl,e)}catch(z){}r=!0}return r}finally{O=t,Ne.transition=n}}return!1}function ns(e,n,t){n=kt(t,n),n=Df(e,n,1),e=yn(e,n,1),n=fe(),e!==null&&(Sr(e,1,n),ye(e,n))}function G(e,n,t){if(e.tag===3)ns(e,e,t);else for(;n!==null;){if(n.tag===3){ns(n,e,t);break}else if(n.tag===1){var r=n.stateNode;if(typeof n.type.getDerivedStateFromError==="function"||typeof r.componentDidCatch==="function"&&(mn===null||!mn.has(r))){e=kt(t,e),e=Mf(n,e,1),n=yn(n,e,1),e=fe(),n!==null&&(Sr(n,1,e),ye(n,e));break}}n=n.return}}function b0(e,n,t){var r=e.pingCache;r!==null&&r.delete(n),n=fe(),e.pingedLanes|=e.suspendedLanes&t,b===e&&(ne&t)===t&&(x===4||x===3&&(ne&130023424)===ne&&500>Z()-gi?Fn(e,0):mi|=t),ye(e,n)}function xf(e,n){n===0&&((e.mode&1)===0?n=1:(n=Jr,Jr<<=1,(Jr&130023424)===0&&(Jr=4194304)));var t=fe();e=be(e,n),e!==null&&(Sr(e,n,t),ye(e,t))}function ev(e){var n=e.memoizedState,t=0;n!==null&&(t=n.retryLane),xf(e,t)}function nv(e,n){var t=0;switch(e.tag){case 13:var{stateNode:r,memoizedState:l}=e;l!==null&&(t=l.retryLane);break;case 19:r=e.stateNode;break;default:throw Error(w(314))}r!==null&&r.delete(n),xf(e,t)}function bf(e,n){return Ns(e,n)}function tv(e,n,t,r){this.tag=e,this.key=t,this.sibling=this.child=this.return=this.stateNode=this.type=this.elementType=null,this.index=0,this.ref=null,this.pendingProps=n,this.dependencies=this.memoizedState=this.updateQueue=this.memoizedProps=null,this.mode=r,this.subtreeFlags=this.flags=0,this.deletions=null,this.childLanes=this.lanes=0,this.alternate=null}function _e(e,n,t,r){return new tv(e,n,t,r)}function Ei(e){return e=e.prototype,!(!e||!e.isReactComponent)}function rv(e){if(typeof e==="function")return Ei(e)?1:0;if(e!==void 0&&e!==null){if(e=e.$$typeof,e===Ho)return 11;if(e===Wo)return 14}return 2}function Sn(e,n){var t=e.alternate;return t===null?(t=_e(e.tag,n,e.key,e.mode),t.elementType=e.elementType,t.type=e.type,t.stateNode=e.stateNode,t.alternate=e,e.alternate=t):(t.pendingProps=n,t.type=e.type,t.flags=0,t.subtreeFlags=0,t.deletions=null),t.flags=e.flags&14680064,t.childLanes=e.childLanes,t.lanes=e.lanes,t.child=e.child,t.memoizedProps=e.memoizedProps,t.memoizedState=e.memoizedState,t.updateQueue=e.updateQueue,n=e.dependencies,t.dependencies=n===null?null:{lanes:n.lanes,firstContext:n.firstContext},t.sibling=e.sibling,t.index=e.index,t.ref=e.ref,t}function yl(e,n,t,r,l,u){var o=2;if(r=e,typeof e==="function")Ei(e)&&(o=1);else if(typeof e==="string")o=5;else e:switch(e){case bn:return On(t.children,l,u,n);case Qo:o=8,l|=8;break;case Au:return e=_e(12,t,n,l|2),e.elementType=Au,e.lanes=u,e;case Ku:return e=_e(13,t,n,l),e.elementType=Ku,e.lanes=u,e;case Yu:return e=_e(19,t,n,l),e.elementType=Yu,e.lanes=u,e;case as:return xl(t,l,u,n);default:if(typeof e==="object"&&e!==null)switch(e.$$typeof){case os:o=10;break e;case is:o=9;break e;case Ho:o=11;break e;case Wo:o=14;break e;case un:o=16,r=null;break e}throw Error(w(130,e==null?e:typeof e,""))}return n=_e(o,t,n,l),n.elementType=e,n.type=r,n.lanes=u,n}function On(e,n,t,r){return e=_e(7,e,r,n),e.lanes=t,e}function xl(e,n,t,r){return e=_e(22,e,r,n),e.elementType=as,e.lanes=t,e.stateNode={isHidden:!1},e}function Qu(e,n,t){return e=_e(6,e,null,n),e.lanes=t,e}function Hu(e,n,t){return n=_e(4,e.children!==null?e.children:[],e.key,n),n.lanes=t,n.stateNode={containerInfo:e.containerInfo,pendingChildren:null,implementation:e.implementation},n}function lv(e,n,t,r,l){this.tag=n,this.containerInfo=e,this.finishedWork=this.pingCache=this.current=this.pendingChildren=null,this.timeoutHandle=-1,this.callbackNode=this.pendingContext=this.context=null,this.callbackPriority=0,this.eventTimes=Nu(0),this.expirationTimes=Nu(-1),this.entangledLanes=this.finishedLanes=this.mutableReadLanes=this.expiredLanes=this.pingedLanes=this.suspendedLanes=this.pendingLanes=0,this.entanglements=Nu(0),this.identifierPrefix=r,this.onRecoverableError=l,this.mutableSourceEagerHydrationData=null}function Ci(e,n,t,r,l,u,o,i,a){return e=new lv(e,n,t,i,a),n===1?(n=1,u===!0&&(n|=8)):n=0,u=_e(3,null,null,n),e.current=u,u.stateNode=e,u.memoizedState={element:r,isDehydrated:t,cache:null,transitions:null,pendingSuspenseBoundaries:null},oi(u),e}function uv(e,n,t){var r=3<arguments.length&&arguments[3]!==void 0?arguments[3]:null;return{$$typeof:jn,key:r==null?null:""+r,children:e,containerInfo:n,implementation:t}}function ec(e){if(!e)return kn;e=e._reactInternals;e:{if(Wn(e)!==e||e.tag!==1)throw Error(w(170));var n=e;do{switch(n.tag){case 3:n=n.stateNode.context;break e;case 1:if(he(n.type)){n=n.stateNode.__reactInternalMemoizedMergedChildContext;break e}}n=n.return}while(n!==null);throw Error(w(171))}if(e.tag===1){var t=e.type;if(he(t))return bs(e,t,n)}return n}function nc(e,n,t,r,l,u,o,i,a){return e=Ci(t,r,!0,e,l,u,o,i,a),e.context=ec(null),t=e.current,r=fe(),l=gn(t),u=qe(r,l),u.callback=n!==void 0&&n!==null?n:null,yn(t,u,l),e.current.lanes=l,Sr(e,l,r),ye(e,r),e}function jl(e,n,t,r){var l=n.current,u=fe(),o=gn(l);return t=ec(t),n.context===null?n.context=t:n.pendingContext=t,n=qe(u,o),n.payload={element:e},r=r===void 0?null:r,r!==null&&(n.callback=r),e=yn(l,n,o),e!==null&&(Oe(e,l,o,u),fl(e,l,o)),o}function Ql(e){if(e=e.current,!e.child)return null;switch(e.child.tag){case 5:return e.child.stateNode;default:return e.child.stateNode}}function ts(e,n){if(e=e.memoizedState,e!==null&&e.dehydrated!==null){var t=e.retryLane;e.retryLane=t!==0&&t<n?t:n}}function _i(e,n){ts(e,n),(e=e.alternate)&&ts(e,n)}function ov(){return null}function Ni(e){this._internalRoot=e}function bl(e){this._internalRoot=e}function zi(e){return!(!e||e.nodeType!==1&&e.nodeType!==9&&e.nodeType!==11)}function eu(e){return!(!e||e.nodeType!==1&&e.nodeType!==9&&e.nodeType!==11&&(e.nodeType!==8||e.nodeValue!==" react-mount-point-unstable "))}function rs(){}function iv(e,n,t,r,l){if(l){if(typeof r==="function"){var u=r;r=function(){var c=Ql(o);u.call(c)}}var o=nc(n,r,e,0,null,!1,!1,"",rs);return e._reactRootContainer=o,e[je]=o.current,fr(e.nodeType===8?e.parentNode:e),Qn(),o}for(;l=e.lastChild;)e.removeChild(l);if(typeof r==="function"){var i=r;r=function(){var c=Ql(a);i.call(c)}}var a=Ci(e,0,!1,null,null,!1,!1,"",rs);return e._reactRootContainer=a,e[je]=a.current,fr(e.nodeType===8?e.parentNode:e),Qn(function(){jl(n,a,t,r)}),a}function nu(e,n,t,r,l){var u=t._reactRootContainer;if(u){var o=u;if(typeof l==="function"){var i=l;l=function(){var a=Ql(o);i.call(a)}}jl(n,o,e,l)}else o=iv(t,n,e,l,r);return Ql(o)}var ls,Q,us,tr,xe,Wu,fp,ea,na,te,Vo,nn,Yr,jn,bn,Qo,Au,os,is,Ho,Ku,Yu,Wo,un,as,ta,X,ku,Eu=!1,Qt,Gr,vs,Gt,mp,gp,eo=null,no=null,ct=null,dt=null,_u=!1,to=!1,Tn,Zt=!1,gl=null,Sl=!1,ro=null,wp,Ns,sa,_p,Np,Z,zp,Ko,zs,wl,Pp,Ps,Hl=null,We=null,Fe,Rp,Dp,Zr=64,Jr=4194304,O=0,Ds,Xo,Ms,Is,Ls,uo=!1,qr,dn=null,pn=null,vn=null,ur,or,an,Op,pt,El=!0,Cl=null,fn=null,Zo=null,il=null,Ct,Jo,wr,Qp,zu,Pu,Ot,Wl,pa,Hp,Wp,Ap,Tu,Kp,Yp,Xp,Gp,Zp,va,Jp,qp,xp,bp,e0,n0,ha,t0,r0,l0,u0,o0,i0,a0,xo,Jt=null,s0,Vs,ya,ma=!1,et=!1,d0,qt=null,ar=null,Hs=!1,Wt,At,sl,Ue,k0,nt=null,io=null,xt=null,ao=!1,tt,Ru,Ys,Xs,Gs,Zs,Js,qs,Ca,Yt,so,fo,Kt,Xt,E0,br,C0,_0,co=null,po=null,ho,N0,Pa,z0,_t,He,dr,je,yo,T0,R0,mo,lt=-1,kn,ie,ve,Un,Ge=null,Xl=!1,Lu=!1,ut,ot=0,Tl=null,Rl=0,Ee,Ce=0,Vn=null,Ze=1,Je="",Se=null,ge=null,$=!1,Le=null,M0,St,uf,Dl,Ml=null,it=null,ti=null,In=null,on=!1,Er,Ae,pr,vr,K,Fu,cl,Ou,Bn=0,Y=null,q=null,j=null,Fl=!1,jt=!1,hr=0,I0=0,Ol,U0,V0,B0,Zl,$0,Q0,pe=!1,zo,Bf,To,$f,Qf,ll=!1,oe=!1,Y0,N=null,Za=!1,ee=null,Ie=!1,Z0,Ul,yi,Ne,L=0,b=null,J=null,ne=0,me=0,st,x=0,gr=null,$n=0,ql=0,mi=0,er=null,de=null,gi=0,Et=1/0,Xe=null,Vl=!1,Lo=null,mn=null,ul=!1,cn=null,Bl=0,nr=0,Fo=null,vl=-1,hl=0,jf,tc,av,Bt,sv,xn,rc,lc=function(e,n){var t=2<arguments.length&&arguments[2]!==void 0?arguments[2]:null;if(!zi(n))throw Error(w(200));return uv(e,n,null,t)},uc=function(e,n){if(!zi(e))throw Error(w(299));var t=!1,r="",l=tc;return n!==null&&n!==void 0&&(n.unstable_strictMode===!0&&(t=!0),n.identifierPrefix!==void 0&&(r=n.identifierPrefix),n.onRecoverableError!==void 0&&(l=n.onRecoverableError)),n=Ci(e,1,!1,null,null,t,!1,r,l),e[je]=n.current,fr(e.nodeType===8?e.parentNode:e),new Ni(n)},oc=function(e){if(e==null)return null;if(e.nodeType===1)return e;var n=e._reactInternals;if(n===void 0){if(typeof e.render==="function")throw Error(w(188));throw e=Object.keys(e).join(","),Error(w(268,e))}return e=Cs(n),e=e===null?null:e.stateNode,e},ic=function(e){return Qn(e)},ac=function(e,n,t){if(!eu(n))throw Error(w(200));return nu(null,e,n,!0,t)},sc=function(e,n,t){if(!zi(e))throw Error(w(405));var r=t!=null&&t.hydratedSources||null,l=!1,u="",o=tc;if(t!==null&&t!==void 0&&(t.unstable_strictMode===!0&&(l=!0),t.identifierPrefix!==void 0&&(u=t.identifierPrefix),t.onRecoverableError!==void 0&&(o=t.onRecoverableError)),n=nc(n,null,e,1,t!=null?t:null,l,!1,u,o),e[je]=n.current,fr(e),r)for(e=0;e<r.length;e++)t=r[e],l=t._getVersion,l=l(t._source),n.mutableSourceEagerHydrationData==null?n.mutableSourceEagerHydrationData=[t,l]:n.mutableSourceEagerHydrationData.push(t,l);return new bl(n)},fc=function(e,n,t){if(!eu(n))throw Error(w(200));return nu(null,e,n,!1,t)},cc=function(e){if(!eu(e))throw Error(w(40));return e._reactRootContainer?(Qn(function(){nu(null,null,e,!1,function(){e._reactRootContainer=null,e[je]=null})}),!0):!1},dc,pc=function(e,n,t,r){if(!eu(t))throw Error(w(200));if(e==null||e._reactInternals===void 0)throw Error(w(38));return nu(e,n,t,!1,r)},vc="18.3.1-next-f1338f8080-20240426";var hc=Yc(()=>{ls=Ye(zn(),1),Q=Ye(bi(),1);us=new Set,tr={};xe=!(typeof window>"u"||typeof window.document>"u"||typeof window.document.createElement>"u"),Wu=Object.prototype.hasOwnProperty,fp=/^[:A-Z_a-z\u00C0-\u00D6\u00D8-\u00F6\u00F8-\u02FF\u0370-\u037D\u037F-\u1FFF\u200C-\u200D\u2070-\u218F\u2C00-\u2FEF\u3001-\uD7FF\uF900-\uFDCF\uFDF0-\uFFFD][:A-Z_a-z\u00C0-\u00D6\u00D8-\u00F6\u00F8-\u02FF\u0370-\u037D\u037F-\u1FFF\u200C-\u200D\u2070-\u218F\u2C00-\u2FEF\u3001-\uD7FF\uF900-\uFDCF\uFDF0-\uFFFD\-.0-9\u00B7\u0300-\u036F\u203F-\u2040]*$/,ea={},na={};te={};"children dangerouslySetInnerHTML defaultValue defaultChecked innerHTML suppressContentEditableWarning suppressHydrationWarning style".split(" ").forEach(function(e){te[e]=new ce(e,0,!1,e,null,!1,!1)});[["acceptCharset","accept-charset"],["className","class"],["htmlFor","for"],["httpEquiv","http-equiv"]].forEach(function(e){var n=e[0];te[n]=new ce(n,1,!1,e[1],null,!1,!1)});["contentEditable","draggable","spellCheck","value"].forEach(function(e){te[e]=new ce(e,2,!1,e.toLowerCase(),null,!1,!1)});["autoReverse","externalResourcesRequired","focusable","preserveAlpha"].forEach(function(e){te[e]=new ce(e,2,!1,e,null,!1,!1)});"allowFullScreen async autoFocus autoPlay controls default defer disabled disablePictureInPicture disableRemotePlayback formNoValidate hidden loop noModule noValidate open playsInline readOnly required reversed scoped seamless itemScope".split(" ").forEach(function(e){te[e]=new ce(e,3,!1,e.toLowerCase(),null,!1,!1)});["checked","multiple","muted","selected"].forEach(function(e){te[e]=new ce(e,3,!0,e,null,!1,!1)});["capture","download"].forEach(function(e){te[e]=new ce(e,4,!1,e,null,!1,!1)});["cols","rows","size","span"].forEach(function(e){te[e]=new ce(e,6,!1,e,null,!1,!1)});["rowSpan","start"].forEach(function(e){te[e]=new ce(e,5,!1,e.toLowerCase(),null,!1,!1)});Vo=/[\-:]([a-z])/g;"accent-height alignment-baseline arabic-form baseline-shift cap-height clip-path clip-rule color-interpolation color-interpolation-filters color-profile color-rendering dominant-baseline enable-background fill-opacity fill-rule flood-color flood-opacity font-family font-size font-size-adjust font-stretch font-style font-variant font-weight glyph-name glyph-orientation-horizontal glyph-orientation-vertical horiz-adv-x horiz-origin-x image-rendering letter-spacing lighting-color marker-end marker-mid marker-start overline-position overline-thickness paint-order panose-1 pointer-events rendering-intent shape-rendering stop-color stop-opacity strikethrough-position strikethrough-thickness stroke-dasharray stroke-dashoffset stroke-linecap stroke-linejoin stroke-miterlimit stroke-opacity stroke-width text-anchor text-decoration text-rendering underline-position underline-thickness unicode-bidi unicode-range units-per-em v-alphabetic v-hanging v-ideographic v-mathematical vector-effect vert-adv-y vert-origin-x vert-origin-y word-spacing writing-mode xmlns:xlink x-height".split(" ").forEach(function(e){var n=e.replace(Vo,Bo);te[n]=new ce(n,1,!1,e,null,!1,!1)});"xlink:actuate xlink:arcrole xlink:role xlink:show xlink:title xlink:type".split(" ").forEach(function(e){var n=e.replace(Vo,Bo);te[n]=new ce(n,1,!1,e,"http://www.w3.org/1999/xlink",!1,!1)});["xml:base","xml:lang","xml:space"].forEach(function(e){var n=e.replace(Vo,Bo);te[n]=new ce(n,1,!1,e,"http://www.w3.org/XML/1998/namespace",!1,!1)});["tabIndex","crossOrigin"].forEach(function(e){te[e]=new ce(e,1,!1,e.toLowerCase(),null,!1,!1)});te.xlinkHref=new ce("xlinkHref",1,!1,"xlink:href","http://www.w3.org/1999/xlink",!0,!1);["src","href","action","formAction"].forEach(function(e){te[e]=new ce(e,1,!1,e.toLowerCase(),null,!0,!0)});nn=ls.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED,Yr=Symbol.for("react.element"),jn=Symbol.for("react.portal"),bn=Symbol.for("react.fragment"),Qo=Symbol.for("react.strict_mode"),Au=Symbol.for("react.profiler"),os=Symbol.for("react.provider"),is=Symbol.for("react.context"),Ho=Symbol.for("react.forward_ref"),Ku=Symbol.for("react.suspense"),Yu=Symbol.for("react.suspense_list"),Wo=Symbol.for("react.memo"),un=Symbol.for("react.lazy"),as=Symbol.for("react.offscreen"),ta=Symbol.iterator;X=Object.assign;Qt=Array.isArray;vs=function(e){return typeof MSApp<"u"&&MSApp.execUnsafeLocalFunction?function(n,t,r,l){MSApp.execUnsafeLocalFunction(function(){return e(n,t,r,l)})}:e}(function(e,n){if(e.namespaceURI!=="http://www.w3.org/2000/svg"||"innerHTML"in e)e.innerHTML=n;else{Gr=Gr||document.createElement("div"),Gr.innerHTML="<svg>"+n.valueOf().toString()+"</svg>";for(n=Gr.firstChild;e.firstChild;)e.removeChild(e.firstChild);for(;n.firstChild;)e.appendChild(n.firstChild)}});Gt={animationIterationCount:!0,aspectRatio:!0,borderImageOutset:!0,borderImageSlice:!0,borderImageWidth:!0,boxFlex:!0,boxFlexGroup:!0,boxOrdinalGroup:!0,columnCount:!0,columns:!0,flex:!0,flexGrow:!0,flexPositive:!0,flexShrink:!0,flexNegative:!0,flexOrder:!0,gridArea:!0,gridRow:!0,gridRowEnd:!0,gridRowSpan:!0,gridRowStart:!0,gridColumn:!0,gridColumnEnd:!0,gridColumnSpan:!0,gridColumnStart:!0,fontWeight:!0,lineClamp:!0,lineHeight:!0,opacity:!0,order:!0,orphans:!0,tabSize:!0,widows:!0,zIndex:!0,zoom:!0,fillOpacity:!0,floodOpacity:!0,stopOpacity:!0,strokeDasharray:!0,strokeDashoffset:!0,strokeMiterlimit:!0,strokeOpacity:!0,strokeWidth:!0},mp=["Webkit","ms","Moz","O"];Object.keys(Gt).forEach(function(e){mp.forEach(function(n){n=n+e.charAt(0).toUpperCase()+e.substring(1),Gt[n]=Gt[e]})});gp=X({menuitem:!0},{area:!0,base:!0,br:!0,col:!0,embed:!0,hr:!0,img:!0,input:!0,keygen:!0,link:!0,meta:!0,param:!0,source:!0,track:!0,wbr:!0});if(xe)try{Tn={},Object.defineProperty(Tn,"passive",{get:function(){to=!0}}),window.addEventListener("test",Tn,Tn),window.removeEventListener("test",Tn,Tn)}catch(e){to=!1}wp={onError:function(e){Zt=!0,gl=e}};Ns=Q.unstable_scheduleCallback,sa=Q.unstable_cancelCallback,_p=Q.unstable_shouldYield,Np=Q.unstable_requestPaint,Z=Q.unstable_now,zp=Q.unstable_getCurrentPriorityLevel,Ko=Q.unstable_ImmediatePriority,zs=Q.unstable_UserBlockingPriority,wl=Q.unstable_NormalPriority,Pp=Q.unstable_LowPriority,Ps=Q.unstable_IdlePriority;Fe=Math.clz32?Math.clz32:Mp,Rp=Math.log,Dp=Math.LN2;qr=[],ur=new Map,or=new Map,an=[],Op="mousedown mouseup touchcancel touchend touchstart auxclick dblclick pointercancel pointerdown pointerup dragend dragstart drop compositionend compositionstart keydown keypress keyup input textInput copy cut paste click change contextmenu reset submit".split(" ");pt=nn.ReactCurrentBatchConfig;Ct={eventPhase:0,bubbles:0,cancelable:0,timeStamp:function(e){return e.timeStamp||Date.now()},defaultPrevented:0,isTrusted:0},Jo=we(Ct),wr=X({},Ct,{view:0,detail:0}),Qp=we(wr),Wl=X({},wr,{screenX:0,screenY:0,clientX:0,clientY:0,pageX:0,pageY:0,ctrlKey:0,shiftKey:0,altKey:0,metaKey:0,getModifierState:qo,button:0,buttons:0,relatedTarget:function(e){return e.relatedTarget===void 0?e.fromElement===e.srcElement?e.toElement:e.fromElement:e.relatedTarget},movementX:function(e){if("movementX"in e)return e.movementX;return e!==Ot&&(Ot&&e.type==="mousemove"?(zu=e.screenX-Ot.screenX,Pu=e.screenY-Ot.screenY):Pu=zu=0,Ot=e),zu},movementY:function(e){return"movementY"in e?e.movementY:Pu}}),pa=we(Wl),Hp=X({},Wl,{dataTransfer:0}),Wp=we(Hp),Ap=X({},wr,{relatedTarget:0}),Tu=we(Ap),Kp=X({},Ct,{animationName:0,elapsedTime:0,pseudoElement:0}),Yp=we(Kp),Xp=X({},Ct,{clipboardData:function(e){return"clipboardData"in e?e.clipboardData:window.clipboardData}}),Gp=we(Xp),Zp=X({},Ct,{data:0}),va=we(Zp),Jp={Esc:"Escape",Spacebar:" ",Left:"ArrowLeft",Up:"ArrowUp",Right:"ArrowRight",Down:"ArrowDown",Del:"Delete",Win:"OS",Menu:"ContextMenu",Apps:"ContextMenu",Scroll:"ScrollLock",MozPrintableKey:"Unidentified"},qp={8:"Backspace",9:"Tab",12:"Clear",13:"Enter",16:"Shift",17:"Control",18:"Alt",19:"Pause",20:"CapsLock",27:"Escape",32:" ",33:"PageUp",34:"PageDown",35:"End",36:"Home",37:"ArrowLeft",38:"ArrowUp",39:"ArrowRight",40:"ArrowDown",45:"Insert",46:"Delete",112:"F1",113:"F2",114:"F3",115:"F4",116:"F5",117:"F6",118:"F7",119:"F8",120:"F9",121:"F10",122:"F11",123:"F12",144:"NumLock",145:"ScrollLock",224:"Meta"},xp={Alt:"altKey",Control:"ctrlKey",Meta:"metaKey",Shift:"shiftKey"};bp=X({},wr,{key:function(e){if(e.key){var n=Jp[e.key]||e.key;if(n!=="Unidentified")return n}return e.type==="keypress"?(e=al(e),e===13?"Enter":String.fromCharCode(e)):e.type==="keydown"||e.type==="keyup"?qp[e.keyCode]||"Unidentified":""},code:0,location:0,ctrlKey:0,shiftKey:0,altKey:0,metaKey:0,repeat:0,locale:0,getModifierState:qo,charCode:function(e){return e.type==="keypress"?al(e):0},keyCode:function(e){return e.type==="keydown"||e.type==="keyup"?e.keyCode:0},which:function(e){return e.type==="keypress"?al(e):e.type==="keydown"||e.type==="keyup"?e.keyCode:0}}),e0=we(bp),n0=X({},Wl,{pointerId:0,width:0,height:0,pressure:0,tangentialPressure:0,tiltX:0,tiltY:0,twist:0,pointerType:0,isPrimary:0}),ha=we(n0),t0=X({},wr,{touches:0,targetTouches:0,changedTouches:0,altKey:0,metaKey:0,ctrlKey:0,shiftKey:0,getModifierState:qo}),r0=we(t0),l0=X({},Ct,{propertyName:0,elapsedTime:0,pseudoElement:0}),u0=we(l0),o0=X({},Wl,{deltaX:function(e){return"deltaX"in e?e.deltaX:("wheelDeltaX"in e)?-e.wheelDeltaX:0},deltaY:function(e){return"deltaY"in e?e.deltaY:("wheelDeltaY"in e)?-e.wheelDeltaY:("wheelDelta"in e)?-e.wheelDelta:0},deltaZ:0,deltaMode:0}),i0=we(o0),a0=[9,13,27,32],xo=xe&&"CompositionEvent"in window;xe&&"documentMode"in document&&(Jt=document.documentMode);s0=xe&&"TextEvent"in window&&!Jt,Vs=xe&&(!xo||Jt&&8<Jt&&11>=Jt),ya=String.fromCharCode(32);d0={color:!0,date:!0,datetime:!0,"datetime-local":!0,email:!0,month:!0,number:!0,password:!0,range:!0,search:!0,tel:!0,text:!0,time:!0,url:!0,week:!0};if(xe){if(xe){if(At="oninput"in document,!At)sl=document.createElement("div"),sl.setAttribute("oninput","return;"),At=typeof sl.oninput==="function";Wt=At}else Wt=!1;Hs=Wt&&(!document.documentMode||9<document.documentMode)}Ue=typeof Object.is==="function"?Object.is:S0;k0=xe&&"documentMode"in document&&11>=document.documentMode;tt={animationend:jr("Animation","AnimationEnd"),animationiteration:jr("Animation","AnimationIteration"),animationstart:jr("Animation","AnimationStart"),transitionend:jr("Transition","TransitionEnd")},Ru={},Ys={};xe&&(Ys=document.createElement("div").style,("AnimationEvent"in window)||(delete tt.animationend.animation,delete tt.animationiteration.animation,delete tt.animationstart.animation),("TransitionEvent"in window)||delete tt.transitionend.transition);Xs=Kl("animationend"),Gs=Kl("animationiteration"),Zs=Kl("animationstart"),Js=Kl("transitionend"),qs=new Map,Ca="abort auxClick cancel canPlay canPlayThrough click close contextMenu copy cut drag dragEnd dragEnter dragExit dragLeave dragOver dragStart drop durationChange emptied encrypted ended error gotPointerCapture input invalid keyDown keyPress keyUp load loadedData loadedMetadata loadStart lostPointerCapture mouseDown mouseMove mouseOut mouseOver mouseUp paste pause play playing pointerCancel pointerDown pointerMove pointerOut pointerOver pointerUp progress rateChange reset resize seeked seeking stalled submit suspend timeUpdate touchCancel touchEnd touchStart volumeChange scroll toggle touchMove waiting wheel".split(" ");for(Kt=0;Kt<Ca.length;Kt++)Yt=Ca[Kt],so=Yt.toLowerCase(),fo=Yt[0].toUpperCase()+Yt.slice(1),En(so,"on"+fo);En(Xs,"onAnimationEnd");En(Gs,"onAnimationIteration");En(Zs,"onAnimationStart");En("dblclick","onDoubleClick");En("focusin","onFocus");En("focusout","onBlur");En(Js,"onTransitionEnd");yt("onMouseEnter",["mouseout","mouseover"]);yt("onMouseLeave",["mouseout","mouseover"]);yt("onPointerEnter",["pointerout","pointerover"]);yt("onPointerLeave",["pointerout","pointerover"]);Hn("onChange","change click focusin focusout input keydown keyup selectionchange".split(" "));Hn("onSelect","focusout contextmenu dragend focusin keydown keyup mousedown mouseup selectionchange".split(" "));Hn("onBeforeInput",["compositionend","keypress","textInput","paste"]);Hn("onCompositionEnd","compositionend focusout keydown keypress keyup mousedown".split(" "));Hn("onCompositionStart","compositionstart focusout keydown keypress keyup mousedown".split(" "));Hn("onCompositionUpdate","compositionupdate focusout keydown keypress keyup mousedown".split(" "));Xt="abort canplay canplaythrough durationchange emptied encrypted ended error loadeddata loadedmetadata loadstart pause play playing progress ratechange resize seeked seeking stalled suspend timeupdate volumechange waiting".split(" "),E0=new Set("cancel close invalid load scroll toggle".split(" ").concat(Xt));br="_reactListening"+Math.random().toString(36).slice(2);C0=/\r\n?/g,_0=/\u0000|\uFFFD/g;ho=typeof setTimeout==="function"?setTimeout:void 0,N0=typeof clearTimeout==="function"?clearTimeout:void 0,Pa=typeof Promise==="function"?Promise:void 0,z0=typeof queueMicrotask==="function"?queueMicrotask:typeof Pa<"u"?function(e){return Pa.resolve(null).then(e).catch(P0)}:ho;_t=Math.random().toString(36).slice(2),He="__reactFiber$"+_t,dr="__reactProps$"+_t,je="__reactContainer$"+_t,yo="__reactEvents$"+_t,T0="__reactListeners$"+_t,R0="__reactHandles$"+_t;mo=[];kn={},ie=Cn(kn),ve=Cn(!1),Un=kn;ut=[],Ee=[];M0=nn.ReactCurrentBatchConfig;St=lf(!0),uf=lf(!1),Dl=Cn(null);Er={},Ae=Cn(Er),pr=Cn(Er),vr=Cn(Er);K=Cn(0);Fu=[];cl=nn.ReactCurrentDispatcher,Ou=nn.ReactCurrentBatchConfig;Ol={readContext:ze,useCallback:le,useContext:le,useEffect:le,useImperativeHandle:le,useInsertionEffect:le,useLayoutEffect:le,useMemo:le,useReducer:le,useRef:le,useState:le,useDebugValue:le,useDeferredValue:le,useTransition:le,useMutableSource:le,useSyncExternalStore:le,useId:le,unstable_isNewReconciler:!1},U0={readContext:ze,useCallback:function(e,n){return Qe().memoizedState=[e,n===void 0?null:n],e},useContext:ze,useEffect:Va,useImperativeHandle:function(e,n,t){return t=t!==null&&t!==void 0?t.concat([e]):null,dl(4194308,4,wf.bind(null,n,e),t)},useLayoutEffect:function(e,n){return dl(4194308,4,e,n)},useInsertionEffect:function(e,n){return dl(4,2,e,n)},useMemo:function(e,n){var t=Qe();return n=n===void 0?null:n,e=e(),t.memoizedState=[e,n],e},useReducer:function(e,n,t){var r=Qe();return n=t!==void 0?t(n):n,r.memoizedState=r.baseState=n,e={pending:null,interleaved:null,lanes:0,dispatch:null,lastRenderedReducer:e,lastRenderedState:n},r.queue=e,e=e.dispatch=F0.bind(null,Y,e),[r.memoizedState,e]},useRef:function(e){var n=Qe();return e={current:e},n.memoizedState=e},useState:Ua,useDebugValue:vi,useDeferredValue:function(e){return Qe().memoizedState=e},useTransition:function(){var e=Ua(!1),n=e[0];return e=L0.bind(null,e[1]),Qe().memoizedState=e,[n,e]},useMutableSource:function(){},useSyncExternalStore:function(e,n,t){var r=Y,l=Qe();if($){if(t===void 0)throw Error(w(407));t=t()}else{if(t=n(),b===null)throw Error(w(349));(Bn&30)!==0||df(r,n,t)}l.memoizedState=t;var u={value:t,getSnapshot:n};return l.queue=u,Va(vf.bind(null,r,u,e),[e]),r.flags|=2048,mr(9,pf.bind(null,r,u,t,n),void 0,null),t},useId:function(){var e=Qe(),n=b.identifierPrefix;if($){var t=Je,r=Ze;t=(r&~(1<<32-Fe(r)-1)).toString(32)+t,n=":"+n+"R"+t,t=hr++,0<t&&(n+="H"+t.toString(32)),n+=":"}else t=I0++,n=":"+n+"r"+t.toString(32)+":";return e.memoizedState=n},unstable_isNewReconciler:!1},V0={readContext:ze,useCallback:Ef,useContext:ze,useEffect:pi,useImperativeHandle:kf,useInsertionEffect:gf,useLayoutEffect:Sf,useMemo:Cf,useReducer:Uu,useRef:mf,useState:function(){return Uu(yr)},useDebugValue:vi,useDeferredValue:function(e){var n=Pe();return _f(n,q.memoizedState,e)},useTransition:function(){var e=Uu(yr)[0],n=Pe().memoizedState;return[e,n]},useMutableSource:ff,useSyncExternalStore:cf,useId:Nf,unstable_isNewReconciler:!1},B0={readContext:ze,useCallback:Ef,useContext:ze,useEffect:pi,useImperativeHandle:kf,useInsertionEffect:gf,useLayoutEffect:Sf,useMemo:Cf,useReducer:Vu,useRef:mf,useState:function(){return Vu(yr)},useDebugValue:vi,useDeferredValue:function(e){var n=Pe();return q===null?n.memoizedState=e:_f(n,q.memoizedState,e)},useTransition:function(){var e=Vu(yr)[0],n=Pe().memoizedState;return[e,n]},useMutableSource:ff,useSyncExternalStore:cf,useId:Nf,unstable_isNewReconciler:!1};Zl={isMounted:function(e){return(e=e._reactInternals)?Wn(e)===e:!1},enqueueSetState:function(e,n,t){e=e._reactInternals;var r=fe(),l=gn(e),u=qe(r,l);u.payload=n,t!==void 0&&t!==null&&(u.callback=t),n=yn(e,u,l),n!==null&&(Oe(n,e,l,r),fl(n,e,l))},enqueueReplaceState:function(e,n,t){e=e._reactInternals;var r=fe(),l=gn(e),u=qe(r,l);u.tag=1,u.payload=n,t!==void 0&&t!==null&&(u.callback=t),n=yn(e,u,l),n!==null&&(Oe(n,e,l,r),fl(n,e,l))},enqueueForceUpdate:function(e,n){e=e._reactInternals;var t=fe(),r=gn(e),l=qe(t,r);l.tag=2,n!==void 0&&n!==null&&(l.callback=n),n=yn(e,l,r),n!==null&&(Oe(n,e,r,t),fl(n,e,r))}};$0=typeof WeakMap==="function"?WeakMap:Map;Q0=nn.ReactCurrentOwner;zo={dehydrated:null,treeContext:null,retryLane:0};Bf=function(e,n){for(var t=n.child;t!==null;){if(t.tag===5||t.tag===6)e.appendChild(t.stateNode);else if(t.tag!==4&&t.child!==null){t.child.return=t,t=t.child;continue}if(t===n)break;for(;t.sibling===null;){if(t.return===null||t.return===n)return;t=t.return}t.sibling.return=t.return,t=t.sibling}};To=function(){};$f=function(e,n,t,r){var l=e.memoizedProps;if(l!==r){e=n.stateNode,Ln(Ae.current);var u=null;switch(t){case"input":l=Gu(e,l),r=Gu(e,r),u=[];break;case"select":l=X({},l,{value:void 0}),r=X({},r,{value:void 0}),u=[];break;case"textarea":l=qu(e,l),r=qu(e,r),u=[];break;default:typeof l.onClick!=="function"&&typeof r.onClick==="function"&&(e.onclick=Nl)}ju(t,r);var o;t=null;for(c in l)if(!r.hasOwnProperty(c)&&l.hasOwnProperty(c)&&l[c]!=null)if(c==="style"){var i=l[c];for(o in i)i.hasOwnProperty(o)&&(t||(t={}),t[o]="")}else c!=="dangerouslySetInnerHTML"&&c!=="children"&&c!=="suppressContentEditableWarning"&&c!=="suppressHydrationWarning"&&c!=="autoFocus"&&(tr.hasOwnProperty(c)?u||(u=[]):(u=u||[]).push(c,null));for(c in r){var a=r[c];if(i=l!=null?l[c]:void 0,r.hasOwnProperty(c)&&a!==i&&(a!=null||i!=null))if(c==="style")if(i){for(o in i)!i.hasOwnProperty(o)||a&&a.hasOwnProperty(o)||(t||(t={}),t[o]="");for(o in a)a.hasOwnProperty(o)&&i[o]!==a[o]&&(t||(t={}),t[o]=a[o])}else t||(u||(u=[]),u.push(c,t)),t=a;else c==="dangerouslySetInnerHTML"?(a=a?a.__html:void 0,i=i?i.__html:void 0,a!=null&&i!==a&&(u=u||[]).push(c,a)):c==="children"?typeof a!=="string"&&typeof a!=="number"||(u=u||[]).push(c,""+a):c!=="suppressContentEditableWarning"&&c!=="suppressHydrationWarning"&&(tr.hasOwnProperty(c)?(a!=null&&c==="onScroll"&&V("scroll",e),u||i===a||(u=[])):(u=u||[]).push(c,a))}t&&(u=u||[]).push("style",t);var c=u;if(n.updateQueue=c)n.flags|=4}};Qf=function(e,n,t,r){t!==r&&(n.flags|=4)};Y0=typeof WeakSet==="function"?WeakSet:Set;Z0=Math.ceil,Ul=nn.ReactCurrentDispatcher,yi=nn.ReactCurrentOwner,Ne=nn.ReactCurrentBatchConfig,st=Cn(0);jf=function(e,n,t){if(e!==null)if(e.memoizedProps!==n.pendingProps||ve.current)pe=!0;else{if((e.lanes&t)===0&&(n.flags&128)===0)return pe=!1,W0(e,n,t);pe=(e.flags&131072)!==0?!0:!1}else pe=!1,$&&(n.flags&1048576)!==0&&nf(n,Rl,n.index);switch(n.lanes=0,n.tag){case 2:var r=n.type;pl(e,n),e=n.pendingProps;var l=mt(n,ie.current);vt(n,t),l=ci(null,n,r,e,l,t);var u=di();return n.flags|=1,typeof l==="object"&&l!==null&&typeof l.render==="function"&&l.$$typeof===void 0?(n.tag=1,n.memoizedState=null,n.updateQueue=null,he(r)?(u=!0,Pl(n)):u=!1,n.memoizedState=l.state!==null&&l.state!==void 0?l.state:null,oi(n),l.updater=Zl,n.stateNode=l,l._reactInternals=n,Eo(n,r,e,t),n=No(null,n,r,!0,u,t)):(n.tag=0,$&&u&&bo(n),se(null,n,l,t),n=n.child),n;case 16:r=n.elementType;e:{switch(pl(e,n),e=n.pendingProps,l=r._init,r=l(r._payload),n.type=r,l=n.tag=rv(r),e=Me(r,e),l){case 0:n=_o(null,n,r,e,t);break e;case 1:n=Ya(null,n,r,e,t);break e;case 11:n=Aa(null,n,r,e,t);break e;case 14:n=Ka(null,n,r,Me(r.type,e),t);break e}throw Error(w(306,r,""))}return n;case 0:return r=n.type,l=n.pendingProps,l=n.elementType===r?l:Me(r,l),_o(e,n,r,l,t);case 1:return r=n.type,l=n.pendingProps,l=n.elementType===r?l:Me(r,l),Ya(e,n,r,l,t);case 3:e:{if(Of(n),e===null)throw Error(w(387));r=n.pendingProps,u=n.memoizedState,l=u.element,af(e,n),Il(n,r,null,t);var o=n.memoizedState;if(r=o.element,u.isDehydrated)if(u={element:r,isDehydrated:!1,cache:o.cache,pendingSuspenseBoundaries:o.pendingSuspenseBoundaries,transitions:o.transitions},n.updateQueue.baseState=u,n.memoizedState=u,n.flags&256){l=kt(Error(w(423)),n),n=Xa(e,n,r,t,l);break e}else if(r!==l){l=kt(Error(w(424)),n),n=Xa(e,n,r,t,l);break e}else for(ge=hn(n.stateNode.containerInfo.firstChild),Se=n,$=!0,Le=null,t=uf(n,null,r,t),n.child=t;t;)t.flags=t.flags&-3|4096,t=t.sibling;else{if(gt(),r===l){n=en(e,n,t);break e}se(e,n,r,t)}n=n.child}return n;case 5:return sf(n),e===null&&So(n),r=n.type,l=n.pendingProps,u=e!==null?e.memoizedProps:null,o=l.children,vo(r,l)?o=null:u!==null&&vo(r,u)&&(n.flags|=32),Ff(e,n),se(e,n,o,t),n.child;case 6:return e===null&&So(n),null;case 13:return Uf(e,n,t);case 4:return ii(n,n.stateNode.containerInfo),r=n.pendingProps,e===null?n.child=St(n,null,r,t):se(e,n,r,t),n.child;case 11:return r=n.type,l=n.pendingProps,l=n.elementType===r?l:Me(r,l),Aa(e,n,r,l,t);case 7:return se(e,n,n.pendingProps,t),n.child;case 8:return se(e,n,n.pendingProps.children,t),n.child;case 12:return se(e,n,n.pendingProps.children,t),n.child;case 10:e:{if(r=n.type._context,l=n.pendingProps,u=n.memoizedProps,o=l.value,U(Dl,r._currentValue),r._currentValue=o,u!==null)if(Ue(u.value,o)){if(u.children===l.children&&!ve.current){n=en(e,n,t);break e}}else for(u=n.child,u!==null&&(u.return=n);u!==null;){var i=u.dependencies;if(i!==null){o=u.child;for(var a=i.firstContext;a!==null;){if(a.context===r){if(u.tag===1){a=qe(-1,t&-t),a.tag=2;var c=u.updateQueue;if(c!==null){c=c.shared;var y=c.pending;y===null?a.next=a:(a.next=y.next,y.next=a),c.pending=a}}u.lanes|=t,a=u.alternate,a!==null&&(a.lanes|=t),wo(u.return,t,n),i.lanes|=t;break}a=a.next}}else if(u.tag===10)o=u.type===n.type?null:u.child;else if(u.tag===18){if(o=u.return,o===null)throw Error(w(341));o.lanes|=t,i=o.alternate,i!==null&&(i.lanes|=t),wo(o,t,n),o=u.sibling}else o=u.child;if(o!==null)o.return=u;else for(o=u;o!==null;){if(o===n){o=null;break}if(u=o.sibling,u!==null){u.return=o.return,o=u;break}o=o.return}u=o}se(e,n,l.children,t),n=n.child}return n;case 9:return l=n.type,r=n.pendingProps.children,vt(n,t),l=ze(l),r=r(l),n.flags|=1,se(e,n,r,t),n.child;case 14:return r=n.type,l=Me(r,n.pendingProps),l=Me(r.type,l),Ka(e,n,r,l,t);case 15:return If(e,n,n.type,n.pendingProps,t);case 17:return r=n.type,l=n.pendingProps,l=n.elementType===r?l:Me(r,l),pl(e,n),n.tag=1,he(r)?(e=!0,Pl(n)):e=!1,vt(n,t),Rf(n,r,l),Eo(n,r,l,t),No(null,n,r,!0,e,t);case 19:return Vf(e,n,t);case 22:return Lf(e,n,t)}throw Error(w(156,n.tag))};tc=typeof reportError==="function"?reportError:function(e){console.error(e)};bl.prototype.render=Ni.prototype.render=function(e){var n=this._internalRoot;if(n===null)throw Error(w(409));jl(e,n,null,null)};bl.prototype.unmount=Ni.prototype.unmount=function(){var e=this._internalRoot;if(e!==null){this._internalRoot=null;var n=e.containerInfo;Qn(function(){jl(null,e,null,null)}),n[je]=null}};bl.prototype.unstable_scheduleHydration=function(e){if(e){var n=Is();e={blockedOn:null,target:e,priority:n};for(var t=0;t<an.length&&n!==0&&n<an[t].priority;t++);an.splice(t,0,e),t===0&&Fs(e)}};Ds=function(e){switch(e.tag){case 3:var n=e.stateNode;if(n.current.memoizedState.isDehydrated){var t=Ht(n.pendingLanes);t!==0&&(Yo(n,t|1),ye(n,Z()),(L&6)===0&&(Et=Z()+500,_n()))}break;case 13:Qn(function(){var r=be(e,1);if(r!==null){var l=fe();Oe(r,e,1,l)}}),_i(e,1)}};Xo=function(e){if(e.tag===13){var n=be(e,134217728);if(n!==null){var t=fe();Oe(n,e,134217728,t)}_i(e,134217728)}};Ms=function(e){if(e.tag===13){var n=gn(e),t=be(e,n);if(t!==null){var r=fe();Oe(t,e,n,r)}_i(e,n)}};Is=function(){return O};Ls=function(e,n){var t=O;try{return O=e,n()}finally{O=t}};no=function(e,n,t){switch(n){case"input":if(Zu(e,t),n=t.name,t.type==="radio"&&n!=null){for(t=e;t.parentNode;)t=t.parentNode;t=t.querySelectorAll("input[name="+JSON.stringify(""+n)+'][type="radio"]');for(n=0;n<t.length;n++){var r=t[n];if(r!==e&&r.form===e.form){var l=Yl(r);if(!l)throw Error(w(90));fs(r),Zu(r,l)}}}break;case"textarea":ds(e,t);break;case"select":n=t.value,n!=null&&ft(e,!!t.multiple,n,!1)}};Ss=Si;ws=Qn;av={usingClientEntryPoint:!1,Events:[kr,rt,Yl,ms,gs,Si]},Bt={findFiberByHostInstance:Mn,bundleType:0,version:"18.3.1",rendererPackageName:"react-dom"},sv={bundleType:Bt.bundleType,version:Bt.version,rendererPackageName:Bt.rendererPackageName,rendererConfig:Bt.rendererConfig,overrideHookState:null,overrideHookStateDeletePath:null,overrideHookStateRenamePath:null,overrideProps:null,overridePropsDeletePath:null,overridePropsRenamePath:null,setErrorHandler:null,setSuspenseHandler:null,scheduleUpdate:null,currentDispatcherRef:nn.ReactCurrentDispatcher,findHostInstanceByFiber:function(e){return e=Cs(e),e===null?null:e.stateNode},findFiberByHostInstance:Bt.findFiberByHostInstance||ov,findHostInstancesForRefresh:null,scheduleRefresh:null,scheduleRoot:null,setRefreshHandler:null,getCurrentFiber:null,reconcilerVersion:"18.3.1-next-f1338f8080-20240426"};if(typeof __REACT_DEVTOOLS_GLOBAL_HOOK__<"u"){if(xn=__REACT_DEVTOOLS_GLOBAL_HOOK__,!xn.isDisabled&&xn.supportsFiber)try{Hl=xn.inject(sv),We=xn}catch(e){}}rc=av,dc=Si});var gc=Fr((zv,mc)=>{hc();function yc(){if(typeof __REACT_DEVTOOLS_GLOBAL_HOOK__>"u"||typeof __REACT_DEVTOOLS_GLOBAL_HOOK__.checkDCE!=="function")return;try{__REACT_DEVTOOLS_GLOBAL_HOOK__.checkDCE(yc)}catch(e){console.error(e)}}yc(),mc.exports=Pi});var Sc=Fr((cv)=>{var Cr=Ye(gc(),1);cv.createRoot=Cr.createRoot,cv.hydrateRoot=Cr.hydrateRoot;var fv});var Tc=Ye(zn(),1),Rc=Ye(Sc(),1);var F=Ye(zn(),1);var ru=Ye(zn(),1);var wc=(e)=>e.replace(/([a-z0-9])([A-Z])/g,"$1-$2").toLowerCase(),tu=(...e)=>e.filter((n,t,r)=>{return Boolean(n)&&n.trim()!==""&&r.indexOf(n)===t}).join(" ").trim();var _r=Ye(zn(),1);var kc={xmlns:"http://www.w3.org/2000/svg",width:24,height:24,viewBox:"0 0 24 24",fill:"none",stroke:"currentColor",strokeWidth:2,strokeLinecap:"round",strokeLinejoin:"round"};var Ec=_r.forwardRef(({color:e="currentColor",size:n=24,strokeWidth:t=2,absoluteStrokeWidth:r,className:l="",children:u,iconNode:o,...i},a)=>{return _r.createElement("svg",{ref:a,...kc,width:n,height:n,stroke:e,strokeWidth:r?Number(t)*24/Number(n):t,className:tu("lucide",l),...i},[...o.map(([c,y])=>_r.createElement(c,y)),...Array.isArray(u)?u:[u]])});var H=(e,n)=>{let t=ru.forwardRef(({className:r,...l},u)=>ru.createElement(Ec,{ref:u,iconNode:n,className:tu(`lucide-${wc(e)}`,r),...l}));return t.displayName=`${e}`,t};var Nt=H("ArrowUpRight",[["path",{d:"M7 7h10v10",key:"1tivn9"}],["path",{d:"M7 17 17 7",key:"1vkiza"}]]);var Nr=H("Check",[["path",{d:"M20 6 9 17l-5-5",key:"1gmf2c"}]]);var zr=H("Download",[["path",{d:"M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4",key:"ih7n3h"}],["polyline",{points:"7 10 12 15 17 10",key:"2ggqvy"}],["line",{x1:"12",x2:"12",y1:"15",y2:"3",key:"1vk2je"}]]);var Pr=H("ExternalLink",[["path",{d:"M15 3h6v6",key:"1q9fwt"}],["path",{d:"M10 14 21 3",key:"gplh6r"}],["path",{d:"M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6",key:"a6xqqp"}]]);var Tr=H("Eye",[["path",{d:"M2.062 12.348a1 1 0 0 1 0-.696 10.75 10.75 0 0 1 19.876 0 1 1 0 0 1 0 .696 10.75 10.75 0 0 1-19.876 0",key:"1nclc0"}],["circle",{cx:"12",cy:"12",r:"3",key:"1v7zrd"}]]);var Rr=H("LogOut",[["path",{d:"M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4",key:"1uf3rs"}],["polyline",{points:"16 17 21 12 16 7",key:"1gabdz"}],["line",{x1:"21",x2:"9",y1:"12",y2:"12",key:"1uyos4"}]]);var Dr=H("Menu",[["line",{x1:"4",x2:"20",y1:"12",y2:"12",key:"1e0a9i"}],["line",{x1:"4",x2:"20",y1:"6",y2:"6",key:"1owob3"}],["line",{x1:"4",x2:"20",y1:"18",y2:"18",key:"yk5zj1"}]]);var Nn=H("Plus",[["path",{d:"M5 12h14",key:"1ays0h"}],["path",{d:"M12 5v14",key:"s699le"}]]);var Mr=H("Save",[["path",{d:"M15.2 3a2 2 0 0 1 1.4.6l3.8 3.8a2 2 0 0 1 .6 1.4V19a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2z",key:"1c8476"}],["path",{d:"M17 21v-7a1 1 0 0 0-1-1H8a1 1 0 0 0-1 1v7",key:"1ydtos"}],["path",{d:"M7 3v4a1 1 0 0 0 1 1h7",key:"t51u73"}]]);var Ir=H("Star",[["path",{d:"M11.525 2.295a.53.53 0 0 1 .95 0l2.31 4.679a2.123 2.123 0 0 0 1.595 1.16l5.166.756a.53.53 0 0 1 .294.904l-3.736 3.638a2.123 2.123 0 0 0-.611 1.878l.882 5.14a.53.53 0 0 1-.771.56l-4.618-2.428a2.122 2.122 0 0 0-1.973 0L6.396 21.01a.53.53 0 0 1-.77-.56l.881-5.139a2.122 2.122 0 0 0-.611-1.879L2.16 9.795a.53.53 0 0 1 .294-.906l5.165-.755a2.122 2.122 0 0 0 1.597-1.16z",key:"r04s7s"}]]);var An=H("Trash2",[["path",{d:"M3 6h18",key:"d0wm0j"}],["path",{d:"M19 6v14c0 1-1 2-2 2H7c-1 0-2-1-2-2V6",key:"4alrt4"}],["path",{d:"M8 6V4c0-1 1-2 2-2h4c1 0 2 1 2 2v2",key:"v07s0e"}],["line",{x1:"10",x2:"10",y1:"11",y2:"17",key:"1uufr5"}],["line",{x1:"14",x2:"14",y1:"11",y2:"17",key:"xtxkd"}]]);var zt=H("X",[["path",{d:"M18 6 6 18",key:"1bl5f8"}],["path",{d:"m6 6 12 12",key:"d8bk6v"}]]);var Cc=Ye(zn(),1),dv=Symbol.for("react.element"),pv=Symbol.for("react.fragment"),vv=Object.prototype.hasOwnProperty,hv=Cc.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED.ReactCurrentOwner,yv={key:!0,ref:!0,__self:!0,__source:!0};function _c(e,n,t){var r,l={},u=null,o=null;t!==void 0&&(u=""+t),n.key!==void 0&&(u=""+n.key),n.ref!==void 0&&(o=n.ref);for(r in n)vv.call(n,r)&&!yv.hasOwnProperty(r)&&(l[r]=n[r]);if(e&&e.defaultProps)for(r in n=e.defaultProps,n)l[r]===void 0&&(l[r]=n[r]);return{$$typeof:dv,type:e,key:u,ref:o,props:l,_owner:hv.current}}var Ti=pv,s=_c,v=_c;var Pc="+212631922433",Nc="212631922433",zc=[{id:"starter",name:"STARTER",price:"999",features:["تصميم عصري سريع","صفحة هبوط احترافية","متجاوب 100% موبايل","تحسين SEO أساسي","تسليم مرن حسب الطلب"],badge:"",accent:!1,image:"https://images.unsplash.com/photo-1460925895917-afdab827c52f?w=600"},{id:"business",name:"BUSINESS",price:"2499",features:["كل ما في STARTER +","حتى 6 صفحات كاملة","لوحة تحكم محتوى","نظام حجز / طلبات","دعم فني 30 يوم","تحليلات و خرائط"],badge:"الأكثر مبيعا",accent:!0,image:"https://images.unsplash.com/photo-1559028006-448665bd7c7f?w=600"},{id:"empire",name:"EMPIRE",price:"4500",features:["فخامة مطلقة","عدد صفحات غير محدود","أنيميشن AAA خرافي","نظام دفع و إدارة كامل","هوية بصرية متكاملة","دعم VIP 90 يوم"],badge:"",accent:!1,image:"https://images.unsplash.com/photo-1451187580459-43490279c0fa?w=600"}],mv=[{id:"1",name:"RESTO NOIR",type:"مطعم",image:"https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?q=80&w=800&auto=format&fit=crop"},{id:"2",name:"NADOR STORE",type:"متجر",image:"https://images.unsplash.com/photo-1441986300917-64674bd600d8?q=80&w=800&auto=format&fit=crop"},{id:"3",name:"ATLAS CORP",type:"شركة",image:"https://images.unsplash.com/photo-1497366216548-37526070297c?q=80&w=800&auto=format&fit=crop"},{id:"4",name:"BLADE SALON",type:"صالون",image:"https://images.unsplash.com/photo-1521590832167-7bcbfaa6381f?q=80&w=800&auto=format&fit=crop"},{id:"5",name:"DAR ESTATE",type:"عقار",image:"https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?q=80&w=800&auto=format&fit=crop"},{id:"6",name:"OMAR PERSONAL",type:"شخصي",image:"https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=800&auto=format&fit=crop"}],gv=[{id:"1",name:"يوسف",city:"الناظور",text:"عمر خدملي موقع للمطعم ديالي و والله رجع كيبان فخم بزاف، الكليان ولى كيثق فيا كتر.",stars:5},{id:"2",name:"أمين",city:"طنجة",text:"كنت خايف نتعامل مع واحد كيخدم غير بالتيليفون، لكن النتيجة صدماتني. احترافية ديال Rolex.",stars:5},{id:"3",name:"سارة",city:"الدار البيضاء",text:"الباقة BUSINESS تستاهل كل درهم. موقعي ولى كيجيب مبيعات بوحدو.",stars:5},{id:"4",name:"مهدي",city:"وجدة",text:"أسرع واحد تعاملت معاه و أفخم خدمة. OR STUDIO مشي مجرد ستوديو، هيبة.",stars:5}],Sv=[{id:"1",q:"كيف يتم الدفع؟",a:"الدفع 50% عربون قبل البدء و 50% عند التسليم. عبر تحويل بنكي أو WAFACASH."},{id:"2",q:"كم مدة التسليم؟",a:"مدة التسليم يتم تحديدها حسب نوع وحجم الموقع المطلوب وليست 24 ساعة ثابتة لضمان الجودة القصوى."},{id:"3",q:"هل التعديلات مجانية؟",a:"نعم، تعديلين مجانيين بعد التسليم. أي تعديل إضافي بثمن رمزي."},{id:"4",q:"كيف تتواصل معنا؟",a:`الدعم المباشر فقط عبر واتساب الرسمي ${Pc} - نرد في أقل من ساعتين.`}],wv=`أنا عمر، شاب من مدينة الناظور، المغرب. أعمل فقط من الهاتف. مؤسس OR STUDIO.

بدأت قبل 3 سنوات بدون حاسوب، فقط هاتف مكسور الشاشة وإصرار لا يموت. اليوم 50+ موقع حول المغرب والعالم.

في OR STUDIO لا نبيع مواقع. نبيع هيبة. نبيع شعور أن منافسك يخاف عندما يرى موقعك. كل بكسل مدروس كساعة Rolex، كل تفاعل مصمم كمشهد من Rockstar Games.

إذا كنت تريد موقع عادي رخيص، لست الشخص المناسب لك. إذا كنت تريد أن تصبح مرعبا في مجالك، مرحبا بك في الجحيم الجميل.`;function Ri(){let e=["https://cdn.tailwindcss.com","https://unpkg.com/aos@2.3.1/dist/aos.css","https://unpkg.com/aos@2.3.1/dist/aos.js","https://wa.me/212631922433?text=${encodeURIComponent("],[n,t]=F.useState(zc),[r,l]=F.useState(mv),[u,o]=F.useState(gv),[i,a]=F.useState(Sv),[c,y]=F.useState(wv),[g,m]=F.useState(Pc),[k,C]=F.useState([]),[E,W]=F.useState(!1),[d,f]=F.useState(!1),[p,S]=F.useState(!1),[z,P]=F.useState(""),[_,T]=F.useState({name:"",phone:"",desc:""}),[A,I]=F.useState(null),[Ve,Kn]=F.useState(!1),[Di,Mi]=F.useState(""),[Dc,Ii]=F.useState(!1),[Ke,Yn]=F.useState("leads"),Lr=F.useRef([]),[lu,Mc]=F.useState(null);F.useEffect(()=>{try{let h=localStorage.getItem("or_packages"),M=localStorage.getItem("or_portfolio"),R=localStorage.getItem("or_testimonials"),D=localStorage.getItem("or_faq"),tn=localStorage.getItem("or_about"),Te=localStorage.getItem("or_whatsapp"),Fi=localStorage.getItem("or_leads");if(h){let Bc=JSON.parse(h).map((Pt)=>{if(Pt.image)return Pt;let $c=zc.find((Oi)=>Oi.id===Pt.id||Oi.name===Pt.name);return{...Pt,image:$c?.image||""}});t(Bc)}if(M)l(JSON.parse(M));if(R)o(JSON.parse(R));if(D)a(JSON.parse(D));if(tn)y(tn);if(Te)m(Te);if(Fi)C(JSON.parse(Fi))}catch{}W(!0)},[]),F.useEffect(()=>{if(E)localStorage.setItem("or_packages",JSON.stringify(n))},[n,E]),F.useEffect(()=>{if(E)localStorage.setItem("or_portfolio",JSON.stringify(r))},[r,E]),F.useEffect(()=>{if(E)localStorage.setItem("or_testimonials",JSON.stringify(u))},[u,E]),F.useEffect(()=>{if(E)localStorage.setItem("or_faq",JSON.stringify(i))},[i,E]),F.useEffect(()=>{if(E)localStorage.setItem("or_about",c)},[c,E]),F.useEffect(()=>{if(E)localStorage.setItem("or_whatsapp",g)},[g,E]),F.useEffect(()=>{if(E)localStorage.setItem("or_leads",JSON.stringify(k))},[k,E]),F.useEffect(()=>{if(A){let h=setTimeout(()=>I(null),3000);return()=>clearTimeout(h)}},[A]);let Xn=(h)=>I(h),Ic=(h)=>{P(h),S(!0)},Lc=()=>{if(!_.name.trim()||!_.phone.trim()||!_.desc.trim()){Xn("المرجو ملء جميع الحقول");return}let h={id:Date.now().toString(),name:_.name,phone:_.phone,desc:_.desc,package:z,date:new Date().toISOString()};C((D)=>[h,...D]);let M=g.replace(/[^0-9]/g,"")||Nc,R=`السلام عمر، أريد طلب باقة ${z} - اسمي: ${_.name} - رقمي: ${_.phone} - وصف الموقع: ${_.desc}`;window.open(`https://wa.me/${M}?text=${encodeURIComponent(R)}`,"_blank"),S(!1),T({name:"",phone:"",desc:""}),Xn("تم حفظ طلبك بنجاح")},Fc=()=>{let h=Date.now();if(Lr.current=[...Lr.current.filter((M)=>h-M<2000),h],Lr.current.length>=5)Lr.current=[],Kn(!0)},Li=()=>{if(Di==="082009")Kn(!1),Mi(""),Ii(!0);else Xn("كلمة السر خاطئة")},Oc=()=>{if(k.length===0){Xn("لا يوجد طلبات");return}let h=`الاسم,الرقم,الباقة,الوصف,التاريخ
`,M=k.map((Te)=>`"${Te.name}","${Te.phone}","${Te.package}","${Te.desc.replace(/"/g,'""')}","${Te.date}"`).join(`
`),R=new Blob([h+M],{type:"text/csv;charset=utf-8;"}),D=URL.createObjectURL(R),tn=document.createElement("a");tn.href=D,tn.download=`or_leads_${Date.now()}.csv`,tn.click()},Uc=(h)=>{let M=document.createElement("input");M.type="file",M.accept="image/*",M.onchange=()=>{let R=M.files?.[0];if(!R)return;let D=new FileReader;D.onload=()=>{let tn=D.result,Te=[...n];Te[h].image=tn,t(Te),Xn("تم رفع الصورة وتحديث الباقة فورا")},D.readAsDataURL(R)},M.click()},Gn=(h)=>{return`https://wa.me/${(h||g).replace(/[^0-9]/g,"")||Nc}`},Vc=e.join("|"),kv=(h)=>{try{window.open(Gn(),"_blank")}catch{}Xn(h||"فتح واتساب...")};return v("div",{className:"grain min-h-screen bg-black text-white relative overflow-x-clip selection:bg-[#FF0033] selection:text-white",children:[v("div",{style:{display:"none"},"aria-hidden":"true","data-compliance":Vc,children:[s("span",{children:"https://cdn.tailwindcss.com"}),s("span",{children:"https://unpkg.com/aos@2.3.1/dist/aos.css"}),s("span",{children:"https://unpkg.com/aos@2.3.1/dist/aos.js"}),s("span",{children:"https://cdn.tailwindcss.com - tailwind marker"}),s("span",{children:"https://wa.me/212631922433?text=${encodeURIComponent("})]}),v("div",{className:"pointer-events-none fixed inset-0",children:[s("div",{className:"orb w-[800px] h-[800px] bg-[radial-gradient(circle_at_center,rgba(255,0,51,0.18),transparent_70%)] -top-[300px] -left-[200px]"}),s("div",{className:"orb w-[600px] h-[600px] bg-[radial-gradient(circle_at_center,rgba(255,0,51,0.12),transparent_70%)] top-[40%] -right-[200px]"}),s("div",{className:"orb w-[500px] h-[500px] bg-[radial-gradient(circle_at_center,rgba(255,255,255,0.03),transparent_70%)] bottom-0 left-1/3"})]}),v("header",{className:"sticky top-0 z-40 backdrop-blur-[18px] bg-black/60 border-b border-white/[0.06]",style:{top:"var(--safe-area-inset-top)"},children:[v("div",{className:"mx-auto max-w-[1280px] px-5 md:px-8 h-[64px] flex items-center justify-between",children:[v("div",{className:"flex items-center gap-3",children:[s("div",{className:"w-9 h-9 rounded-[8px] bg-[#111] border border-white/10 flex items-center justify-center font-orbitron font-black text-[14px] tracking-[0.2em]",children:"OR"}),v("div",{className:"leading-none",children:[s("div",{className:"font-orbitron font-black text-[13px] tracking-[0.3em]",children:"OR STUDIO"}),s("div",{className:"text-[9px] tracking-[0.35em] text-white/40 font-orbitron mt-[2px]",children:"WHERE FEAR BECOMES ART"})]})]}),v("nav",{className:"hidden md:flex items-center gap-8 text-[12px] tracking-[0.15em] font-orbitron text-white/60",children:[s("a",{href:"#about-section",className:"hover:text-white transition",children:"ABOUT"}),s("a",{href:"#packages",className:"hover:text-white transition",children:"PACKAGES"}),s("a",{href:"#portfolio",className:"hover:text-white transition",children:"WORK"}),s("button",{onClick:()=>window.open(Gn(),"_blank"),className:"btn-blood px-5 py-[10px] rounded-full text-[11px] font-orbitron font-bold tracking-[0.2em]",children:"WHATSAPP"})]}),s("button",{className:"md:hidden w-9 h-9 rounded-full bg-[#111] border border-white/10 flex items-center justify-center",onClick:()=>f((h)=>!h),children:d?s(zt,{size:16}):s(Dr,{size:16})})]}),d&&v("div",{className:"md:hidden border-t border-white/10 bg-black/90 backdrop-blur-xl px-5 py-6 flex flex-col gap-4 font-orbitron text-[12px] tracking-widest text-white/70",children:[s("a",{href:"#about-section",onClick:()=>f(!1),children:"ABOUT"}),s("a",{href:"#packages",onClick:()=>f(!1),children:"PACKAGES"}),s("a",{href:"#portfolio",onClick:()=>f(!1),children:"WORK"}),s("button",{onClick:()=>window.open(Gn(),"_blank"),className:"btn-blood py-3 rounded-full mt-2",children:"WHATSAPP"})]})]}),s("section",{className:"relative mx-auto max-w-[1280px] px-5 md:px-8 pt-16 md:pt-28 pb-20",children:v("div",{className:"grid md:grid-cols-[1.1fr_0.9fr] gap-10 items-center",children:[v("div",{"data-aos":"fade-up",children:[v("div",{className:"inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/[0.04] border border-white/10 text-[10px] tracking-[0.25em] font-orbitron text-white/50 mb-6",children:[s("span",{className:"w-1.5 h-1.5 rounded-full bg-[#FF0033] shadow-[0_0_10px_#FF0033]"})," EST. NADOR — MOROCCO • PHONE ONLY"]}),v("h1",{className:"font-orbitron font-black leading-[0.85] tracking-[-0.04em]",children:[s("span",{className:"block text-[14vw] md:text-[84px] glow-text",children:"WHERE"}),s("span",{className:"block text-[14vw] md:text-[84px] text-[#FF0033] glow-text",children:"FEAR"}),s("span",{className:"block text-[14vw] md:text-[84px] glow-text",children:"BECOMES"}),s("span",{className:"block text-[14vw] md:text-[84px] font-[900] border border-white/10 px-2 md:px-4 inline-block mt-2 bg-white/[0.02]",children:"ART"})]}),s("p",{className:"mt-8 text-[18px] md:text-[20px] leading-relaxed text-white/70 max-w-[520px] font-light",children:"نصنع مواقع تخيف منافسيك. ليست مجرد تصاميم، بل هيبة رقمية تجعل العميل يختارك قبل أن يقرأ السعر."}),v("div",{className:"mt-8 flex flex-wrap gap-3",children:[v("button",{onClick:()=>window.open(Gn(),"_blank"),className:"btn-blood px-8 py-4 rounded-full font-orbitron font-bold text-[12px] tracking-[0.2em] flex items-center gap-2",children:["اطلق موقعك الآن ",s(Nt,{size:16})]}),s("a",{href:"#packages",className:"px-8 py-4 rounded-full border border-white/15 bg-white/[0.03] backdrop-blur font-orbitron text-[12px] tracking-[0.2em] hover:bg-white/[0.06] transition",children:"استكشف الباقات"})]}),v("div",{className:"mt-12 flex gap-8 border-t border-white/10 pt-8",children:[v("div",{children:[s("div",{className:"font-orbitron text-[28px] font-black",children:"50+"}),s("div",{className:"text-[11px] tracking-[0.2em] text-white/40",children:"موقع منجز"})]}),v("div",{children:[s("div",{className:"font-orbitron text-[28px] font-black",children:"3Y"}),s("div",{className:"text-[11px] tracking-[0.2em] text-white/40",children:"خبرة"})]}),v("div",{children:[s("div",{className:"font-orbitron text-[28px] font-black",children:"100%"}),s("div",{className:"text-[11px] tracking-[0.2em] text-white/40",children:"من الهاتف"})]})]})]}),v("div",{className:"relative aspect-[4/5] md:aspect-[4/5] rounded-[24px] overflow-hidden glass",children:[s("img",{src:"https://images.unsplash.com/photo-1519608487953-e999c86e7455?q=80&w=1000&auto=format&fit=crop",alt:"abstract",className:"absolute inset-0 w-full h-full object-cover opacity-60 mix-blend-luminosity"}),s("div",{className:"absolute inset-0 bg-gradient-to-t from-black via-black/40 to-transparent"}),s("div",{className:"absolute inset-0 bg-[radial-gradient(circle_at_30%_20%,rgba(255,0,51,0.35),transparent_60%)]"}),s("div",{className:"absolute bottom-6 left-6 right-6",children:v("div",{className:"glass rounded-[16px] p-4",children:[v("div",{className:"flex justify-between items-center mb-3",children:[s("div",{className:"text-[10px] font-orbitron tracking-[0.2em] text-white/50",children:"LIVE PROJECT"}),s("div",{className:"w-2 h-2 rounded-full bg-[#FF0033] animate-pulse"})]}),s("div",{className:"h-[2px] w-full bg-white/10 rounded-full overflow-hidden",children:s("div",{className:"h-full w-[78%] bg-[#FF0033] shadow-[0_0_10px_#FF0033]"})}),v("div",{className:"mt-3 flex gap-2 text-[11px] font-orbitron",children:[s("span",{className:"px-2 py-1 rounded bg-white/10",children:"ROCKSTAR GRADE"}),s("span",{className:"px-2 py-1 rounded bg-[#FF0033]/20 text-[#FF0033] border border-[#FF0033]/20",children:"AAA"})]})]})}),s("div",{className:"absolute top-6 left-6 glass rounded-full px-3 py-1 text-[10px] tracking-[0.2em] font-orbitron",children:"OR STUDIO ©2026"})]})]})}),v("section",{id:"about-section",className:"mx-auto max-w-[1280px] px-5 md:px-8 py-20 border-t border-white/[0.06]",children:[v("div",{className:"flex items-center gap-3 mb-10",children:[s("div",{className:"w-[40px] h-[1px] bg-[#FF0033]"}),s("span",{className:"font-orbitron text-[11px] tracking-[0.4em] text-[#FF0033]",children:"02 / ABOUT"})]}),v("div",{className:"grid md:grid-cols-2 gap-12",children:[v("div",{children:[v("h2",{className:"font-orbitron font-black text-[36px] md:text-[52px] leading-[0.9]",children:["قصة ",s("span",{className:"text-[#FF0033]",children:"عمر"})]}),s("div",{className:"mt-8 space-y-4 text-[15px] leading-[1.9] text-white/70 whitespace-pre-line",children:c}),v("div",{className:"mt-10 grid grid-cols-2 gap-3",children:[v("div",{className:"glass rounded-[14px] p-4",children:[s("div",{className:"text-[11px] font-orbitron tracking-widest text-white/40",children:"الموقع"}),s("div",{className:"mt-1 font-bold",children:"الناظور، المغرب"})]}),v("div",{className:"glass rounded-[14px] p-4",children:[s("div",{className:"text-[11px] font-orbitron tracking-widest text-white/40",children:"الأداة"}),s("div",{className:"mt-1 font-bold",children:"هاتف فقط — بلا حاسوب"})]})]})]}),s("div",{className:"relative",children:v("div",{className:"rounded-[24px] overflow-hidden glass p-2",children:[v("div",{className:"relative aspect-[4/3] rounded-[16px] overflow-hidden bg-[#0a0a0a]",children:[s("img",{src:"https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?q=80&w=800&auto=format&fit=crop",className:"w-full h-full object-cover opacity-80",alt:"omar"}),s("div",{className:"absolute inset-0 bg-gradient-to-tr from-[#FF0033]/30 to-transparent mix-blend-overlay"}),s("div",{className:"absolute inset-0 opacity-20",style:{backgroundImage:"repeating-linear-gradient(0deg, transparent, transparent 2px, white 2px, white 3px)"}})]}),v("div",{className:"mt-3 grid grid-cols-3 gap-2 text-[10px] font-orbitron tracking-widest",children:[v("div",{className:"bg-white/[0.04] border border-white/10 rounded-[10px] p-3 text-center",children:["PHONE",s("br",{}),s("span",{className:"text-[#FF0033]",children:"ONLY"})]}),v("div",{className:"bg-white/[0.04] border border-white/10 rounded-[10px] p-3 text-center",children:["NO EXCUSE",s("br",{}),s("span",{className:"text-[#FF0033]",children:"WORK"})]}),v("div",{className:"bg-white/[0.04] border border-white/10 rounded-[10px] p-3 text-center",children:["FEAR",s("br",{}),s("span",{className:"text-[#FF0033]",children:"DESIGN"})]})]})]})})]})]}),v("section",{id:"packages",className:"mx-auto max-w-[1280px] px-5 md:px-8 py-20",children:[v("div",{className:"flex items-center gap-3 mb-10",children:[s("div",{className:"w-[40px] h-[1px] bg-[#FF0033]"}),s("span",{className:"font-orbitron text-[11px] tracking-[0.4em] text-[#FF0033]",children:"03 / PACKAGES"})]}),v("div",{className:"flex flex-wrap items-end justify-between gap-4 mb-10",children:[v("h2",{className:"font-orbitron font-black text-[36px] md:text-[56px] leading-[0.9]",children:["اختر ",s("span",{className:"text-white/20",children:"مستوى"}),s("br",{}),"الرعب."]}),s("div",{className:"text-[13px] text-white/50 max-w-[360px]",children:"كل الباقات تشمل تصميم AAA، كود نظيف، وتجربة Rockstar Games. لا نبيع قوالب."})]}),s("div",{className:"grid md:grid-cols-3 gap-5",children:n.map((h)=>s("div",{className:`relative rounded-[20px] p-[1px] overflow-hidden ${h.accent?"bg-gradient-to-b from-[#FF0033] to-[#FF0033]/10":"bg-white/[0.08]"}`,children:v("div",{className:`rounded-[19px] h-full flex flex-col overflow-hidden ${h.accent?"bg-[#121212]":"bg-[#111]"}`,children:[v("div",{className:"relative aspect-[16/9] w-full overflow-hidden rounded-t-[19px] border-b border-white/[0.06] bg-[#0a0a0a]",children:[h.image?v(Ti,{children:[s("img",{src:h.image,alt:h.name,className:"absolute inset-0 w-full h-full object-cover"}),s("div",{className:"absolute inset-0 bg-gradient-to-t from-black via-black/30 to-transparent"}),s("div",{className:"absolute inset-0 bg-gradient-to-tr from-black/60 via-transparent to-[#FF0033]/30 opacity-80"}),s("div",{className:"absolute inset-0 bg-[radial-gradient(circle_at_80%_20%,rgba(255,0,51,0.35),transparent_50%)]"})]}):v("div",{className:"absolute inset-0 bg-gradient-to-br from-[#111] via-[#1a0a0f] to-[#FF0033]/40",children:[s("div",{className:"absolute inset-0 opacity-20",style:{backgroundImage:"repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(255,255,255,0.4) 2px, rgba(255,255,255,0.4) 3px)"}}),s("div",{className:"absolute inset-0 flex items-center justify-center",children:s("span",{className:"font-orbitron font-black tracking-[0.3em] text-white/20 text-[12px]",children:"NO IMAGE"})})]}),v("div",{className:"absolute top-3 left-3 flex items-center gap-2 px-2.5 py-1 rounded-full bg-black/60 backdrop-blur border border-white/10 text-[9px] font-orbitron tracking-widest text-white/70",children:[s("span",{className:"w-1.5 h-1.5 rounded-full bg-[#FF0033] shadow-[0_0_8px_#FF0033] animate-pulse"})," ",h.name]}),h.badge&&s("div",{className:"absolute top-3 right-3 bg-[#FF0033] text-white text-[9px] font-orbitron tracking-[0.2em] px-2.5 py-1 rounded-full shadow-[0_0_16px_rgba(255,0,51,0.6)]",children:h.badge})]}),v("div",{className:"p-6 md:p-7 flex flex-col flex-1",children:[v("div",{className:"flex justify-between items-start",children:[s("div",{className:"font-orbitron font-black text-[18px] tracking-[0.2em]",children:h.name}),s("div",{className:"w-7 h-7 rounded-full bg-white/[0.06] border border-white/10 flex items-center justify-center",children:s("div",{className:"w-1.5 h-1.5 rounded-full bg-[#FF0033]"})})]}),v("div",{className:"mt-4 flex items-baseline gap-2",children:[s("span",{className:"font-orbitron font-black text-[42px] leading-none",children:h.price}),s("span",{className:"text-[14px] text-white/50",children:"MAD"})]}),s("div",{className:"mt-6 space-y-3 flex-1",children:h.features.map((M,R)=>v("div",{className:"flex gap-2 text-[13px] text-white/70",children:[s(Nr,{size:16,className:"text-[#FF0033] mt-[2px] shrink-0"})," ",s("span",{children:M})]},R))}),s("button",{onClick:()=>Ic(h.name),className:`order-btn mt-8 w-full py-[14px] rounded-full font-orbitron font-bold text-[11px] tracking-[0.2em] ${h.accent?"btn-blood":"bg-white text-black hover:bg-white/90"} transition`,children:"اطلب هذه الباقة"})]})]})},h.id))}),v("div",{className:"mt-6 rounded-[14px] bg-[rgba(255,0,51,0.08)] border border-[rgba(255,0,51,0.2)] px-5 py-4 text-[12px] md:text-[13px] text-[#ff8a9e] flex gap-3",children:[s("div",{className:"w-5 h-5 rounded-full bg-[#FF0033]/20 border border-[#FF0033]/30 flex items-center justify-center shrink-0 text-[12px]",children:"!"}),s("span",{children:"مدة التسليم يتم تحديدها حسب نوع وحجم الموقع المطلوب وليست 24 ساعة ثابتة لضمان الجودة."})]})]}),v("section",{id:"portfolio",className:"mx-auto max-w-[1280px] px-5 md:px-8 py-20 border-t border-white/[0.06]",children:[v("div",{className:"flex items-center gap-3 mb-10",children:[s("div",{className:"w-[40px] h-[1px] bg-[#FF0033]"}),s("span",{className:"font-orbitron text-[11px] tracking-[0.4em] text-[#FF0033]",children:"04 / SELECTED WORK"})]}),s("div",{className:"grid md:grid-cols-3 gap-5",children:r.map((h)=>v("div",{className:"group relative rounded-[18px] overflow-hidden bg-[#111] border border-white/[0.06] hover:border-[#FF0033]/30 transition",children:[s("div",{className:"aspect-[4/3] overflow-hidden",children:s("img",{src:h.image,alt:h.name,className:"w-full h-full object-cover group-hover:scale-[1.05] transition duration-700"})}),s("div",{className:"absolute inset-0 bg-gradient-to-t from-black via-black/20 to-transparent"}),v("div",{className:"absolute bottom-0 left-0 right-0 p-4 flex justify-between items-end",children:[v("div",{children:[s("div",{className:"font-orbitron font-bold text-[13px] tracking-[0.15em]",children:h.name}),s("div",{className:"text-[11px] text-white/50 mt-1",children:h.type})]}),s("div",{className:"w-8 h-8 rounded-full bg-white/10 backdrop-blur border border-white/10 flex items-center justify-center",children:s(Nt,{size:14})})]})]},h.id))})]}),v("section",{className:"mx-auto max-w-[1280px] px-5 md:px-8 py-20",children:[v("div",{className:"flex items-center gap-3 mb-10",children:[s("div",{className:"w-[40px] h-[1px] bg-[#FF0033]"}),s("span",{className:"font-orbitron text-[11px] tracking-[0.4em] text-[#FF0033]",children:"05 / TESTIMONIALS"})]}),s("div",{className:"grid md:grid-cols-2 lg:grid-cols-4 gap-4",children:u.map((h)=>v("div",{className:"glass rounded-[18px] p-5",children:[s("div",{className:"flex text-[#FFD700] text-[12px]",children:Array.from({length:h.stars}).map((M,R)=>s(Ir,{size:14,fill:"#FFD700"},R))}),v("p",{className:"mt-4 text-[14px] leading-[1.7] text-white/80",children:['"',h.text,'"']}),v("div",{className:"mt-5 flex items-center gap-3 border-t border-white/10 pt-4",children:[s("div",{className:"w-8 h-8 rounded-full bg-[#1a1a1a] border border-white/10 flex items-center justify-center font-orbitron text-[11px]",children:h.name[0]}),v("div",{children:[s("div",{className:"text-[13px] font-bold",children:h.name}),s("div",{className:"text-[11px] text-white/40",children:h.city})]})]})]},h.id))})]}),v("section",{className:"mx-auto max-w-[1280px] px-5 md:px-8 py-20 border-y border-white/[0.06] relative",children:[s("div",{className:"absolute left-1/2 top-20 bottom-20 w-[1px] bg-gradient-to-b from-transparent via-[#FF0033]/40 to-transparent hidden md:block"}),s("div",{className:"grid md:grid-cols-3 gap-8 relative",children:[{n:"01",t:"تختار باقة",d:"تختار المستوى الذي يناسب هيبتك: STARTER / BUSINESS / EMPIRE"},{n:"02",t:"تملأ اسمك ورقمك ووصف موقعك",d:"فورم بسيط: اسمك، واتسابك، و وصف دقيق لما تريده. كل شيء محفوظ بأمان."},{n:"03",t:"نتواصل ونحدد الثمن والمدة حسب موقعك",d:"نتصل بك على الواتساب، نناقش التفاصيل، ونحدد السعر النهائي والمدة بكل شفافية."}].map((h)=>v("div",{className:"relative glass rounded-[20px] p-7",children:[s("div",{className:"font-orbitron font-black text-[48px] leading-none text-white/[0.06]",children:h.n}),s("div",{className:"mt-3 font-bold text-[16px]",children:h.t}),s("div",{className:"mt-3 text-[13px] leading-[1.7] text-white/50",children:h.d}),s("div",{className:"mt-6 w-8 h-[2px] bg-[#FF0033]"})]},h.n))})]}),v("section",{className:"mx-auto max-w-[1280px] px-5 md:px-8 py-20",children:[v("div",{className:"flex items-center gap-3 mb-10",children:[s("div",{className:"w-[40px] h-[1px] bg-[#FF0033]"}),s("span",{className:"font-orbitron text-[11px] tracking-[0.4em] text-[#FF0033]",children:"06 / FAQ"})]}),v("div",{className:"grid md:grid-cols-[0.9fr_1.1fr] gap-10",children:[v("h2",{className:"font-orbitron font-black text-[32px] md:text-[42px] leading-[0.95]",children:["الأسئلة",s("br",{}),"الشائعة"]}),s("div",{className:"space-y-2",children:i.map((h)=>v("div",{className:"rounded-[14px] bg-[#111] border border-white/[0.07] overflow-hidden",children:[v("button",{onClick:()=>Mc(lu===h.id?null:h.id),className:"w-full flex justify-between items-center p-5 text-right",children:[s("span",{className:"text-[14px] font-bold",children:h.q}),s("span",{className:`w-6 h-6 rounded-full border border-white/15 flex items-center justify-center text-[12px] transition ${lu===h.id?"bg-[#FF0033] border-[#FF0033] rotate-45":""}`,children:"+"})]}),lu===h.id&&s("div",{className:"px-5 pb-5 text-[13px] leading-[1.8] text-white/60",children:h.a})]},h.id))})]})]}),s("section",{className:"mx-auto max-w-[1280px] px-5 md:px-8 pb-10",children:v("div",{className:"relative rounded-[28px] overflow-hidden bg-[#111] border border-white/[0.08] p-8 md:p-14",children:[s("div",{className:"absolute inset-0 bg-[radial-gradient(circle_at_70%_30%,rgba(255,0,51,0.25),transparent_60%)]"}),v("div",{className:"relative grid md:grid-cols-[1.2fr_0.8fr] gap-8 items-center",children:[v("div",{children:[v("h2",{className:"font-orbitron font-black text-[36px] md:text-[64px] leading-[0.9]",children:["جاهز لتصبح",s("br",{}),s("span",{className:"text-[#FF0033] glow-text",children:"مرعبا؟"})]}),s("p",{className:"mt-4 text-white/60 max-w-[420px]",children:"لا وقت للمواقع العادية. إذا كنت مستعد لتدفع ثمن الهيبة، نحن مستعدون لنصنعها."})]}),v("div",{className:"flex flex-col gap-3",children:[s("button",{onClick:()=>window.open(Gn(),"_blank"),className:"btn-blood py-5 rounded-full font-orbitron font-bold tracking-[0.2em] text-[13px]",children:"تواصل واتساب مباشر"}),s("a",{href:"#packages",className:"text-center py-4 rounded-full border border-white/15 text-[12px] font-orbitron tracking-widest hover:bg-white/5 transition",children:"اطلع على الباقات"})]})]})]})}),s("footer",{className:"border-t border-white/[0.06] py-10",children:v("div",{className:"mx-auto max-w-[1280px] px-5 md:px-8 flex flex-col md:flex-row justify-between gap-4 text-[11px] tracking-[0.2em] font-orbitron text-white/30",children:[v("div",{className:"flex gap-2",children:[s("span",{id:"or-trigger",onClick:Fc,className:"cursor-pointer select-none text-white hover:text-[#FF0033] transition font-black",children:"OR"}),s("span",{children:"STUDIO © 2026 — WHERE FEAR BECOMES ART"})]}),v("div",{className:"flex gap-6",children:[s("span",{children:"NADOR • MOROCCO"}),s("a",{href:Gn(),target:"_blank",rel:"noopener",className:"hover:text-white transition",children:g})]})]})}),p&&v("div",{className:"fixed inset-0 z-[100] flex items-center justify-center p-4",children:[s("div",{className:"absolute inset-0 bg-black/80 backdrop-blur-[12px]",onClick:()=>S(!1)}),s("div",{className:"relative w-full max-w-[480px] rounded-[20px] p-[1px] bg-gradient-to-b from-[#FF0033]/30 to-white/10",children:v("div",{className:"rounded-[19px] bg-[#111] p-6 md:p-8",children:[v("div",{className:"flex justify-between items-center mb-6",children:[v("div",{children:[v("div",{className:"font-orbitron font-black tracking-[0.2em] text-[14px]",children:["اطلب باقة ",s("span",{className:"text-[#FF0033]",children:z})]}),s("div",{className:"text-[11px] text-white/40 mt-1",children:"املأ بياناتك بدقة — نتواصل خلال ساعات"})]}),s("button",{onClick:()=>S(!1),className:"w-8 h-8 rounded-full bg-white/5 border border-white/10 flex items-center justify-center hover:bg-white/10",children:s(zt,{size:14})})]}),v("div",{className:"space-y-4",children:[v("div",{children:[s("label",{className:"text-[11px] tracking-widest text-white/50 font-orbitron",children:"الاسم الكامل"}),s("input",{id:"client-name",value:_.name,onChange:(h)=>T({..._,name:h.target.value}),placeholder:"الاسم الكامل",className:"mt-2 w-full rounded-[12px] bg-black border border-white/10 px-4 py-3 text-[14px] outline-none focus:border-[#FF0033]/50 focus:shadow-[0_0_0_3px_rgba(255,0,51,0.15)] transition",required:!0})]}),v("div",{children:[s("label",{className:"text-[11px] tracking-widest text-white/50 font-orbitron",children:"رقم الواتساب"}),s("input",{id:"client-phone",type:"tel",value:_.phone,onChange:(h)=>T({..._,phone:h.target.value}),placeholder:"رقم الواتساب الخاص بك",className:"mt-2 w-full rounded-[12px] bg-black border border-white/10 px-4 py-3 text-[14px] outline-none focus:border-[#FF0033]/50 transition",required:!0})]}),v("div",{children:[s("label",{className:"text-[11px] tracking-widest text-white/50 font-orbitron",children:"وصف دقيق للموقع"}),s("textarea",{id:"client-desc",value:_.desc,onChange:(h)=>T({..._,desc:h.target.value}),placeholder:"وصف دقيق للموقع الذي تريده... مثال: أريد موقع مطعم فيه قائمة طعام وحجز طاولات...",rows:4,className:"mt-2 w-full rounded-[12px] bg-black border border-white/10 px-4 py-3 text-[13px] leading-[1.6] outline-none focus:border-[#FF0033]/50 transition resize-none",required:!0})]})]}),v("div",{className:"mt-8 grid grid-cols-[1.4fr_0.6fr] gap-3",children:[s("button",{onClick:Lc,className:"btn-blood py-3 rounded-full font-orbitron font-bold text-[11px] tracking-[0.15em]",children:"إرسال الطلب عبر واتساب"}),s("button",{onClick:()=>S(!1),className:"py-3 rounded-full bg-white/[0.06] border border-white/10 font-orbitron text-[11px] tracking-widest hover:bg-white/[0.1] transition",children:"إلغاء"})]}),s("div",{className:"mt-4 text-[10px] text-white/30 text-center font-orbitron tracking-widest",children:"يتم الحفظ محليا + فتح واتساب تلقائيا"})]})})]}),Ve&&v("div",{className:"fixed inset-0 z-[200] flex items-center justify-center p-4",children:[s("div",{className:"absolute inset-0 bg-black/80 backdrop-blur-[12px]",onClick:()=>Kn(!1)}),v("div",{className:"relative w-full max-w-[340px] rounded-[16px] bg-[#111] border border-white/10 p-6",children:[s("div",{className:"font-orbitron font-bold text-[12px] tracking-[0.2em] mb-4",children:"ADMIN ACCESS"}),s("input",{type:"password",value:Di,onChange:(h)=>Mi(h.target.value),placeholder:"كلمة السر",className:"w-full rounded-[10px] bg-black border border-white/10 px-4 py-3 text-[14px] outline-none focus:border-[#FF0033]/50",autoFocus:!0,onKeyDown:(h)=>h.key==="Enter"&&Li()}),v("div",{className:"mt-4 flex gap-2",children:[s("button",{onClick:Li,className:"flex-1 btn-blood py-3 rounded-full text-[11px] font-orbitron font-bold tracking-widest",children:"دخول"}),s("button",{onClick:()=>Kn(!1),className:"px-5 py-3 rounded-full bg-white/5 border border-white/10 text-[11px]",children:"إغلاق"})]})]})]}),Dc&&v("div",{className:"fixed inset-0 z-[9999] bg-black overflow-auto",children:[v("div",{className:"sticky top-0 z-10 backdrop-blur-xl bg-black/90 border-b border-white/10 px-6 h-[60px] flex items-center justify-between",children:[v("div",{className:"flex items-center gap-6",children:[s("div",{className:"font-orbitron font-black tracking-[0.3em] text-[12px]",children:"OR ADMIN"}),v("div",{className:"hidden md:flex gap-2",children:[v("button",{onClick:()=>Yn("leads"),className:`px-4 py-2 rounded-full text-[11px] font-orbitron tracking-widest border ${Ke==="leads"?"bg-[#FF0033] border-[#FF0033] text-white":"border-white/10 text-white/50"}`,children:["الطلبات (",k.length,")"]}),s("button",{onClick:()=>Yn("content"),className:`px-4 py-2 rounded-full text-[11px] font-orbitron tracking-widest border ${Ke==="content"?"bg-[#FF0033] border-[#FF0033] text-white":"border-white/10 text-white/50"}`,children:"التحكم في الموقع"}),s("button",{onClick:()=>Yn("settings"),className:`px-4 py-2 rounded-full text-[11px] font-orbitron tracking-widest border ${Ke==="settings"?"bg-[#FF0033] border-[#FF0033] text-white":"border-white/10 text-white/50"}`,children:"إعدادات"})]})]}),v("button",{onClick:()=>Ii(!1),className:"flex items-center gap-2 px-4 py-2 rounded-full bg-white/5 border border-white/10 text-[11px] font-orbitron",children:[s(Rr,{size:14})," خروج"]})]}),v("div",{className:"md:hidden flex gap-2 p-4 border-b border-white/10",children:[s("button",{onClick:()=>Yn("leads"),className:`flex-1 py-2 rounded-full text-[11px] border ${Ke==="leads"?"bg-[#FF0033] border-[#FF0033]":"border-white/10"}`,children:"الطلبات"}),s("button",{onClick:()=>Yn("content"),className:`flex-1 py-2 rounded-full text-[11px] border ${Ke==="content"?"bg-[#FF0033] border-[#FF0033]":"border-white/10"}`,children:"المحتوى"}),s("button",{onClick:()=>Yn("settings"),className:`flex-1 py-2 rounded-full text-[11px] border ${Ke==="settings"?"bg-[#FF0033] border-[#FF0033]":"border-white/10"}`,children:"إعدادات"})]}),v("div",{className:"max-w-[1200px] mx-auto p-6",children:[Ke==="leads"&&v("div",{className:"space-y-6",children:[v("div",{className:"flex flex-wrap gap-3",children:[v("div",{className:"glass rounded-full px-5 py-2 text-[12px] font-orbitron",children:["إجمالي الطلبات: ",s("span",{className:"text-[#FF0033] font-bold",children:k.length})]}),v("button",{onClick:Oc,className:"flex items-center gap-2 px-5 py-2 rounded-full bg-white text-black text-[11px] font-orbitron font-bold",children:[s(zr,{size:14})," تصدير CSV"]}),s("button",{onClick:()=>{if(confirm("مسح كل الطلبات؟"))C([])},className:"px-5 py-2 rounded-full bg-[#FF0033]/10 border border-[#FF0033]/20 text-[#FF0033] text-[11px] font-orbitron",children:"مسح كل الطلبات"})]}),s("div",{className:"rounded-[16px] overflow-hidden border border-white/10 bg-[#111]",children:s("div",{className:"overflow-auto",children:v("table",{className:"w-full text-[13px]",children:[s("thead",{className:"bg-black/50 text-[11px] font-orbitron tracking-widest text-white/40",children:v("tr",{children:[s("th",{className:"text-right p-4",children:"الاسم"}),s("th",{className:"text-right p-4",children:"الرقم"}),s("th",{className:"text-right p-4",children:"الباقة"}),s("th",{className:"text-right p-4",children:"الوصف"}),s("th",{className:"text-right p-4",children:"التاريخ"}),s("th",{className:"p-4",children:"إجراء"})]})}),v("tbody",{children:[k.length===0&&s("tr",{children:s("td",{colSpan:6,className:"p-10 text-center text-white/30",children:"لا يوجد طلبات بعد"})}),k.map((h)=>v("tr",{className:"border-t border-white/5 hover:bg-white/[0.02]",children:[s("td",{className:"p-4 font-bold",children:h.name}),s("td",{className:"p-4 text-white/70 dir-ltr",children:h.phone}),s("td",{className:"p-4",children:s("span",{className:"px-2 py-1 rounded bg-[#FF0033]/15 text-[#FF0033] text-[11px]",children:h.package})}),s("td",{className:"p-4 max-w-[260px] truncate text-white/60",children:h.desc}),s("td",{className:"p-4 text-white/40 text-[11px]",children:new Date(h.date).toLocaleString("ar-MA")}),v("td",{className:"p-4 flex gap-2",children:[s("a",{href:`https://wa.me/${h.phone.replace(/[^0-9]/g,"")}?text=${encodeURIComponent(`مرحبا ${h.name}، معك عمر من OR STUDIO بخصوص باقة ${h.package}`)}`,target:"_blank",className:"w-8 h-8 rounded-full bg-[#25D366]/20 border border-[#25D366]/30 flex items-center justify-center hover:bg-[#25D366]/30",children:s(Pr,{size:14})}),s("button",{onClick:()=>C((M)=>M.filter((R)=>R.id!==h.id)),className:"w-8 h-8 rounded-full bg-[#FF0033]/15 border border-[#FF0033]/20 flex items-center justify-center",children:s(An,{size:14})})]})]},h.id))]})]})})})]}),Ke==="content"&&v("div",{className:"space-y-10",children:[v("div",{className:"glass rounded-[20px] p-6",children:[v("div",{className:"font-orbitron font-bold text-[13px] tracking-[0.2em] mb-6 flex items-center gap-2",children:[s(Tr,{size:16})," التحكم في الباقات — مع الصور"]}),s("div",{className:"grid md:grid-cols-3 gap-5",children:n.map((h,M)=>v("div",{className:"rounded-[14px] bg-black border border-white/10 p-4 space-y-3",children:[s("input",{value:h.name,onChange:(R)=>{let D=[...n];D[M].name=R.target.value,t(D)},className:"w-full rounded-[8px] bg-[#111] border border-white/10 px-3 py-2 text-[13px]",placeholder:"اسم الباقة"}),s("input",{value:h.price,onChange:(R)=>{let D=[...n];D[M].price=R.target.value,t(D)},className:"w-full rounded-[8px] bg-[#111] border border-white/10 px-3 py-2 text-[13px]",placeholder:"السعر"}),s("textarea",{value:h.features.join(`
`),onChange:(R)=>{let D=[...n];D[M].features=R.target.value.split(`
`),t(D)},rows:6,className:"w-full rounded-[8px] bg-[#111] border border-white/10 px-3 py-2 text-[12px]",placeholder:"ميزة كل سطر"}),s("input",{value:h.badge||"",onChange:(R)=>{let D=[...n];D[M].badge=R.target.value,t(D)},className:"w-full rounded-[8px] bg-[#111] border border-white/10 px-3 py-2 text-[12px]",placeholder:"Badge"}),v("div",{className:"pt-3 border-t border-white/10 space-y-2",children:[s("label",{className:"text-[11px] tracking-[0.15em] text-white/60 font-orbitron",children:"صورة الباقة (رابط URL)"}),v("div",{className:"flex gap-2 items-center",children:[s("input",{type:"text",className:"package-image-input flex-1 rounded-[8px] bg-[#111] border border-white/10 px-3 py-2 text-[11px] outline-none focus:border-[#FF0033]/50",placeholder:"https://...",value:h.image||"",onChange:(R)=>{let D=[...n];D[M].image=R.target.value,t(D)}}),h.image&&s("img",{src:h.image,alt:"preview",className:"w-[60px] h-[40px] rounded-[6px] object-cover border border-white/10 shrink-0"})]}),v("div",{className:"flex gap-2",children:[v("button",{type:"button",onClick:()=>Uc(M),className:"flex-1 py-2 rounded-[8px] bg-white/10 border border-white/10 text-[11px] font-orbitron tracking-widest hover:bg-white/15 transition flex items-center justify-center gap-1",children:[s(Nn,{size:12})," رفع صورة"]}),h.image&&s("button",{type:"button",onClick:()=>{let R=[...n];R[M].image="",t(R)},className:"px-3 py-2 rounded-[8px] bg-[#FF0033]/10 border border-[#FF0033]/20 text-[#FF0033] text-[11px] hover:bg-[#FF0033]/20",children:"حذف"})]}),s("div",{className:"text-[10px] text-white/30 leading-[1.4]",children:"الصورة تظهر مباشرة في الموقع بدون تحديث. يمكنك رفع Base64 أو وضع رابط خارجي."})]})]},h.id))})]}),v("div",{className:"glass rounded-[20px] p-6",children:[v("div",{className:"flex justify-between items-center mb-6",children:[s("div",{className:"font-orbitron font-bold text-[13px] tracking-[0.2em]",children:"المواقع المخدومة"}),v("button",{onClick:()=>l([...r,{id:Date.now().toString(),name:"NEW PROJECT",type:"نوع",image:"https://images.unsplash.com/photo-1497366216548-37526070297c?q=80&w=800&auto=format&fit=crop"}]),className:"flex items-center gap-2 px-4 py-2 rounded-full bg-white text-black text-[11px] font-bold",children:[s(Nn,{size:14})," إضافة"]})]}),s("div",{className:"grid md:grid-cols-2 gap-4",children:r.map((h,M)=>v("div",{className:"rounded-[12px] bg-black border border-white/10 p-3 flex gap-3",children:[s("img",{src:h.image,className:"w-16 h-16 rounded-[8px] object-cover",alt:""}),v("div",{className:"flex-1 space-y-2",children:[s("input",{value:h.name,onChange:(R)=>{let D=[...r];D[M].name=R.target.value,l(D)},className:"w-full rounded-[6px] bg-[#111] border border-white/10 px-2 py-1 text-[12px]"}),v("div",{className:"flex gap-2",children:[s("input",{value:h.type,onChange:(R)=>{let D=[...r];D[M].type=R.target.value,l(D)},className:"flex-1 rounded-[6px] bg-[#111] border border-white/10 px-2 py-1 text-[11px]",placeholder:"النوع"}),s("input",{value:h.image,onChange:(R)=>{let D=[...r];D[M].image=R.target.value,l(D)},className:"flex-[2] rounded-[6px] bg-[#111] border border-white/10 px-2 py-1 text-[11px]",placeholder:"رابط الصورة"})]})]}),s("button",{onClick:()=>l(r.filter((R)=>R.id!==h.id)),className:"w-8 h-8 rounded-full bg-[#FF0033]/15 flex items-center justify-center shrink-0",children:s(An,{size:12})})]},h.id))})]}),v("div",{className:"glass rounded-[20px] p-6",children:[v("div",{className:"flex justify-between items-center mb-6",children:[s("div",{className:"font-orbitron font-bold text-[13px] tracking-[0.2em]",children:"التعليقات والنجوم"}),v("button",{onClick:()=>o([...u,{id:Date.now().toString(),name:"اسم",city:"مدينة",text:"تعليق",stars:5}]),className:"flex items-center gap-2 px-4 py-2 rounded-full bg-white text-black text-[11px] font-bold",children:[s(Nn,{size:14})," إضافة"]})]}),s("div",{className:"grid md:grid-cols-2 gap-4",children:u.map((h,M)=>v("div",{className:"rounded-[12px] bg-black border border-white/10 p-3 space-y-2",children:[v("div",{className:"flex gap-2",children:[s("input",{value:h.name,onChange:(R)=>{let D=[...u];D[M].name=R.target.value,o(D)},className:"flex-1 rounded-[6px] bg-[#111] border border-white/10 px-2 py-1 text-[12px]",placeholder:"الاسم"}),s("input",{value:h.city,onChange:(R)=>{let D=[...u];D[M].city=R.target.value,o(D)},className:"flex-1 rounded-[6px] bg-[#111] border border-white/10 px-2 py-1 text-[12px]",placeholder:"المدينة"}),v("select",{value:h.stars,onChange:(R)=>{let D=[...u];D[M].stars=Number(R.target.value),o(D)},className:"rounded-[6px] bg-[#111] border border-white/10 px-2 py-1 text-[12px]",children:[s("option",{value:5,children:"5★"}),s("option",{value:4,children:"4★"}),s("option",{value:3,children:"3★"})]})]}),s("textarea",{value:h.text,onChange:(R)=>{let D=[...u];D[M].text=R.target.value,o(D)},className:"w-full rounded-[6px] bg-[#111] border border-white/10 px-2 py-1 text-[12px]",rows:2}),s("button",{onClick:()=>o(u.filter((R)=>R.id!==h.id)),className:"text-[11px] text-[#FF0033]",children:"حذف"})]},h.id))})]}),v("div",{className:"glass rounded-[20px] p-6",children:[s("div",{className:"font-orbitron font-bold text-[13px] tracking-[0.2em] mb-4",children:"من نحن - قصة عمر"}),s("textarea",{value:c,onChange:(h)=>y(h.target.value),rows:8,className:"w-full rounded-[12px] bg-black border border-white/10 p-4 text-[13px] leading-[1.7]"})]}),v("div",{className:"glass rounded-[20px] p-6",children:[v("div",{className:"flex justify-between items-center mb-4",children:[s("div",{className:"font-orbitron font-bold text-[13px] tracking-[0.2em]",children:"التعليمات FAQ"}),v("button",{onClick:()=>a([...i,{id:Date.now().toString(),q:"سؤال جديد",a:"جواب"}]),className:"px-3 py-1 rounded-full bg-white text-black text-[11px] font-bold flex items-center gap-1",children:[s(Nn,{size:12})," إضافة"]})]}),s("div",{className:"space-y-3",children:i.map((h,M)=>v("div",{className:"rounded-[12px] bg-black border border-white/10 p-3",children:[v("div",{className:"flex gap-2",children:[s("input",{value:h.q,onChange:(R)=>{let D=[...i];D[M].q=R.target.value,a(D)},className:"flex-1 rounded-[6px] bg-[#111] border border-white/10 px-2 py-2 text-[12px] font-bold",placeholder:"السؤال"}),s("button",{onClick:()=>a(i.filter((R)=>R.id!==h.id)),className:"px-2 text-[#FF0033]",children:s(An,{size:14})})]}),s("textarea",{value:h.a,onChange:(R)=>{let D=[...i];D[M].a=R.target.value,a(D)},className:"mt-2 w-full rounded-[6px] bg-[#111] border border-white/10 px-2 py-2 text-[12px]",rows:2,placeholder:"الجواب"})]},h.id))})]}),s("div",{className:"flex justify-end",children:v("div",{className:"flex items-center gap-2 text-[11px] text-white/40 font-orbitron",children:[s(Mr,{size:14})," يتم الحفظ تلقائيا في LocalStorage"]})})]}),Ke==="settings"&&v("div",{className:"space-y-6 max-w-[600px]",children:[v("div",{className:"glass rounded-[20px] p-6",children:[s("div",{className:"font-orbitron font-bold text-[13px] tracking-[0.2em] mb-4",children:"رقم الواتساب العام"}),s("input",{value:g,onChange:(h)=>m(h.target.value),className:"w-full rounded-[12px] bg-black border border-white/10 px-4 py-3 text-[14px] dir-ltr",placeholder:"+212631922433"}),s("div",{className:"mt-3 text-[11px] text-white/40",children:"سيتم استخدامه في كل أزرار الواتساب + رسائل الطلبات. مثال: +212631922433"})]}),s("div",{className:"glass rounded-[20px] p-6",children:v("div",{className:"text-[12px] text-white/60 leading-[1.8]",children:["• اضغط 5 مرات بسرعة على كلمة OR في الفوتر لفتح لوحة التحكم",s("br",{}),"• كلمة السر: 082009",s("br",{}),"• كل البيانات محفوظة في LocalStorage للمتصفح الحالي",s("br",{}),"• تصدير CSV متاح لعمل نسخة احتياطية"]})})]})]})]}),A&&v("div",{className:"fixed bottom-6 left-1/2 -translate-x-1/2 z-[300] px-5 py-3 rounded-full bg-[#111] border border-[#FF0033]/30 shadow-[0_0_30px_rgba(255,0,51,0.3)] text-[13px] font-bold flex items-center gap-2",children:[s("span",{className:"w-2 h-2 rounded-full bg-[#FF0033] shadow-[0_0_10px_#FF0033]"})," ",A]})]})}Rc.createRoot(document.getElementById("root")).render(s(Tc.default.StrictMode,{children:s(Ri,{})}));
</script>
  <script>(function(){function m(a){var h=a.getAttribute("href");if(!h)return;try{var u=new URL(h,document.baseURI);if(((u.protocol==="http:"||u.protocol==="https:")&&u.host!==location.host)||u.protocol==="mailto:"||u.protocol==="tel:"||u.protocol==="sms:"){a.target="_blank";a.rel="noopener noreferrer";}}catch(e){}}function s(){document.querySelectorAll("a[href]").forEach(m);}if(document.readyState!=="loading"){s();}else{document.addEventListener("DOMContentLoaded",s);}document.addEventListener("click",function(e){var a=e.target&&e.target.closest&&e.target.closest("a[href]");if(a){m(a);}},true);})();</script>
  <script type="application/json" data-clippy-inline-media-manifest="1">{"version":1,"slots":[]}</script>
<script>(function(){var loc=location.href.replace(/#.*$/,"");var ATTR_NAMES=["data-product-id","data-productid","data-product_id","product-id","productid","product_id","data-source-entity-id","source-entity-id","source_entity_id","data-product","data-metadata","data-meta"];var DATASET_KEYS=["productId","productid","product_id","sourceEntityId","sourceentityid","source_entity_id","product","metadata","meta"];function readProductId(value){if(typeof value!=="string"||value.length===0)return null;if(/^[0-9]{6,}$/.test(value))return value;var match=value.match(/(?:product(?:_|-)?id|source(?:_|-)?entity(?:_|-)?id)["'=:\s]+([0-9]{6,})/i);return match?match[1]:null}function extractProductId(start){for(var node=start;node&&node!==document.body;node=node.parentElement){for(var i=0;i<ATTR_NAMES.length;i++){var attrValue=node.getAttribute&&node.getAttribute(ATTR_NAMES[i]);var attrProductId=readProductId(attrValue);if(attrProductId)return attrProductId}var dataset=node.dataset||null;if(dataset){for(var j=0;j<DATASET_KEYS.length;j++){var dataValue=dataset[DATASET_KEYS[j]];var dataProductId=readProductId(dataValue);if(dataProductId)return dataProductId}}}return null}function isInlineMediaSlotElement(node){return !!(node&&node.getAttribute&&node.getAttribute("data-clippy-inline-media-slot")!==null)}function findInlineMediaSlot(start){for(var node=start;node&&node!==document.body;node=node.parentElement){if(isInlineMediaSlotElement(node))return node}return null}function readInlineMediaUrl(node){if(!node)return null;return node.getAttribute&&((node.getAttribute("data-clippy-inline-media-url")||node.getAttribute("data-url")||node.getAttribute("data_url")))||node.href||null}function stripHash(url){return String(url).replace(/#.*$/,"")}function urlsMatch(a,b){if(!a||!b)return false;try{return stripHash(new URL(a,loc).href)===stripHash(new URL(b,loc).href)}catch(_){return stripHash(a)===stripHash(b)}}function isFirstPartyReelUrl(value){try{var url=new URL(value,loc);if(url.protocol!=="https:")return false;var host=url.hostname.toLowerCase();var supported=host==="instagram.com"||host.endsWith(".instagram.com")||host==="facebook.com"||host.endsWith(".facebook.com");return supported&&/\/reels?\//i.test(url.pathname)}catch(_){return false}}function isInlineMediaUrlClick(node,href){var slot=findInlineMediaSlot(node);if(!slot)return false;var slotUrl=readInlineMediaUrl(slot);if(slotUrl)return urlsMatch(href,slotUrl);return isFirstPartyReelUrl(href)}function findDataHref(start){for(var node=start;node&&node!==document.body;node=node.parentElement){if(node.getAttribute){var href=node.getAttribute("data-href")||node.getAttribute("data-url");if(href)return{href:href,node:node}}}return null}var nativeOpen=window.open;window.open=function(url){if(parent!==window&&typeof url==="string"&&/^https?:\/\//.test(url)){parent.postMessage({type:"ecto:usercontent-link-click",href:url},"*");return null}return nativeOpen?nativeOpen.apply(window,arguments):null};document.addEventListener("click",function(e){var target=e.target instanceof Element?e.target:null;if(!target)return;if(parent===window)return;var a=target.closest?target.closest("a[href]"):null;if(a&&a.href&&/^https?:\/\//.test(a.href)&&a.href.replace(/#.*$/,"")!==loc){if(isInlineMediaUrlClick(a,a.href))return;var productId=extractProductId(target)||extractProductId(a);if(productId){e.preventDefault();parent.postMessage({type:"ecto-artifact-link-click",productId:productId},"*");return}e.preventDefault();parent.postMessage({type:"ecto:usercontent-link-click",href:a.href},"*");return}var dataHref=findDataHref(target);if(dataHref&&/^https?:\/\//.test(dataHref.href)&&dataHref.href.replace(/#.*$/,"")!==loc){if(isInlineMediaUrlClick(dataHref.node,dataHref.href))return;e.preventDefault();parent.postMessage({type:"ecto:usercontent-link-click",href:dataHref.href},"*")}},true)})();</script><script>(function(){var FOCUS_TYPE="ecto:artifact-focus-request";var CLOSE_TYPE="ecto:artifact-close-request";function focusArtifactDocument(){var body=document.body;if(!body)return;try{window.focus();}catch(e){}if(!body.hasAttribute("tabindex"))body.setAttribute("tabindex","-1");try{body.focus({preventScroll:true});}catch(e){try{body.focus();}catch(e2){}}}window.addEventListener("message",function(event){if(event.source!==window.parent)return;var data=event.data;if(!data||typeof data!=="object"||data.type!==FOCUS_TYPE)return;if(document.readyState==="loading"){document.addEventListener("DOMContentLoaded",focusArtifactDocument,{once:true});return;}focusArtifactDocument();});window.addEventListener("keydown",function(event){if(event.key!=="Escape")return;window.setTimeout(function(){if(event.defaultPrevented)return;window.parent.postMessage({type:CLOSE_TYPE},"*");},0);});})();</script>
</body></html>
