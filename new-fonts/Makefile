all: webdings.new.ttf wingdings.new.ttf wingdings2.new.ttf wingdings3.new.ttf mt-extra.new.ttf

webdings.new.ttf: ../../script/font2font.py ../webdings/webdings-mapping.new.csv
	fontforge -lang=py -script ../../script/font2font.py ../webdings/webdings-mapping.new.csv ../webdings/webdings.new.ttf

wingdings.new.ttf: ../../script/font2font.py ../wingdings/wingdings-mapping.new.csv
	../../script/font2font.py ../wingdings/wingdings-mapping.new.csv ../wingdings/wingdings.new.ttf

wingdings2.new.ttf: ../../script/font2font.py ../wingdings2/wingdings2-mapping.new.csv
	../../script/font2font.py ../wingdings2/wingdings2-mapping.new.csv ../wingdings2/wingdings2.new.ttf

wingdings3.new.ttf: ../../script/font2font.py ../wingdings3/wingdings3-mapping.new.csv
	../../script/font2font.py ../wingdings3/wingdings3-mapping.new.csv ../wingdings3/wingdings3.new.ttf

mt-extra.new.ttf: ../../script/font2font.py ../mt-extra/mt-extra-mapping.new.csv
	../../script/font2font.py ../mt-extra/mt-extra-mapping.new.csv ../mt-extra/mt-extra.new.ttf
