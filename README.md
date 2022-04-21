pip install BeautifulSoup
pip install requests
impot time
pip install webbrowser

url= requests.get (https://app.simplefx.com/)

soup=beautifulsoup(url.content, "html.parser")
resultado= soup.find(<font style="vertical-align: inherit;">-122,73 USD</font>)
presioinicio_text=resultado.text
precioinicio= float(precioinicio_text)
preciodeseado= 25usd


if precio >  preciodeseado
print(hora de cobrar)
