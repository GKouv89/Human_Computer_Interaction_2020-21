﻿Επικοινωνία Ανθρώπου Μηχανής
Άσκηση 3
Φοιτητές:
Κωνσταντίνα Σταφυλά - 1115201700149
Αλέξανδρος Νεοφώτιστος - 1115201700270
Γεωργία Κουτίβα - 1115201700060

## Λειτουργικότητα:

### Εγγραφή
Η φόρμα εγγραφής διαφοροποιεί τον λογαριασμό που θα δημιουργηθεί με βάση την ιδιότητα του χρήστη. Ζητά από τον χρήστη να δηλώσει την ιδιότητά του: εργαζόμενος ή εργοδότης. Τα περισσότερα πεδία στην φόρμα αφορούν και τους δύο τύπους χρηστών: Ονοματεπώνυμο, Κωδικός (και επιβεβαίωση), ΑΦΜ. Αν ο χρήστης δηλώσει ότι θέλει να εγγραφεί ως εργοδότης, δηλώνει την επωνυμία της επιχείρησής του και την ΔΟΥ αυτής. Αν ο χρήστης δηλώσει ότι θέλει να εγγραφεί ως εργαζόμενος, επιλέγει από μία λίστα (**dropdown**) με τις επιχειρήσεις που είναι δηλωμένες στο σύστημα σε ποια εργάζεται και δηλώνει αν έχει τέκνο κάτω των 12 ετών (**checkbox**).

### Σελίδες Πληροφόρησης
Στην ιστοσελίδα μας έχουν υλοποιηθεί σελίδες πληροφόρησης για:

 - Τα μέτρα εναντίον του COVID-19 στους εργασιακούς χώρους
 - Τις ώρες και τον τρόπο λειτουργίας των υπηρεσιών του Υπουργείου  
 - Την άδεια ειδικού σκοπού λόγω COVID-19 σε γονείς
 - Την αναστολή σύμβασης εργασίας
 - Την εξ'αποστάσεως απασχόληση

### Αίτηση Αναστολής Σύμβασης Εργασίας/Αίτηση Εξ'Αποστάσεως Απασχόλησης Εργαζόμενου

 - Οι δύο αυτές αιτήσεις γίνονται από την ίδια διεπαφή. Πριν την αίτηση, μία ενδιάμεση σελίδα ενημερώνει τον χρήστη ότι πρέπει να είναι συνδεδεμένος με λογαριασμό *εργοδότη* και περιγράφει την διαδικασία, η οποία είναι εξής:
	 * Εμφανίζεται μία λίστα με τους υπαλλήλους που *δεν είναι ήδη σε ειδικό εργασιακό καθεστώς*. Κάθε τεμάχιο/υπάλληλος είναι και ένα **checkbox**. 
	 * Για κάθε υπάλληλο που ο χρήστης επιλέγει, εμφανίζεται η επιλογή αναστολής σύμβασης ή απασχόλησης μέσω τηλεργασίας. Αυτή η επιλογή είναι ένα **ραδιοπλήκτρο**.
	 * Στο τέλος, επιλέγεται ένα κοινό για όλους τους υπαλλήλους διάστημα στο οποίο θα ισχύσει το νέο εργασιακό καθεστώς.

### Αίτηση Άδειας Ειδικού Σκοπού
 

 - Πριν την αίτηση, μία ενδιάμεση σελίδα ενημερώνει τον χρήστη, ανάλογα με το αν είναι συνδεδεμένος και ανάλογα με το είδους λογαριασμού με το οποίο έχει συνδεθεί, ότι απαιτείται να είναι συνδεδεμένος στο σύστημα ως εργαζόμενος και να έχει δηλώσει είτε κατά την εγγραφή του είτε τροποποιώντας το προφίλ του ότι έχει τέκνο 12 ετών. Αν το σύστημα επιβεβαιώσει ότι πληροί το κριτήριο αυτό, τότε ζητείται να επιλέξει το διάστημα για το οποίο επιθυμεί να πάρει άδεια.
	 - Επειδή ο νόμος απαιτεί η συγκεκριμένη άδεια να διαρκεί 4 ημέρες τουλάχιστον, αυτός ο περιορισμός αποτυπώνεται και στον datepicker της ημερομηνίας λήξης της άδειας.

### Διεπαφή Ραντεβού
Σε αντίθεση με τις παραπάνω άδειες, ο χρήστης δεν απαιτείται να είναι συνδεδεμένος για να κλείσει ραντεβού στο υπουργείο. Η διεπαφή του ραντεβού χωρίζεται σε 3 τμήματα

 - Στο πρώτο τμήμα, ζητείται να επιλεχθεί η περιφερειακή ενότητα (**dropdown**). Κατόπιν αυτής της επιλογής, ένα δεύτερο dropdown εμφανίζεται κάτω από το πρώτο με τα παραρτήματα μόνο της εν λόγω ενότητας.
 - Στο δεύτερο τμήμα, ζητείται από τον χρήστη να δώσει το ονοματεπώνυμό του (απλά **text fields** που όμως είναι **required**) και να επιλέξει ημερομηνία.
	 - Αν τα έξι ημίωρα ραντεβού μίας ημερομηνίας στο συγκεκριμένο παράρτημα είναι κλειστά, τότε η ημερομηνία *δεν* είναι επιλέξιμη στο datepicker
 - Στο τρίτο και τελευταίο τμήμα, ζητείται από τον χρήστη να επιλέξει ένα από τα διαθέσιμα ραντεβού της ημέρας εκείνης. Τα ραντεβού είναι 6 για κάθε μέρα, και ημίωρα. Αν ένα ραντεβού έχει κλείσει από άλλον χρήστη, δεν είναι ορατό στο **dropdown** επιλογής ώρας.

### Προφίλ Χρήστη

Όντας συνδεδεμένος, ο χρήστης πάντα έχει την δυνατότητα  να προβάλλει τα στοιχεία του και να επεξεργαστεί ορισμένα από αυτά, ανάλογα με την ιδιότητα του λογαριασμού του.

 - Αν είναι εργοδότης, έχει την δυνατότητα να αλλάξει την επωνυμία ή την ΔΟΥ της επιχείρησής του
 - Αν είναι εργαζόμενος, έχει την δυνατότητα να δηλώσει αν πλέον δεν έχει τέκνο κάτω των 12 ετών ή αν μόλις απέκτησε

Επιπλέον:

 - Αν είναι εργοδότης, στην καρτέλα ''Οι υπάλληλοί μου" βλέπει όλους τους υπαλλήλους του και αν αυτοί βρίσκονται σε ειδικό εργασιακό καθεστώς (αναστολή σύμβασης, εξ'αποστάσεως απασχόληση, άδεια ειδικού σκοπού) για πόσο ισχύει αυτό
 - Αν είναι εργαζόμενος, βλέπει άμεσα στο προφίλ του την ειδική εργασιακή κατάσταση την οποία έχει δηλώσει ο εργοδότης του για αυτόν, και έχει την επιλογή στην καρτέλα "Οι άδειές μου" να δει το ιστορικό αδειών ειδικού σκοπού που έχει πάρει.

## Βάση Δεδομένων

 Οι οντότητες που έχουμε στην βάση δεδομένων μας είναι οι εξής:
 - Ραντεβού
 - Παράρτημα (branch)
 - Περιφερειακή Ενότητα (regUnit)
 - ΔΟΥ
 - Επιχείρηση
 - Εργοδότης
 - Εργαζόμενος
 - Φόρμες Εργοδότη (ουσιαστικά τα πιστοποιητικά αναστολής σύμβασης και τηλεργασίας που υποβάλλονται από τον εργοδότη)
 -  Πιστοποιητικό Άδειας Ειδικού σκοπού (parentalleavecertificate)
 - Χρήστης

Οι παραπάνω οντότητες είναι διασυνδεδεμένες μεταξύ τους μέσω ξένων κλειδιών ώστε να διαφυλαχθεί η συνδρομικότητα των πληροφοριών. Στην διασφάλιση αυτή βοηθούν και οι οντότητες Εταιρεία, Παράρτημα, Περιφερειακή Ενότητα και ΔΟΥ, οι οποίες αφαιρούν από τον χρήστη την ευθύνη να συμπληρώσει text boxes σε αρκετά σημεία. Οι οντότητες των φορμών αποθηκεύονται στην βάση για προβολή της κατάστασης των υπαλλήλων. 

## Μερικά Βασικά Accounts:

 - **geokouv89** : Βασικός λογαριασμός εργοδότη. Έχει 3 εργαζόμενους, ώστε να ελέγχονται οι διαφορετικές περιπτώσεις εργασιακών καθεστώτων.
	 - Password: geokouv89
 - **ks** & : Βασικοί λογαριασμοί εργαζόμενων, εργάζονται στην εταιρεία του 1ου λογαριασμού
	 - Passwords: ksksks και 



