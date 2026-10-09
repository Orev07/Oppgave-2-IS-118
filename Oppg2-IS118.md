# Interaktiv historie - Erling som prosjektleder

print("Velkommen til prosjektspillet!")
print("Du spiller som Erling, prosjektleder for en studentgruppe.\n")

# Variabel som holder styr på hvor mange gode valg spilleren tar
poeng = 0

# -------------------
# Beslutningspunkt 1
# -------------------

print("Konflikt 1: Silje og Elias er uenige om hvordan prosjektet skal gjennomføres.")
print("1. Samle begge til et møte og høre begge sider.")
print("2. Ta parti med Silje uten å høre Elias.")

valg1 = input("Velg 1 eller 2: ")

if valg1 == "1":
    print("\nDu arrangerer et møte. Begge føler seg hørt.")
    poeng += 1
elif valg1 == "2":
    print("\nDu tar parti med Silje. Elias blir frustrert.")
else:
    print("\nUgyldig valg. Erling gjør ingenting, og konflikten fortsetter.")

# -------------------
# Beslutningspunkt 2
# -------------------

print("\nKonflikt 2: Hamdi og Hallgeir er uenige om arbeidsfordelingen.")
print("1. Fordele oppgavene på nytt slik at begge blir fornøyde.")
print("2. Be dem løse problemet selv.")

valg2 = input("Velg 1 eller 2: ")

if valg2 == "1":
    print("\nDu fordeler oppgavene på nytt. Samarbeidet blir bedre.")
    poeng += 1
elif valg2 == "2":
    print("\nDe prøver å løse det selv, men problemet fortsetter.")
else:
    print("\nUgyldig valg. Situasjonen forblir uklar.")

# -------------------
# Beslutningspunkt 3
# -------------------

print("\nMotivasjonen i teamet synker etter flere uker med arbeid.")
print("1. Arrangere en teambuilding-aktivitet.")
print("2. Ignorere problemet og fokusere kun på fristen.")

valg3 = input("Velg 1 eller 2: ")

if valg3 == "1":
    print("\nTeamet får ny motivasjon og bedre stemning.")
    poeng += 1
elif valg3 == "2":
    print("\nStressnivået øker og flere mister motivasjonen.")
else:
    print("\nUgyldig valg. Motivasjonen endres ikke.")

# -------------------
# Sluttresultat
# -------------------

print("\n--- SLUTTRESULTAT ---")

if poeng == 3:
    print("Prosjektet blir en stor suksess!")
    print("Teamet samarbeider godt, leverer i tide og får topp resultat.")
elif poeng == 2:
    print("Prosjektet går greit.")
    print("Noen utfordringer oppstår, men gruppen fullfører arbeidet.")
else:
    print("Prosjektet får problemer.")
    print("Konflikter og lav motivasjon fører til forsinkelser og svakere resultat.")

print("\nTakk for at du spilte!")