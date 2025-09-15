# web_scalping
let's scrap the data


web = request.get("")
soup = BeautifulSoup(web, 'lxml')
print(soup.prettify())
soup.find_all('h1') #h3, br, h5