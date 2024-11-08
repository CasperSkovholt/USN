# Antall kjørte km per år
km_per_aar = 10000  

# Forsikringskostnader
forsikring_elbil = 5000  
forsikring_bensinbil = 7500  

# Trafikkforsikringsavgift (samme for begge biltyper)
trafikkforsikringsavgift = 8.38 * 365 

# Drivstoffkostnader
strømpris_per_kwh = 2.00  
forbruk_elbil = 0.2  
kostnad_strøm_elbil = forbruk_elbil * strømpris_per_kwh * km_per_aar  # årlige drivstoffkostnader for elbil

forbruk_bensinbil = 1.0  
kostnad_bensin_bensinbil = forbruk_bensinbil * km_per_aar  # årlige drivstoffkostnader for bensinbil

# Bomavgifter
bomavgift_elbil = 0.1  
bomavgift_bensinbil = 0.3  
kostnad_bom_elbil = bomavgift_elbil * km_per_aar  # årlige bomkostnader for elbil
kostnad_bom_bensinbil = bomavgift_bensinbil * km_per_aar  # årlige bomkostnader for bensinbil

# Totale kostnader for elbil
totalkostnad_elbil = (
    forsikring_elbil + trafikkforsikringsavgift + kostnad_strøm_elbil + kostnad_bom_elbil
)

# Totale kostnader for bensinbil
totalkostnad_bensinbil = (
    forsikring_bensinbil + trafikkforsikringsavgift + kostnad_bensin_bensinbil + kostnad_bom_bensinbil
)

# Kostnadsdifferanse
kostnadsdifferanse = (totalkostnad_bensinbil - totalkostnad_elbil)

# Presentasjon av resultatene
print(f"Totale årlige kostnader for elbil: {totalkostnad_elbil:.2f} kr")
print(f"Totale årlige kostnader for bensinbil: {totalkostnad_bensinbil:.2f} kr")
print(f"Årlig kostnadsdifferanse (bensinbil - elbil): {kostnadsdifferanse:.2f} kr")
