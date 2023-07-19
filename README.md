Αυτό το αρχείο README έχει δημιουργηθεί με σκοπό να παρουσιάσει τα αποτελέσματα της εργασίας που πραγματοποιήθηκε στο μάθημα "Τηλεπισκόπηση & Ανάλυση Εικόνων". 

Για το πρώτο ερώτημα της εργασίας, δημιουργήσαμε ένα γράφημα που παρουσιάζει τις τιμές των δεικτών NDVI και NDWI από την 1η Ιανουαρίου 2021 έως τις 18 Ιουνίου 2023.

Ο δείκτης NDVI αντιπροσωπεύει την παραλλακτικότητα της βλάστησης στην καλλιέργεια και κυμαίνεται από τιμές -1 έως 1. Τιμές μικρότερες από 0.1 υποδηλώνουν γυμνό έδαφος, τιμές από 0.2 έως 0.5 υποδεικνύουν την ύπαρξη βλάστησης, ενώ τιμές πάνω από 0.6 υποδεικνύουν πυκνή βλάστηση.

Από την άλλη, ο δείκτης NDWI μας επιτρέπει να ανιχνεύουμε περιοχές ή σημεία με ύπαρξη νερού. Οι τιμές του κυμαίνονται από -1 έως 1. Τιμές από -1 έως -0.3 υποδηλώνουν ξηρές επιφάνειες χωρίς νερό, τιμές από -0.3 έως 0 υποδεικνύουν λιγότερο ξηρές επιφάνειες αλλά χωρίς παρουσία νερού, τιμές από 0 έως 0.2 υποδεικνύουν μια μικρή ποσότητα νερού, ενώ τιμές πάνω από 0.2 υποδεικνύουν επιφάνειες με παρουσία νερού.

![ClimateEngine (2)](https://github.com/mariandr3/mariandr3/assets/139487823/4fb5ff63-c7fb-48f6-a718-262198dd1fc4)

Μπορούμε να παρατηρήσουμε ότι οι δείκτες ανεβαίνουν αρχικά, όταν η βλάστηση αρχίζει να αναπτύσσεται. Καθώς η καλλιέργεια ωριμάζει, οι τιμές των δεικτών αρχίζουν να μειώνονται.  Ωστόσο, είναι πιθανό να παρατηρήσουμε και απότομες αλλαγές στις τιμές των δεικτών, όπου ο δείκτης πέφτει απότομα και στη συνέχεια ανεβαίνει ξανά, παρατηρώντας μια περίοδο διακύμανσης.

Ωστόσο, σε ορισμένες περιπτώσεις όπου η καλλιέργεια υφίσταται συχνές κοπές, μπορεί να παρατηρηθούν απότομες αλλαγές στον δείκτη. Πιο συγκεκριμένα, όταν ο δείκτης βρίσκεται σε υψηλά επίπεδα, μπορεί να πέσει απότομα μετά από μια κοπή, και στη συνέχεια να ανέβει ξανά, επαναλαμβάνοντας αυτό το μοτίβο.



Για το δεύτερο ερώτημα της εργασίας, δημιουργήθηκε ένας ιστότοπος ((https://mariandr3.github.io/mariandr3/)) που εμφανίζει την παραλλακτικότητα του αγροτεμαχίου μας με βάση τους δείκτες GBNDVI, GRNDVI, RBNDVI και WDRVI. O ιστότοπος δημιουργήθηκε χρησιμοποιώντας το πρόγραμμα ArcMap, ενώ η δημιουργία ενός καταλόγου αρχείων με τη χρήση του QGIS μας επέτρεψε να κατασκευάσουμε τον ιστότοπο. 

Για την ανάκτηση των περιγραφικών δεδομένων για κάθε δείκτη, χρησιμοποιήσαμε το ArcMap και συγκεκριμένα το Attribute Table. Με τη βοήθεια της λειτουργίας "Export" στο ArcMap, εξήγγειλαμε τα δεδομένα που μας ενδιέφεραν και τα αποθηκεύσαμε σε ένα αρχείο Word. Αυτό μας επέτρεψε να έχουμε πρόσβαση στα περιγραφικά χαρακτηριστικά των δεικτών, πληροφορίες που μας βοηθούν να κατανοήσουμε την κατάσταση της βλάστησης και τις διακυμάνσεις των δεικτών.

Με αυτόν τον τρόπο, μπορέσαμε να αξιοποιήσουμε τα δεδομένα του Attribute Table και να τα οργανώσουμε σε ένα αρχείο Word για περαιτέρω ανάλυση και παρουσίαση των περιγραφικών χαρακτηριστικών των δεικτών στην εργασία μας.

![gbndvi](https://github.com/mariandr3/mariandr3/assets/139487823/b4f0ee6f-25bd-4447-8a8d-9db8598e7a10)


Oι δείκτες GBNDVI (Green-Blue Normalized Difference Vegetation Index), GRNDVI (Green-Red Normalized Difference Vegetation Index) και RBNDVI (Red-Blue Normalized Difference Vegetation Index) έχουν αποδειχθεί να έχουν στενή συσχέτιση με τον δείκτη LAI (Leaf Area Index), ο οποίος χρησιμοποιείται ως μέτρο της ποσότητας των φύλλων χλωροφύλλης σε μια περιοχή.

Αυτό συμβαίνει επειδή οι μπάντες GREEN και BLUE δείχνουν να αποτυπώνουν με μεγαλύτερη ακρίβεια την ανακλαστικότητα της χλωροφύλλης σε σχέση με τη RED μπάντα. Συγκεκριμένα, σε ένα υγιές φύλλο, η RED μπάντα απορροφάται περισσότερο από όλες τις άλλες. Ενώ, η μεγαλύτερη ανακλαστικότητα παρατηρείται στις μπάντες NIR και GREEN.

Οι δείκτες GBNDVI και GRNDVI είναι σχεδόν ίδιοι. Αυτό σημαίνει ότι οι NIR και RED μπάντες έχουν παρόμοια ποσοστά ανακλαστικότητας. Ωστόσο, ο δείκτης RBNDVI είναι λίγο υψηλότερος από τους άλλους δύο. Αυτό σημαίνει ότι οι RED και BLUE μπάντες έχουν μικρότερα ποσοστά ανακλαστικότητας από την GREEN μπάντα.


![grndvi](https://github.com/mariandr3/mariandr3/assets/139487823/c0310af0-ceb4-4e47-a937-fb9b895fd3d1)

Ο δείκτης WDRVI χρησιμοποιείται για να διορθώσει το πρόβλημα του κορεσμού (saturation) που παρουσιάζει ο δείκτης NDVI. Στην πραγματικότητα, αναφέρεται σε ένα συγκεκριμένο στάδιο ανάπτυξης των φυτών, όπου τα φύλλα φτάνουν σε κρίσιμα επίπεδα χρωστικών ουσιών. Κατά την φάση αυτή, η ανακλαστικότητα της κοντινής υπέρυθρης (NIR) μπάντας αυξάνεται, ενώ η ανακλαστικότητα της κόκκινης (Red) μπάντας παραμένει σταθερή, καθώς εξακολουθεί να απορροφάται από τα φυτά.

Ο δείκτης NDVI δεν είναι τόσο ακριβής κατά τη διάρκεια αυτού του σταδίου ανάπτυξης των φυτών. Για να αντιμετωπίσουμε αυτήν την αύξηση της ανακλαστικότητας της NIR μπάντας, χρησιμοποιούμε έναν συντελεστή βαρύτητας στον τύπο υπολογισμού του WDRVI. Αυτό μας επιτρέπει να διορθώσουμε τις ανωμαλίες και να λάβουμε μια καλύτερη και πιο ακριβή εικόνα σχετικά με την παραλλακτικότητα και την υγεία των φυτών σε αυτό το ειδικό στάδιο ανάπτυξης τους.

![rbndvi](https://github.com/mariandr3/mariandr3/assets/139487823/7cb4d3a1-c5b5-43e6-8e72-6d21470997f8)

Διαπιστώνουμε ότι η μέση τιμή του δείκτη έχει μεγάλη απόκλιση απο την μέγιστη και την ελάχιστη τιμή, υποδηλώνοντας την ύπαρξη παραλλακτικότητα. Αυτό φαίνεται επίσης και στον χάρτη μας, με τις χαμηλότερες τιμές του δείκτη να εμφανίζονται στην κάτω αριστερή μεριά και τις υψηλότερες τιμές στην πάνω δεξιά μεριά. 


![wdrvi](https://github.com/mariandr3/mariandr3/assets/139487823/dc4d48c3-9094-4e16-b30b-af6b477072e4)

Συνοψίζοντας, οι δείκτες GBNDVI, GRNDVI και RBNDVI είναι σχεδόν παρόμοιοι μεταξύ τους, καθώς οι μέσοι όροι τους είναι πολύ κοντά μεταξύ τους. Ωστόσο, η μεγαλύτερη συσχέτιση παρατηρείται μεταξύ των δεικτών GBNDVI και GRNDVI.

