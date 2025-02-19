#"PHONEIFOGA#
# Installation Process
git clone https://github.com/sundowndev/PhoneInfoga
cd PhoneInfoga/
python3 -m pip install -r requirements.txt

#Usage
usage: phoneinfoga.py -n <number> [options]

Advanced information gathering tool for phone numbers
(https://github.com/sundowndev/PhoneInfoga)

optional arguments:
  -h, --help            show this help message and exit
  -n number, --number number
                        The phone number to scan (E164 or International
                        format)
  -i input_file, --input input_file
                        Phone number list to scan (one per line)
  -o output_file, --output output_file
                        Output to save scan results
  -s scanner, --scanner scanner (any to skip, default: all)
                        The scanner to use
  --osint               Use OSINT reconnaissance
  -u, --update          Update the tool & databases

  #Example of Phonenumber Searched
  #Here(+42) is The Country code
  python3 phoneinfoga.py -n "(+42)837544833"
  #You Can check several Numbers at once By using 
  python3 phoneinfoga.py -i numbers.txt -o results.txt
  
