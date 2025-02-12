Semantic Web & GraphDB
Eφαρμογή βασισμένη σε Java και RDF4J που μετατρέπει μοντέλα RDFS σε OWL, φορτώνει δεδομένα σε μια απομακρυσμένη GraphDB και εκτελεί SPARQL ερωτήματα για εξαγωγή στατιστικών.
Χαρακτηριστικά

✔ Μετατροπή RDF Schema (RDFS) σε Web Ontology Language (OWL)
✔ Φόρτωση οντολογίας στην GraphDB μέσω RDF4J
✔ Δημιουργία και εκτέλεση SPARQL ερωτημάτων
✔ Ανάλυση και εξαγωγή στατιστικών δεδομένων από το μοντέλο
Τεχνολογίες

🔹 Java 17
🔹 Maven
🔹 RDF4J
🔹 GraphDB
🔹 SPARQL

Αρχεία

    Main.java → Κύρια κλάση της εφαρμογής
    astronomy.ttl → Αρχικό αρχείο RDFS με αστρονομικά δεδομένα
    astronomyOWL.ttl → Μετασχηματισμένο OWL αρχείο
    pom.xml → Maven dependencies
    report_projectB_SemanticWeb.pdf → Αναφορά του έργου

Οδηγίες Εκτέλεσης

    Βεβαιωθείτε ότι η GraphDB τρέχει τοπικά (http://localhost:7200/).
    Επεξεργαστείτε το Main.java για να ορίσετε το κατάλληλο repository name.
    Χρησιμοποιήστε mvn compile exec:java για να εκτελέσετε το πρόγραμμα.
    Τα αποτελέσματα των SPARQL queries εκτυπώνονται στη κονσόλα.
