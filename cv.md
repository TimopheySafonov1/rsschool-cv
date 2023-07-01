# **Timophey Safonov**
![my photo](TImopheySafonov.jpg)
## My Contact
+48793152384

timophey.safonov@outlook.com

Warsaw, Poland

## About me

As a QA engineer, I have developed strong testing skills,
attention to detail, and collaboration abilities to ensure high-quality software through test planning, execution, and defect
reporting. I am proficient in various testing methodologies
and have experience working closely with cross-functional
teams to meet project requirements and deliver reliable
software.

## Skills

- Manual testing of web applications
- API testing
- Mobile testing
- Agile
- HTML
- CSS
- API testing
- SQL
- Git
- Linux
- .NUnit
- .Net(C#)

## Code examples
``` C#
namespace ClassLibrary1
{
    public static class TypeOfSequence
    {
        public static string? Name (long source)
        {

            if (source >= -9 && source <= 9)
            {
                return "One digit number.";
            }
            bool isIncreasing = true;
            bool isDecreasing = true;
            bool isStrictlyIncreasing = true;
            bool isStrictlyDecreasing = true;
            bool Monotonous = true;

            long temp = source;
            long previousCurrent = temp % 10;
            temp /= 10;
            do
            {
                long current = temp % 10;
                isIncreasing &= (previousCurrent >= current);
                isDecreasing &= (previousCurrent <= current);
                isStrictlyIncreasing &= (previousCurrent > current);
                isStrictlyDecreasing &= (previousCurrent < current);
                Monotonous &= (previousCurrent == current);
                previousCurrent = current;

            } while ((temp /= 10) != 0);
            
            if (isIncreasing && isStrictlyIncreasing)
            {
                return "Strictly Increasing.";
            }
            if (isDecreasing && isIncreasing)
            {
                return "Monotonous";
            }
            if (isIncreasing && !isStrictlyIncreasing)
            {
                return "Increasing";
            }
            if (isDecreasing && isStrictlyDecreasing)
            {
                return "Strictly Decreasing.";
            }
            if (isDecreasing && !isStrictlyDecreasing)
            {
                return "Decreasing.";
            }
            
            return "Unordered.";

        }
      
    }
}
```

## Experience 

**Support Specialist**

*September 2020 - September 2022*

 - quality control of electrical goods;
 - data visualization;
 - commodity analytics;
 - work with waybills, consignment notes, and CMR;
 - networking with the sales manager;
 - organization of the warehouse;

 ## Education

 **Belarusian National Technical University**

 Bachelors in Power Engineering

 September 2022 - June 2023

 **Beetroot Academy**

 QA MANUAL

 May 2023 - June 2023

