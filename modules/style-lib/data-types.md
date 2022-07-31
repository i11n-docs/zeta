# Data Types
<!--
TEMPLATE

## {DataTypeName}

**CSS Data Type:** [`<css-data-type>`][url-to-mdn]

{Description}

{Summary}

### Example{s}
#### {ExampleTitle}

{ExampleDescription}

{ExampleCode}

### References

* [{ReferenceName}]({ReferenceUrl}) - {ReferenceDescription}

-->

## CssAlphaValue

**CSS Data Type:** [`<alpha-value>`][mdn-alpha-value]

Sets the [alpha-channel][mdn-alpha-channel], or transparency, of a color.

A `CssAlphaValue` can be presented as a [`CssNumber`](#cssnumber) or a
[`CssPercentage`](#csspercentage).

As a [`CssNumber`](#cssnumber), the effective range is `0` (fully transparent)
to `1` (fully opaque). Negative values are clamped to `0` and values greater
than `1` are clamped to `1`. This value is effectively a 
[`CssPercentage`](#csspercentage) represented as a [`CssNumber`](#cssnumber).
i.e. A [`CssNumber`](#cssnumber) of `0.4` is equivalent to a
[`CssPercentage`](#csspercentage) of `"40%"`.

As a [`CssPercentage`](#csspercentage), `"0%"` and `"100%"` are equivalent to
`0` and `1`, respectively.

### Example
```jsx
const style1 = {
  //  CssAlphaValue
  opacity: 0.5,
  backgroundColor: "red",
  maxWidth: 200
};

const style2 = {
  //  CssAlphaValue
  opacity: "50%",
  backgroundColor: "blue",
  color: "black",
  padding: "10px"
};

const ExampleComponent = (props) => {
  return (
    <div style={style1}>
      <div style={style2}>&nbsp;</div>
    </div>
  );
};

const app = document.querySelector("#app");

ReactDOM.render(<ExampleComponent />, app);
```

---

## CssAngle

**CSS Data Type:** [`<angle>`][mdn-angle]

---

## CssAnglePercentage

**CSS Data Type:** [`<angle-percentage>`][mdn-angle-percentage]

---

## CssBasicShape

**CSS Data Type:** [`<basic-shape>`][mdn-basic-shape]

---

## CssBlendMode

**CSS Data Type:** [`<blend-mode>`][mdn-blend-mode]

---

## CssColor

**CSS Data Type:** [`<color>`][mdn-color]

---

## CssCustomIdent

**CSS Data Type:** [`<custom-ident>`][mdn-custom-ident]

---

## CssDimension

**CSS Data Type:** [`<dimension>`][mdn-dimension]

---

## CssDisplayBox

**CSS Data Type:** [`<display-box>`][mdn-display-box]

---

## CssDisplayInside

**CSS Data Type:** [`<display-inside>`][mdn-display-inside]

---

## CssDisplayInternal

**CSS Data Type:** [`<display-internal>`][mdn-display-internal]

---

## CssDisplayLegacy

**CSS Data Type:** [`<display-legacy>`][mdn-display-legacy]

---

## CssDisplayListitem

**CSS Data Type:** [`<display-list-item>`][mdn-display-list-item]

---

## CssDisplayOutside

**CSS Data Type:** [`<display-outside>`][mdn-display-outside]

---

## CssEasingFunction

**CSS Data Type:** [`<easing-function>`][mdn-easing-function]

---

## CssFilterFunction

**CSS Data Type:** [`<filter-function>`][mdn-filter-function]

---

## CssFlex

**CSS Data Type:** [`<flex>`][mdn-flex]

---

## CssFrequency

**CSS Data Type:** [`<frequency>`][mdn-frequency]

---

## CssFrequencyPercentage

**CSS Data Type:** [`<frequency-percentage>`][mdn-frequency-percentage]

---

## CssGradient

**CSS Data Type:** [`<gradient>`][mdn-gradient]

---

## CssHexColor

**CSS Data Type:** [`<hex-color>`][mdn-hex-color]

---

## CssIdent

**CSS Data Type:** [`<ident>`][mdn-ident]

---

## CssImage

**CSS Data Type:** [`<image>`][mdn-image]

---

## CssInteger

**CSS Data Type:** [`<integer>`][mdn-integer]

---

## CssLength

**CSS Data Type:** [`<length>`][mdn-length]

---

## CssLengthPercentage

**CSS Data Type:** [`<length-percentage>`][mdn-length-percentage]

---

## CssNumber

**CSS Data Type:** [`<number>`][mdn-number]

---

## CssPercentage

**CSS Data Type:** [`<number>`][mdn-alphavalue]

---

## CssPosition

**CSS Data Type:** [`<position>`][mdn-position]

---

## CssRatio

**CSS Data Type:** [`<ratio>`][mdn-ratio]

---

## CssResolution

**CSS Data Type:** [`<resolution>`][mdn-resolution]

---

## CssString

**CSS Data Type:** [`<string>`][mdn-string]

---

## CssTime

**CSS Data Type:** [`<time>`][mdn-time]

---

## CssTimePercentage

**CSS Data Type:** [`<percentage>`][mdn-percentage]

---

## CssTransformFunction

**CSS Data Type:** [`<transform-function>`][mdn-transform-function]

---

## CssTransitionValue

**CSS Data Type:** [`<transition>`][mdn-transition]

---

# Functional Notation

## CssMatrixFunction

**CSS Data Type:** [`matrix()`][mdn-matrix-fn]

---

## CssMatrix3dFunction

**CSS Data Type:** [`matrix3d()`][mdn-matrix3d-fn]

---

## CssPerspectiveFunction

**CSS Data Type:** [`perspective()`][mdn-perspective-fn]

---

## CssRotateFunction

**CSS Data Type:** [`rotate()`][mdn-rotate-fn]

---

## CssRotate3dFunction

**CSS Data Type:** [`rotate3d()`][mdn-rotate3d-fn]

---

## CssRotateXFunction

**CSS Data Type:** [`rotatex()`][mdn-rotatex-fn]

---

## CssRotateYFunction

**CSS Data Type:** [`rotatey()`][mdn-rotatey-fn]

---

## CssRotateZFunction

**CSS Data Type:** [`rotatez()`][mdn-rotatez-fn]

---

## CssScaleFunction

**CSS Data Type:** [`scale()`][mdn-scale-fn]

---

## CssScale3dFunction

**CSS Data Type:** [`scale3d()`][mdn-scale3d-fn]

---

## CssScaleXFunction

**CSS Data Type:** [`scalex()`][mdn-scalex-fn]

---

## CssScaleYFunction

**CSS Data Type:** [`scaley()`][mdn-scaley-fn]

---

## CssScaleZFunction

**CSS Data Type:** [`scalez()`][mdn-scalez-fn]

---

## CssSkewFunction

**CSS Data Type:** [`skew()`][mdn-skew-fn]

---

## CssSkewXFunction

**CSS Data Type:** [`skewx()`][mdn-skewx-fn]

---

## CssSkewYFunction

**CSS Data Type:** [`skewy()`][mdn-skewy-fn]

---

## CssTranslateFunction

**CSS Data Type:** [`translate()`][mdn-translate-fn]

---

## CssTranslate3dFunction

**CSS Data Type:** [`translate3d()`][mdn-translate3d-fn]

---

## CssTranslateXFunction

**CSS Data Type:** [`translatex()`][mdn-translatex-fn]

---

## CssTranslateYFunction

**CSS Data Type:** [`translatey()`][mdn-translatey-fn]

---

## CssTranslateZFunction

**CSS Data Type:** [`translatez()`][mdn-translatez-fn]

---

## CssCalcFunction

**CSS Data Type:** [`calc()`][mdn-calc-fn]

---

## CssClampFunction

**CSS Data Type:** [`clamp()`][mdn-clamp-fn]

---

## CssMaxFunction

**CSS Data Type:** [`max()`][mdn-max-fn]

---

## CssMinFunction

**CSS Data Type:** [`min()`][mdn-min-fn]

---

## 🧪 CssAbsFunction

> **Experimental**

**CSS Data Type:** [`abs()`][mdn-abs-fn]

---

## 🧪 CssAcosFunction

> **Experimental**

**CSS Data Type:** [`acos()`][mdn-acos-fn]

---

## 🧪 CssAsinFunction

> **Experimental**

**CSS Data Type:** [`asin()`][mdn-asin-fn]

---

## 🧪 CssAtanFunction

> **Experimental**

**CSS Data Type:** [`atan()`][mdn-atan-fn]

---

## 🧪 CssAtan2Function

> **Experimental**

**CSS Data Type:** [`atan2()`][mdn-atan2-fn]

---

## 🧪 CssCosFunction

> **Experimental**

**CSS Data Type:** [`cos()`][mdn-cos-fn]

---

## 🧪 CssExpFunction

> **Experimental**

**CSS Data Type:** [`exp()`][mdn-exp-fn]

---

## 🧪 CssHypotFunction

> **Experimental**

**CSS Data Type:** [`hypot()`][mdn-hypot-fn]

---

## 🧪 CssLogFunction

> **Experimental**

**CSS Data Type:** [`log()`][mdn-log-fn]

---

## 🧪 CssModFunction

> **Experimental**

**CSS Data Type:** [`mod()`][mdn-mod-fn]

---

## 🧪 CssPowFunction

> **Experimental**

**CSS Data Type:** [`pow()`][mdn-pow-fn]

---

## 🧪 CssRemFunction

> **Experimental**

**CSS Data Type:** [`rem()`][mdn-rem-fn]

---

## 🧪 CssRoundFunction

> **Experimental**

**CSS Data Type:** [`round()`][mdn-round-fn]

---

## 🧪 CssSignFunction

> **Experimental**

**CSS Data Type:** [`sign()`][mdn-sign-fn]

---

## 🧪 CssSinFunction

> **Experimental**

**CSS Data Type:** [`sin()`][mdn-sin-fn]

---

## 🧪 CssSqrtFunction

> **Experimental**

**CSS Data Type:** [`sqrt()`][mdn-sqrt-fn]

---

## 🧪 CssTanFunction

> **Experimental**

**CSS Data Type:** [`tan()`][mdn-tan-fn]

---

## CssBlurFunction

**CSS Data Type:** [`blur()`][mdn-blur-fn]

---

## CssBrightnessFunction

**CSS Data Type:** [`brightness()`][mdn-brightness-fn]

---

## CssContrastFunction

**CSS Data Type:** [`contrast()`][mdn-contrast-fn]

---

## CssDropShadowFunction

**CSS Data Type:** [`drop-shadow()`][mdn-drop-shadow-fn]

---

## CssGrayscaleFunction

**CSS Data Type:** [`grayscale()`][mdn-grayscale-fn]

---

## CssHueRotateFunction

**CSS Data Type:** [`hue-rotate()`][mdn-hue-rotate-fn]

---

## CssInvertFunction

**CSS Data Type:** [`invert()`][mdn-invert-fn]

---

## CssOpacityFunction

**CSS Data Type:** [`opacity()`][mdn-opacity-fn]

---

## CssSaturateFunction

**CSS Data Type:** [`saturate()`][mdn-saturate-fn]

---

## CssSepiaFunction

**CSS Data Type:** [`sepia()`][mdn-sepia-fn]

---

## 🧪 CssColorFunction

> **Experimental**

**CSS Data Type:** [`color()`][mdn-color-fn]

---

## 🧪 CssColorMixFunction

> **Experimental**

**CSS Data Type:** [`color-mix()`][mdn-color-mix-fn]

---

## 🧪 CssColorContrastFunction

> **Experimental**

**CSS Data Type:** [`color-contrast()`][mdn-color-contrast-fn]

---

## 🧪 CssDeviceCmykFunction

> **Experimental**

**CSS Data Type:** [`device-cmyk()`][mdn-device-cmyk-fn]

---

## CssHslFunction

**CSS Data Type:** [`hsl()`][mdn-hsl-fn]

---

## CssHslaFunction

**CSS Data Type:** [`hsla()`][mdn-hsla-fn]

---

## 🧪 CssHwbFunction

> **Experimental**

**CSS Data Type:** [`hwb()`][mdn-hwb-fn]

---

## 🧪 CssLabFunction

> **Experimental**

**CSS Data Type:** [`lab()`][mdn-lab-fn]

---

## 🧪 CssLchFunction

> **Experimental**

**CSS Data Type:** [`lch()`][mdn-lch-fn]

---

## 🧪 CssOkLabFunction

> **Experimental**

**CSS Data Type:** [`oklab()`][mdn-oklab-fn]

---

## 🧪 CssOkLchFunction

> **Experimental**

**CSS Data Type:** [`oklch()`][mdn-oklch-fn]

---

## CssRgbFunction

**CSS Data Type:** [`rgb()`][mdn-rgb-fn]

---

## CssRgbaFunction

**CSS Data Type:** [`rgba()`][mdn-rgba-fn]

---

## CssConicGradientFunction

**CSS Data Type:** [`conic-gradient()`][mdn-conic-gradient-fn]

---

## 🧪 CssImageFunction

> **Experimental**

**CSS Data Type:** [`image()`][mdn-image-fn]

---

## 🧪 CssImageSetFunction

> **Experimental**

**CSS Data Type:** [`image-set()`][mdn-image-set-fn]

---

## CssLinearGradientFunction

**CSS Data Type:** [`linear-gradient()`][mdn-linear-gradient-fn]

---

## CssRadialGradientFunction

**CSS Data Type:** [`radial-gradient()`][mdn-radial-gradient-fn]

---

## CssRepeatingLinearGradientFunction

**CSS Data Type:** [`repeating-linear-gradient()`][mdn-repeating-linear-gradient-fn]

---

## CssRepeatingRadialGradientFunction

**CSS Data Type:** [`repeating-radial-gradient()`][mdn-repeating-radial-gradient-fn]

---

## CssRepeatingConicGradientFunction

**CSS Data Type:** [`repeating-conic-gradient()`][mdn-repeating-conic-gradient-fn]

---

## CssCrossFadeFunction

**CSS Data Type:** [`cross-fade()`][mdn-cross-fade-fn]

---

## CssElementFunction

**CSS Data Type:** [`element()`][mdn-element-fn]

---

## CssPaintFunction

**CSS Data Type:** [`paint()`][mdn-paint-fn]

---

## CssCounterFunction

**CSS Data Type:** [`counter()`][mdn-counter-fn]

---

## CssCountersFunction

**CSS Data Type:** [`counters()`][mdn-counters-fn]

---

## CssSymbolsFunction

**CSS Data Type:** [`symbols()`][mdn-symbols-fn]

---

## CssStylisticFunction

**CSS Data Type:** [`stylistic()`][mdn-stylistic-fn]

---

## CssStylesetFunction

**CSS Data Type:** [`styleset()`][mdn-styleset-fn]

---

## CssCharacterVariantFunction

**CSS Data Type:** [`character-variant()`][mdn-character-variant-fn]

---

## CssSwashFunction

**CSS Data Type:** [`swash()`][mdn-swash-fn]

---

## CssOrnamentsFunction

**CSS Data Type:** [`ornaments()`][mdn-ornaments-fn]

---

## CssAnnotationFunction

**CSS Data Type:** [`annotation()`][mdn-annotation-fn]

---

## CssCircleFunction

**CSS Data Type:** [`circle()`][mdn-circle-fn]

---

## CssEllipseFunction

**CSS Data Type:** [`ellipse()`][mdn-ellipse-fn]

---

## CssInsetFunction

**CSS Data Type:** [`inset()`][mdn-inset-fn]

--- 

## CssPolygonFunction

**CSS Data Type:** [`polygon()`][mdn-polygon-fn]

---

## CssPathFunction

**CSS Data Type:** [`path()`][mdn-path-fn]

---

## CssAttrFunction

**CSS Data Type:** [`attr()`][mdn-attr-fn]

---

## CssEnvFunction

**CSS Data Type:** [`env()`][mdn-env-fn]

---

## CssUrlFunction

**CSS Data Type:** [`url()`][mdn-url-fn]

---

## CssVarFunction

**CSS Data Type:** [`var()`][mdn-var-fn]

---

## CssFitContentFunction

**CSS Data Type:** [`fit-content()`][mdn-fit-content-fn]

---

## CssMinMaxFunction

**CSS Data Type:** [`minmax()`][mdn-minmax-fn]

---

## CssRepeatFunction

**CSS Data Type:** [`repeat()`][mdn-repeat-fn]

---

<!-- Links -->
<!-- Properties -->
[mdn-alpha-value]: https://developer.mozilla.org/en-US/docs/Web/CSS/alpha-value "<alpha-value> - CSS: Cascading Style Sheets | MDN"
<!-- Functional Notation -->
[mdn-matrix-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/matrix "matrix() - CSS: Cascading Style Sheets | MDN"
[mdn-matrix3d-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/matrix3d "matrix3d() - CSS: Cascading Style Sheets | MDN"
[mdn-perspective-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/perspective "perspective() - CSS: Cascading Style Sheets | MDN"
[mdn-rotate-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotate "rotate() - CSS: Cascading Style Sheets | MDN"
[mdn-rotate3d-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotate3d "rotate3d() - CSS: Cascading Style Sheets | MDN"
[mdn-rotatex-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotatex "rotatex() - CSS: Cascading Style Sheets | MDN"
[mdn-rotatey-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotatey "rotatey() - CSS: Cascading Style Sheets | MDN"
[mdn-rotatez-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotatez "rotatez() - CSS: Cascading Style Sheets | MDN"
[mdn-scale-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scale "scale() - CSS: Cascading Style Sheets | MDN"
[mdn-scale3d-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scale3d "scale3d() - CSS: Cascading Style Sheets | MDN"
[mdn-scalex-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scalex "scalex() - CSS: Cascading Style Sheets | MDN"
[mdn-scaley-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scaley "scaley() - CSS: Cascading Style Sheets | MDN"
[mdn-scalez-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/scalez "scalez() - CSS: Cascading Style Sheets | MDN"
[mdn-skew-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/skew "skew() - CSS: Cascading Style Sheets | MDN"
[mdn-skewx-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/skewx "skewx() - CSS: Cascading Style Sheets | MDN"
[mdn-skewy-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/skewy "skewy() - CSS: Cascading Style Sheets | MDN"
[mdn-translate-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate "translate() - CSS: Cascading Style Sheets | MDN"
[mdn-translate3d-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate3d "translate3d() - CSS: Cascading Style Sheets | MDN"
[mdn-translatex-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translatex "translatex() - CSS: Cascading Style Sheets | MDN"
[mdn-translatey-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translatey "translatey() - CSS: Cascading Style Sheets | MDN"
[mdn-translatez-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translatez "translatez() - CSS: Cascading Style Sheets | MDN"

[mdn-calc-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/calc "calc() - CSS: Cascading Style Sheets | MDN"
[mdn-clamp-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/clamp "clamp() - CSS: Cascading Style Sheets | MDN"
[mdn-max-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/max "max() - CSS: Cascading Style Sheets | MDN"
[mdn-min-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/min "min() - CSS: Cascading Style Sheets | MDN"
[mdn-abs-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/abs "abs() - CSS: Cascading Style Sheets | MDN"
[mdn-acos-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "acos() - CSS: Cascading Style Sheets | MDN"
[mdn-asin-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "asin() - CSS: Cascading Style Sheets | MDN"
[mdn-atan-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "atan() - CSS: Cascading Style Sheets | MDN"
[mdn-atan2-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "atan2() - CSS: Cascading Style Sheets | MDN"
[mdn-cos-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "cos() - CSS: Cascading Style Sheets | MDN"
[mdn-exp-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "exp() - CSS: Cascading Style Sheets | MDN"
[mdn-hypot-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "hypot() - CSS: Cascading Style Sheets | MDN"
[mdn-log-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "log() - CSS: Cascading Style Sheets | MDN"
[mdn-mod-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "mod() - CSS: Cascading Style Sheets | MDN"
[mdn-pow-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "pow() - CSS: Cascading Style Sheets | MDN"
[mdn-rem-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "rem() - CSS: Cascading Style Sheets | MDN"
[mdn-round-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "round() - CSS: Cascading Style Sheets | MDN"
[mdn-sign-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/sign "sign() - CSS: Cascading Style Sheets | MDN"
[mdn-sin-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "sin() - CSS: Cascading Style Sheets | MDN"
[mdn-sqrt-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "sqrt() - CSS: Cascading Style Sheets | MDN"
[mdn-tan-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#math_functions "tan() - CSS: Cascading Style Sheets | MDN"

[mdn-blur-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/blur "blur() - CSS: Cascading Style Sheets | MDN"
[mdn-brightness-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/brightness "brightness() - CSS: Cascading Style Sheets | MDN"
[mdn-contrast-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/contrast "contrast() - CSS: Cascading Style Sheets | MDN"
[mdn-drop-shadow-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow "drop-shadow() - CSS: Cascading Style Sheets | MDN"
[mdn-grayscale-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/grayscale "grayscale() - CSS: Cascading Style Sheets | MDN"
[mdn-hue-rotate-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/hue-rotate "hue-rotate() - CSS: Cascading Style Sheets | MDN"
[mdn-invert-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/invert "invert() - CSS: Cascading Style Sheets | MDN"
[mdn-opacity-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/opacity "opacity() - CSS: Cascading Style Sheets | MDN"
[mdn-saturate-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/saturate "saturate() - CSS: Cascading Style Sheets | MDN"
[mdn-sepia-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/sepia "sepia() - CSS: Cascading Style Sheets | MDN"

[mdn-color-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/color "color() - CSS: Cascading Style Sheets | MDN"
[mdn-color-mix-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/color-mix "color-mix() - CSS: Cascading Style Sheets | MDN"
[mdn-color-contrast-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/color-contrast "color-contrast() - CSS: Cascading Style Sheets | MDN"
[mdn-device-cmyk-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/device-cmyk "device-cmyk() - CSS: Cascading Style Sheets | MDN"
[mdn-hsl-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/hsl "hsl() - CSS: Cascading Style Sheets | MDN"
[mdn-hsla-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/hsla "hsla() - CSS: Cascading Style Sheets | MDN"
[mdn-hwb-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/hwb "hwb() - CSS: Cascading Style Sheets | MDN"
[mdn-lab-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/lab "lab() - CSS: Cascading Style Sheets | MDN"
[mdn-lch-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/lch "lch() - CSS: Cascading Style Sheets | MDN"
[mdn-oklab-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/oklab "oklab() - CSS: Cascading Style Sheets | MDN"
[mdn-oklch-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/oklch "oklch() - CSS: Cascading Style Sheets | MDN"
[mdn-rgb-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/rgb "rgb() - CSS: Cascading Style Sheets | MDN"
[mdn-rgba-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/rgba "rgba() - CSS: Cascading Style Sheets | MDN"

[mdn-conic-gradient-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/conic-gradient "conic-gradient() - CSS: Cascading Style Sheets | MDN"
[mdn-image-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/image/image "image() - CSS: Cascading Style Sheets | MDN"
[mdn-image-set-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/image/image-set "image-set() - CSS: Cascading Style Sheets | MDN"
[mdn-linear-gradient-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient "linear-gradient() - CSS: Cascading Style Sheets | MDN"
[mdn-radial-gradient-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/radial-gradient "radial-gradient() - CSS: Cascading Style Sheets | MDN"
[mdn-repeating-linear-gradient-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/repeating-linear-gradient "repeating-linear-gradient() - CSS: Cascading Style Sheets | MDN"
[mdn-repeating-radial-gradient-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/repeating-radial-gradient "repeating-radial-gradient() - CSS: Cascading Style Sheets | MDN"
[mdn-repeating-conic-gradient-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/repeating-conic-gradient "repeating-conic-gradient() - CSS: Cascading Style Sheets | MDN"
[mdn-cross-fade-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/cross-fade "cross-fade() - CSS: Cascading Style Sheets | MDN"
[mdn-element-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/element "element() - CSS: Cascading Style Sheets | MDN"
[mdn-paint-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/image/image "paint() - CSS: Cascading Style Sheets | MDN"

[mdn-counter-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/counter "counter() - CSS: Cascading Style Sheets | MDN"
[mdn-counters-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/counters "counters() - CSS: Cascading Style Sheets | MDN"
[mdn-symbols-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/symbols "symbols() - CSS: Cascading Style Sheets | MDN"

[mdn-stylistic-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#font_functions "stylistic() - CSS: Cascading Style Sheets | MDN"
[mdn-styleset-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#font_functions "styleset() - CSS: Cascading Style Sheets | MDN"
[mdn-character-variant-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#font_functions "character-variant() - CSS: Cascading Style Sheets | MDN"
[mdn-swash-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#font_functions "swash() - CSS: Cascading Style Sheets | MDN"
[mdn-ornaments-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#font_functions "ornaments() - CSS: Cascading Style Sheets | MDN"
[mdn-annotation-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Functions#font_functions "annotation() - CSS: Cascading Style Sheets | MDN"

[mdn-circle-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape/circle "circle() - CSS: Cascading Style Sheets | MDN"
[mdn-ellipse-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape/ellipse "ellipse() - CSS: Cascading Style Sheets | MDN"
[mdn-inset-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape/inset "inset() - CSS: Cascading Style Sheets | MDN"
[mdn-polygon-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape/polygon "polygon() - CSS: Cascading Style Sheets | MDN"
[mdn-path-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape/path "path() - CSS: Cascading Style Sheets | MDN"

[mdn-attr-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/attr "attr() - CSS: Cascading Style Sheets | MDN"
[mdn-env-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/env "env() - CSS: Cascading Style Sheets | MDN"
[mdn-url-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/url "url() - CSS: Cascading Style Sheets | MDN"
[mdn-var-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/var "var() - CSS: Cascading Style Sheets | MDN"

[mdn-fit-content-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/fit-content "fit-content() - CSS: Cascading Style Sheets | MDN"
[mdn-minmax-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/minmax "minmax() - CSS: Cascading Style Sheets | MDN"
[mdn-repeat-fn]: https://developer.mozilla.org/en-US/docs/Web/CSS/repeat "repeat() - CSS: Cascading Style Sheets | MDN"
<!-- CSS Property References -->

<!-- MDN References -->
[mdn-alpha-channel]: https://developer.mozilla.org/en-US/docs/Glossary/Alpha "Alpha (alpha channel) - MDN Web Docs Glossary: Definitions of Web-related terms"