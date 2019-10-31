# 寶可夢圖鑑

---

此為 Vue 做成的 SPA 頁面。

並串接 Pokemon 的 Restful API。

使用者可以藉由輸入寶可夢編號，取得寶可夢的樣子與基本資料。

請先安裝 modules 來使用。



```
npm install
```

如果你喜歡，請給我一顆星，我會很感謝你。 If you like this, please give me a star. Thank you!!

# 寶可夢查詢(圖鑑版本)

---

<img src='https://raw.githubusercontent.com/tsen1220/pokedex-vue/master/src/assets/introduction.jpg' alt=''>

# 寶可夢查詢

---

<img src='https://raw.githubusercontent.com/tsen1220/pokedex-vue/master/src/assets/introduction1.jpg' alt=''>


API資料處理方面就不贅述。

下為router設定。

```
Vue router setting:

  routes: [
    {
      path: "/",
      name: "Home",
      component: Home
    },
    {
      path: "/Pokedex",
      name: "Pokedex",
      component: Pokedex
    },
    {
      path: "/PokeDict",
      name: "PokeDict",
      component: PokeDict
    }
  ]


```
