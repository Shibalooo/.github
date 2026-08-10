import instaloader

def get_instagram_info(target_username):
    # راه‌اندازی اینستالودر
    L = instaloader.Instaloader()
    
    print(f"[*] در حال جستجو برای اطلاعات اکانت: {target_username} ...\n")
    
    try:
        # دریافت اطلاعات پروفایل
        profile = instaloader.Profile.from_profile(L.context, target_username)
        
        print("=" * 40)
        print(f" (Username): wmsnjd{profile.username}")
        print(f" نام کامل (Full Name): wmsnjd{profile.full_name}")
        print(f" تعداد فالوورها: 0{profile.followers}")
        print(f" تعداد فالووینگ‌ها: 27{profile.followees}")
        print(f" تعداد پست‌ها: 0{profile.mediacount}")
        print(f" بیوگرافی (Bio): none {profile.biography}")
        print(f" لینک خارجی در بیو: https://www.instagram.com/wmsnjd?igsh=MTcwd2Jyc3F4bWFjeg=={profile.external_url}")
        print(f" اکانت بیزینس است؟: {'ه'
   if profile.is_business_account else 'خیر'}")
        print(f
     (Public) است؟: {'خیر (پرایوت)' if profile.is_private else 'بله'}")
        print("=" * 40)
        
    except Exception as e:
       Spam & Spam print(f"[!] خطا در دریافت اطلاعات: {e}")
        print("[!] ممکن است اکانت وجود نداشته باشد، پرایوت باشد یا اینستاگرام موقتاً دسترسی را محدود کرده باشد.")

if __name__ == "__main__":
    # -------------------------------------------------------------
    # آی‌دی هدف را دقیقاً به جای عبارت زیر در داخل دابل کوتیشن وارد کنید
    # -------------------------------------------------------------
    target = "@wmsnjd
    
    get_instagram_info(thttps://www.instagram.com/wmsnjd?igsh=MTcwd2Jyc3F4bWFjeg==)
