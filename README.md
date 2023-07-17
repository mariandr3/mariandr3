Αυτό το αρχείο README έχει δημιουργηθεί με σκοπό να παρουσιάσει τα αποτελέσματα της εργασίας που πραγματοποιήθηκε στο μάθημα "Τηλεπισκόπηση & Ανάλυση Εικόνων". 

Για το πρώτο ερώτημα της εργασίας, δημιουργήσαμε ένα γράφημα που παρουσιάζει τις τιμές των δεικτών NDVI και NDWI από την 1η Ιανουαρίου 2021 έως τις 18 Ιουνίου 2023.

Ο δείκτης NDVI αντιπροσωπεύει την παραλλακτικότητα της βλάστησης στην καλλιέργεια και κυμαίνεται από τιμές -1 έως 1. Τιμές μικρότερες από 0.1 υποδηλώνουν γυμνό έδαφος, τιμές από 0.2 έως 0.5 υποδεικνύουν την ύπαρξη βλάστησης, ενώ τιμές πάνω από 0.6 υποδεικνύουν πυκνή βλάστηση.

Από την άλλη, ο δείκτης NDWI μας επιτρέπει να ανιχνεύουμε περιοχές ή σημεία με ύπαρξη νερού. Οι τιμές του κυμαίνονται από -1 έως 1. Τιμές από -1 έως -0.3 υποδηλώνουν ξηρές επιφάνειες χωρίς νερό, τιμές από -0.3 έως 0 υποδεικνύουν λιγότερο ξηρές επιφάνειες αλλά χωρίς παρουσία νερού, τιμές από 0 έως 0.2 υποδεικνύουν μια μικρή ποσότητα νερού, ενώ τιμές πάνω από 0.2 υποδεικνύουν επιφάνειες με παρουσία νερού.

![ClimateEngine (2)](https://github.com/mariandr3/mariandr3/assets/139487823/4fb5ff63-c7fb-48f6-a718-262198dd1fc4)

Μπορούμε να παρατηρήσουμε ότι οι δείκτες ανεβαίνουν αρχικά, όταν η βλάστηση αρχίζει να αναπτύσσεται. Καθώς η καλλιέργεια ωριμάζει, οι τιμές των δεικτών αρχίζουν να μειώνονται.  Ωστόσο, είναι πιθανό να παρατηρήσουμε και απότομες αλλαγές στις τιμές των δεικτών, όπου ο δείκτης πέφτει απότομα και στη συνέχεια ανεβαίνει ξανά, παρατηρώντας μια περίοδο διακύμανσης.

Ωστόσο, σε ορισμένες περιπτώσεις όπου η καλλιέργεια υφίσταται συχνές κοπές, μπορεί να παρατηρηθούν απότομες αλλαγές στον δείκτη. Πιο συγκεκριμένα, όταν ο δείκτης βρίσκεται σε υψηλά επίπεδα, μπορεί να πέσει απότομα μετά από μια κοπή, και στη συνέχεια να ανέβει ξανά, επαναλαμβάνοντας αυτό το μοτίβο.



Για το δεύτερο ερώτημα της εργασίας, δημιουργήθηκε ένας ιστότοπος (https://github.com/mariandr3/mariandr3/blob/main/README.md) που εμφανίζει την παραλλακτικότητα του αγροτεμαχίου μας με βάση τους δείκτες GBNDVI, GRNDVI, RBNDVI και WDRVI. O ιστότοπος δημιουργήθηκε χρησιμοποιώντας το πρόγραμμα ArcMap, ενώ η δημιουργία ενός καταλόγου αρχείων με τη χρήση του QGIS μας επέτρεψε να κατασκευάσουμε τον ιστότοπο. 

Για την ανάκτηση των περιγραφικών δεδομένων για κάθε δείκτη, χρησιμοποιήσαμε το ArcMap και συγκεκριμένα το Attribute Table. Με τη βοήθεια της λειτουργίας "Export" στο ArcMap, εξήγγειλαμε τα δεδομένα που μας ενδιέφεραν και τα αποθηκεύσαμε σε ένα αρχείο Word. Αυτό μας επέτρεψε να έχουμε πρόσβαση στα περιγραφικά χαρακτηριστικά των δεικτών, πληροφορίες που μας βοηθούν να κατανοήσουμε την κατάσταση της βλάστησης και τις διακυμάνσεις των δεικτών.

Με αυτόν τον τρόπο, μπορέσαμε να αξιοποιήσουμε τα δεδομένα του Attribute Table και να τα οργανώσουμε σε ένα αρχείο Word για περαιτέρω ανάλυση και παρουσίαση των περιγραφικών χαρακτηριστικών των δεικτών στην εργασία μας.

<p>-----<"(https://github.com/mariandr3/mariandr3/assets/139487823/9c863940-e9d7-49dd-8599-442c90865f66)
 align="bottom" width="48" height="48">-----</p>![rbndvi_new]
