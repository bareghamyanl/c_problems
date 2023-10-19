## Problems (Deadline : 22.10.2023, 21:00)

#### Խնդիր 1
Տրված է կետ, որն ընկած չէ կոորդինատների առանցքների
վրա: Արտածել կոորդինատային քառորդի համարը, որտեղ
ընկած է այդ կետը:

#### Խնդիր 2
Արտածել **YES**, եթե տրված (x,y) կետը պատկանում է
(0,0),(0,-1),(-1,0) կետերով կառուցված եռանկյանը,
**NO**` հակառակ դեպքում:

#### Խնդիր 3
Տրված են ուղղանկյան երեք գագաթների կոորդինատները:
Ուղղանկյան կողմերը զուգահեռ են կոորդինատների առանցքներին: Արտածել չորրորդ կետի կոորդինատները:

#### Խնդիր 4
Տրված n > 7 բնական թվի համար գտնել այնպիսի a և b բնական թվեր, որ 3a + 5b = n:

#### Խնդիր 5
Գրել պարզ հաշվիչ , որը մուտքում կստանա 2 իրական թիվ, գործողության տեսակը և կարտածի գործողության  արդյունքը  (switch ... case):


### Enum  օրինակներ
```c
#include <stdio.h>
enum week {Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday};
int main()
{
    // creating today variable of enum week type
    enum week today;
    today = Wednesday;
    printf("Day %d",today+1);
    return 0;
}
```
#### Խնդրի լուծման օրինակ
**Խնդիր:**
Գրեք C ծրագիր ՝ թվարկված տվյալների տեսակները 7 օրվա ընթացքում ստեղծելու և դրանց արժեքները ամբողջ հաստատունների վրա ցուցադրելու համար:  
**Լուծում :**
```c
#include <stdio.h>
int main()
{
    enum week{Sun, Mon, Tue, Wed, Thu, Fri, Sat};
    printf("Sun = %d", Sun);
    printf("\nMon = %d", Mon);
    printf("\nTue = %d", Tue);
    printf("\nWed = %d", Wed);
    printf("\nThu = %d", Thu);
    printf("\nFri = %d", Fri);
    printf("\nSat = %d", Sat);
    return 0;
}

```

#### Խնդիր 6
Կանխատեսեք հետևյալ C ծրագրի արդյունքը
```c
#include <stdio.h> 
enum day {sunday = 1, tuesday, wednesday, thursday, friday, saturday}; 
int main() 
{ 
	enum day d = thursday; 
	printf("The day number stored in d is %d", d); 
	return 0; 
}
```
