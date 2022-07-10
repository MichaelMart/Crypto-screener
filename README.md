# Crypto-screener

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Crypto-screener производит непрерывный мониторинг цен всех монет доступных для фьючерсной торговли на бирже Binance. Для этого используется Binance API и TradingView API. При обнаружении определенной ситуации на рынке, трейдер получит уведомление в телеграмм от бота с указанием имени торговой пары и описания события, которое произошло. Бот отслеживает несколько видов ситуаций:

1. Резкое изменение цены.
2. Крупные лимитные заявки в стакане фьючерса и спота.
3. Авторский сигнал, который срабатывает если во время скопления средних скользящих, цена резко изменяется и при этом аномально увеличивается торговый объем.

Для работы бота нужно вписать свои API ключи на бирже Binance и токен для телеграм бота. Также скрипт дублирует вывод всех сигналов в консоль, поэтому использование телеграм бота не обязательно.


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Crypto-screener continuously monitors the prices of all coins available for futures trading on the Binance exchange. For this, the Binance API and TradingView API are used. When a certain market situation is detected, the trader will receive a telegram notification from the bot indicating the name of the trading pair and a description of the event that occurred. The bot monitors several types of situations:

1. A sharp change in price.
2. Large limit orders in the futures and spot order book.
3. The author's signal, which is triggered if during the accumulation of moving averages, the price changes sharply and at the same time the trading volume increases abnormally.

For the bot to work, you need to enter your API keys on the Binance exchange and a token for the telegram bot. Also, the script duplicates the output of all signals to the console, so the use of a telegram bot is not necessary.
