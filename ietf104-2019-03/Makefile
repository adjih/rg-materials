BASE=ietf104_nwcrg_agenda
BASE1=ietf104_swif_hackathon
#BASE2=ietf104_nwcrg_minutes

MDFILE=${BASE}.md
MDFILE1=${BASE1}.md
MDFILE2=${BASE2}.md

PDFFILE=${BASE}.pdf
PDFFILE1=${BASE1}.pdf
PDFFILE2=${BASE2}.pdf

HTMLFILE=${BASE}.html
HTMLFILE1=${BASE1}.html
HTMLFILE2=${BASE2}.html

html:
	# standalone HTML output
	pandoc -s ${MDFILE} -o ${HTMLFILE}
	pandoc -s ${MDFILE1} -o ${HTMLFILE1}
	#pandoc -s ${MDFILE2} -o ${HTMLFILE2}

pdf:
	# standalone PDF output
	#pandoc -s ${MDFILE} -o ${PDFFILE}
	#pandoc -s ${MDFILE1} -o ${PDFFILE1}
	#pandoc -s ${MDFILE2} -o ${PDFFILE2}
