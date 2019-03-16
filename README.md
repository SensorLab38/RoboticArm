# RoboticArm

Η Ομάδα μας "Oι μικροί προγραμματιστές" αποτελείται από δέκα (10) μαθητές 4ης δημοτικού.
Η ομάδα Θα κατασκευάσει ένα σταθερό ρομποτικό βραχίονα ο οποίος θα προγραμματιστεί να μεταφέρει μεταλλικά αντικείμενα από μία ή περισσότερες θέσεις σε μία άλλη.

Θα σχεδιαστεί και το πρωτότυπο θα κατασκευαστεί από χονδρό χαρτόνι. 

Στην συνέχεια η ομάδα θα επιλέξει το υλικό για την τελική φάση υλοποίησης, μεταξύ κόντρα πλακέ ή ακρυλικού υλικού.

Θα Ακολουθήση η μελετή για την τοπολογία των εξαρτημάτων και θα επιλέξουμε την καλύτερη δυνατή τοποθέτηση των αισθητήρων στην κατασκευή σε σχέση τις καλοδιώσεις, έτσι ώστε η κίνηση του βραχίονα να μην εμποδίζεται σε καμμία από τις προγραμματισμένες κινήσεις του.   

Για την λειτουργία του έχει επιλεγεί ο μικροκοντρόλερ Arduino UNO, δύο Stepper motors, ένας ηλεκτρομαγνήτης, ένα relay, τρία Led, αντιστάσεις και καλώδια, βίδες καθώς και τα ξύλινα μέρη του βραχίονα.

Ο προγραμματισμός του βραχίονα θα γίνει με την γλώσσα Arduino IDE.

Ο ρομποτικός βραχίονας θα λειτουργεί αυτόματα και θα συντονιστεί ώστε να συνεργάζεται με άλλο όμοιο ρομποτικό βραχίονα για μεταφόρτωση μεταλλικών αντικειμένων.

Αναλυτικά όλα τα υλικά που θα χρησιμοποιηθούν είναι τα ακόλουθα:

1 Χ Arduino UNO			7,90€

1 Χ Breadboard 200 οπές		3,00€

4 Χ Stepper motor 	 	5,00€

4 Χ Motor Driver 		3,80

1 Χ Relay - SRD-05VDC-SL-C 	2,50

2 Χ Ηλεκτρομαγνήτης 12V/5KG 	15,80

5 Χ Leds 			0,50

30 Χ Cables (Καλώδια)		1,50

1 Χ Καλώδιο USB0		1,30

1 Χ Τροφοδοτικό 12V 		3,90

2 Χ Ηλεκτρικά τζακ		1,00

1 Χ Πλακέτα βάσης 		2,50

1 Χ Πλακέτα βάσης βραχίονα	2,00

2 Χ Κάθετα μέρη του βραχίονα	2,00

2 Χ Οριζόντια μέρη βραχίονα	2,00

1 Χ Μπαταριοθήκη 3.5V		1,00

2 Χ Μπαταρίες 3.5V 		7,80

1 Χ Μπαταριοθήκη για 9V 	0,80

1 Χ Μπαταρία 9V 		3,00

3 Χ Καρούλια    		2,70

2 Χ Προσαρμοστήρες (shaft)	4,00

34 Χ Βίδες  2cm/3mm		0,51

6 Χ Βίδες  6cm/3mm 		0,18

60 Χ Παξιμάδια 3M		0,60

34 Χ Αποστάτες 1cm Black	1,70

4 Χ Αποστάτες 6cm  Black	0,20

2 Χ Ρόδες			1,80

Το συνολικό κόστος της κατασκευής δεν ξεπερνάει τα 91,00 Ευρώ.  
**********************************************************************
Σάββατο 23-02-2019 

Η πρώτη φάση της εκπαίδευσης έχει ολοκληρωθεί. 
Οι μαθητές εκπαιδεύτηκαν στις βασικές έννοιες του προγραμματισμού με την γλώσσα IDE του Arduino Uno. 
Με την βοήθεια του Eργαστηρίου Rομποτικής (SensorLab38) έμαθαν να προραμματίζουν τους αισθητήρες και να ανάβοσβήνουν τα λαμπάκια (led και RGB led) όπως μπορουμε να δούμε στο παρακάτω σχήμα:

![leds](https://github.com/SensorLab38/RoboticArm/blob/master/Fritzing%203%20leds.png)

![3 Leds](https://github.com/SensorLab38/RoboticArm/blob/master/S4A%204%20Lads%20-%20pic.png)

Παράλληλα με την βοήθεια του δασκάλου τους μελέτησαν και συζήτησαν για τον σχεδιασμό του ρομποτικού βραχίονα.

Από την συζήτηση διαπιστώθηκε ότι υπήρχαν δύο προτάσεις σχετικά με τις λειτουργίες του βραχίονα. Ορισμένοι μαθητές πρότειναν ο βραχίονας να τοποθετηθεί πάνω σε μία πλατφόρμα με ρόδες και να μετακινείται. Δηλαδή να φοτρώνει φορτία από το ένα μέρος και να τα αποθέτει σε ένα άλλο. 
Η άλλη πρόταση ήταν ο βραχίονας να να είναι σταθερός και να φορτώνει τα φορτία πάνω στην πλατφορμα.

Τελικά αποφασίστηκε η δεύτερη πρόταση διότι με την πρώτη πρόταση το έργο θα γινόταν ερκετά πολύπλοκο τόσο στην κατασκευή του ρομποτικού όσο και στην ανάπτυξη του κώδικα. Άλλωστε ο χρόνος μέχρι την παράδοση του έργου στην επιτροπή διαγωνισμού δεν επαρκούσε.  

Η ομάδα θα συνεχίσει και μετά τον διαγωνισμό για να ολοκληρώσει και την πρώτη πρόταση.
**********************************************************************************************

Σάββατο 02 Μαρτίου 2019

Αυτή την εβδομάδα η ομάδα μελέτησε το stepper motor καθώς και το stepper motor drive (ULN2003).

![stepper](https://github.com/SensorLab38/RoboticArm/blob/master/StepperMotorWithDriver_1200x1200.jpg)

Οι διαστάσεις είναι απαραίτητες για την τοποθέτηση του stepper στην κατασκευή.

![stepper dimensions](https://github.com/SensorLab38/RoboticArm/blob/master/Stepper%20motor%20dimensions.jpg)


Οι τεχνικές προδιαγραφές είναι πολύ χρήσιμες για να κατανοήσουμε τη λειτουργία του stepper.

![stepper specs](https://github.com/SensorLab38/RoboticArm/blob/master/datasheet-of-stepper-motor.png) 

Το εσωτερικό του stepper motor.

![stepper parts1](https://github.com/SensorLab38/RoboticArm/blob/master/stepper-parts1.png)

Τα πηνία στο εσωτερικό του stepper motor

![stepper parts](https://github.com/SensorLab38/RoboticArm/blob/master/stepper-parts.jpg)

Διάραμμα συνδεσμολογίας των εσωτερικών πηνίων toy stepper motor. 

![stepper diagram drive](https://github.com/SensorLab38/RoboticArm/blob/master/28byj-stepper-motor-wiring-diagram-1024x780.png)

Συνδεσμολογία του Arduino με το Stepper motor και του stepper motor drive .

![stepper drive diagram](https://github.com/SensorLab38/RoboticArm/blob/master/diagram%20arduino%20stepper%20drive.jpg)

Προγραμματισμός ενός Stepper Motor 

#include <Stepper.h>
#define STEPS 32                        //Steps per revolution (βήματα ανά περιστροφή)

Stepper stepper(STEPS, 8, 9, 10, 11);   //Stepper class (Συνάρτηση που περιγράφει την σύνδεση του step Mottor στο Arduino) 

int val = 1024;                         //Variable (Ορίζουμε την μεταβλητή "val" 

void setup() {                          // Η συνάρτηση SETUP
  stepper.setSpeed(600);                // Η συνάρτηση "SetSpeed" μας δηλώνει την ταχύτητα περιστοφής του step motor/ 
}

void loop() {                           // Η συνάρτηση "LOOP"
    stepper.step(val);                  // Η συνάρτηση "stepper.step" δηλώνει την κίνηση προς μία κατευθυνση του step motor.
    delay(1000);                        // Καθυστέρηση 1 δεύτερο.
    stepper.step(-val);                 // Η συνάρτηση "stepper.step" δηλώνει την κίνηση προς την αντίθετη κατεύθυνση του step motor.
    delay(1000);                        // Καθυστέρηση 1 δεύτερο.
    while(1);                           // Η συνάρτηση "while" διακόπτει την κίνηση του step motor.
}
    





