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
     / e disjunctie
     ~ e implicatie
     = e echivalenta
     &, ^, * sunt conjunctii

 *Nefolosirea conventiilor duce la eroare*

#### [ EXEMPLE ]
      Screenshot 2021-12-18 184531.png

      (((P⇔Q)∨S)⇒T) devine (((P=Q)/S)~T)
      ((P⇔Q)∧((¬Q)∧(¬P))) devine ((P=Q)&((!Q)&(!P)))
      ((P⇔Q)∨((¬Q)∨P)) devine ((P=Q)/((!Q)/P))
      
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

[ Rusu Emanuel ]

Grupa 1, subgrupa 2

Facultatea de Matematica - Informatica, anul I

Prof: Adrian Craciun

Prof. seminar: Alexandra Fortis
