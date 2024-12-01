# "Faydalı" proqram kimi görsənir, məsələn, kalkulyator
def calc():
    print("Bu bir kalkulyatordur.")
    print("3 + 5 =", 3 + 5)

# Əslində isə gizli bir funksiya var:
def steal_data():
    with open("sifreler.txt", "r") as file:
        data = file.read()
    # Məlumatları hakerin serverinə göndərir
    print("Məlumat oğurlandı:", data)

# İstifadəçi proqramı işlədir:
calc()

# Eyni zamanda gizli funksiya çalışır:
steal_data()
