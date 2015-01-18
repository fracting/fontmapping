all: webdings-mapping.new.html wingdings-mapping.html wingdings2-mapping.html wingdings3-mapping.html mt-extra-mapping.html webdings-mapping.new.html wingdings-mapping.new.html wingdings2-mapping.new.html wingdings3-mapping.new.html mt-extra-mapping.new.html

webdings-mapping.html: ../../script/csv2html.py ../webdings/webdings-mapping.csv
	../../script/csv2html.py ../webdings/webdings-mapping.csv webdings-mapping.html

wingdings-mapping.html: ../../script/csv2html.py ../wingdings/wingdings-mapping.csv
	../../script/csv2html.py ../wingdings/wingdings-mapping.csv wingdings-mapping.html

wingdings2-mapping.html: ../../script/csv2html.py ../wingdings2/wingdings2-mapping.csv
	../../script/csv2html.py ../wingdings2/wingdings2-mapping.csv wingdings2-mapping.html

wingdings3-mapping.html: ../../script/csv2html.py ../wingdings3/wingdings3-mapping.csv
	../../script/csv2html.py ../wingdings3/wingdings3-mapping.csv wingdings3-mapping.html

mt-extra-mapping.html: ../../script/csv2html.py ../mt-extra/mt-extra-mapping.csv
	../../script/csv2html.py ../mt-extra/mt-extra-mapping.csv mt-extra-mapping.html

webdings-mapping.new.html: ../../script/csv2html.py ../webdings/webdings-mapping.new.csv
	../../script/csv2html.py ../webdings/webdings-mapping.new.csv webdings-mapping.new.html

wingdings-mapping.new.html: ../../script/csv2html.py ../wingdings/wingdings-mapping.new.csv
	../../script/csv2html.py ../wingdings/wingdings-mapping.new.csv wingdings-mapping.new.html

wingdings2-mapping.new.html: ../../script/csv2html.py ../wingdings2/wingdings2-mapping.new.csv
	../../script/csv2html.py ../wingdings2/wingdings2-mapping.new.csv wingdings2-mapping.new.html

wingdings3-mapping.new.html: ../../script/csv2html.py ../wingdings3/wingdings3-mapping.new.csv
	../../script/csv2html.py ../wingdings3/wingdings3-mapping.new.csv wingdings3-mapping.new.html

mt-extra-mapping.new.html: ../../script/csv2html.py ../mt-extra/mt-extra-mapping.new.csv
	../../script/csv2html.py ../mt-extra/mt-extra-mapping.new.csv mt-extra-mapping.new.html

../webdings/webdings-mapping.new.csv: ../../script/csv2csv.py ../webdings/webdings-mapping.csv
	../../script/csv2csv.py ../webdings/webdings-mapping.csv ../webdings/webdings-mapping.new.csv

../wingdings/wingdings-mapping.new.csv: ../../script/csv2csv.py ../wingdings/wingdings-mapping.csv
	../../script/csv2csv.py ../wingdings/wingdings-mapping.csv ../wingdings/wingdings-mapping.new.csv

../windings2/windings2-mapping.new.csv: ../../script/csv2csv.py ../windings2/windings2-mapping.csv
	../../script/csv2csv.py ../windings2/windings2-mapping.csv ../windings2/windings2-mapping.new.csv

../wingdings3/wingdings3-mapping.new.csv: ../../script/csv2csv.py ../wingdings3/wingdings3-mapping.csv
	../../script/csv2csv.py ../wingdings3/wingdings3-mapping.csv ../wingdings3/wingdings3-mapping.new.csv

../mt-extra/mt-extra-mapping.new.csv: ../../script/csv2csv.py ../mt-extra/mt-extra-mapping.csv
	../../script/csv2csv.py ../mt-extra/mt-extra-mapping.csv ../mt-extra/mt-extra-mapping.new.csv
