# Ενιαία πλατφόρμα διαχείρισης εκπαιδευτικού υλικού

Το σύστημα διαχείρισης εκπαιδευτικού υλικού που έχει υλοποιηθεί στο πλαίσιο του έργου του Επινοώ( http://www.epinoo.gr/ ) αφορά τη διαχείριση και την παρουσίαση μαθημάτων, άρθρων, τηλεδιασκέψεων, ειδική σελίδα στο facebook καθώς και προβολή σε χάρτη των συνδεδεμένων χρηστών. Οι χρήστες στην ενιαία αυτή πλατφόρμα είναι κοινοί και αυτό επιτυγχάνεται μέσω Single Sign On(SSO). Μέσω του  Shibboleth( https://aai.grnet.gr/ )  μπορούν οι ήδη υπάρχοντες χρήστες μέλη της ακαδημαϊκής, ερευνητικής και εκπαιδευτικής κοινότητας της Ελλάδας να πραγματοποιούν είσοδο στην πλατφόρμα και να μην απαιτείται η δημιουργία νέων λογαριασμών.

Η πλατφόρμα βασίζεται σε ήδη υφιστάμενα Λογισμικά Ανοικτού Κώδικα, όπως το Moodle, το WordPress και το Big Blue Button, όλα μαζί ενοποιημένα, λειτουργώντας σαν μία ενιαία πλατφόρμα. Επίσης έχουν δημιουργηθεί επεκτάσεις, όπως plugins και modules, για να υποστηρίξουν τις απαιτήσεις της ενιαίας πλατφόρμας.  Η πλατφόρμα έχει την δυνατότητα για κάθε μάθημα που καταχωρείτε στο moodle, να δημοσιεύεται αυτόματα στο wordpress και στην ειδικά διαμορφωμένη σελίδα στο Facebook.

Οι επιμέρους λογισμικά( Moodle, WordPress, Big Blue Button αλλά και η σελίδα στο Facebook) έχουν βασική λειτουργικότητα που μπορεί να επεκταθεί με άλλα πρόσθετα που παρέχουν τα αποθετήρια τους και να προσαρμοστεί στις ανάγκες του οργανισμού που την χρησιμοποιεί. Αναλυτικότερα, το WordPress αποτελεί τον κεντρικό δικτυακό τόπο του φορέα, εκεί αναρτώνται τα νέα άρθρα, οι εκδηλώσεις, προβάλλονται τα feeds των μαθημάτων, δυνατότητα για  πληρωμές και για την άντληση δωρεών και γενικότερα οποιαδήποτε λειτουργικότητα μπορεί να προστεθεί σε έναν WordPress ιστότοπο. Στην εκπαιδευτική πλατφόρμα moodle δημιουργούνται και προβάλλονται τα μαθήματα, οι κατηγορίες τους, οι ενότητες και οι τρόποι διδασκαλίας της κάθε ενότητας. Για την πραγματοποίηση των τηλεδιασκέψεων γίνεται χρήση της πλατφόρμας big blue button όπου οι προσκεκλημένοι μπορούν να εισέρχονται με συνδέσμους από τα μαθήματα του moodle. Επίσης μπορεί να δημιουργηθεί σελίδα στο facebook με τη χρήση του canvas app και να προβάλει τα τελευταία μαθήματα, άρθρα, το χάρτη με τους συνδεδεμένους χρήστες που βρίσκονται σε κοντινή απόσταση κα. Επιπρόσθετα μπορεί να γίνει χρήση του λογισμικού SelCont, ενός συστήματος που προσφέρει λύση στους διδάσκοντες για την παρουσίαση ηλεκτρονικών μαθημάτων συγχρονίζοντας περιεχόμενο από πολλαπλές πηγές.

Η πλατφόρμα διαχείρισης εκπαιδευτικού υλικού του Επινοώ απευθύνεται σε κοινότητες χρηστών όπως καθηγητές οποιασδήποτε βαθμίδας που θέλουν να προσφέρουν διαδικτυακά μαθήματά, σε σχολές και φροντιστήρια που θέλουν να πραγματοποιούν και να διαθέτουν τα μαθήματά τους ηλεκτρονικά, σε ομάδες οποιουδήποτε επιστημονικού αντικειμένου που επιθυμούν να πραγματοποιούν είτε μαθήματα, είτε σεμινάρια διαδικτυακά και σε πολλές άλλες κατηγορίες φορέων που παρέχουν εκπαίδευση. Επίσης απευθύνεται σε προγραμματιστές που επιθυμούν να επεκτείνουν τη λειτουργικότητα της πλατφόρμας καθώς όλες οι τεχνολογίες που χρησιμοποιούνται είναι ανοιχτού κώδικα.

Το επιπλέον κόστος για χρήση της ενιαίας πλατφόρμας διαχείρισης εκπαιδευτικού υλικού αφορά την υπολογιστική υποδομή που θα φιλοξενηθεί η πλατφόρμα, δηλαδή τα δύο Virtual Machines(VMs) που θα χρησιμοποιηθούν (το ένα είναι για moodle, wordpress, SelCont, MySql και το δεύτερο είναι για το Big Blue Button) και ανέρχεται περίπου σε 30-60 ευρώ το μήνα, ανάλογα την χρήση. Για τα λογισμικά δεν απαιτείται κάποιο κόστος καθώς όλα είναι ελεύθερα διαθέσιμα.

# Ενδεικτική υλοποίηση:

Δείτε συνδέσμους συνδέσμους προς τις πλατφόρμες από την ενδεικτική υλοποίηση <a href="https://github.com/eellak/epinoo-platform/wiki/%CE%95%CE%BD%CE%B4%CE%B5%CE%B9%CE%BA%CF%84%CE%B9%CE%BA%CE%AE-%CF%85%CE%BB%CE%BF%CF%80%CE%BF%CE%AF%CE%B7%CF%83%CE%B7" target="_blank">εδώ</a>.

# Αναλυτικές οδηγίες για την εγκατάσταση της πλατφόρμας

* <a href="https://github.com/eellak/epinoo-platform/wiki/%CF%80%CE%B1%CF%81%CE%B1%CE%B4%CE%BF%CF%87%CE%AD%CF%82" target="_blank">Παραδοχές</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/%CE%91%CF%85%CF%84%CE%BF%CE%BC%CE%B1%CF%84%CE%BF%CF%80%CE%BF%CE%B9%CE%B7%CE%BC%CE%AD%CE%BD%CE%B5%CF%82-%CE%B4%CE%B9%CE%B1%CE%B4%CE%B9%CE%BA%CE%B1%CF%83%CE%AF%CE%B5%CF%82" target="_blank">Αυτοματοποιημένες διαδικασίες</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/%CE%A0%CF%81%CE%BF%CE%B1%CF%80%CE%B1%CE%B9%CF%84%CE%BF%CF%8D%CE%BC%CE%B5%CE%BD%CE%B1-%CE%B5%CE%B3%CE%BA%CE%B1%CF%84%CE%AC%CF%83%CF%84%CE%B1%CF%83%CE%B7%CF%82" target="_blank">Προαπαιτούμενα εγκατάστασης</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/Makefile" target="_blank">Makefile</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/%CE%A0%CE%B1%CF%81%CE%AC%CE%BC%CE%B5%CF%84%CF%81%CE%BF%CE%B9-Makefile" target="_blank">Παράμετροι Makefile</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/Makefile-Targets" target="_blank">Makefile Targets</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/Puppet-modules" target="_blank">Puppet modules</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/apache" target="_blank">apache</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/mysql" target="_blank">mysql</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/ffmpeg" target="_blank">ffmpeg</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/Big-Blue-Button-(bbb)" target="_blank">Big Blue Button (bbb)</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/moodle" target="_blank">moodle</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/wordpress" target="_blank">wordpress</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/ajenti" target="_blank">ajenti</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/WP-FB-AutoConnect-Button" target="_blank">WP FB AutoConnect Button</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/Facebook-App-for-Epinoo.gr" target="_blank">Facebook App for Epinoo.gr</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/%CE%A3%CE%B5%CE%BB%CE%AF%CE%B4%CE%B1-Facebook" target="_blank">Σελίδα Facebook</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/%CE%A1%CF%8D%CE%B8%CE%BC%CE%B9%CF%83%CE%B7-Single-Sign-On-(SSO)" target="_blank">Ρύθμιση Single Sign On (SSO)</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/Moodle-Courses-View-plugin-for-Wordpress" target="_blank">Moodle Courses View plugin Wordpress</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/SelCont" target="_blank">SelCont</a>
* <a href="https://github.com/eellak/epinoo-platform/wiki/%CE%9C%CE%B5%CF%84%CE%B1%CF%86%CF%81%CE%AC%CF%83%CE%B5%CE%B9%CF%82-%CF%83%CF%84%CE%B1-%CE%95%CE%BB%CE%BB%CE%B7%CE%BD%CE%B9%CE%BA%CE%AC" target="_blank">Μεταφράσεις στα ελληνικά</a>

