# Report-Template
A generic template for report used for all submissions while at Penn. 

How to use
----------
Be sure to generate the .aux file each time you update the bibliography. Note that a custom cite style has been used.

1. Delete .aux file 
2. bibtex report
3. pdflatex report.pdf


Adding an image 
---------------
```
\begin{figure}[H]
\centerline{\includegraphics[width=10cm, height=7cm]{image_name.png}}
\caption{\label{fig:figure_label}Figure Description}
\end{figure}
```

Including code
--------------
```
\lstinputlisting{codeFile.cpp}
```



