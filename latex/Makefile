all: project-plan.pdf

project-plan.pdf: main.tex sections/overview.tex sections/structure.tex sections/responsibilities.tex sections/timeline.tex sections/schema.tex
	pdflatex -interaction=nonstopmode -halt-on-error -jobname=project-plan main.tex
	pdflatex -interaction=nonstopmode -halt-on-error -jobname=project-plan main.tex

clean:
	rm -f *.aux *.log *.out *.toc *.lof *.lot project-plan.pdf
