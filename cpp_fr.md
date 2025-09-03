
1. Quelle est la différence entre le C, le C++ et le C# ? 
2. Quelle est la différence entre un pointeur et une référence en C++ ?
3. Qu’est-ce que le RAII (Resource Acquisition Is Initialization) et pourquoi est-ce important pour la gestion de la mémoire en C++ ?
4. Quelle est la différence entre `new`/`delete` et `malloc`/`free` en C++ ?
5. Pourquoi `new` est-il plus adapté à la programmation orientée objet ?
6. Comment est-ce que `delete[]` fait pour savoir combien d'éléments il doit supprimer ?
7. Comment la gestion de la mémoire diffère-t-elle entre C++ et C# ?
8. En quoi la compilation de C++ diffère-t-elle de celle de C# ?
9. À quoi sert `const_cast` en C++ ?
10. Quand utilise-t-on `dynamic_cast`, et comment fonctionne-t-il ?
11. Qu’est-ce que `reinterpret_cast` permet de faire ?
12. Dans quel cas utilise-t-on `static_cast` ?
13. 8. Qu’est-ce qu’un smart pointer en C++ ?
14. Quelle est la particularité de `unique_ptr` ?
15. Comment `shared_ptr` gère-t-il la mémoire partagée ?
16. Quelle est la différence entre `shared_ptr` et `weak_ptr`, et dans quel cas utilise-t-on un `weak_ptr` ?
17. Quels sont les avantages de l’approche orientée objet en C++ ?
18. Qu’est-ce qu’un constructeur en C++ ?
19. Quelle est la particularité syntaxique d’un constructeur ?
20. Pourquoi les constructeurs n’ont-ils pas de type de retour ?
21. Qu’est-ce qu’une fonction virtuelle en C++ ?
22. Quelles sont les règles à respecter avec les fonctions virtuelles ?
23. Pourquoi ne peut-on pas avoir de constructeur virtuel, mais un destructeur virtuel, si ?
24. Que se passe-t-il si on n’utilise pas le mot-clé `virtual` dans une hiérarchie de classes ?
25. Qu’est-ce qu’une fonction virtuelle pure ?
26. Qu’est-ce qu’une classe abstraite en C++ ?
27. Quel est le rôle des classes de base abstraites dans le polymorphisme en C++ ?
28. À quoi sert le mot-clé `const` en C++ ?
29. Quelle est la différence entre `const` et `#define` pour définir des constantes ?
30. Peut-on utiliser une variable `const` pour définir la taille d’un tableau ?
31. Qu’est-ce que l’object slicing en C++ ?
32. Dans quelle situation survient-il et quelles en sont les conséquences ?
33. Qu’est-ce qu’un template de fonction en C++ ? Et à quoi ça sert ? 
34. Quand est-ce qu'on doit utiliser un destructeur virtuel ? 
35. Quelle est la différence entre allouer de la mémoire sur la heap vs sur la stack ?
36. Explique le mot clé `inline`.
37. C'est quoi l'endianness ou boutisme en français ? 
38. Explique la méthode du `const-correctness`.
39. Quelle coût est associé à l'appel d'une fonction virtuelle ?
40. C'est quoi la taille d'un pointeur en C++ ? (le résultat de `sizeof`) ? 
41. Parles moi des mémoire caches L1 et L2 ?
42. Explique moi les `move semantics`
43. C'est quoi la différence entre `class` et `struct` en C++ ? 
44. Explique la règle des 5. Partage ton écran et implémente les.
45. Quelle est la différence entre allocation dynamique et allocation statique (stack) ?
46. Explique les mots-clés `constexpr`, `inline`, `noexcept`
47. C'est quoi la différence entre `std::vector` et `std::array` ?
48. C'est quoi la différence entre `std::map`, `std::vector`, `std::set`, `std::list`
49. Comment fonctionne `std::move` quand l'utiliser ? 
50. C'est quoi la différence entre pointeur et référence ?



51. C'est quoi l'alignement mémoire ? 
52. C'est quoi un `halword`, `word`, `dword`, `qword` ? 
53. Pourquoi est-ce que les mémoires les plus rapides sont aussi les plus petites ?
54. C'est quoi le déférencement ?
55. C'est quoi une stack frame ?
56. Est-ce qu'une fonction peut être vue comme un pointeur vers un ensemble d'instructions ?
57. Est-ce que la heap est une région de la mémoire RAM ?
58. Que signifie le mot clé `extern` ? 
59. Quand utiliser le `extern 'C'` ?
60. Quelles sont les étapes de compilation du C++ ?
61. Quels sont les différents états d'exécution d'un processus ?
62. Quel est le rôle du kernel ? 
63. Quelle est la différence entre la concurrence et le parallélisme ? 
64. Qu'est-ce que le name mangling ?
65. C'est quoi une `mutex` et une `sémaphore` ? Quelle est la différence entre les deux ?
66. C'est quoi le diamond problem ?
67. C'est quoi l'héritage virtuel  ?
68. Explique moi ce qu'est la table virtuelle.
69. C'est quoi le binding statique et dynamique en C++ ?  
70. Comment est-ce que tu affecterais un objet de type quelconque à un int ? 
71. Quel est l'effet de mettre `const` devant une fonction ?
72. C'est quoi la différence entre les lambda et les fonctions ? 
73. C'est quoi le prefetch ? 
74. C'est quoi le `cache locality` ? Code un exemple 

75. À quoi sert le mot-clé `friend` en C++ ?
76. C'est quoi la `forward declaration` ?
77. Que signifie le mot-clé `mutable` en C++ ? Dans quel cas est-ce qu'on l'utilise ?
78. C'est quoi un `std::optional`, quand est-ce qu'on l'utilise ?
79. Quelle est la différence entre un `std::optional` et un `unique_ptr` ?
80. Explique le mot clé `alignas` et la fonction `alignof`.
81. Comment est-ce que les mêmes statiques se comportent dans des classes avec des templates ou bien dans des fonctions ?
82. Quelle est la taille d'une classe qui n'aurait pas de membres (variables) à l'intérieur ? Pourquoi ? Qu'en est-il des classes avec seulement des méthodes (fonctions) ou encore des membres statiques ?
83. À quoi peut servir une classe vide ?
84. Est-ce que c'est une bonne idée d'avoir des membres constants dans une classe ? 
85. Que se passe-t-il si on effectue un move (déplacement de propriété) d'un objet vers un autre sachant que la classe n'a que des types primitifs ?
86. Comment est-ce qu'on déclare un tableau sur la stack en C++?
87. Quelle est la différence entre la stack et la heap ?
88. Dans une hiérarchie de classes A -> B -> C, dans quel ordre seront appelés les constructeurs ? 
89. Dans une hiérarchie de classes A -> B -> C, dans quel ordre seront appelés les destructeurs ?
90. C'est quoi le `cache miss` et le `cache hit` ?
91. Compare moi un tableau et une liste chaînée dans leur usage.
92. Pourquoi en C++ on a les types de données `map`, et `set`, et d'un autre côté on a leur version `unordered_map` et `unordered_set` ? 
93. Comment est-ce qu'on déclare une fonction pure ? 
94. C'est quoi une classe abstraite en C++ ?
95. Quand est-ce que un destructeur `virtual` est important et quand est-ce qu'il ne l'est pas ?
96. À quoi sert le mot-clé `final` en C++ ?
97. Parles moi de `template specialization`.
98. C'est quoi une variable atomique ?
99. C'est quoi le `padding` et le `packing` ?
100. À quoi sert la directive `#pragma once`
101. À quoi sert les directives `#pragma pack(push, n)` et `#pragma pack(pop)` ? Quand est-ce qu'il est pratique de les utiliser ?
