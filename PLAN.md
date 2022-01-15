# Was ist der Plan? #

Ein Webprogramm welches jede Gebietsgliederung auf Grundlage des Landesverbandes im Rahmen des Mitgliedermanagements, insbesondere die Beitragsberechnung unterstützt.

## Basierende Funktionen? ## 

    [ ] Geschäftsstellen-Benutzersystem

        [ ] AdminLVL 5 Account für IT

            [ ] höchste Zugriffsberechtigung

            [ ] kann alle Daten jedes Kreisverbandes und des Landesverbandes einsehen

            [ ] benötigt höchste Datenfreigabe durch den Landesvorstand und entsprechende Datenschutzverpflichtung

            [ ] Generalaccount, wird nur genutzt wenn es notwendig ist

            [ ] hat alle Zugriffsberechtigungen aus LVL 4

        [ ] AdminLVL 4 Account für die Landesgeschäftsführung
        
            [ ] kann alle Mitgliedsdaten jedes Kreisverbandes einsehen und bearbeiten

            [ ] kann neue Mitglieder erstellen und diese einem Kreisverband zuordnen

            [ ] kann die Beitragsdaten der Kreisverbände und des Landesverbandes nicht einsehen

            [ ] hat alle Zugriffsberechtigungen aus LVL 3, mit Ausnahme der Beitragsdaten

        [ ] AdminLVL 3 Account für Landesvorsitz- und Schatzmeister

            [ ] kann alle Mitgliedsdaten jedes Kreisverbandes einsehen, jedoch nicht bearbeiten

            [ ] kann alle Mitgliedsdaten des Landesverbandes einsehen und bearbeiten (der Mitglieder die keinem Kreisverband zugeordnet sind)

            [ ] kann die Beitragsdaten des Landesverbandes einsehen und bearbeiten

        [ ] AdminLVL 2 Account für die Kreisgeschäftsführung

            [ ] kann alle Mitgliedsdaten des eigenen Kreisverbandes einsehen und eingeschränkt bearbeiten
            
                [ ] jede Bearbeitung der Mitgliesdaten werden der LGF gemeldet und müssen von dort genehmigt werden

            [ ] kann die Beitragsdaten des Kreisverbandes nicht einsehen

            [ ] hat alle Zugriffsberechtigungen aus LVL 1, mit Ausnahme der Beitragsdaten

        [ ] AdminLVL 1 Account für Kreisvorsitz- und Schatzmeister

            [ ] kann alle Mitgliedsdaten des eigenen Kreisverbandes einsehen, jedoch nicht bearbeiten

            [ ] kann die Beitragsdaten des Kreisverbandes einsehen und bearbeiten

            [ ] sollte ein Kreisverband keine Kreisgeschäftsführung haben, so erhält der Schatzmeister die Rechte der KGF

    [ ] Mitgliederverwaltung

        [ ] vollumfängliche Mitgliederansicht für alle ab AdminLVL 3

        [ ] kreisabhängige Mitgliederansicht für AdminLVL 1 & 2

    [ ] Beitragsverwaltung

        [ ] auf KV-Ebene kann LVL 1 bei dem eigenen Kreis für die Mitglieder die Beitragsdaten über mehrere Jahre hinweg aufzeichnen

            [ ] sowohl fällige Beiträge

            [ ] als auch Zahlungen oder auch Teilzahlungen

    [ ] Dokumentenverwaltung

        [ ] es kann automatisch standartisierte Briefe erstellt werden

            [ ] Rechnungen für die Mitgliedsbeiträge

            [ ] Mahnungen für die Mitgliedsbeiträge