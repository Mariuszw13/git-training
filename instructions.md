<<<<<<< HEAD
## Osoba A

1. Przejdź z tej gałęzi (branch) na nową
2. Dodaj następujący fragment kodu w pliku `style.css`
```css
.astronaut{
    width: 250px;
    height: 300px;
    position: absolute;
    z-index: 11;
    top: calc(50% - 150px);
    left: calc(50% - 125px);
    -webkit-animation: astronaut 5s linear infinite;
}
.schoolbag{
    width: 200px;
    height: 150px;
    position: absolute;
    z-index: 10;
    top: calc(50% - 75px);
    left: calc(50% - 50px);
    background-color: red;
    border-radius: 50px 50px 0 0 / 30px 30px 0 0;
}
.head{
    width: 97px;
    height: 80px;
    position: absolute;
    z-index: 3;
    background: -webkit-linear-gradient(left, #e3e8eb 0%, #e3e8eb 50%, #fbfdfa 50%, #fbfdfa 100%);
    border-radius: 50%;
    top: 34px;
    left: calc(50% - 47.5px);
}
.head:after{
    content: "";
    width: 60px;
    height: 50px;
    position: absolute;
    top: calc(50% - 25px);
    left: calc(50% - 30px);
    background: -webkit-linear-gradient(top, #15aece 0%, #15aece 50%, #0391bf 50%, #0391bf 100%);
    border-radius: 15px;
}
.head:before{
    content: "";
    width: 12px;
    height: 25px;
    position: absolute;
    top: calc(50% - 12.5px);
    left: -4px;
    background-color: #618095;
    border-radius: 5px;
    box-shadow: 92px 0px 0px #618095;
}
.body{
    width: 85px;
    height: 100px;
    position: absolute;
    z-index: 2;
    background-color: #fffbff;
    border-radius: 40px / 20px;
    top: 105px;
    left: calc(50% - 41px);
    background: -webkit-linear-gradient(left, #e3e8eb 0%, #e3e8eb 50%, #fbfdfa 50%, #fbfdfa 100%);
}
```
3. Zrób commita z wprowadzonymi zmianami
4. Wypchnij zmiany na zdalne repozytorium
5. Poczekaj aż osoba B wprowadzi swoje zmiany
6. Sprawdź jak wygląda strona otwierając plik `index.html` w przeglądarce
7. Zrób reset swojego commita i popraw kod
8. Wypchnij zmiany na zdalne repozytorium używając przełącznika `-f` (force)

## Osoba B

1. Poczekaj aż osoba A umieści swoją gałąź ze zmianami na zdalnym repozytorium
2. Po tym jak osoba A umieściła swoje zmiany na zdalnym repozytorium, przejdź na utworzoną przez nią gałąź
3. Dodaj następujący fragment kodu w pliku `style.css`
```css
.panel{
    width: 60px;
    height: 40px;
    position: absolute;
    top: 20px;
    left: calc(50% - 30px);
    background-color: #102037;
  }
  .panel:before{
    content: "";
    width: 30px;
    height: 5px;
    position: absolute;
    top: 9px;
    left: 7px;
    background-color: #102037;
    box-shadow: 0px 9px 0px #102037, 0px 18px 0px #102037;
  }
  .panel:after{
    content: "";
    width: 8px;
    height: 8px;
    position: absolute;
    top: 9px;
    right: 7px;
    background-color: #102037;
    border-radius: 50%;
    box-shadow: 0px 14px 0px 2px #102037;
  }
  .arm{
    width: 80px;
    height: 30px;
    position: absolute;
    top: 121px;
    z-index: 2;
  }
  .arm-left{
    left: 30px;
    background-color: #102037;
    border-radius: 0 0 0 39px;
  }
  .arm-right{
    right: 30px;
    background-color: #102037;
    border-radius: 0 0 39px 0;
  }
  .arm-left:before,
  .arm-right:before{
    content: "";
    width: 30px;
    height: 70px;
    position: absolute;
    top: -40px;
  }
  .arm-left:before{
    border-radius: 50px 50px 0px 120px / 50px 50px 0 110px;
    left: 0;
    background-color: #102037;
  }
  .arm-right:before{
    border-radius: 50px 50px 120px 0 / 50px 50px 110px 0;
    right: 0;
    background-color: #102037;
  }
  .arm-left:after,
  .arm-right:after{
    content: "";
    width: 30px;
    height: 10px;
    position: absolute;
    top: -24px;
  }
  .arm-left:after{
    background-color: #102037;
    left: 0;
  }
  .arm-right:after{
    right: 0;
    background-color: #102037;
  }
  .leg{
      width: 30px;
      height: 40px;
      position: absolute;
      z-index: 2;
      bottom: 70px;
  }
  .leg-left{
      left: 76px;
      background-color: #102037;
      transform: rotate(20deg);
  }
  .leg-right{
      right: 73px;
      background-color: #102037;
      transform: rotate(-20deg)
  }
  .leg-left:before,
  .leg-right:before{
      content: '';
      width: 50px;
      height: 25px;
      position: absolute;
      bottom: -26px;
  }
  .leg-left:before{
      left: -20px;
      background-color: #102037;
      border-radius: 30px 0 0 0 ;
  }
  .leg-right:before{
      right: -20px;
      background-color: #102037;
      border-radius: 0 30px 0 0 ;
  }
```
3. Zrób commita z wprowadzonymi zmianami, nie wrzucaj ich na zdalne repozytorium
4. Poczekaj aż osoba A wprowadzi zmiany z punktów 6-8
5. Spróbój pobrać zmiany wprowadzone przez osobę A
=======
1. W pliku `index.html` pod tagiem `<body>` dodaj kod znajdujący się poniżej:
```
      <div class="box-of-star4">
<<<<<<< HEAD
        <div class="star star-position5"></div>
        <div class="star star-position6"></div>
        <div class="star star-position7"></div>
=======
        <div class="star star-position1"></div>
        <div class="star star-position2"></div>
        <div class="star star-position3"></div>
        <div class="star star-position4"></div>
>>>>>>> develop
      </div>
```

2. Skommituj zmiany i zrób push na zdalne repozytorium
3. Utwórz pull request do brancha `develop`
>>>>>>> 7c214e7184d3427ace6ee321792e15ab8ae4b6cd
