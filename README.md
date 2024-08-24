# geriSayanSaya-

import time

def geri_sayan_sayaç(sure):
    while sure > 0:
        print(f"kalan süre: {sure} saniye")
        time.sleep(1)
        sure -= 1

    print("süre bitti")


geri_sayan_sayaç(10)
