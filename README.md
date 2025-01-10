# Course Syllabi for Electronic Engineering, NUST, ZW

Syllabi in LaTeX.


## Course

In the `course` directory, you can edit the syllabus information of each course. Each course has its own tex file named using the course code. 
In the `programme` directory, you can edit the following information of the degree programme:
<ul>
    <li>Name of the Department</li>
    <li>Degree Programme Information</li>
    <li>Entry Requirements</li>
    <li>Learning Outcomes</li>
    <li>Programme Assessment</li>
    <li>Programme Summary</li>
</ul>

## Lecturer
The names, qualifications and school email information is edited in the `staff` directory. Every lecturer has a tex file named using their surname.


## Logo

The resource `assests/nustLogoPng.png` is the logo from NUST, ZW. You can include the logo using,

```
\includegraphics[width=70mm]{\assets/nustLogoPng.png}
```  

## Bullet Items
Itemizations such as learning outcomes are designated with a [blue square](assets/blue_bullet.png).  To return to the default bullet item (black circle), comment out line #83 in `syllabus.tex`, specifically, 

```
\renewcommand{\labelitemi}{\includegraphics[]{\assets/blue_bullet.png}}
```

