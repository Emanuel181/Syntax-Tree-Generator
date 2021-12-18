#### Acest progra ia ca argument o propozitie si retuneaza sintaxa abstracta a acesteia folosind arborii binari

#### Ultima actualizare: 13.12.2021


#### [ REPOZITORIU ]

  Github

#### [ CUM SE RULEAZA CODUL ]

Programul se va descarca inainte apasand pe butonul verde "Code" si selectand "Downlad as ZIP" sau se poate copia direct codul sursa, din fisierul **main.py** intr-un IDE(cum ar fi **Visual Studio 2019**) sau editor de text(cum ar fi **Visual Studio Code**; in cazul acesta, va fi nevoie instalarea de extensii ce permit rularea de cod C++).

#### Cerinte ale input-ului

In analiza propozitiei nu trebuie sa existe spatii intre elemente, de asemena, vor trebui folosite conventii pentru conectorii logice, deoarece encoding-ul din C++ nu recunoaste decat o gama mica de caractere.
  
  ##### Conventii din cauza codifiarii in C++ a caracterelor
     ! e negatie
     / e disjunctie![146648999-32af3456-9203-4f91-871c-6da7fd0db944](https://user-images.githubusercontent.com/92999481/146649026-795afefd-e8e3-4e8e-8708-d0cb16dc88e6.png)

     ~ e implicatie
     = e echivalenta
     &, ^, * sunt conjunctii

 *Nefolosirea conventiilor duce la eroare*

#### [ EXEMPLE ]

      (((P⇔Q)∨S)⇒T) devine (((P=Q)/S)~T)
      ((P⇔Q)∧((¬Q)∧(¬P))) devine ((P=Q)&((!Q)&(!P)))
      ((P⇔Q)∨((¬Q)∨P)) devine ((P=Q)/((!Q)/P))
      
      ![Screenshot 2021-12-18 184416](https://user-images.githubusercontent.com/92999481/146649043-75d01c9c-7004-4bc8-936b-fb05f8552b36.png)
      ![Screenshot 2021-12-18 184440](https://user-images.githubusercontent.com/92999481/146649055-b72e27cc-c352-4fd8-ac2b-7d2441c8e703.png)
      ![Screenshot 2021-12-18 184531](https://user-images.githubusercontent.com/92999481/146649059-6146a2a3-1f6b-418f-a0ba-2d1f56d015a8.png)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

[ Rusu Emanuel ]

Grupa 1, subgrupa 2

Facultatea de Matematica - Informatica, anul I

Prof: Adrian Craciun


Prof. seminar: Alexandra Fortis
