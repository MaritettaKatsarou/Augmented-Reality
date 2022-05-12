# Lesson: Interaction Design

### First and Last Name: :id: Maria-Nikoletta Katsarou
### University Registration Number: dpsd19051
### GitHub Personal Profile: [@MaritettaKatsarou](https://github.com/MaritettaKatsarou)
### Augmented Reality [Personal Repository](https://maritettakatsarou.github.io/Augmented-Reality/)

# Introduction

# ~~Summary~~ Notes
### Για όλα τα deliverables χρησιμοποιήθηκε το [Atom](https://atom.io) για την σύνταξη του κώδικα.

# :cherry_blossom: 1st Deliverable
### :pushpin: 1st step: Έγινε η εισαγωγή των σχημάτων με τη βοήθεια του κώδικα απο το: [A-Frame School](https://glitch.com/~aframe-school-position) 
 *// έγινε χρήση του εργαλείου μορφοποίησης κώδικα, (prettier), για να είναι πιο ευανάγνωστος //*
### :pushpin: 2nd step: Άλλαξα τα χρώματα, τις διαστάσεις και την τοποθεσία κάθε σχήματος 
 *// ώστε να είναι "μπλεγμένα" μεταξύ τους και να δημιουργήσουν κάτι που να μοιάζει με μικρόφωνο //*
### :pushpin: 3rd step: Απο μελέτη του [A-Frame Particle System](https://www.npmjs.com/package/aframe-particle-system-component) βρήκα το πως εντάσσουμε το χιόνι στο σκηνικό
### :pushpin: 4th step: Στη συνέχεια, απο το [NPM](https://www.npmjs.com/) βρήκα τον κώδικα για το [Speech Command](https://www.npmjs.com/package/aframe-speech-command-component)
 *// Σε καποιο ενδιαμεσο σταδιο αποφασησα να αλλαξω και το title σε Maritetta's_MarkerBased για να το κανω πιο personalised //*
 
 *//Γενικότερα, αντιμετώπισα διάφορα θέματα με την εργασία και γι'αυτό εχω κάνει και τοσες φορες upload και επειδή ίσως το κυρίως πρόβλημα είναι του laptop μου, ελπίζω να παίζει σε όποιον άλλο το δοκιμάσει//* 
 
# :cherry_blossom: 2nd Deliverable
### :pushpin: 1st step: Δημιούργησα το περιεχόμενο του marker μου στο [Canva](https://www.canva.com) και το έκανα upload στο [AR.js Marker Training](https://ar-js-org.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) για να παρω το .patt αρχείο που χρειαζόμαστε.
 *// το 1ο marker δεν έπαιζε οπότε αποφάσισα να το αλλάξω :thinking://*
 
 *// ούτε το 2ο δεν έπαιζε :weary: έκανα διάφορες δοκιμές που δεν έπιασαν και μετά είπα να δοκιμάσω να βαλω πιο πολυ περιθώριο στο marker μου το οποίο επίσης δεν λειτούργησε. Μετά είδα σε κάποιο chat στο GitHub πως σε ένα άτομο που είχε παρόμοιο πρόβλημα με εμένα του πρότειναν να βάλει στο marker του background color το (240,240,240) δλδ γκρί οπότε το δοκίμασα και εγώ και δούλεψε) :+1: //*
 ![card](scrnshot.png)
 Βέβαια δεν το έκανα upload στο link που αναφέρει
 
 ### :pushpin: 2nd step: Δημιούργησα την παρακάτω εικόνα που ήθελα να εμφανίζεται (με τη χρήση του ProCreate στο ipad και την ανεβασα στα assets αφού πρώτα την έκανα reverse μέσω του [ResizePixel](https://www.resizepixel.com/mirror-image) γιατί αλλιώς φαινόταν ανάποδα )
 ![card](Dpsd19051Card.png)
 
 
 
 (note: πρόβλημα με το marker page, τριτη 10/05 απο τις 9:20 περίπου και μετά)
 
 :interrobang: χάλασε όλος ο κώδικας και προσπάθησα με δίαφορους τρόπους να το φτιάξω, χωρίς μεγάλη επιτυχία, εν τέλη πήρα απο το ιστορικό των uploads εναν παλιό μου κώδικα που δούλευαν όλα καλά αλλά τωρα δεν παίζει απόλυτα σωστά. Ελπίζω να μετρήσει το οτι τουλάχιστον έφτιαξα τα γραφικά και απλά για κάποιο λόγο ο κώδικας δεν παίζει. :interrobang:
 
 ### :pushpin: 3rd step: Δημιούργησα τα animation μου στο Blender και τα έκανα export σε .mov , .mp4 , .gif για να δοκιμάσω σε ποιά μορφή θα μου τα έπαιζε transparent.
 *// έψαξα και βρήκα πως το mp4 δεν γίνεται να παίξει σε transparent αλλά το άφησα στα assets γιατί αν δεν αναγνωρίζει τις άλλες μορφές να έχω μια εναλλακτική και ας εχει πίσω background //*
 
 ![H](AnimatedCube_H.gif)
 -----------------------------------------------------------------------------------------------------------------------------------------------------
 ![O](AnimatedCube-O0001-0030.gif)
 
 *// Tο σκεπτικό πίσω απο το animation ήταν να κάνω κάτι διαφορετικό απο την κλασσική σφαίρα που θα έπιχειρουσαν όλοι και έτσι σκέφτηκα να φτίαξω την "ταυτότητα" του κάθε στοιχείου απο τον περιοδικό πίνακα σε 3D. Με αυτό τον τρόπο φαίνονται όλα τα δεδομένα τους όπως πχ ατομική μάζα (κάτω απο το όνομα) και ο ατομικός αριθμός (πάνω δεξιά) //*
 
 ![water](water.gif)
 *// Για το νερό απλά έκανα 2 σταγόνες //*
 

# :cherry_blossom: 3rd Deliverable 


# Conclusions


# Sources are linked throughout the text
 <div align="center">:cherry_blossom: :cherry_blossom: :cherry_blossom:
