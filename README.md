# popes
Dataset of all official popes from Peter to Francis, scraped from the Wikipedia article ["List of popes"](https://en.wikipedia.org/wiki/List_of_popes). Used in my blog post ["Francis is an old pope"](https://twopoints.blog/posts/2023-02-06-francis-is-an-old-pope/).

## Variables
- `number`: Pontiff number  
- `name_full`: Full papal name, including regnal suffix in Roman numerals  
- `name`: Papal name without suffix  
- `personal_name`: Pope's birth name  
- `suffix`: Regnal suffix in integer format  
- `suffix_L`: Regnal suffix in Latin letters  
- `name_L`: Papal name in Latin without suffix  
- `canonization`: Current stage in the canonization process, if applicable  
- `birth`: Date of birth  
- `DMY_birth`: Date of birth in DD/MM/YYYY format  
- `birth_place`: Place of birth  
- `start`: Date of accession to the papacy  
- `DMY_start`: Date of accession to the papacy in DD/MM/YYYY format  
- `end`: Date of end of papacy  
- `DMY_end`: Date of end of papacy in DD/MM/YYYY format  
- `age_start`: Age at the start of papacy, in full years  
- `age_end`: Age at the end of papacy, in full years  
- `tenure`: Length of papacy in fractional years  
- `notes`: Notes regarding the papacy  
- `wiki`: Link to the Wikipedia article dedicated to the pope

## Notes
- All antipopes were excluded.
- Where only birth years are given, the birth date is assumed to be 30 June.
- Where only years are given for the pope's tenure, it is assumed that tenure started on 1 January and ended on 31 December.
- Where multiple or a range of years are given due to historical uncertainty, the earliest year is used.