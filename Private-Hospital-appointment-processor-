import sys  # Used for exiting the program on errors


# ---- FUNCTION: Create all the patient data ----
def create_patients():
    patients = [
        {
            "patient_id": "PT001",
            "name": "Alice Morgan",
            "nhs_number": "943 567 1234",
            "age": 45,
            "gender": "Female",
            "address": "7 Elm Street, Bristol",
            "phone": "07710 111222",
            "medical_history": "Asthma, Hypertension",
            "tests": [
                {"test_name": "Full Blood Count", "date": "02/09/2026", "result": "Normal", "cost_gbp": 85.00},
                {"test_name": "Chest X-Ray", "date": "02/09/2026", "result": "Clear", "cost_gbp": 150.00}
            ],
            "hospitalisation": {
                "admitted": "01/09/2026",
                "discharged": "04/09/2026",
                "days": 3,
                "daily_rate_gbp": 350.00,
                "procedure": "Bronchoscopy",
                "procedure_cost_gbp": 1200.00,
                "medication_cost_gbp": 180.00
            },
            "consultation_cost_gbp": 200.00
        },
        {
            "patient_id": "PT002",
            "name": "Brian Clarke",
            "nhs_number": "712 345 6789",
            "age": 62,
            "gender": "Male",
            "address": "22 Oak Avenue, Bath",
            "phone": "07720 222333",
            "medical_history": "Type 2 Diabetes, High Cholesterol",
            "tests": [
                {"test_name": "HbA1c Blood Test", "date": "03/09/2026", "result": "6.8%", "cost_gbp": 95.00},
                {"test_name": "Lipid Panel", "date": "03/09/2026", "result": "Elevated LDL", "cost_gbp": 75.00},
                {"test_name": "ECG", "date": "04/09/2026", "result": "Normal sinus", "cost_gbp": 120.00}
            ],
            "hospitalisation": {
                "admitted": "03/09/2026",
                "discharged": "05/09/2026",
                "days": 2,
                "daily_rate_gbp": 350.00,
                "procedure": "Cardiac Stress Test",
                "procedure_cost_gbp": 800.00,
                "medication_cost_gbp": 220.00
            },
            "consultation_cost_gbp": 200.00
        },
        {
            "patient_id": "PT003",
            "name": "Catherine Davis",
            "nhs_number": "856 123 4567",
            "age": 34,
            "gender": "Female",
            "address": "15 River Lane, Taunton",
            "phone": "07730 333444",
            "medical_history": "None",
            "tests": [
                {"test_name": "Pregnancy Blood Panel", "date": "05/09/2026", "result": "Normal", "cost_gbp": 110.00},
                {"test_name": "Ultrasound Scan", "date": "05/09/2026", "result": "Healthy", "cost_gbp": 200.00}
            ],
            "hospitalisation": {
                "admitted": "",
                "discharged": "",
                "days": 0,
                "daily_rate_gbp": 0,
                "procedure": "None",
                "procedure_cost_gbp": 0,
                "medication_cost_gbp": 0
            },
            "consultation_cost_gbp": 150.00
        },
        {
            "patient_id": "PT004",
            "name": "David Evans",
            "nhs_number": "634 789 0123",
            "age": 71,
            "gender": "Male",
            "address": "3 Castle Road, Wells",
            "phone": "07740 444555",
            "medical_history": "Arthritis, Previous Hip Replacement",
            "tests": [
                {"test_name": "Full Blood Count", "date": "01/09/2026", "result": "Low Haemoglobin", "cost_gbp": 85.00},
                {"test_name": "Knee MRI Scan", "date": "02/09/2026", "result": "Cartilage Wear", "cost_gbp": 450.00}
            ],
            "hospitalisation": {
                "admitted": "02/09/2026",
                "discharged": "07/09/2026",
                "days": 5,
                "daily_rate_gbp": 350.00,
                "procedure": "Knee Replacement Surgery",
                "procedure_cost_gbp": 5500.00,
                "medication_cost_gbp": 350.00
            },
            "consultation_cost_gbp": 200.00
        },
        {
            "patient_id": "PT005",
            "name": "Emily Foster",
            "nhs_number": "521 456 7890",
            "age": 28,
            "gender": "Female",
            "address": "9 Meadow Close, Frome",
            "phone": "07750 555666",
            "medical_history": "Migraine",
            "tests": [
                {"test_name": "Brain CT Scan", "date": "04/09/2026", "result": "No abnormality", "cost_gbp": 380.00},
                {"test_name": "Full Blood Count", "date": "04/09/2026", "result": "Normal", "cost_gbp": 85.00}
            ],
            "hospitalisation": {
                "admitted": "",
                "discharged": "",
                "days": 0,
                "daily_rate_gbp": 0,
                "procedure": "None",
                "procedure_cost_gbp": 0,
                "medication_cost_gbp": 0
            },
            "consultation_cost_gbp": 150.00
        },
        {
            "patient_id": "PT006",
            "name": "Frank Green",
            "nhs_number": "478 234 5678",
            "age": 55,
            "gender": "Male",
            "address": "18 High Street, Glastonbury",
            "phone": "07760 666777",
            "medical_history": "COPD, Smoker",
            "tests": [
                {"test_name": "Lung Function Test", "date": "06/09/2026", "result": "Reduced capacity", "cost_gbp": 160.00},
                {"test_name": "Chest X-Ray", "date": "06/09/2026", "result": "Mild scarring", "cost_gbp": 150.00},
                {"test_name": "Arterial Blood Gas", "date": "07/09/2026", "result": "Low O2", "cost_gbp": 95.00}
            ],
            "hospitalisation": {
                "admitted": "06/09/2026",
                "discharged": "10/09/2026",
                "days": 4,
                "daily_rate_gbp": 350.00,
                "procedure": "Nebuliser Therapy",
                "procedure_cost_gbp": 600.00,
                "medication_cost_gbp": 280.00
            },
            "consultation_cost_gbp": 200.00
        },
        {
            "patient_id": "PT007",
            "name": "Grace Hall",
            "nhs_number": "365 678 9012",
            "age": 19,
            "gender": "Female",
            "address": "6 College Way, Exeter",
            "phone": "07770 777888",
            "medical_history": "None",
            "tests": [
                {"test_name": "Full Blood Count", "date": "08/09/2026", "result": "Normal", "cost_gbp": 85.00}
            ],
            "hospitalisation": {
                "admitted": "",
                "discharged": "",
                "days": 0,
                "daily_rate_gbp": 0,
                "procedure": "None",
                "procedure_cost_gbp": 0,
                "medication_cost_gbp": 0
            },
            "consultation_cost_gbp": 100.00
        },
        {
            "patient_id": "PT008",
            "name": "Henry Irving",
            "nhs_number": "289 012 3456",
            "age": 48,
            "gender": "Male",
            "address": "11 Station Road, Chippenham",
            "phone": "07780 888999",
            "medical_history": "Kidney Stones (recurring)",
            "tests": [
                {"test_name": "Urine Analysis", "date": "07/09/2026", "result": "Blood present", "cost_gbp": 65.00},
                {"test_name": "Abdominal CT Scan", "date": "07/09/2026", "result": "Stone detected", "cost_gbp": 400.00},
                {"test_name": "Kidney Function Blood Test", "date": "08/09/2026", "result": "Slightly elevated", "cost_gbp": 90.00}
            ],
            "hospitalisation": {
                "admitted": "07/09/2026",
                "discharged": "09/09/2026",
                "days": 2,
                "daily_rate_gbp": 350.00,
                "procedure": "Lithotripsy",
                "procedure_cost_gbp": 2800.00,
                "medication_cost_gbp": 150.00
            },
            "consultation_cost_gbp": 200.00
        }
    ]

    return patients


# ============================================================
# OPTION 1: View all patients
# ============================================================
def view_all_patients(patients):
    print("\n" + "=" * 60)
    print("             ALL REGISTERED PATIENTS")
    print("=" * 60)

    # Loop through each patient and display their details
    for p in patients:
        print(f"\n  Patient ID:       {p['patient_id']}")
        print(f"  Name:             {p['name']}")
        print(f"  NHS Number:       {p['nhs_number']}")
        print(f"  Age:              {p['age']}")
        print(f"  Gender:           {p['gender']}")
        print(f"  Address:          {p['address']}")
        print(f"  Phone:            {p['phone']}")
        print(f"  Medical History:  {p['medical_history']}")

        # Display test records
        print(f"  Tests ({len(p['tests'])}):")
        for t in p["tests"]:
            print(f"    - {t['test_name']} ({t['date']}): "
                  f"{t['result']} | GBP {t['cost_gbp']:.2f}")

        # Display hospitalisation details
        h = p["hospitalisation"]
        if h["days"] > 0:
            print(f"  Hospitalisation:")
            print(f"    Admitted:       {h['admitted']}")
            print(f"    Discharged:     {h['discharged']}")
            print(f"    Days:           {h['days']}")
            print(f"    Daily Rate:     GBP {h['daily_rate_gbp']:.2f}")
            print(f"    Procedure:      {h['procedure']}")
            print(f"    Procedure Cost: GBP {h['procedure_cost_gbp']:.2f}")
            print(f"    Medication:     GBP {h['medication_cost_gbp']:.2f}")
        else:
            print(f"  Hospitalisation:  Outpatient only (no admission)")

        print(f"  Consultation Fee: GBP {p['consultation_cost_gbp']:.2f}")
        print("-" * 60)

    print(f"\n  Total patients: {len(patients)}")


# ============================================================
# OPTION 2: View all test results
# ============================================================
def view_all_tests(patients):
    print("\n" + "=" * 90)
    print("                          ALL TEST RESULTS")
    print("=" * 90)
    print(f"  {'Patient':<18} {'Test Name':<28} {'Date':<12} {'Result':<20} {'Cost':>8}")
    print("-" * 90)

    total_tests = 0

    # Loop through each patient
    for p in patients:
        # Loop through each test for that patient
        for t in p["tests"]:
            print(f"  {p['name']:<18} {t['test_name']:<28} {t['date']:<12} "
                  f"{t['result']:<20} {t['cost_gbp']:>7.2f}")
            total_tests = total_tests + 1

    print("=" * 90)
    print(f"  Total tests performed: {total_tests}")


# ============================================================
# OPTION 3: Calculate total hospitalisation costs (Calc #1)
# ============================================================
def calculate_hospitalisation_costs(patients):
    total_room = 0
    total_procedures = 0
    total_medication = 0
    admitted_count = 0

    # Loop through each patient
    for p in patients:
        h = p["hospitalisation"]

        # Only count patients who were actually admitted
        if h["days"] > 0:
            admitted_count = admitted_count + 1

            # Room cost = number of days * daily rate
            room_cost = h["days"] * h["daily_rate_gbp"]
            total_room = total_room + room_cost
            total_procedures = total_procedures + h["procedure_cost_gbp"]
            total_medication = total_medication + h["medication_cost_gbp"]

    # Calculate the grand total
    grand_total = total_room + total_procedures + total_medication

    # Display the results
    print("\n" + "=" * 55)
    print("  CALCULATION #1: TOTAL HOSPITALISATION COSTS")
    print("=" * 55)
    print(f"  Patients admitted:      {admitted_count}")
    print(f"  Total room charges:     GBP {total_room:.2f}")
    print(f"  Total procedure costs:  GBP {total_procedures:.2f}")
    print(f"  Total medication costs: GBP {total_medication:.2f}")
    print("-" * 55)
    print(f"  GRAND TOTAL:            GBP {grand_total:.2f}")
    print("=" * 55)

    # Show breakdown per admitted patient
    print("\n  Breakdown by patient:")
    for p in patients:
        h = p["hospitalisation"]
        if h["days"] > 0:
            room = h["days"] * h["daily_rate_gbp"]
            patient_total = room + h["procedure_cost_gbp"] + h["medication_cost_gbp"]
            print(f"    {p['name']:<20} {h['days']} days | "
                  f"Room: {room:.2f} + Procedure: {h['procedure_cost_gbp']:.2f} "
                  f"+ Meds: {h['medication_cost_gbp']:.2f} = GBP {patient_total:.2f}")

    return grand_total


# ============================================================
# OPTION 4: Calculate total revenue from tests (Calc #2)
# ============================================================
def calculate_test_revenue(patients):
    total_revenue = 0
    total_tests = 0

    # Dictionary to group revenue by test type
    test_type_totals = {}

    # Loop through all patients and their tests
    for p in patients:
        for t in p["tests"]:
            total_revenue = total_revenue + t["cost_gbp"]
            total_tests = total_tests + 1

            # Group by test name
            test_name = t["test_name"]
            if test_name in test_type_totals:
                test_type_totals[test_name]["count"] = test_type_totals[test_name]["count"] + 1
                test_type_totals[test_name]["total"] = test_type_totals[test_name]["total"] + t["cost_gbp"]
            else:
                test_type_totals[test_name] = {"count": 1, "total": t["cost_gbp"]}

    # Display the results
    print("\n" + "=" * 60)
    print("  CALCULATION #2: TOTAL REVENUE FROM TESTS")
    print("=" * 60)
    print(f"  Total tests performed:   {total_tests}")
    print(f"  Total Test Revenue:      GBP {total_revenue:.2f}")
    print("-" * 60)
    print("  Breakdown by test type:")
    print(f"    {'Test Name':<28} {'Count':>6} {'Revenue':>10}")
    print("    " + "-" * 46)

    # Loop through each test type and display its totals
    for test_name in test_type_totals:
        count = test_type_totals[test_name]["count"]
        total = test_type_totals[test_name]["total"]
        print(f"    {test_name:<28} {count:>6} GBP {total:>7.2f}")

    print("=" * 60)

    return total_revenue


# ============================================================
# OPTION 5: Calculate patient billing summary (Calc #3)
# ============================================================
def calculate_billing_summary(patients):
    print("\n" + "=" * 70)
    print("     CALCULATION #3: PATIENT BILLING SUMMARY")
    print("=" * 70)

    grand_total = 0

    # Loop through each patient
    for p in patients:
        # Add up all test costs for this patient
        test_total = 0
        for t in p["tests"]:
            test_total = test_total + t["cost_gbp"]

        # Calculate hospitalisation total
        h = p["hospitalisation"]
        room_cost = h["days"] * h["daily_rate_gbp"]
        hosp_total = room_cost + h["procedure_cost_gbp"] + h["medication_cost_gbp"]

        # Consultation cost
        consult = p["consultation_cost_gbp"]

        # Patient's total bill
        patient_total = consult + test_total + hosp_total

        grand_total = grand_total + patient_total

        # Display the breakdown
        print(f"\n  {p['name']} ({p['patient_id']})")
        print(f"    Consultation:       GBP {consult:>9.2f}")
        print(f"    Tests ({len(p['tests'])}):           GBP {test_total:>9.2f}")

        if h["days"] > 0:
            print(f"    Room ({h['days']} days):        GBP {room_cost:>9.2f}")
            print(f"    Procedure:          GBP {h['procedure_cost_gbp']:>9.2f}")
            print(f"    Medication:         GBP {h['medication_cost_gbp']:>9.2f}")
        else:
            print(f"    Hospitalisation:    GBP      0.00  (outpatient)")

        print(f"    --------------------------------")
        print(f"    TOTAL BILL:         GBP {patient_total:>9.2f}")

    print("\n" + "=" * 70)
    print(f"  GRAND TOTAL (all patients): GBP {grand_total:.2f}")
    print("=" * 70)

    return grand_total


# ============================================================
# OPTION 6: Look up a specific patient
# ============================================================
def lookup_patient(patients):
    print("\n" + "=" * 42)
    print("         PATIENT LOOKUP")
    print("=" * 42)
    print("  Search by:")
    print("    1. Patient name")
    print("    2. Patient ID")
    print("    3. NHS number")
    print("    4. Date of visit")
    print("=" * 42)

    search_choice = input("  Choose search method (1-4): ")

    # Ask for the search term based on the user's choice
    if search_choice == "1":
        search_term = input("  Enter patient name (or part of it): ")
    elif search_choice == "2":
        search_term = input("  Enter patient ID (e.g. PT001): ")
    elif search_choice == "3":
        search_term = input("  Enter NHS number (or part of it): ")
    elif search_choice == "4":
        search_term = input("  Enter date (e.g. 02/09/2026): ")
    else:
        print("  Invalid choice.")
        return

    # Search through patients for matches
    results = []

    for p in patients:
        found = False  # Flag to track if this patient matches

        if search_choice == "1":
            # Search by name (case-insensitive)
            if search_term.lower() in p["name"].lower():
                found = True

        elif search_choice == "2":
            # Search by patient ID (case-insensitive)
            if search_term.lower() in p["patient_id"].lower():
                found = True

        elif search_choice == "3":
            # Search by NHS number
            if search_term in p["nhs_number"]:
                found = True

        elif search_choice == "4":
            # Search by date in tests or hospitalisation
            for t in p["tests"]:
                if search_term in t["date"]:
                    found = True

            if search_term in p["hospitalisation"]["admitted"]:
                found = True

        # If found, add to results
        if found == True:
            results.append(p)

    # Display the results
    if len(results) == 0:
        print(f"\n  No patients found matching '{search_term}'.")
    else:
        print(f"\n  Found {len(results)} patient(s):\n")
        for p in results:
            print(f"  Patient ID:       {p['patient_id']}")
            print(f"  Name:             {p['name']}")
            print(f"  NHS Number:       {p['nhs_number']}")
            print(f"  Age:              {p['age']}   Gender: {p['gender']}")
            print(f"  Phone:            {p['phone']}")
            print(f"  Medical History:  {p['medical_history']}")

            print(f"  Tests:")
            for t in p["tests"]:
                print(f"    - {t['test_name']} ({t['date']}): {t['result']}")

            h = p["hospitalisation"]
            if h["days"] > 0:
                print(f"  Admitted: {h['admitted']} to {h['discharged']} "
                      f"({h['days']} days) | {h['procedure']}")
            else:
                print(f"  Hospitalisation: Outpatient only")

            print("-" * 50)


# ============================================================
# FUNCTION: Write results to an output report file
# ============================================================
def write_report(patients):
    filename = "output_report.txt"

    try:
        file = open(filename, "w")  # Open file for writing

        # Header
        file.write("PRIVATE HOSPITAL - DATA PROCESSING REPORT\n")
        file.write("=" * 50 + "\n")
        file.write(f"Total patients: {len(patients)}\n\n")

        # All patients
        file.write("PATIENT RECORDS\n")
        file.write("-" * 50 + "\n")
        for p in patients:
            file.write(f"Patient {p['patient_id']}: {p['name']}\n")
            file.write(f"  NHS: {p['nhs_number']} | Age: {p['age']} | {p['gender']}\n")
            file.write(f"  Address: {p['address']}\n")
            file.write(f"  Phone: {p['phone']}\n")
            file.write(f"  History: {p['medical_history']}\n")

            for t in p["tests"]:
                file.write(f"  Test: {t['test_name']} ({t['date']}) "
                           f"- {t['result']} | GBP {t['cost_gbp']:.2f}\n")

            h = p["hospitalisation"]
            if h["days"] > 0:
                room = h["days"] * h["daily_rate_gbp"]
                file.write(f"  Hospitalised: {h['admitted']} to {h['discharged']} "
                           f"({h['days']} days)\n")
                file.write(f"  Room: GBP {room:.2f} | Procedure: GBP "
                           f"{h['procedure_cost_gbp']:.2f} | Meds: GBP "
                           f"{h['medication_cost_gbp']:.2f}\n")
            file.write(f"  Consultation: GBP {p['consultation_cost_gbp']:.2f}\n\n")

        # Calculation 1: Hospitalisation costs
        total_hosp = 0
        for p in patients:
            h = p["hospitalisation"]
            if h["days"] > 0:
                total_hosp = total_hosp + (h["days"] * h["daily_rate_gbp"])
                total_hosp = total_hosp + h["procedure_cost_gbp"]
                total_hosp = total_hosp + h["medication_cost_gbp"]

        file.write("CALCULATION RESULTS\n")
        file.write("-" * 50 + "\n")
        file.write(f"1. Total Hospitalisation Costs: GBP {total_hosp:.2f}\n")

        # Calculation 2: Test revenue
        total_tests = 0
        for p in patients:
            for t in p["tests"]:
                total_tests = total_tests + t["cost_gbp"]
        file.write(f"2. Total Test Revenue: GBP {total_tests:.2f}\n")

        # Calculation 3: Grand total billing
        grand_total = 0
        for p in patients:
            test_total = 0
            for t in p["tests"]:
                test_total = test_total + t["cost_gbp"]
            h = p["hospitalisation"]
            room = h["days"] * h["daily_rate_gbp"]
            hosp = room + h["procedure_cost_gbp"] + h["medication_cost_gbp"]
            grand_total = grand_total + p["consultation_cost_gbp"] + test_total + hosp
        file.write(f"3. Grand Total Billing: GBP {grand_total:.2f}\n")

        file.write("\n" + "=" * 50 + "\n")
        file.write("End of report.\n")

        file.close()
        print(f"\n  Report saved to '{filename}'.")

    except Exception as e:
        print(f"  Error writing report: {e}")


# ============================================================
# FUNCTION: Interactive main menu
# ============================================================
def show_menu(patients):
    while True:
        # Display the menu
        print("\n" + "=" * 55)
        print("               MAIN MENU")
        print("=" * 55)
        print("  1. View all patients")
        print("  2. View all test results")
        print("  3. Calculate total hospitalisation costs")
        print("  4. Calculate total revenue from tests")
        print("  5. Calculate patient billing summary")
        print("  6. Look up a specific patient")
        print("  7. Exit program")
        print("=" * 55)

        # Get the user's choice
        choice = input("  Choose an option (1-7): ")

        # Run the matching function based on user choice
        if choice == "1":
            view_all_patients(patients)

        elif choice == "2":
            view_all_tests(patients)

        elif choice == "3":
            calculate_hospitalisation_costs(patients)

        elif choice == "4":
            calculate_test_revenue(patients)

        elif choice == "5":
            calculate_billing_summary(patients)

        elif choice == "6":
            lookup_patient(patients)

        elif choice == "7":
            # Save the report before exiting
            write_report(patients)
            print("  Exiting program. Goodbye!")
            break  # Exit the while loop

        else:
            print("  Invalid option. Please enter a number between 1 and 7.")


# ============================================================
# MAIN PROGRAM - This is where execution begins
# ============================================================

# Display a welcome message
print("=" * 55)
print("   WELCOME TO THE HOSPITAL DATA PROCESSOR")
print("=" * 55)

# Step 1: Create the patient data
patients = create_patients()
print(f"  Loaded {len(patients)} patient records.\n")

# Step 2: Launch the interactive menu
show_menu(patients)
