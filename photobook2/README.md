## :art: Notice
- This practice is created by [【HTML/CSS コーディング練習】入門編：フォトサイト2／LP](https://code-step.com/photo2-menu/)
- I don't own the copyrights to pictures in this practice. Here is the resource: </br>
  <a href="https://unsplash.com/ja/s/%E5%86%99%E7%9C%9F/%E5%AE%B6%E5%85%B7?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>の<a href="https://unsplash.com/@ka_idris?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Kam Idris</a>が撮影した写真 </br>
  <a href="https://unsplash.com/ja?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>の<a href="https://unsplash.com/@pixasquare?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Pixasquare</a>が撮影した写真 </br>
  <a href="https://unsplash.com/ja/s/%E5%86%99%E7%9C%9F/%E5%AE%B6%E5%85%B7?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>の<a href="https://unsplash.com/@spacejoy?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Spacejoy</a>が撮影した写真 </br>
  <a href="https://unsplash.com/ja/s/%E5%86%99%E7%9C%9F/%E5%AE%B6%E5%85%B7?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>の<a href="https://unsplash.com/@spacejoy?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Spacejoy</a>が撮影した写真 </br>
  <a href="https://unsplash.com/ja/s/%E5%86%99%E7%9C%9F/%E5%AE%B6%E5%85%B7?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>の<a href="https://unsplash.com/@pickawood?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Pickawood</a>が撮影した写真

## :wrench: Built with
- HTML
- CSS
- Responsive web design(@media (max-width: 768px))

## :hammer: I do this practice with
- BEM Naming
- Sass

##  :scroll: Problem and solution
- Different image size
```scss
// _style.scss
.photo__list {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-bottom: 45px;

  img {
    max-width: 49%;
    margin-bottom: 15px;
    vertical-align: bottom;
    object-fit: cover;
    object-position: 50% 50%;
  }
}

@media screen and (max-width: 768px) {
    img {
      max-width: 100%;
    }
}
```
