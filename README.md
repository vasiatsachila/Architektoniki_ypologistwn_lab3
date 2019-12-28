## Lab 3

### ερώτημα 1

1. a.Dynamic Power: Είναι η ενλεργεια που χρεισημοποιείτε από το κύκλωμα εν ώρα λειτουργείας. Εξαρτάται από την χωριτικότητα του συστήματος (total load capacitance), την παροχή τάσης (supply voltage) την συχνότητα του ρολογιού (cloak frequency) και τον συντελεστή δραστηριότητας (activity factor).

b. Leakage: Είναι η ενέργεια που καταναλώνεται από το σύστημα την ώρα που δεν εκτελεί κάτι. Προστείθεται στην μέση συνολική ενέργεια που καταναλώνει το σύστημα. 

c. Ένα μεγάλο χρονικά πρόγραμμα σίγουρα μειώνει το leakage καθώς δεν μένει ανενεργό (idle) το σύστημα για μεγάλο χρονικό διάστημα. Από την άλλη η Dynamic Power δεν έχει καμία άμεση εξάρτηση από τον χρονικό όγκο του προγράμματος. 

2.a. Θεωριτικά με καλή χρήση του επεξεργαστή που καταναλλώνει 40 Watt, ελαχιστοποίη του leakage και με σωστή εναλλαγή από τα διάφορα mode (sleep, dream) και φυσικά με σωστή επιλογή επεξεργαστή για την χρήση που χρειάζεται το σχετικό μηχάνημα θα μπορούσε ίσως να καταναλλώνει συνολικά λιγότερη μπαταρία. 

Having different sleep modes allows tradeoffs between
the power savings and the wakeup overhead with respect to
wakeup power and delay. For example, dream mode can save
50% more static power than sleep mode, but at the expense
of twice the wakeup delay and three times the wakeup energy. The user can specify power-saving modes for various
components.

b. 

3. Ο Xeon είναι ένας επεξεργαστής με πολύ μεγάλο leakage οπότε είναι ένας επεξεργαστής που γίνεται πιο αποδοτικός ως προς την ενεργεια που καταναλλώνει όταν είναι σε συνεχή χρήση. Αντίθετα αν τρέξει μόνο μία εφερμογή και μάλιστα 40 φορές γρηγορότερα από τον Α9 στον ίδιο χρόνο που θα "περιμένει" θα έχει πολύ μεγάλο leakage. +Νούμερα


### ερώτημα 2
