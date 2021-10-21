1. W pliku `index.html` pod tagiem `<body>` dodaj kod znajdujący się poniżej:
```
    <div class="box-of-star2">
<<<<<<< HEAD
        <div class="star star-position5"></div>
        <div class="star star-position6"></div>
        <div class="star star-position7"></div>
=======
        <div class="star star-position1"></div>
        <div class="star star-position2"></div>
        <div class="star star-position3"></div>
        <div class="star star-position4"></div>
>>>>>>> 1e1e5d6d715bf2a2b1c0302b27cf2307790fe9ca
      </div>
```

2. Skommituj zmiany i zrób push na zdalne repozytorium
3. Utwórz pull request do brancha `develop`
