# IndicWoff2
Webfonts for Indic Languages
The fonts have been derived from SakalBharati font provided at the below location:

http://cdac.in/index.aspx?id=dl_sakal_bharati_font
    
Fonts in ttf and Woff2 format. Since ttf fonts are large in size they are relatively hard to use directly on web. So a woff2 format of the same fonts is available for use in the web. woff2 is a compressed versino of the ttf and woff.

##Usage
woff2 can be used in a webpage/website by specifying the URL to woff2 file in css. Ex:
```css
@font-face {
    font-family: 'SakalBharati';    //replace SakarBharati with your custom name.
    src: url('RELATIVE-PATH-TO-WOFF2-FILE-FROM-CSS-FILE') format('woff2');
}

div {
    font-family: 'SakalBharati';     //the name that you've used in the @font-face
    font-style: normal;
    font-weight: normal;
}
```
You may need to check support for @font-face in respective browser documentations.

##Sakal Bharati
is a Unicode based Open Type font which includes 13 scripts in one font i.e. Assamese, Bengali, Devanagari, Gujarati, Kannada Malayalam, Meetei Mayek, Oriya, Ol Chiki, Punjabi, Telugu, Tamil & Urdu. It is a Monothick font wherein the Glyphs have equal thickness of the horizontal and vertical stems. The Font has same X height for all 13 scripts, which caters to almost all the 22 scheduled languages of India. It is a single font having more than 3698 glyphs. The glyphs across the languages are designed to have matching styles including English.

By making use of this font, website and/or application designing for Indian languages is greatly simplified.

###Salient Features:

*A large number of scripts are supported (all 22 scheduled languages) in one single font.
*Admits single thickness.
*All the glyphs have single height.
*Being Monothick, it is easily legible.
*Pleasing to the eye and can be deployed in a wide range of applications where readability is of prime importance.
*Supports Rupee Symbol.

###License
OFL Lincese is applied to the above files. Please read LICENSE_OFL.txt for more details.

###Warranty
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE
COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM
OTHER DEALINGS IN THE FONT SOFTWARE.
