# Εργασίες 2020-2021

## 1. Χρωματισμός γράφου (αλγόριθμοι και πολυπλοκότητα - προπτυχιακό)

### Περίληψη εργασίας

Το πρόβλημα του χρωματισμού γραφήματος είναι ένα NP‐hard πρόβλημα συνδυαστικής βελτιστοποίησης. Αφορά την ανάθεση ενός χρώματος σε κάθε κορυφή ενός γραφήματος έτσι ώστε γειτονικές κορυφές να χρωματίζονται με διαφορετικό χρώμα (όπως στο ακόλουθο σχήμα), ενώ παράλληλα χρησιμοποιείται ο ελάχιστος αριθμός διαφορετικών χρωμάτων. Στην παρούσα εργασία ζητείται η υλοποίηση τεσσάρων αλγορίθμων χρωματισμού γραφημάτων και η εφαρμογή τους σε γνωστά προβλήματα από τη βιβλιογραφία.

![](https://iq.opengenus.org/content/images/2018/07/gc2.PNG)

* Χρωματισμός γράφου [wikipedia](https://en.wikipedia.org/wiki/Graph_coloring).
* [Graph Coloring Greedy Algorithm [O(V^2 + E) time complexity]](https://iq.opengenus.org/graph-colouring-greedy-algorithm/)

---

## 2. Χρονοπρογραμματισμός εξετάσεων Πανεπιστημίου (Αλγόριθμοι και προχωρημένες δομές δεδομένων - μεταπτυχιακό)

### Περίληψη εργασίας -

Η αποδοτική δημιουργία προγραμμάτων εξετάσεων είναι ένα σημαντικό και επαναλαμβανόμενο πρόβλημα το οποίο καλούνται να αντιμετωπίσουν τα εκπαιδευτικά ιδρύματα σε όλο τον κόσμο. Μια απλοποιημένη μορφή του προβλήματος έχει προταθεί το 1996 από τους Carter κ.ά. οι οποίοι διέθεσαν δημόσια 13 στιγμιότυπα προβλημάτων που εν συνεχεία χρησιμοποιήθηκαν σε πληθώρα επιστημονικών εργασιών χρονοπρογραμματισμού. Στα πλαίσια της παρούσας εργασίας ζητείται να κατασκευάσετε μια εφαρμογή που θα είναι σε θέση να παράγει λύσεις για τα προβλήματα αυτά.

* [Benchmark Data Sets in Exam Timetabling](http://www.asap.cs.nott.ac.uk/external/resources/)

---

## 3. Αποσπάσματα κώδικα

* [read_data.cpp](/app/src/read_data.cpp): ανάγνωση δεδομένων [car-s-92.stu](./app/datasets/car-f-92.stu), καταγραφή φοιτητών ανά εξέταση.
* [set_ops.cpp](/app/src/set_ops.cpp): εύρεση τομής ενός std::set<int> με ένα άλλο std::set<int>.
* [random_numbers.cpp](./app/src/random_numbers.cpp), [random_numbers2.cpp](./app/src/random_numbers2.cpp): παραγωγή ψεύδο-τυχαίων ακέραιων τιμών στο διάστημα [1,V].
* [greedy_coloring.cpp](./app/src/greedy_coloring.cpp): απεικόνιση γράφου ως λίστα γειτνίασης και greedy χρωματισμός του γράφου.
* [count_common_elements.cpp](./app/src/count_common_elements.cpp) εύρεση πλήθους κοινών στοιχείων ανάμεσα σε 2 vectors.
* [2d_array.cpp](./app/src/2d_array.cpp) δυναμικός δισδιάστατος πίνακας στη C++ (και στη C).

## 4. Ένα Project σε Eclipse 

Εγκατάσταση των λογισμικών:

* [tdm-gcc](https://jmeubank.github.io/tdm-gcc/)
* [Eclipse Installer](https://www.eclipse.org/downloads/packages/)


[Το project σε eclipse (περιέχει το αρχείο read_data.cpp)](https://github.com/chgogos/alco/tree/main/sample_eclipse_project)

---

## Εικόνες whiteboard

* [20201102](![](/img/20201102_aads.svg))
* [20201109](![](/img/20201109_aads.png))

