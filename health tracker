Water Intake & Health Tracker


print("💧 Welcome to your Water Intake & Health Tracker 💪")

total_water = 0
days = int(input("How many days do you want to track? "))

for day in range(1, days + 1):
    print(f"\nDay {day}")
    water = int(input("How many glasses of water did you drink today? "))
    total_water += water

    # Check health status for the day
    if water >= 8:
        print("✅ Excellent! You stayed fully hydrated today.")
    elif water >= 5:
        print("🙂 Good! But try to drink a bit more water.")
    else:
        print("⚠️ You need to drink more water to stay healthy!")

# After the loop, show average intake
average = total_water / days
print("\n📊 Tracking complete!")
print(f"Your average daily water intake: {average:.1f} glasses")

# Final health summary
if average >= 8:
    print("🌟 Overall health: Excellent hydration!")
elif average >= 5:
    print("💧 Overall health: Fair, but drink a little more.")
else:
    print("🚱 Overall health: Poor hydration! Start drinking more water.")

#  BSAISS2 1st semester
