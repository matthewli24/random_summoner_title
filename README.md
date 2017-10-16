Random Title Generator 
================================
Note: This is work in progress. This little project is made for my own practice and entertainment.
********************************
Description: This little program is developed on Ubuntu and uses C++ to handle HTTP queries and JSON data from RIOT's SUMMONER-V3 and LEAGUE-V3 API.
This program only accepts valid NA Summoner Names in the meantime.
********************************
USAGE:
1) Need to insert a API KEY in main.cpp
2) To compile on Ubuntu: g++ -o <main> *.cpp -lcurl
3) Requires the curl/curl.h library. Can be install with:
sudo apt-get install libcurl-dev 
OR sudo apt-get install libcurl4-openssl-dev (the OpenSSL variant)
OR sudo apt-get install libcurl4-gnutls-dev (the gnutls variant)
4) To run the program on command line for example: ./main NA-Summoner-Name
*******************************
To Do List
- Do more Error Handling
- Need more testing
- Incorporte champion mastery API to decide main role
- Add more unique and funny nouns
