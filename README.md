
import datetime

def birthday_program():
    print("สุขสันต์วันเกิด ")
    # 1. 26.08.2568
    name = input("gusky: ")
    birth_str = input("26.08.2568 ")
    today = datetime.date.today()
    age = today.year - birthday.year
    if (today.month, today.day) < (birthday.month, birthday.day):
        age -= 1
    next_birthday = birthday.replace(year=today.year)
    if next_birthday < today:
        next_birthday = birthday.replace(year=today.year + 1)

    days_left = (next_birthday - today).days

    print("\n--- 26.08.2568 ---")
    print("ชื่อ:", gusky)
    print("วันเกิด:", birthday.strftime("%d %B %Y"))
    print("19:", age, "ปี")

    if days_left == 0:
        print("🎂 สุขสันต์วันเกิดนะ", gus, "🎉 ขอให้มีความสุขมาก ๆ 🥳")
    else:
        print("เหลืออีก", days_left, "วัน จะถึงวันเกิดถัดไป 🎁")
