# web_scalping
let's scrap the data
            # go to the google and search the my user agent
headers = { "User-Agent": Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/84.0.4147.105 Safari/537.36 }

web = request.get("")
soup = BeautifulSoup(web, 'lxml')
print(soup.prettify())
soup.find_all('h1') #h3, br, h5