| **Name** | Anastasiya Gaydukova |
| --- | --- |
| **Date of birth** | 1st of March 1996 |
| **Address** | 139a Bogdanovicha St, apt. 150, Minsk, 220123, Belarus |
| **Phone number** | +375-29-1097482 |
| **Email** | [asya.grunberg@gmail.com](mailto:asya.grunberg@gmail.com) |
| **Marital status** | Single |
| **Nationality** | Belarusian |

**Objective**

I want to obtain a position as a front-end developer in company epam. My knowledge of programming, English level, experience, character achieving company&#39;s goals.

**Education**

Belarussian State University, department of biology, 5th year student (2016-2021)

**Qualifications**

July 2017 – October 2018: English courses in International House, finished B2 level.

November 2018 – January 2019: programming in Python courses at TeachMeSkills, Minsk, Belarus.

February 2020 – March 2020: programming in C++ at Institute of Business of BSU, Minsk, Belarus.

Certificates on Stepik: &quot;Programming on Python&quot;, &quot;Basics of Statistics&quot;.

Coursework in bioinformatics: &quot;Identification of 5&#39;-non-translated regions in human RNA molecules&quot;.

**Personal qualities**

I am а quick learner, hardworking and open to change. Able to prioritize and adapt well to new situations.

**Skills**

Languages:

Native Russian

Fluent Belorussian

Upper-Intermediate English

Basic knowledge of Python, C++, R, statistics, command line.

In-depth knowledge of Excel, Word.

**Code examples**

1. A program that can encrypt and decrypt a substitution cipher. The program accepts input two lines of the same length, the first line contains the characters of the original alphabet, the second line contains the characters of the final alphabet, after which there is a line that needs to be encrypted with the transmitted key, and another line that needs to be decrypted.

beg = input()

end = input()

s\_1 = input()

s\_2 = input()

dict\_beg = {}

dict\_cipher = {}

index\_beg = 0

index\_end = 0

for i in beg:

dict\_beg[i] = end[index\_beg]

index\_beg += 1

for i in end:

dict\_cipher[i] = beg[index\_end]

index\_end += 1

s\_1\_end = &#39;&#39;

s\_2\_end = &#39;&#39;

for i in s\_1:

i = dict\_beg[i]

s\_1\_end = s\_1\_end + i

for i in s\_2:

i = dict\_cipher[i]

s\_2\_end = s\_2\_end + i

print(s\_1\_end)

print(s\_2\_end)

2. The program that reads the string, encodes it with the suggested compression algorithm and outputs the encoded sequence to standard output. Coding is done as follows: s = &#39;aaaabbсaa&#39; is converted to &#39;a4b2с1a2&#39;, that is, groups of identical characters in the original string are replaced with this character and the number of its repetitions in this position of the string.

s = input(&#39;&#39;)

previous = s[0]

a = 0

b = &#39;&#39;

for current in s:

if previous == current:

a = a + 1

if previous != current:

b = b + previous + str(a)

a = 1

previous = current

b = b + current + str(a)

print(b)

3. The program that outputs a rhombus of a given diagonal.

i = 1

n = int(input())

r = int((n - 1) / 2)

while i \&lt; n:

x = &#39;&#39;

for k in range(r):

x = x + &#39; &#39;

for k in range(i):

x = x + &#39;\*&#39;

i = i + 2

r = r - 1

print(x)

i = 1

c = 0

while n \&gt;= i:

x = &#39;&#39;

for k in range(c):

x = x + &#39; &#39;

for k in range(n):

x = x + &#39;\*&#39;

n = n - 2

c = c + 1

print(x)