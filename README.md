# Web_Scrapping
We Have to fetch All headlines And Articles from opindia website
import required functions...1)requests,2)BS4.BeautifulSoup
Copy and Paste URL
Data=requests.get(url)
preparing data into HTML form
Soup=BS4.BeautifulSoup(data.content)
inspect Webcode & Select copy paste the class and div if content to soup.find_all
Append Data in List
