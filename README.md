- 👋 Hi, I’m chaouki chaouachi

Try this One ;)


procédure tri_selection_cc (liste L)
   n ← taille de L
   pour i allant de 1 à n-(i+1)
      min ← i
      pour j allant de i+1 à n
         si L[j] < L[min] alors
            min ← j
      fin pour
      si min ≠ i alors
         échanger L[i] et L[min]
   fin pour
fin procédure
