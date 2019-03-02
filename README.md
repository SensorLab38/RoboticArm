# RoboticArm

Η Ομάδα μας "Oι μικροί προγραμματιστές" αποτελείται από πέντε μαθητές 4ης δημοτικού.
Η ομάδα Θα κατασκευάσει ένα σταθερό ρομποτικό βραχίονα ο οποίος θα προγραμματιστεί να μεταφέρει μεταλλικά αντικείμενα από μία ή περισσότερες θέσεις σε μία άλλη.

Θα σχεδιαστεί και το πρωτότυπο θα κατασκευαστεί από χονδρό χαρτόνι. 

Στην συνέχεια η ομάδα θα επιλέξει το υλικό για την τελική φάση υλοποίησης, μεταξύ κόντρα πλακέ ή ακρυλικού υλικού.

Για την λειτουργία του έχει επιλεγεί ο μικροκοντρόλερ Arduino UNO, δύο Stepper motors, ένας ηλεκτρομαγνήτης, τρία Led, αντιστάσεις και καλώδια.

Ο προγραμματισμός του βραχίονα θα γίνει με την γλώσσα Arduino IDE.

Ο ρομποτικός βραχίονας θα λειτουργεί αυτόματα και θα συντονιστεί ώστε να συνεργάζεται με άλλον, όμοιο ρομποτικό βραχίονα για μεταφόρτωση των αντικειμένων.

Τα υλικά που θα χρησιμοποιηθούν είναι:

1 Χ Arduino UNO			7,90€

1 Χ Breadboard 200 οπές		3,00€

2 Χ Stepper motor 	 	5,00€


4	Motor Driver - 					2		1,90		3,80
5	Relay - SRD-05VDC-SL-C relay			1		2,50		2,50
	6	Electromagnet (Ηλεκτρομαγνήτης) 12V/5KG	2		7,90		15,80
7	Leds 						5		0,10		0,50
8	Cables (Καλώδια)				30		0,05		1,50
9	Καλώδιο USB					1		1,30		1,30
10	Τροφοδοτικό 12V και δύο ηλεκτρικά τζακ  	1		3,90		3,90
11	Δύο ηλεκτρικά τζακ (μαύρο και κόκκινο)  	2		0,50		1,00
12	Πλακέτα βάσης					1		2,50		2,50
13	Πλακέτα βάσης στήριξης του βραχίονα		1		2,00		2,00
14	Δύο κάθετα μέρη του βραχίονα			2		1,00		2,00
15	Δύο οριζόντια μέρη του βραχίονα			2		1,00		2,00
16	Μπαταριοθήκη για μπαταρία 3.5V			1		1,00		1,00
17	Μπαταρίες 3.5V					2		3,90		7,80
18	Μπαταριοθήκη για μπαταρία 9V			1		0,80		0,80
19	Μπαταρία 9V					1		3,00		3,00
20	Τρία καρούλια					3		0,90		2,70
21	Δύο προσαρμοστήρες (shaft) για τα μοτέρ		2		2,00		4,00
22	Βίδες  2cm/3mm 					34		0,02		0,51
23	Βίδες  6cm/3mm					6		0,03		0,18
24	Παξιμάδια 3M					60		0,01		0,60
25	Αποστάτες 1cm  πλαστικοί Black			34		0,05		1,70
26	Αποστάτες 6cm  πλαστικοί Black			4		0,05		0,20
27	Ρόδες						2		0,90		1,80
										Σύνολο	78,99

Το συνολικό κόστος της κατασκευής δεν ξεπερνάει τα 80,00 Ευρώ.  
**********************************************************************
Σάββατο 23-02-2019 

Η πρώτη φάση της εκπαίδευσης έχει ολοκληρωθεί. 
Οι μαθητές εκπαιδεύτηκαν στις βασικές έννοιες του προγραμματισμού με την γλώσσα IDE του Arduino Uno. 
Με την βοήθεια του Eργαστηρίου Rομποτικής (SensorLab38) έμαθαν να προραμματίζουν τους αισθητήρες και να ανάβοσβήνουν τα λαμπάκια (led και RGB led) όπως μπορουμε να δούμε στο παρακάτω σχήμα:

![leds](https://github.com/SensorLab38/RoboticArm/blob/master/Fritzing%203%20leds.png)

Παράλληλα με την βοήθεια του δασκάλου τους μελέτησαν και συζήτησαν για τον σχεδιασμό του ρομποτικού βραχίονα.

Από την συζήτηση διαπιστόθηκε ότι Υπήρχαν δύο προτάσεις σχετικά με τις λειτουργίες του βραχίονα. Ορισμένοι μαθητές πρότειναν ο βραχίονας να τοποθετηθεί πάνω σε μία πλαυφόρμα με ρόδες και να μετακινήται. Δηλαδή να φοτρώνει φορτία από το ένα μέρος και να τα αποθέτει σε ένα άλλο. 
Η άλλη πρόταση ήταν ο βραχίονας να να είναι σταθερός και να φορτώνει τα φορτία επό το έδαφος επάνω στην πλατφορμα.

Τελικά αποφασίστηκε η δεύτερη πρόταση διότι με την πρώτη πρόταση το έργο θα γινόταν ερκετά πολύπλοκο τόσο στην κατασκευή του ρομποτικού όσο και στην ανάπτυξη του κώδικα. Άλλωστε ο χρόνος μέχρι την παράδοση του έργου στην επιτροπή διαγωνισμού δεν επαρκούσε.  

Η ομάδα θα συνεχίσει και μετά τον διαγωνισμό για να ολοκληρώσει και την πρώτη πρόταση.
**********************************************************************************************

Σάββατο 02 Μαρτίου 2019

Αυτή την εβδομάδα η ομάδα μελέτησε το stepper motor καθώς και το stepper motor drive (ULN2003).

![stepper](https://github.com/SensorLab38/RoboticArm/blob/master/StepperMotorWithDriver_1200x1200.jpg)


