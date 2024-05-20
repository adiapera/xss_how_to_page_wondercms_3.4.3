# XSS in WonderCMS 3.4.3 (HOW TO PAGE)
**Software link:** WonderCMS 3.4.3 [https://www.wondercms.com/download]

**@author:** Antonio Díaz Pérez.

**Description:** Cross-site scripting (XSS) vulnerability in the HOW TO Page section of WonderCMS 3.4.3 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into all fields.

**CVE:** CVE-2024-32339.

## PoC
### HOW TO Page (CVE-2024-32339)
1. Enter to HOW TO page and in any parameter set the payload:

![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/2e5d39bf-eb47-4996-976e-2bd3b9befc21)
![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/437fa7f1-91d4-4dad-af73-4ee77401a633)

or

![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/b55ae5e0-fa12-4533-a771-d4ce77935d6f)
![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/0fab4cdc-8a00-4a9e-900e-f0d5be9467b1)

or

![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/b55ae5e0-fa12-4533-a771-d4ce77935d6f)
![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/f78735a1-1681-45ff-b877-14dca1150523)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/8c8d79c9-0ddc-4b05-8cc5-b01128f208e8)
![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/fde6198c-f052-4d5b-abbc-ff0170842448)

or

![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/fac56ef6-a764-4b99-9c86-7cfa8304cf80)
![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/fabc37eb-dbd6-401c-83cf-ac0788f16710)

or

![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/037593f6-3ba1-4e47-9ec7-8d4b953c7b80)
![image](https://github.com/adiapera/xss_how_to_page_wondercms_3.4.3/assets/165512291/1239debd-eb72-47d2-93b2-79e32b5bee7e)




