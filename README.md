# Currency Exchange by Google Finance
* Simple Java Project for currency exchange by Google Finance
* Projeto Java simples para c�mbio (cota��o) de moedas atrav�s do Google Finance
* Simple Java Proyecto para la conversi�n de moneda por Google Finance

# Usage

#### Simple Quote
```java
//execute Google Finance simple request 
CurrencyQuoteRS quote = ConsultGoogleFinance.exchangeCurrency(Currency.USD, Currency.BRL);
```

#### Print Simple Quote (default amount = 1.0)
```java
PrintCurrencyQuote.print(quote);
/*
Result...
BRL 3.3092
USD 1.0
EXCHANGE RATE: 3.3092
QUOTE DATE: 14/11/2017 17:51
*/
```

#### Amount Quote
```java
//execute Google Finance amount request 
CurrencyQuoteRS amountQuote = ConsultGoogleFinance.exchangeCurrency(Currency.USD, Currency.BRL, 10.00);
```

#### Print Amount Quote
```java
PrintCurrencyQuote.print(amountQuote);
/*
Result...
BRL 30.3092
USD 10.0
EXCHANGE RATE: 3.3092
QUOTE DATE: 14/11/2017 17:51
*/
```
