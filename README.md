# An Effective Approach to Conducting Randomized Controlled Trials Using Online Questionnaire Distribution Platforms

# Randomly distribute questionnaires
隨機分派問卷（或網址）Randomly assign questionnaires (or URLs)

## 介紹 Introduction
運用此專案code，滿足需要隨機派發不同版本問卷，或是隨機前往其中一個網址之需求 Use the code in this project to meet the need for randomly distributing different versions of questionnaires or redirecting users to one of several URLs at random.

## 使用方式 Instruction
在 [`url.js`](url.js) 中填入自己想要隨機派發的問卷網址們（注意頁面上提示的規則），其他檔案不須更動。 Simply add the URLs you want to randomly distribute in url.js (pay attention to the rules noted on the page). No other files need to be modified.

之後將 `index.html` 作為入口發布，當使用者進入時就會由程式隨機抽出其中一個網址並將使用者重新導向過去。 Then, publish index.html as the entry point. When users access this page, the script will randomly select one of the URLs and redirect them accordingly.

### 教學文 Tutorial
不才寫的一篇簡單教學文──[〈隨機分配問卷？讓 Github Pages 幫你吧！〉](https://hms5232.medium.com/%E9%9A%A8%E6%A9%9F%E5%88%86%E9%85%8D%E5%95%8F%E5%8D%B7-%E8%AE%93-github-pages-%E5%B9%AB%E4%BD%A0%E5%90%A7-764372f26cd9)，懇請各方斧正。 Here’s a simple tutorial wrote by original author: “Randomly Distribute Questionnaires? Let Github Pages Help!”. Your feedback is welcome!

### 範例 Example
![GitHub deployments](https://img.shields.io/github/deployments/hms5232/random-survey/github-pages)

本儲存庫的 Github Pages 將會依照 `url.js` 隨機將使用者導向本人的 Github 或 GitLab 等地方。👇  The GitHub Pages of this repository will randomly redirect users based on the URLs in url.js—for example, to my GitHub or GitLab, etc.👇
https://hms5232.github.io/random-survey/

## 鳴謝 Acknowledgments
本專案係參考[〈【html javascript】隨機分配問卷〉](http://g23988.blogspot.com/2015/08/html-javascript.html)之概念改寫而成。感謝前人大大的無私分享。This project was inspired by the concept from “【html javascript】Randomly Assign Questionnaires”. Many thanks to the original creator for their generous sharing.

## 其他版本 Other Versions
### GitLab 🦊
如果比較喜歡 GitLab 或有什麼原因偏好 GitLab，也可以參考 GitLab Pages 的版本：https://gitlab.com/hms5232/bird-screen-url If you prefer GitLab or have a reason to use it, a GitLab Pages version is available here: https://gitlab.com/hms5232/bird-screen-url

## LICNESE
See [LICENSE file](LICENSE).
