---
layout: post
title: Usando Equações em Markdown
author: Agostinho Brito
tag:
  - equacoes
  - LaTeX
mathjax: true
---
# Quimica

## Lista 03 - Rendimento

*Q1-* (Fuvest-SP) O nitrogênio pode ser obtido pela decomposição térmica de nitrito de amônio.

\begin{enumerate}[label=\alph*)]
	\item Escreva a equação de decomposição do nitrito de amônio.
	\item Calcule o volume de nitrogênio obtido, nas CNTP, pela decomposição de 12,8 g de nitrito de amônio, supondo que o rendimento da reação seja de 80\% (em massa).
\end{enumerate}

(Massa atômicas: \ce{H} = 1; \ce{O} = 16; \ce{N} = 14)
\\
\\
\textbf{\textcolor{red}{Resolução}}
\\
\\
a) Equação química balanceada:

$$ \ce{NH_4NO_2}_{(s)} \ce{->} 2 \ce{H_2O}_{(l)} + \ce{N_2}_{(g)}$$
\\
b) Segundo a equação química, já balanceada, 1 mol de \ce{N2} é produzido para cada mol de \ce{NH4NO2} que reage. Além disso, sabemos que 1 mol de qualquer gás nas CNTP ocupa um volume igual a 22,4 L. Logo:
\begin{center}
1 mol de \ce{NH_4NO_2} - - - - 1 mol de \ce{N_2}\\
64 g de \ce{NH_4NO_2} - - - - 22,4 L de \ce{N_2}\\
12,8 g de \ce{NH_4NO_2} - - - - $V_{N_2}}$\\
\vspace{.2cm}
\\
$V_\ce{N_2}$ = $\frac{12,8 \cancel{g} \cdot 22,4 L}{64 \cancel{g}}$\\
$V_\ce{N_2} = 4,48 L$
\end{center}
Como a reação apresentou 80\% de rendimento, o volume de \ce{N_2} é dado por:

\begin{center}
	100\% de rendimento - - - - 4,88 L de \ce{N_2}\\
	80\% de rendimento - - - - V_\ce{N_2}\\
	\vspace{.2cm}
	$V_\ce{N_2}$ = $\frac{80\bcancel{\%} \cdot 4,48 L}{100\bcancel{\%}}$\\
	\vspace{.2cm}
	$V_{\ce{N_2}} = 3,58 L$
\end{center}
