# Mainframe aansluiten (QDP B.V.)

Installatiescripts waarmee een medewerker van QDP B.V. een laptop aansluit op het bedrijfs-Mainframe.
Er staan geen sleutels of bedrijfsgegevens in: toegang loopt via het eigen GitHub-account van de medewerker.

Windows, in een gewone PowerShell:

    $env:MF_ORG="QDP-BV"; irm https://raw.githubusercontent.com/QDP-BV/mainframe-aansluiten/main/aansluiten.ps1 | iex

Mac:

    MF_ORG=QDP-BV sh -c "$(curl -fsSL https://raw.githubusercontent.com/QDP-BV/mainframe-aansluiten/main/medewerker-welkom.sh)"
